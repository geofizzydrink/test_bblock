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


# OGC API DGGS `pangaea.terranexus.dggs.api.OGC-API-DGGS_Core-zoneInfo`

This Building Block serves as a template to define and test the schema specification for an OGC API DGGS Server

<p class="status">
    <span data-rainbow-uri="http://www.opengis.net/def/status">Status</span>:
    <a href="http://www.opengis.net/def/status/under-development" target="_blank" data-rainbow-uri>Under development</a>
</p>

<aside class="warning">
Validation for this building block has <strong><a href="https://github.com/geofizzydrink/test_bblock/blob/master/build/tests/terranexus/dggs/api/OGC-API-DGGS_Core-zoneInfo/" target="_blank">failed</a></strong>
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
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/terranexus/dggs/api/OGC-API-DGGS_Core-zoneInfo/example_2_1.json">Open in new window</a>
    <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=json&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Ftests%2Fterranexus%2Fdggs%2Fapi%2FOGC-API-DGGS_Core-zoneInfo%2Fexample_2_1.json&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on JSON Viewer</a></p>
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
  "@context": "https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_Core-zoneInfo/context.jsonld"
}
```

<blockquote class="lang-specific jsonld">
  <p class="example-links">
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/terranexus/dggs/api/OGC-API-DGGS_Core-zoneInfo/example_2_1.jsonld">Open in new window</a>
    <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Ftests%2Fterranexus%2Fdggs%2Fapi%2FOGC-API-DGGS_Core-zoneInfo%2Fexample_2_1.jsonld">View on JSON-LD Playground</a>
</blockquote>



The content of this example. 


# JSON Schema

```yaml--schema
$schema: https://json-schema.org/draft/2020-12/schema
title: Information for a specific Discrete Global Grid System zone
description: Zone information for a particular zone of a DGGS, including useful information
  such as zone geometry, data access links and statistics
type: object
required:
- id
- links
properties:
  id:
    description: Zone identifier based on the DGGRS.
    type: string
  links:
    description: Links to related resources. A `[ogc-rel:dggrs-zone-data]` link to
      retrieve data for this zone and a `[ogc-rel:dggrs]` back to the `.../dggs` resource
      must be included.
    type: array
    items:
      $ref: '#/$defs/link'
  shapeType:
    description: The type of shape for the zone geometry (e.g., hexagon or pentagon)
    type: string
  level:
    description: The refinement level of this zone
    type: integer
    minimum: 0
  crs:
    description: The Coordinate Reference System in which the geometry, centroid and
      bbox properties are specified
    type: string
    format: uri
    default: '[OGC:CRS84]'
  centroid:
    description: The centroid of the zone, in the CRS specified in crs property
    type: array
    items:
      type: number
      minItems: 2
      maxItems: 3
  bbox:
    description: The spatial envelope of the zone (bounding box), in the CRS specified
      in crs property
    type: array
    items:
      type: number
      minItems: 4
      maxItems: 6
  areaMetersSquare:
    description: Surface area of the zone in meters square.
    type: number
  volumeMetersCube:
    description: Volume of the zone in meters cube for a DGGS with three spatial dimension.
    type: number
  temporalDurationSeconds:
    description: Amount of time covered by the zone for a temporal DGGS.
    type: number
  geometry:
    description: Spatial geometry of the zone.
    oneOf:
    - $ref: https://opengeospatial.github.io/bblocks/annotated-schemas/geo/features/feature/schema.yaml
    - $ref: '#/$defs/fg-json-feature'
  temporalInterval:
    description: Sart and end time of the zone.
    type: array
    items:
      type: string
    minItems: 2
    maxItems: 2
  statistics:
    type: object
    description: Statistics for individual fields of the data (e.g., fields of the
      range of a coverage, or relevant numeric properties of a feature collection)
    additionalProperties:
      type: object
      properties:
        minimum:
          type: number
        maximum:
          type: number
        average:
          type: number
        stdDev:
          type: number
$defs:
  link:
    type: object
    required:
    - href
    - rel
    properties:
      href:
        type: string
        description: Supplies the URI to a remote resource (or resource fragment).
        example: http://data.example.com/buildings/123
      rel:
        type: string
        description: The type or semantics of the relation.
        example: alternate
      type:
        type: string
        description: A hint indicating what the media type of the result of dereferencing
          the link should be.
        example: application/geo+json
      hreflang:
        type: string
        description: A hint indicating what the language of the result of dereferencing
          the link should be.
        example: en
      title:
        type: string
        description: Used to label the destination of a link such that it can be used
          as a human-readable identifier.
        example: Trierer Strasse 70, 53115 Bonn
      length:
        type: integer
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

> <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=yaml&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Fannotated%2Fterranexus%2Fdggs%2Fapi%2FOGC-API-DGGS_Core-zoneInfo%2Fschema.yaml&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on YAML Viewer</a>

Links to the schema:

* YAML version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_Core-zoneInfo/schema.yaml" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_Core-zoneInfo/schema.yaml</a>
* JSON version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_Core-zoneInfo/schema.json" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_Core-zoneInfo/schema.json</a>


# JSON-LD Context

```json--ldContext
{
  "@context": {
    "type": "@type",
    "id": "@id",
    "properties": "@nest",
    "geometry": "geojson:geometry",
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
      "@id": "geojson:features"
    },
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
    },
    "geojson": "https://purl.org/geojson/vocab#",
    "rdfs": "http://www.w3.org/2000/01/rdf-schema#",
    "dct": "http://purl.org/dc/terms/",
    "owlTime": "http://www.w3.org/2006/time#",
    "oa": "http://www.w3.org/ns/oa#",
    "@version": 1.1
  }
}
```

> <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Fannotated%2Fterranexus%2Fdggs%2Fapi%2FOGC-API-DGGS_Core-zoneInfo%2Fcontext.jsonld">View on JSON-LD Playground</a>

You can find the full JSON-LD context here:
<a href="https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_Core-zoneInfo/context.jsonld" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_Core-zoneInfo/context.jsonld</a>

# References

* [Sample source document](https://example.com/sources/1)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: <a href="https://github.com/geofizzydrink/test_bblock" target="_blank">https://github.com/geofizzydrink/test_bblock</a>
* Path:
<code><a href="https://github.com/geofizzydrink/test_bblock/blob/HEAD/_sources/OGC-API-DGGS_Core-zoneInfo" target="_blank">_sources/OGC-API-DGGS_Core-zoneInfo</a></code>

