---
title: OGC API DGGS (Schema)

language_tabs:
  - json: JSON
  - jsonld: JSON-LD

toc_footers:
  - Version 0.1
  - <a href='#'>OGC API DGGS</a>
  - <a href='https://blocks.ogc.org/register.html'>Building Blocks register</a>

search: true

code_clipboard: true

meta:
  - name: OGC API DGGS (Schema)
---


# OGC API DGGS `pangaea.terranexus.dggs.api.OGC-API-DGGS_ZoneQuery-ZoneList_GeoJSON-Encoding`

This Building Block serves as a template to define and test the schema specification for an OGC API DGGS Server

<p class="status">
    <span data-rainbow-uri="http://www.opengis.net/def/status">Status</span>:
    <a href="http://www.opengis.net/def/status/under-development" target="_blank" data-rainbow-uri>Under development</a>
</p>

<aside class="warning">
Validation for this building block has <strong><a href="https://github.com/geofizzydrink/test_bblock/blob/master/build/tests/terranexus/dggs/api/OGC-API-DGGS_ZoneQuery-ZoneList_GeoJSON-Encoding/" target="_blank">failed</a></strong>
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
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/terranexus/dggs/api/OGC-API-DGGS_ZoneQuery-ZoneList_GeoJSON-Encoding/example_2_1.json">Open in new window</a>
    <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=json&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Ftests%2Fterranexus%2Fdggs%2Fapi%2FOGC-API-DGGS_ZoneQuery-ZoneList_GeoJSON-Encoding%2Fexample_2_1.json&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on JSON Viewer</a></p>
</blockquote>




```jsonld
{
  "gridConstraint": [
    "cellEqualSized",
    "cellConformal"
  ],
  "zoneGeometry": {
    "zoneType": "triangle"
  },
  "surfaceInterpolation": "elliptical",
  "referenceSystemType": {
    "CRS": "EPSG:7789",
    "GLOBE": "EPGS:7019",
    "MDRS": "TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2-topological",
    "ZIRS": "TopologicalMortonCode"
  },
  "refinementStrategy": "nestedChildCell",
  "refinementRatio": 9,
  "basePolyhedron": "Icosahedron",
  "@context": "https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_ZoneQuery-ZoneList_GeoJSON-Encoding/context.jsonld"
}
```

<blockquote class="lang-specific jsonld">
  <p class="example-links">
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/terranexus/dggs/api/OGC-API-DGGS_ZoneQuery-ZoneList_GeoJSON-Encoding/example_2_1.jsonld">Open in new window</a>
    <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Ftests%2Fterranexus%2Fdggs%2Fapi%2FOGC-API-DGGS_ZoneQuery-ZoneList_GeoJSON-Encoding%2Fexample_2_1.jsonld">View on JSON-LD Playground</a>
</blockquote>



The content of this example. 


# JSON Schema

```yaml--schema
$schema: https://json-schema.org/draft/2020-12/schema
title: OGC API DGGS - Zone Query Features and Geometry JSON encoding response.
description: Features and Geometry JSON response for the DGGRS zone list resource.
allOf:
- $ref: '#/$defs/fg-json-featureCollection'
- type: object
- properties:
    a:
      type: string
      format: uri
    b:
      type: number
$defs:
  fg-json-featureCollection:
    $schema: https://json-schema.org/draft/2019-09/schema
    title: a JSON-FG Feature Collection
    description: This JSON Schema is part of JSON-FG version 0.1.1
    type: object
    required:
    - type
    - features
    allOf:
    - $ref: https://opengeospatial.github.io/bblocks/annotated-schemas/geo/features/featureCollection/schema.yaml
    - properties:
        type:
          type: string
          enum:
          - FeatureCollection
          x-jsonld-id: '@type'
        featureType:
          $ref: https://beta.schemas.opengis.net/json-fg/featuretype.json
          x-jsonld-id: https://purl.org/geojson/vocab#collectionFeatureType
        geometryDimension:
          type: integer
          minimum: 0
          maximum: 3
        coordRefSys:
          $ref: https://beta.schemas.opengis.net/json-fg/coordrefsys.json
        links:
          type: array
          items:
            allOf:
            - $ref: https://beta.schemas.opengis.net/json-fg/link.json
            - $ref: https://opengeospatial.github.io/bblocks/annotated-schemas/ogc-utils/json-link/schema.yaml
          x-jsonld-id: rdfs:seeAlso
        features:
          type: array
          items:
            $ref: '#/$defs/fg-json-feature'
          x-jsonld-container: '@set'
          x-jsonld-id: https://purl.org/geojson/vocab#features
    x-jsonld-prefixes:
      geojson: https://purl.org/geojson/vocab#
  fg-json-feature:
    $schema: https://json-schema.org/draft/2019-09/schema
    title: a JSON-FG Feature
    description: This JSON Schema is part of JSON-FG version 0.1.1
    type: object
    required:
    - type
    - time
    - place
    - geometry
    - properties
    allOf:
    - $ref: https://opengeospatial.github.io/bblocks/annotated-schemas/geo/features/feature/schema.yaml
    - properties:
        type:
          type: string
          enum:
          - Feature
          x-jsonld-id: '@type'
        id:
          oneOf:
          - type: number
          - type: string
          x-jsonld-id: '@id'
        featureType:
          $ref: https://beta.schemas.opengis.net/json-fg/featuretype.json
          x-jsonld-id: '@type'
        links:
          type: array
          items:
            allOf:
            - $ref: https://beta.schemas.opengis.net/json-fg/link.json
            - $ref: https://opengeospatial.github.io/bblocks/annotated-schemas/ogc-utils/json-link/schema.yaml
          x-jsonld-id: http://www.w3.org/2000/01/rdf-schema#seeAlso
        time:
          title: the time member
          description: This JSON Schema is part of JSON-FG version 0.2.2
          oneOf:
          - type: 'null'
          - type: object
            properties:
              date:
                $ref: '#/$timedefs/date'
              timestamp:
                $ref: '#/$timedefs/timestamp'
              interval:
                $ref: '#/$timedefs/interval'
          x-jsonld-id: http://purl.org/dc/terms/time
        coordRefSys:
          $ref: https://beta.schemas.opengis.net/json-fg/coordrefsys.json
          x-jsonld-id: http://www.opengis.net/def/glossary/term/CoordinateReferenceSystemCRS
        place:
          $ref: https://beta.schemas.opengis.net/json-fg/place.json
          x-jsonld-id: http://purl.org/dc/terms/spatial
        geometry:
          $ref: https://beta.schemas.opengis.net/json-fg/geometry.json
          x-jsonld-id: https://purl.org/geojson/vocab#geometry
        properties:
          oneOf:
          - type: 'null'
          - type: object
          x-jsonld-id: '@nest'
    x-jsonld-extra-terms:
      Feature: https://purl.org/geojson/vocab#Feature
      FeatureCollection: https://purl.org/geojson/vocab#FeatureCollection
      GeometryCollection: https://purl.org/geojson/vocab#GeometryCollection
      LineString: https://purl.org/geojson/vocab#LineString
      MultiLineString: https://purl.org/geojson/vocab#MultiLineString
      MultiPoint: https://purl.org/geojson/vocab#MultiPoint
      MultiPolygon: https://purl.org/geojson/vocab#MultiPolygon
      Point: https://purl.org/geojson/vocab#Point
      Polygon: https://purl.org/geojson/vocab#Polygon
      Polyhedron: https://purl.org/geojson/vocab#Polyhedron
      MultiPolyhedron: https://purl.org/geojson/vocab#MultiPolyhedron
      Prism:
        x-jsonld-id: https://purl.org/geojson/vocab#Prism
        x-jsonld-context:
          base: https://purl.org/geojson/vocab#prismBase
          lower: https://purl.org/geojson/vocab#prismLower
          upper: https://purl.org/geojson/vocab#prismUpper
      MultiPrism:
        x-jsonld-id: https://purl.org/geojson/vocab#MultiPrism
        x-jsonld-context:
          prisms: https://purl.org/geojson/vocab#prisms
      bbox:
        x-jsonld-container: '@list'
        x-jsonld-id: https://purl.org/geojson/vocab#bbox
      coordinates:
        x-jsonld-container: '@list'
        x-jsonld-id: https://purl.org/geojson/vocab#coordinates
      features:
        x-jsonld-container: '@set'
        x-jsonld-id: https://purl.org/geojson/vocab#features
      geometries:
        x-jsonld-id: https://purl.org/geojson/vocab#geometry
        x-jsonld-container: '@list'
    x-jsonld-prefixes:
      geojson: https://purl.org/geojson/vocab#
      rdfs: http://www.w3.org/2000/01/rdf-schema#
      dct: http://purl.org/dc/terms/
      owlTime: http://www.w3.org/2006/time#
$timedefs:
  date:
    type: string
    pattern: ^\d{4}-\d{2}-\d{2}$
  timestamp:
    type: string
    pattern: ^\d{4}-\d{2}-\d{2}T\d{2}:\d{2}:\d{2}(?:\.\d+)?Z$|^\d{4}-\d{2}-\d{2}T\d{2}:\d{2}:\d{2}(?:\.\d+)?\+00:00$
  interval:
    type: array
    minItems: 2
    maxItems: 2
    items:
      oneOf:
      - $ref: '#/$timedefs/date'
      - $ref: '#/$timedefs/timestamp'
      - type: string
        enum:
        - ..
x-jsonld-prefixes:
  geojson: https://purl.org/geojson/vocab#
  rdfs: http://www.w3.org/2000/01/rdf-schema#
  dct: http://purl.org/dc/terms/
  owlTime: http://www.w3.org/2006/time#

```

> <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=yaml&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Fannotated%2Fterranexus%2Fdggs%2Fapi%2FOGC-API-DGGS_ZoneQuery-ZoneList_GeoJSON-Encoding%2Fschema.yaml&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on YAML Viewer</a>

Links to the schema:

* YAML version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_ZoneQuery-ZoneList_GeoJSON-Encoding/schema.yaml" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_ZoneQuery-ZoneList_GeoJSON-Encoding/schema.yaml</a>
* JSON version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_ZoneQuery-ZoneList_GeoJSON-Encoding/schema.json" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_ZoneQuery-ZoneList_GeoJSON-Encoding/schema.json</a>


# JSON-LD Context

```json--ldContext
{
  "@context": {
    "links": {
      "@context": {
        "href": {
          "@type": "@id",
          "@id": "oa:hasTarget"
        },
        "rel": {
          "@context": {
            "@base": "http://www.iana.org/assignments/relation/"
          },
          "@id": "http://www.iana.org/assignments/relation",
          "@type": "@id"
        },
        "type": "dct:type",
        "hreflang": "dct:language",
        "title": "rdfs:label",
        "length": "dct:extent"
      },
      "@id": "rdfs:seeAlso"
    },
    "type": "@type",
    "id": "@id",
    "properties": "@nest",
    "geometry": {
      "@context": {
        "coordinates": {
          "@container": "@list",
          "@id": "geojson:coordinates"
        }
      },
      "@id": "geojson:geometry"
    },
    "bbox": {
      "@container": "@list",
      "@id": "geojson:bbox"
    },
    "Feature": "geojson:Feature",
    "FeatureCollection": "geojson:FeatureCollection",
    "GeometryCollection": "geojson:GeometryCollection",
    "LineString": "geojson:LineString",
    "MultiLineString": "geojson:MultiLineString",
    "MultiPoint": "geojson:MultiPoint",
    "MultiPolygon": "geojson:MultiPolygon",
    "Point": "geojson:Point",
    "Polygon": "geojson:Polygon",
    "features": {
      "@container": "@set",
      "@id": "geojson:features",
      "@context": {
        "links": {
          "@context": {
            "href": {
              "@type": "@id",
              "@id": "oa:hasTarget"
            },
            "rel": {
              "@context": {
                "@base": "http://www.iana.org/assignments/relation/"
              },
              "@id": "http://www.iana.org/assignments/relation",
              "@type": "@id"
            },
            "type": "dct:type",
            "hreflang": "dct:language",
            "title": "rdfs:label",
            "length": "dct:extent"
          },
          "@id": "rdfs:seeAlso"
        },
        "featureType": "@type",
        "time": "dct:time",
        "coordRefSys": "http://www.opengis.net/def/glossary/term/CoordinateReferenceSystemCRS",
        "place": "dct:spatial",
        "Polyhedron": "geojson:Polyhedron",
        "MultiPolyhedron": "geojson:MultiPolyhedron",
        "Prism": {
          "@id": "geojson:Prism",
          "@context": {
            "base": "geojson:prismBase",
            "lower": "geojson:prismLower",
            "upper": "geojson:prismUpper"
          }
        },
        "MultiPrism": {
          "@id": "geojson:MultiPrism",
          "@context": {
            "prisms": "geojson:prisms"
          }
        },
        "coordinates": {
          "@container": "@list",
          "@id": "geojson:coordinates"
        },
        "geometries": {
          "@id": "geojson:geometry",
          "@container": "@list"
        }
      }
    },
    "featureType": "geojson:collectionFeatureType",
    "rdfs": "http://www.w3.org/2000/01/rdf-schema#",
    "oa": "http://www.w3.org/ns/oa#",
    "dct": "http://purl.org/dc/terms/",
    "geojson": "https://purl.org/geojson/vocab#",
    "owlTime": "http://www.w3.org/2006/time#",
    "@version": 1.1
  }
}
```

> <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Fannotated%2Fterranexus%2Fdggs%2Fapi%2FOGC-API-DGGS_ZoneQuery-ZoneList_GeoJSON-Encoding%2Fcontext.jsonld">View on JSON-LD Playground</a>

You can find the full JSON-LD context here:
<a href="https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_ZoneQuery-ZoneList_GeoJSON-Encoding/context.jsonld" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_ZoneQuery-ZoneList_GeoJSON-Encoding/context.jsonld</a>

# References

* [Sample source document](https://example.com/sources/1)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: <a href="https://github.com/geofizzydrink/test_bblock" target="_blank">https://github.com/geofizzydrink/test_bblock</a>
* Path:
<code><a href="https://github.com/geofizzydrink/test_bblock/blob/HEAD/_sources/OGC-API-DGGS_ZoneQuery-ZoneList_GeoJSON-Encoding" target="_blank">_sources/OGC-API-DGGS_ZoneQuery-ZoneList_GeoJSON-Encoding</a></code>

