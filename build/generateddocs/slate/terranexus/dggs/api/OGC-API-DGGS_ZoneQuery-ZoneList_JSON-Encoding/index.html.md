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


# OGC API DGGS `pangaea.terranexus.dggs.api.OGC-API-DGGS_ZoneQuery-ZoneList_JSON-Encoding`

This Building Block serves as a template to define and test the schema specification for an OGC API DGGS Server

<p class="status">
    <span data-rainbow-uri="http://www.opengis.net/def/status">Status</span>:
    <a href="http://www.opengis.net/def/status/under-development" target="_blank" data-rainbow-uri>Under development</a>
</p>

<aside class="warning">
Validation for this building block has <strong><a href="https://github.com/geofizzydrink/test_bblock/blob/master/build/tests/terranexus/dggs/api/OGC-API-DGGS_ZoneQuery-ZoneList_JSON-Encoding/" target="_blank">failed</a></strong>
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
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/terranexus/dggs/api/OGC-API-DGGS_ZoneQuery-ZoneList_JSON-Encoding/example_2_1.json">Open in new window</a>
    <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=json&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Ftests%2Fterranexus%2Fdggs%2Fapi%2FOGC-API-DGGS_ZoneQuery-ZoneList_JSON-Encoding%2Fexample_2_1.json&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on JSON Viewer</a></p>
</blockquote>


The content of this example. 


# JSON Schema

```yaml--schema
$schema: https://json-schema.org/draft/2020-12/schema
title: OGC API DGGS - Zone Query JSON encoding response.
description: JSON response for the DGGRS zone list resource.type = object
required:
- zones
properties:
  zones:
    type: array
    items:
      type: string
  returnedAreaMetersSquare:
    type: number
  returnedVolumeMetersCube:
    type: number
  returnedVolumeMetersSquareSeconds:
    type: number
  returnedHyperVolumeMetersCubeSeconds:
    type: number
  links:
    type: array
    items:
      $ref: '#/$defs/link'
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

```

> <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=yaml&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Fannotated%2Fterranexus%2Fdggs%2Fapi%2FOGC-API-DGGS_ZoneQuery-ZoneList_JSON-Encoding%2Fschema.yaml&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on YAML Viewer</a>

Links to the schema:

* YAML version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_ZoneQuery-ZoneList_JSON-Encoding/schema.yaml" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_ZoneQuery-ZoneList_JSON-Encoding/schema.yaml</a>
* JSON version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_ZoneQuery-ZoneList_JSON-Encoding/schema.json" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/OGC-API-DGGS_ZoneQuery-ZoneList_JSON-Encoding/schema.json</a>


# JSON-LD Context

```json--ldContext
None
```

> <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2F_sources%2FOGC-API-DGGS_ZoneQuery-ZoneList_JSON-Encoding%2Fcontext.jsonld">View on JSON-LD Playground</a>

You can find the full JSON-LD context here:
<a href="https://geofizzydrink.github.io/test_bblock/_sources/OGC-API-DGGS_ZoneQuery-ZoneList_JSON-Encoding/context.jsonld" target="_blank">https://geofizzydrink.github.io/test_bblock/_sources/OGC-API-DGGS_ZoneQuery-ZoneList_JSON-Encoding/context.jsonld</a>

# References

* [Sample source document](https://example.com/sources/1)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: <a href="https://github.com/geofizzydrink/test_bblock" target="_blank">https://github.com/geofizzydrink/test_bblock</a>
* Path:
<code><a href="https://github.com/geofizzydrink/test_bblock/blob/HEAD/_sources/OGC-API-DGGS_ZoneQuery-ZoneList_JSON-Encoding" target="_blank">_sources/OGC-API-DGGS_ZoneQuery-ZoneList_JSON-Encoding</a></code>

