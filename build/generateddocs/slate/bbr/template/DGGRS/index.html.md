---
title: OGC API DGGS - Discrete Global Grid Reference System (DGGRS) (Schema)


toc_footers:
  - Version 0.1
  - <a href='#'>OGC API DGGS - Discrete Global Grid Reference System (DGGRS)</a>
  - <a href='https://blocks.ogc.org/register.html'>Building Blocks register</a>

search: true

code_clipboard: true

meta:
  - name: OGC API DGGS - Discrete Global Grid Reference System (DGGRS) (Schema)
---


# OGC API DGGS - Discrete Global Grid Reference System (DGGRS) `ogc.bbr.template.DGGRS`

This Building Block serves as a template to define and test the schema specification for a DGGRS which will underpin the DGGS Registry

<p class="status">
    <span data-rainbow-uri="http://www.opengis.net/def/status">Status</span>:
    <a href="http://www.opengis.net/def/status/under-development" target="_blank" data-rainbow-uri>Under development</a>
</p>

<aside class="warning">
Validation for this building block has <strong><a href="https://github.com/geofizzydrink/test_bblock/blob/master/build/tests/bbr/template/DGGRS/" target="_blank">failed</a></strong>
</aside>

# Description

## Qui hastarum tectus Cithaeron iuvabat

Lorem markdownum vestigia sanguine rursus undis, suspenderat meo mox conlegerat
temperat sucos. Est graves dant sentire sanguinis flores respondent testari.

> Videri vias quid Ausoniae sua flores ante, reminiscitur fuit est. Semel
> [hectora](http://silvaque.org/) peregrinaeque rudem exercent in, Troiana si
> Asida instabilesque somno sed.

## Iam vota cui dilataque peterem

Tinxit lumina lacer liquidarum Aiax si mergitur sed fueris capitisque **et
cadit** contigerant rectum [ferar](http://prosternit.com/quoque.html) temperat.
Monet caput adsensere Ityn furentibus gelidos.
# Examples

## This is an example with just a description and no code snippets.

This is the content of the example.

In **Markdown** format.


## Examples can have content and/or code snippets.



```json
{
    "gridConstraint": ["cellEqualSized","cellConformal"],
	"zoneGeometry": {"zoneType": "triangle"},
	"surfaceInterpolation": "elliptical",
	"referenceSystemType": {"CRS": "EPSG:7789",
    						"GLOBE": "EPGS:7019",
    						"MDRS": "TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2-topological",
    						"ZIRS": "TopologicalMortonCode"},
	"refinementStrategy": "nestedChildCell",
	"refinementRatio": 9,
	"basePolyhedron": "Icosahedron"
}
```

<blockquote class="lang-specific json">
  <p class="example-links">
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/bbr/template/DGGRS/example_2_1.json">Open in new window</a>
    <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=json&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Ftests%2Fbbr%2Ftemplate%2FDGGRS%2Fexample_2_1.json&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on JSON Viewer</a></p>
</blockquote>


The content of this example. 


# JSON Schema

```yaml--schema
$schema: https://json-schema.org/draft/2020-12/schema
description: Discrete Global Grid System Reference System Structure Definition.
type: object
required:
- gridConstraint
- zoneGeometry
- surfaceInterpolation
- referenceSystemType
- refinementStrategy
- refinementRatio
properties:
  basePolyhedron:
    properties:
      orientation:
        properties:
          latitude:
            description: Reference Latitude to fix the orientation of the polyhedron.
            example: 0.0
            type: number
          longitude:
            description: Reference Longitude to fix the orientation of the polyhedron.
            example: 0.0
            type: number
        required:
        - longitude
        - latitude
        type: object
      polyhedronType:
        description: The Type/Class of Polyhedron used to construct the Discrete Global
          Grid System - if it is constructued using a Base Polyhedron.
        example: icosahedron
        type: string
    required:
    - polyhedronType
    - orientation
    type: object
  gridConstraint:
    description: Constraints used to define different categories of DGGS. Each constraint
      is a constraint on the shape, size, or orientation of cells in a DiscreteGlobalGrid.
    oneOf:
    - type: string
      enum:
      - cellAxisAligned
      - cellConformal
      - cellEquiAngular
      - cellEquiDistant
      - cellEqualSized
      example: cellEqualSized
    - type: array
      items:
        type: string
        enum:
        - cellAxisAligned
        - cellConformal
        - cellEquiAngular
        - cellEquiDistant
        - cellEqualSized
        example:
        - cellEqualSized
        - cellConformal
  referenceSystemType:
    type: object
    required:
    - CRS
    - GLOBE
    - MDRS
    - ZIRS
    properties:
      CRS:
        allOf:
        - description: Coordinate Reference System (CRS)
        - $ref: https://opengeospatial.github.io/bblocks/annotated-schemas/ogc-utils/iri-or-curie/schema.yaml
        example: EPSG:7789
      GLOBE:
        description: Globe Reference System Identifier/Specification
        example: EPGS:7019
        type: string
      MDRS:
        description: Metadata Reference System Identifier/Specification.
        example: TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2
        type: string
      ZIRS:
        description: Zone Identifier Reference System Identifier/Specification. This
          is a label describing the specific Zone Identifier Schema for the DGGS
        type: string
        required:
        - ZoneIdentifiers
        properties:
          ZoneIdentifiers:
            description: zone identification schema defined by the Discrete Global
              Grid System
            OneOf:
            - ZoneIdentifierComplex:
                description: compound zoneIdentifier describing a spatio-temporal
                  zoneIdentifier.
                allOf:
                - SpatialZoneIdentifier:
                    description: ZoneIdentifierPrimative representing the spatial
                      identifier for a zone by geographic identifier.
                    type: string
                - TemporalZoneIdentifier:
                    description: ZoneIdentifierPrimative representing the temporal
                      identifier for a zone by temporal period identifier.
                    type: string
            - ZoneIdentifierPrimative:
                description: simple zoneIdentifier describing either a spatial or
                  temporal zoneIdentifier.
                type: string
  refinementRatio:
    description: The ratio of child zones to parent zones
    example: 9
    type: integer
  refinementStrategy:
    description: The refinement strategy used by the Discrete Global Grid System
    enum:
    - centredChildCell
    - nestedChildCell
    - nodeCentredChildCell
    - edgeCentredChildCell
    - faceCentredChildCell
    - solidCentredChildCell
    example: nestedChildCell
    type: string
  surfaceInterpolation:
    description: The Surface Interpolation type used to define zone geometries of
      the Discrete Global Grid System
    enum:
    - spherical
    - elliptical
    example: elliptical
    type: string
  zoneGeometry:
    description: Zone Geometry Specification
    properties:
      spatialDimension:
        description: Number of Spatial Dimensions defined by the Discrete Global Grid
          System.
        example: 2
        type: integer
      temporalDimension:
        description: Number of Temporal Dimensions defined by the Discrete Global
          Grid System.
        example: 0
        type: integer
      topologicalDimension:
        description: Number of Topological Dimensions (Spatial + Temporal Dimensions)
          defined by the Discrete Global Grid System.
        example: 2
        type: integer
      zoneType:
        enum:
        - triangle
        - square
        - hexagon
        - pentagon
        - diamond
        example: triangle
        type: string
    type: object

```

> <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=yaml&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Fannotated%2Fbbr%2Ftemplate%2FDGGRS%2Fschema.yaml&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on YAML Viewer</a>

Links to the schema:

* YAML version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/DGGRS/schema.yaml" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/DGGRS/schema.yaml</a>
* JSON version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/DGGRS/schema.json" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/DGGRS/schema.json</a>


# JSON-LD Context

```json--ldContext
None
```

> <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2F_sources%2FDGGRS%2Fcontext.jsonld">View on JSON-LD Playground</a>

You can find the full JSON-LD context here:
<a href="https://geofizzydrink.github.io/test_bblock/_sources/DGGRS/context.jsonld" target="_blank">https://geofizzydrink.github.io/test_bblock/_sources/DGGRS/context.jsonld</a>

# References

* [Sample source document](https://example.com/sources/1)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: <a href="https://github.com/geofizzydrink/test_bblock" target="_blank">https://github.com/geofizzydrink/test_bblock</a>
* Path:
<code><a href="https://github.com/geofizzydrink/test_bblock/blob/HEAD/_sources/DGGRS" target="_blank">_sources/DGGRS</a></code>

