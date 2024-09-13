---
title: OGC API DGGS (Schema)


toc_footers:
  - Version 0.1
  - <a href='#'>OGC API DGGS</a>
  - <a href='https://blocks.ogc.org/register.html'>Building Blocks register</a>

search: true

code_clipboard: true

meta:
  - name: OGC API DGGS (Schema)
---


# OGC API DGGS `pangaea.terranexus.dggs.api.OGC-API-DGGS_Core-DGGRS`

This Building Block serves as a template to define and test the schema specification for an OGC API DGGS Server

<p class="status">
    <span data-rainbow-uri="http://www.opengis.net/def/status">Status</span>:
    <a href="http://www.opengis.net/def/status/under-development" target="_blank" data-rainbow-uri>Under development</a>
</p>

<aside class="warning">
Validation for this building block has <strong><a href="https://github.com/geofizzydrink/test_bblock/blob/master/build/tests/terranexus/dggs/api/OGC-API-DGGS_Core-DGGRS/" target="_blank">failed</a></strong>
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
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/terranexus/dggs/api/OGC-API-DGGS_Core-DGGRS/example_2_1.json">Open in new window</a>
    <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=json&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Ftests%2Fterranexus%2Fdggs%2Fapi%2FOGC-API-DGGS_Core-DGGRS%2Fexample_2_1.json&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on JSON Viewer</a></p>
</blockquote>


The content of this example. 


# JSON Schema

```yaml--schema
$schema: https://json-schema.org/draft/2020-12/schema
description: Discrete Global Grid System Reference System (DGGRS) Definition.
type: object
required:
- dggh
- zirs
- subZoneOrder
properties:
  title:
    type: string
  description:
    type: string
  uri:
    type: string
    format: uri
    description: The authoritative URI associated with this DGGRS definition
  dggh:
    type: object
    description: The hierarchical series of Discrete Global Grid upon which this DGGRS
      is based, including any parameters.
    properties:
      definition:
        description: The base definition of the hierarchical series of Discrete Global
          Grid, which may be parameterized.
        type: object
        required:
        - spatialDimensions
        - temporalDimensions
        properties:
          crs:
            allOf:
            - description: The native Coordinate Reference System (CRS) in which the
                geometry of the zones for this DGG hierarchy is defined.
            - anyOf:
              - type: string
                format: uri
                example: EPSG:7789
              - $ref: '#/$defs/crs'
          basePolyhedron:
            type: string
            description: The Type/Class of Polyhedron used to construct the Discrete
              Global Grid System - if it is constructued using a Base Polyhedron.
            example: icosahedron
          refinementRatio:
            description: The ratio of the area of zones between two consecutive hierarchy
              level (the ratio of child zones to parent zones, also called the aperture).
            example: 9
            type: integer
          constraints:
            type: object
            properties:
              cellAxisAligned:
                description: Set to true if all edges of the geometry of all zones
                  are aligned with one of the axis of the `crs`.
                type: boolean
                default: false
              cellConformal:
                type: boolean
                default: false
              cellEquiAngular:
                type: boolean
                default: false
              cellEquiDistant:
                type: boolean
                default: false
              cellEqualSized:
                description: Set to true if the area of all zones is the same for
                  a particular zone geometry type of any specifc discrete global grid
                  of the DGG hierarchy.
                type: boolean
                default: false
          spatialDimensions:
            description: Number of Spatial Dimensions defined by the Discrete Global
              Grid System.
            example: 2
            type: integer
          temporalDimensions:
            description: Number of Temporal Dimensions defined by the Discrete Global
              Grid System.
            example: 0
            type: integer
          zoneTypes:
            type: array
            items:
              type: string
              enum:
              - triangle
              - square
              - hexagon
              - pentagon
              - rhombus
            example:
            - hexagon
            - pentagon
          refinementStrategy:
            description: The refinement strategy used by the Discrete Global Grid
              System
            type: array
            items:
              type: string
              enum:
              - centredChildCell
              - nestedChildCell
              - nodeCentredChildCell
              - edgeCentredChildCell
              - faceCentredChildCell
              - solidCentredChildCell
            example:
            - nestedChildCell
            - nodeCentredChildCell
      parameters:
        description: The optional parameters establishing a very specific Discrete
          Global Grid System, where each zone has a well-defined geometry.
        type: object
        properties:
          ellipsoid:
            type: string
            format: uri
            description: Globe Reference System Identifier/Specification
            example:
            - EPGS:7019
          orientation:
            type: object
            properties:
              latitude:
                description: Reference latitude in decimal degrees on reference globe
                  of first vertex to fix the orientation of the polyhedron.
                example: 58.28252559
                type: number
              longitude:
                description: Reference longitude in decimal degrees on reference globe
                  of first vertex to fix the orientation of the polyhedron.
                example: 11.25
                type: number
              azimuth:
                description: Azimuth in decimal degrees of second vertex relative
                  to the first vertex.
                example: 0.0
                type: number
                default: 0.0
              description:
                type: string
            required:
            - longitude
            - latitude
  zirs:
    description: The Zone Identifier Reference System used for this Discrete Global
      Grid System Reference System.
    type: object
    required:
    - textZIRS
    properties:
      textZIRS:
        description: textual zone identifier indexing scheme
        type: object
        required:
        - description
        properties:
          description:
            type: string
            example: 'Topological Morton Code (Space Filling Curve) Identifier. With
              a Level 0 alphabetical identifier from ''A'' to ''S'' followed by a
              numeric reference from 1 to 9 for all subsequent levels representing
              the arrangement of child zones following a Morton (Z-code) subdivision
              of the parent zone. The length of the identifier represents the level
              of refinement.

              '
          type:
            anyOf:
            - type: string
            - type: string
              enum:
              - hierarchicalConcatenation
              - ogc2DTMSHexLevelRowCol
              - levelRootFaceHexRowMajorSubZone
      uint64ZIRS:
        description: 64-bit unsigned integer zone indexing scheme
        type: object
        required:
        - description
        properties:
          description:
            type: string
            example: 'A 64-bit integer with the 30 least significant bits corresponds
              to a column, the next 29 bits corresponding to a row, and the 5 most
              significant bits correspond to a level of an OGC 2D Tile Matrix Set
              identifier, with individual components using little endian.

              '
          type:
            anyOf:
            - type: string
            - type: string
              enum:
              - ogc2DTMSHexLevelRowCol
  subZoneOrder:
    description: The ordering used for this Discrete Global Grid System Reference
      System when encoding the values associated with sub-zones at any given depth
      relative to a parent zone.
    type: object
    required:
    - description
    properties:
      description:
        type: string
        example: 'The zones are ordered in tightly packed scanlines. For an odd relative
          depth, scanlines start along a hexagon edge, whereas for even relative depths,
          scanlines start on a hexagon vertex. Scanlines run in a clockwise direction.
          For sub-zones at an even refinement level, zones are ordered left to right
          along a scanline and scanlines are ordered from top to bottom (considering
          the ISEA planar projection). For sub-zones at an odd refinement level, zones
          are ordered top to bottom along a scanline and scanlines are ordered from
          left to right. Sub-zones are at an even refinement level when the parity
          (even/odd) of the parent zone level corresponds to the parity of the relative
          depth, and at an odd refinement level when the parity of the parent zone
          level and relative depth do not match. For polar pentagons, the orientation
          of the scanlines varies in the ISEA planar projection but is always clockwise,
          the vertex/edge of the first sub-zone is on the left side of the planar
          ISEA projection for the north pole (in root rhombus 0), and on the right
          side for the south pole (in root rhombus 9).

          '
      type:
        anyOf:
        - type: string
        - type: string
          enum:
          - scanline
          - spiralFromCenter
          - mortonCurve
          - hilbertCurve
$defs:
  crs:
    title: CRS
    oneOf:
    - description: Simplification of the object into a url if the other properties
        are not present
      type: string
    - type: object
      oneOf:
      - required:
        - uri
        properties:
          uri:
            description: Reference to one coordinate reference system (CRS)
            type: string
            format: uri
      - required:
        - wkt
        properties:
          wkt:
            description: A string defining the CRS using the JSON encodng for Well
              Known Text
            type: object
      - required:
        - referenceSystem
        properties:
          referenceSystem:
            description: A reference system data structure as defined in the MD_ReferenceSystem
              of the ISO 19115
            type: object

```

> <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=yaml&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Fannotated%2Fterranexus%2Fdggs%2Fapi%2FOGC-API-DGGS_Core-DGGRS%2Fschema.yaml&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on YAML Viewer</a>

Links to the schema:

* YAML version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_Core-DGGRS/schema.yaml" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_Core-DGGRS/schema.yaml</a>
* JSON version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_Core-DGGRS/schema.json" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_Core-DGGRS/schema.json</a>


# JSON-LD Context

```json--ldContext
None
```

> <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2F_sources%2FOGC-API-DGGS_Core-DGGRS%2Fcontext.jsonld">View on JSON-LD Playground</a>

You can find the full JSON-LD context here:
<a href="https://geofizzydrink.github.io/test_bblock/_sources/OGC-API-DGGS_Core-DGGRS/context.jsonld" target="_blank">https://geofizzydrink.github.io/test_bblock/_sources/OGC-API-DGGS_Core-DGGRS/context.jsonld</a>

# References

* [Sample source document](https://example.com/sources/1)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: <a href="https://github.com/geofizzydrink/test_bblock" target="_blank">https://github.com/geofizzydrink/test_bblock</a>
* Path:
<code><a href="https://github.com/geofizzydrink/test_bblock/blob/HEAD/_sources/OGC-API-DGGS_Core-DGGRS" target="_blank">_sources/OGC-API-DGGS_Core-DGGRS</a></code>

