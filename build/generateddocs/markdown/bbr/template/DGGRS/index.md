
# OGC API DGGS - Discrete Global Grid Reference System (DGGRS) (Schema)

`ogc.bbr.template.DGGRS` *v0.1*

This Building Block serves as a template to define and test the schema specification for a DGGRS which will underpin the DGGS Registry

[*Status*](http://www.opengis.net/def/status): Under development

## Description

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
## Examples

### This is an example with just a description and no code snippets.
This is the content of the example.

In **Markdown** format.

### Examples can have content and/or code snippets.
The content of this example. 
#### json
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

## Schema

```yaml
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

Links to the schema:

* YAML version: [schema.yaml](https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/DGGRS/schema.json)
* JSON version: [schema.json](https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/DGGRS/schema.yaml)


# JSON-LD Context

```jsonld
None
```

You can find the full JSON-LD context here:
[context.jsonld](https://geofizzydrink.github.io/test_bblock/_sources/DGGRS/context.jsonld)

## Sources

* [Sample source document](https://example.com/sources/1)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/geofizzydrink/test_bblock](https://github.com/geofizzydrink/test_bblock)
* Path: `_sources/DGGRS`

