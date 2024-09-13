
# OGC API DGGS (Schema)

`pangaea.terranexus.dggs.api.OGC-API-DGGS_DataRetrieval_DGGS-JSON-Encoding` *v0.1*

This Building Block serves as a template to define and test the schema specification for an OGC API DGGS Server

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
type: object
properties:
  dggrs:
    type: string
    format: uri
  zoneId:
    type: string
  depths:
    type: array
    items:
      type: integer
      minimum: 0
  dimensions:
    type: array
    items:
      type: object
      properties:
        name:
          type: string
        definition:
          type: string
          format: uri
        unit:
          type: string
        unitLang:
          type: string
          format: uri
        grid:
          type: object
          properties:
            cellsCount:
              type: integer
            resolution: {}
            coordinates:
              type: array
              items:
                oneOf:
                - type: number
                  nullable: true
                - type: string
                  nullable: true
        interval:
          type: array
          items:
            oneOf:
            - type: number
              nullable: true
            - type: string
              nullable: true
      required:
      - name
      - interval
      - grid
  values:
    additionalProperties:
      type: array
      items:
        type: object
        properties:
          depth:
            type: integer
          shape:
            type: object
            properties:
              count:
                type: integer
              subZones:
                type: integer
              dimensions:
                type: object
                additionalProperties:
                  type: integer
            required:
            - count
            - subZones
          data:
            type: array
            items:
              type: number
              nullable: true
required:
- dggrs
- zoneId
- depths
- values

```

Links to the schema:

* YAML version: [schema.yaml](https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_DataRetrieval_DGGS-JSON-Encoding/schema.json)
* JSON version: [schema.json](https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_DataRetrieval_DGGS-JSON-Encoding/schema.yaml)


# JSON-LD Context

```jsonld
None
```

You can find the full JSON-LD context here:
[context.jsonld](https://geofizzydrink.github.io/test_bblock/_sources/OGC-API-DGGS_DataRetrieval_DGGS-JSON-Encoding/context.jsonld)

## Sources

* [Sample source document](https://example.com/sources/1)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/geofizzydrink/test_bblock](https://github.com/geofizzydrink/test_bblock)
* Path: `_sources/OGC-API-DGGS_DataRetrieval_DGGS-JSON-Encoding`

