---
title: OGC API Features Feature with PROV Building Block (Schema)


toc_footers:
  - Version 0.1
  - <a href='#'>OGC API Features Feature with PROV Building Block</a>
  - <a href='https://blocks.ogc.org/register.html'>Building Blocks register</a>

search: true

code_clipboard: true

meta:
  - name: OGC API Features Feature with PROV Building Block (Schema)
---


# OGC API Features Feature with PROV Building Block `pangaea.terranexus.dggs.api.geojson-feature_with-prov`

This Building Block serves as a template to combine an OGC API Features Feature Object with a Provenance Chain

<p class="status">
    <span data-rainbow-uri="http://www.opengis.net/def/status">Status</span>:
    <a href="http://www.opengis.net/def/status/under-development" target="_blank" data-rainbow-uri>Under development</a>
</p>

<aside class="warning">
Validation for this building block has <strong><a href="https://github.com/geofizzydrink/test_bblock/blob/master/build/tests/terranexus/dggs/api/geojson-feature_with-prov/" target="_blank">failed</a></strong>
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
    "id": "2305843009231960466",
    "type": "Feature",
    "geometry": {
        "type": "Polygon",
        "coordinates": [
            [
                [
                    101.5584643981632,
                    3.0545195946434
                ],
                [
                    101.5587178823866,
                    3.0551860804436
                ],
                [
                    101.5585097051152,
                    3.0552650847031
                ],
                [
                    101.5582562208918,
                    3.0545985989028
                ],
                [
                    101.5584643981632,
                    3.0545195946434
                ]
            ]
        ]
    },
    "properties": {
        "feature::id": 2305843009231960466,
        "created_by": "Potlatch 0.6",
        "landuse": "residential",
        "building": "yes",
        "id": "2305843009231960466",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1725712335.519846,
        "x_max": -1276146.633556901,
        "x_min": -1276196.2185377243,
        "y_max": 6239978.947472959,
        "y_min": 6239965.272903057,
        "z_max": 337676.8530694004,
        "z_min": 337594.5358394981,
        "dggsZones": {
            "TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2": {
                "0": [
                    "T"
                ],
                "11": [
                    "T28498326851",
                    "T28498326476"
                ]
            }
        }
    },
    "links": [
        {
            "rel": "self",
            "type": "application/geo+json",
            "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
            "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466/2305843009231960466?f=json"
        },
        {
            "rel": "alternate",
            "type": "application/geo+json",
            "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
            "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466/2305843009231960466?f=geojson"
        },
        {
            "rel": "alternate",
            "type": "application/vnd.ogc.fg+json",
            "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
            "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466/2305843009231960466?f=jsonfg"
        },
        {
            "rel": "alternate",
            "type": "application/ld+json",
            "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
            "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466/2305843009231960466?f=jsonld"
        },
        {
            "rel": "alternate",
            "type": "text/html",
            "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
            "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466/2305843009231960466"
        },
        {
            "rel": "collection",
            "type": "application/geo+json",
            "title": "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint",
            "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings?f=json"
        },
        {
            "rel": "collection",
            "type": "text/html",
            "title": "The HTML representation of the resources served from the OGC API Feature Collection Endpoint",
            "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings"
        }
    ],
    "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
    "has_provenance": [
        {
            "provType": "Agent",
            "name": "agents:TerraNexus",
            "agentType": "softwareAgent",
            "actedOnBehalfOf": "agents:PangaeaInnovations",
            "qualifiedDelegation": {
                "id": "roles:Software",
                "type": "Delegation",
                "agent": "agents:PangaeaInnovations",
                "hadRole": "roles:Software"
            }
        },
        {
            "provType": "Agent",
            "name": "agents:admin%40terranexus.pangaeainnovations.com",
            "agentType": "Person",
            "actedOnBehalfOf": "agents:%3COrganisation%3E",
            "qualifiedDelegation": {
                "id": "roles:User",
                "type": "Delegation",
                "agent": "agents:%3COrganisation%3E",
                "hadRole": "roles:User"
            }
        },
        {
            "provType": "Agent",
            "name": "agents:MapDataToZones",
            "agentType": "softwareAgent",
            "actedOnBehalfOf": "agents:TerraNexus",
            "qualifiedDelegation": [
                {
                    "id": "terranexusProcesses:MapDataToZones",
                    "type": "Delegation",
                    "agent": "agents:TerraNexus",
                    "hadRole": "roles:ogcapiProcess"
                }
            ]
        },
        {
            "provType": "Agent",
            "name": "agents:_validate_ogcapi_execute_document",
            "agentType": "softwareAgent",
            "actedOnBehalfOf": "terranexusProcesses:MapDataToZones",
            "qualifiedDelegation": [
                {
                    "id": "agents:_validate_ogcapi_execute_document",
                    "type": "Delegation",
                    "agent": "terranexusProcesses:MapDataToZones",
                    "hadRole": "roles:subProcess"
                }
            ]
        },
        {
            "provType": "Agent",
            "name": "agents:_executeMapDataToZones_process",
            "agentType": "softwareAgent",
            "actedOnBehalfOf": "terranexusProcesses:MapDataToZones",
            "qualifiedDelegation": [
                {
                    "id": "agents:_executeMapDataToZones_process",
                    "type": "Delegation",
                    "agent": "terranexusProcesses:MapDataToZones",
                    "hadRole": "roles:subProcess"
                }
            ]
        },
        {
            "provType": "Agent",
            "name": "agents:map_data",
            "agentType": "softwareAgent",
            "actedOnBehalfOf": "agents:_executeMapDataToZones_process",
            "qualifiedDelegation": [
                {
                    "id": "dggsOperations:map_data",
                    "type": "Delegation",
                    "agent": "agents:_executeMapDataToZones_process",
                    "hadRole": "roles:subProcess"
                }
            ]
        },
        {
            "provType": "Agent",
            "name": "agents:map_data_execution",
            "agentType": "softwareAgent",
            "actedOnBehalfOf": "agents:map_data",
            "qualifiedDelegation": [
                {
                    "id": "dggsOperations:map_data",
                    "type": "Delegation",
                    "agent": "agents:map_data",
                    "hadRole": "roles:subProcess"
                }
            ]
        },
        {
            "provType": "Agent",
            "name": "agents:processData_task",
            "agentType": "softwareAgent",
            "actedOnBehalfOf": "agents:map_data_execution",
            "qualifiedDelegation": [
                {
                    "id": "dggsOperations:map_data_execution",
                    "type": "Delegation",
                    "agent": "agents:map_data_execution",
                    "hadRole": "roles:subProcess"
                }
            ]
        },
        {
            "provType": "Agent",
            "name": "agents:reorganiseData_task",
            "agentType": "softwareAgent",
            "actedOnBehalfOf": "agents:processData_task",
            "qualifiedDelegation": [
                {
                    "id": "dggsOperations:processData_task",
                    "type": "Delegation",
                    "agent": "agents:processData_task",
                    "hadRole": "roles:subProcess"
                }
            ]
        },
        {
            "provType": "Agent",
            "name": "agents:map_featureData_task",
            "agentType": "softwareAgent",
            "actedOnBehalfOf": "agents:processData_task",
            "qualifiedDelegation": [
                {
                    "id": "dggsOperations:processData_task",
                    "type": "Delegation",
                    "agent": "agents:processData_task",
                    "hadRole": "roles:subProcess"
                }
            ]
        },
        {
            "provType": "Agent",
            "name": "agents:get_mapped_child_zones_task",
            "agentType": "softwareAgent",
            "actedOnBehalfOf": "agents:map_featureData_task",
            "qualifiedDelegation": [
                {
                    "id": "dggsOperations:map_featureData_task",
                    "type": "Delegation",
                    "agent": "agents:map_featureData_task",
                    "hadRole": "roles:subProcess"
                }
            ]
        },
        {
            "provType": "Agent",
            "name": "agents:PangaeaInnovations",
            "agentType": "organization"
        },
        {
            "provType": "Agent",
            "name": "agents:%3COrganisation%3E",
            "agentType": "organization"
        },
        {
            "provType": "Activity",
            "id": "activities:MapDataToZones_64169fd6ebbc",
            "activityType": "ogcapiProcessJobExecution",
            "startedAtTime": "2024-09-07T12:28:15.870964+00:00",
            "wasAssociatedWith": [
                "agents:TerraNexus",
                "agents:MapDataToZones",
                "agents:_validate_ogcapi_execute_document",
                "agents:_executeMapDataToZones_process",
                "agents:admin%40terranexus.pangaeainnovations.com",
                "agents:map_data",
                "agents:map_data_execution",
                "agents:processData_task"
            ],
            "qualifiedAssociation": [
                {
                    "id": "agents:TerraNexus",
                    "type": "Association",
                    "agent": "agents:TerraNexus",
                    "hadRole": "roles:Software"
                },
                {
                    "id": "terranexusProcesses:MapDataToZones",
                    "type": "Association",
                    "agent": "agents:MapDataToZones",
                    "hadRole": "roles:ogcapiProcess"
                },
                {
                    "id": "dggsOperations:_validate_ogcapi_execute_document",
                    "type": "Association",
                    "agent": "agents:_validate_ogcapi_execute_document",
                    "hadRole": "roles:Software"
                },
                {
                    "id": "dggsOperations:_executeMapDataToZones_process",
                    "type": "Association",
                    "agent": "agents:_executeMapDataToZones_process",
                    "hadRole": "roles:Software"
                },
                {
                    "id": "agents:admin%40terranexus.pangaeainnovations.com",
                    "type": "Association",
                    "agent": "agents:admin%40terranexus.pangaeainnovations.com",
                    "hadRole": "roles:User"
                },
                {
                    "id": "dggsOperations:map_data",
                    "type": "Association",
                    "agent": "agents:map_data",
                    "hadRole": "roles:Software"
                },
                {
                    "id": "dggsOperations:map_data_execution",
                    "type": "Association",
                    "agent": "agents:map_data_execution",
                    "hadRole": "roles:Software"
                },
                {
                    "id": "dggsOperations:processData_task",
                    "type": "Association",
                    "agent": "agents:processData_task",
                    "hadRole": "roles:Software"
                }
            ],
            "used": [
                "terranexusJobs:MapDataToZones_64169fd6ebbc",
                "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7"
            ],
            "generated": [
                "terranexusJobs:MapDataToZones_64169fd6ebbc",
                "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7"
            ]
        },
        {
            "provType": "Activity",
            "id": "dggsOperations:reorganiseData_task-2305843009231960466-Polygon_0",
            "activityType": "dggsOperation",
            "startedAtTime": "2024-09-07T12:32:15.917439+00:00",
            "wasAssociatedWith": [
                "agents:TerraNexus",
                "agents:admin%40terranexus.pangaeainnovations.com",
                "agents:reorganiseData_task"
            ],
            "qualifiedAssociation": [
                {
                    "id": "agents:TerraNexus",
                    "type": "Association",
                    "agent": "agents:TerraNexus",
                    "hadRole": "roles:Software"
                },
                {
                    "id": "agents:admin%40terranexus.pangaeainnovations.com",
                    "type": "Association",
                    "agent": "agents:admin%40terranexus.pangaeainnovations.com",
                    "hadRole": "roles:User"
                },
                {
                    "id": "dggsOperations:reorganiseData_task",
                    "type": "Association",
                    "agent": "agents:reorganiseData_task",
                    "hadRole": "roles:subProcess"
                }
            ],
            "used": [
                "terranexusJobs:MapDataToZones_64169fd6ebbc",
                "terranexusCollections:osm_singapore_buildings/items/2305843009231960466"
            ],
            "endedAtTime": "2024-09-07T12:32:16.126674+00:00"
        },
        {
            "provType": "Activity",
            "id": "dggsOperations:map_featureData_task-2305843009231960466-Polygon_0",
            "activityType": "dggsOperation",
            "startedAtTime": "2024-09-07T12:32:16.761564+00:00",
            "wasAssociatedWith": [
                "agents:TerraNexus",
                "agents:admin%40terranexus.pangaeainnovations.com",
                "agents:map_featureData_task",
                "agents:get_mapped_child_zones_task"
            ],
            "qualifiedAssociation": [
                {
                    "id": "agents:TerraNexus",
                    "type": "Association",
                    "agent": "agents:TerraNexus",
                    "hadRole": "roles:Software"
                },
                {
                    "id": "agents:admin%40terranexus.pangaeainnovations.com",
                    "type": "Association",
                    "agent": "agents:admin%40terranexus.pangaeainnovations.com",
                    "hadRole": "roles:User"
                },
                {
                    "id": "dggsOperations:map_featureData_task",
                    "type": "Association",
                    "agent": "agents:map_featureData_task",
                    "hadRole": "roles:subProcess"
                },
                {
                    "id": "dggsOperations:get_mapped_child_zones_task",
                    "type": "Association",
                    "agent": "agents:get_mapped_child_zones_task",
                    "hadRole": "roles:subProcess"
                }
            ],
            "used": [
                "terranexusJobs:MapDataToZones_64169fd6ebbc",
                "terranexusCollections:osm_singapore_buildings/items/2305843009231960466",
                "terranexusCollections:osm_singapore_buildings___Properties",
                "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
            ],
            "generated": [
                "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
            ],
            "endedAtTime": "2024-09-07T12:33:29.106657+00:00"
        },
        {
            "provType": "Entity",
            "id": "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7",
            "entityType": "rawData",
            "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
            "hadPrimarySource": [
                "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
            ],
            "generatedAtTime": "2024-09-07T12:28:22.792585+00:00",
            "wasDerivedFrom": "terranexusJobs:MapDataToZones_64169fd6ebbc"
        },
        {
            "provType": "Entity",
            "id": "terranexusCollections:osm_singapore_buildings",
            "entityType": "FeatureCollection",
            "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
            "hadPrimarySource": [
                "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
            ],
            "generatedAtTime": "2024-09-07T12:28:25.304603+00:00",
            "wasDerivedFrom": [
                "terranexusJobs:MapDataToZones_64169fd6ebbc",
                "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7.json"
            ],
            "wasAttributedTo": "dggsOperations:processData_task"
        },
        {
            "provType": "Entity",
            "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960466",
            "entityType": "Feature",
            "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
            "hadPrimarySource": [
                "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
            ],
            "generatedAtTime": "2024-09-07T12:32:14.625194+00:00",
            "wasDerivedFrom": [
                "terranexusJobs:MapDataToZones_64169fd6ebbc",
                "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7.json",
                "terranexusCollections:osm_singapore_buildings"
            ],
            "wasAttributedTo": "dggsOperations:processData_task"
        },
        {
            "provType": "Entity",
            "id": "terranexusJobs:MapDataToZones_64169fd6ebbc",
            "entityType": "ogcapiProcessJob",
            "wasGeneratedBy": "terranexusProcesses:MapDataToZones",
            "hadPrimarySource": [
                "agents:admin%40terranexus.pangaeainnovations.com"
            ],
            "generatedAtTime": "2024-09-07T12:28:22.773864+00:00",
            "wasAttributedTo": [
                "agents:MapDataToZones",
                "agents:admin%40terranexus.pangaeainnovations.com"
            ]
        },
        {
            "provType": "Entity",
            "id": "terranexusCollections:osm_singapore_buildings___Properties",
            "entityType": "FeatureCollectionProperties",
            "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
            "hadPrimarySource": [
                "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
            ],
            "generatedAtTime": "2024-09-07T12:28:25.439676+00:00",
            "wasDerivedFrom": [
                "terranexusJobs:MapDataToZones_64169fd6ebbc",
                "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7.json"
            ],
            "wasAttributedTo": "dggsOperations:processData_task"
        },
        {
            "provType": "Entity",
            "id": "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
            "entityType": "FeatureCollectionDGGSZones",
            "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373-Polygon_0",
            "hadPrimarySource": [
                "terranexusCollections:osm_singapore_buildings",
                "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
            ],
            "generatedAtTime": "2024-09-07T12:28:28.137746+00:00",
            "wasDerivedFrom": [
                "terranexusJobs:MapDataToZones_64169fd6ebbc",
                "terranexusCollections:osm_singapore_buildings",
                "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
            ]
        },
        {
            "provType": "Entity",
            "id": "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2___coverage",
            "entityType": "FeatureCollectionDGGSZoneCoverage",
            "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373-Polygon_0",
            "hadPrimarySource": [
                "terranexusCollections:osm_singapore_buildings",
                "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
            ],
            "generatedAtTime": "2024-09-07T12:28:31.459547+00:00",
            "wasDerivedFrom": [
                "terranexusJobs:MapDataToZones_64169fd6ebbc",
                "terranexusCollections:osm_singapore_buildings",
                "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
            ]
        },
        {
            "provType": "Entity",
            "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
            "entityType": "DGGS",
            "wasGeneratedBy": "dggsOperations:initialiseSurfaceDGGS_TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
            "hadPrimarySource": [
                "agents:TerraNexus"
            ],
            "generatedAtTime": "2024-09-07T12:28:21.069077+00:00"
        }
    ],
    "@context": "https://terranexus.pangaeainnovations.com/context/geojsonFeature.jsonld"
}
```

<blockquote class="lang-specific json">
  <p class="example-links">
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/terranexus/dggs/api/geojson-feature_with-prov/example_2_1.json">Open in new window</a>
    <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=json&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Ftests%2Fterranexus%2Fdggs%2Fapi%2Fgeojson-feature_with-prov%2Fexample_2_1.json&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on JSON Viewer</a></p>
</blockquote>


The content of this example. 


# JSON Schema

```yaml--schema
$schema: https://json-schema.org/draft/2020-12/schema
description: CWL Provenance Chain for DGGS actions
allOf:
- $ref: https://ogcincubator.github.io/bblock-prov-schema/build/annotated/ogc-utils/prov/schema.yaml
- $ref: https://opengeospatial.github.io/bblocks/annotated-schemas/geo/features/feature/schema.yaml
- type: object
- properties:
    a:
      type: string
      format: uri
    b:
      type: number

```

> <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=yaml&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Fannotated%2Fterranexus%2Fdggs%2Fapi%2Fgeojson-feature_with-prov%2Fschema.yaml&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on YAML Viewer</a>

Links to the schema:

* YAML version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/geojson-feature_with-prov/schema.yaml" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/geojson-feature_with-prov/schema.yaml</a>
* JSON version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/geojson-feature_with-prov/schema.json" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/geojson-feature_with-prov/schema.json</a>


# JSON-LD Context

```json--ldContext
{
  "@context": {
    "id": "@id",
    "featureType": "@type",
    "entityType": "@type",
    "has_provenance": {
      "@id": "dct:provenance",
      "@type": "@id"
    },
    "wasGeneratedBy": {
      "@id": "prov:wasGeneratedBy",
      "@type": "@id"
    },
    "wasAttributedTo": {
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
      "@id": "prov:wasAttributedTo",
      "@type": "@id"
    },
    "wasDerivedFrom": {
      "@id": "prov:wasDerivedFrom",
      "@type": "@id"
    },
    "alternateOf": {
      "@id": "prov:alternateOf",
      "@type": "@id"
    },
    "hadPrimarySource": {
      "@id": "prov:hadPrimarySource",
      "@type": "@id"
    },
    "specializationOf": {
      "@id": "prov:specializationOf",
      "@type": "@id"
    },
    "wasInvalidatedBy": {
      "@id": "prov:wasInvalidatedBy",
      "@type": "@id"
    },
    "wasQuotedFrom": {
      "@id": "prov:wasQuotedFrom",
      "@type": "@id"
    },
    "wasRevisionOf": {
      "@id": "prov:wasRevisionOf",
      "@type": "@id"
    },
    "atLocation": {
      "@id": "prov:atLocation",
      "@type": "@id"
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
    "qualifiedGeneration": {
      "@context": {
        "atTime": {
          "@id": "prov:atTime",
          "@type": "xsd:dateTime"
        },
        "hadRole": {
          "@id": "prov:hadRole",
          "@type": "@id"
        },
        "influencer": {
          "@id": "prov:influencer",
          "@type": "@id"
        },
        "hadActivity": {
          "@id": "prov:hadActivity",
          "@type": "@id"
        },
        "activity": {
          "@id": "prov:activity",
          "@type": "@id"
        }
      },
      "@id": "prov:qualifiedGeneration",
      "@type": "@id"
    },
    "qualifiedInvalidation": {
      "@context": {
        "atTime": {
          "@id": "prov:atTime",
          "@type": "xsd:dateTime"
        },
        "hadRole": {
          "@id": "prov:hadRole",
          "@type": "@id"
        },
        "influencer": {
          "@id": "prov:influencer",
          "@type": "@id"
        },
        "hadActivity": {
          "@id": "prov:hadActivity",
          "@type": "@id"
        },
        "activity": {
          "@id": "prov:activity",
          "@type": "@id"
        }
      },
      "@id": "prov:qualifiedInvalidation",
      "@type": "@id"
    },
    "qualifiedDerivation": {
      "@context": {
        "hadGeneration": {
          "@context": {
            "atTime": {
              "@id": "prov:atTime",
              "@type": "xsd:dateTime"
            },
            "hadRole": {
              "@id": "prov:hadRole",
              "@type": "@id"
            },
            "influencer": {
              "@id": "prov:influencer",
              "@type": "@id"
            },
            "activity": {
              "@id": "prov:activity",
              "@type": "@id"
            }
          },
          "@id": "prov:hadGeneration",
          "@type": "@id"
        },
        "hadActivity": {
          "@id": "prov:hadActivity",
          "@type": "@id"
        },
        "hadUsage": {
          "@context": {
            "atTime": {
              "@id": "prov:atTime",
              "@type": "xsd:dateTime"
            }
          },
          "@id": "prov:hadUsage",
          "@type": "@id"
        },
        "entity": {
          "@id": "prov:entity",
          "@type": "@id"
        }
      },
      "@id": "prov:qualifiedDerivation",
      "@type": "@id"
    },
    "qualifiedAttribution": {
      "@context": {
        "agent": {
          "@id": "prov:agent",
          "@type": "@id"
        }
      },
      "@id": "prov:qualifiedAttribution",
      "@type": "@id"
    },
    "wasInfluencedBy": {
      "@id": "prov:wasInfluencedBy",
      "@type": "@id"
    },
    "qualifiedInfluence": {
      "@context": {
        "influencer": {
          "@id": "prov:influencer",
          "@type": "@id"
        },
        "entity": {
          "@id": "prov:entity",
          "@type": "@id"
        },
        "activity": {
          "@id": "prov:activity",
          "@type": "@id"
        },
        "agent": {
          "@id": "prov:agent",
          "@type": "@id"
        }
      },
      "@id": "prov:qualifiedInfluence",
      "@type": "@id"
    },
    "provType": "@type",
    "hadMember": {
      "@id": "prov:hadMember",
      "@type": "@id"
    },
    "activityType": "@type",
    "endedAtTime": {
      "@id": "prov:endedAtTime",
      "@type": "xsd:dateTime"
    },
    "wasAssociatedWith": {
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
      "@id": "prov:wasAssociatedWith",
      "@type": "@id"
    },
    "wasInformedBy": {
      "@id": "prov:wasInformedBy",
      "@type": "@id"
    },
    "used": {
      "@id": "prov:used",
      "@type": "@id"
    },
    "wasStartedBy": {
      "@id": "prov:wasStartedBy",
      "@type": "@id"
    },
    "wasEndedBy": {
      "@id": "prov:wasEndedBy",
      "@type": "@id"
    },
    "invalidated": {
      "@id": "prov:invalidated",
      "@type": "@id"
    },
    "generated": {
      "@id": "prov:generated",
      "@type": "@id"
    },
    "qualifiedUsage": {
      "@context": {
        "atTime": {
          "@id": "prov:atTime",
          "@type": "xsd:dateTime"
        },
        "entity": {
          "@id": "prov:entity",
          "@type": "@id"
        }
      },
      "@id": "prov:qualifiedUsage",
      "@type": "@id"
    },
    "qualifiedCommunication": {
      "@context": {
        "atTime": {
          "@id": "prov:atTime",
          "@type": "xsd:dateTime"
        },
        "hadRole": {
          "@id": "prov:hadRole",
          "@type": "@id"
        },
        "influencer": {
          "@id": "prov:influencer",
          "@type": "@id"
        },
        "hadActivity": {
          "@id": "prov:hadActivity",
          "@type": "@id"
        },
        "activity": {
          "@id": "prov:activity",
          "@type": "@id"
        }
      },
      "@id": "prov:qualifiedCommunication",
      "@type": "@id"
    },
    "qualifiedStart": {
      "@context": {
        "atTime": {
          "@id": "prov:atTime",
          "@type": "xsd:dateTime"
        },
        "entity": {
          "@id": "prov:entity",
          "@type": "@id"
        },
        "hadActivity": {
          "@id": "prov:hadActivity",
          "@type": "@id"
        }
      },
      "@id": "prov:qualifiedStart",
      "@type": "@id"
    },
    "qualifiedEnd": {
      "@context": {
        "atTime": {
          "@id": "prov:atTime",
          "@type": "xsd:dateTime"
        },
        "entity": {
          "@id": "prov:entity",
          "@type": "@id"
        },
        "hadActivity": {
          "@id": "prov:hadActivity",
          "@type": "@id"
        }
      },
      "@id": "prov:qualifiedEnd",
      "@type": "@id"
    },
    "qualifiedAssociation": {
      "@context": {
        "agent": {
          "@id": "prov:agent",
          "@type": "@id"
        },
        "hadRole": {
          "@id": "prov:hadRole",
          "@type": "@id"
        },
        "hadPlan": {
          "@id": "prov:hadPlan",
          "@type": "@id"
        }
      },
      "@id": "prov:qualifiedAssociation",
      "@type": "@id"
    },
    "agentType": "@type",
    "name": "rdfs:label",
    "actedOnBehalfOf": {
      "@id": "prov:actedOnBehalfOf",
      "@type": "@id"
    },
    "qualifiedDelegation": {
      "@context": {
        "agent": {
          "@id": "prov:agent",
          "@type": "@id"
        },
        "hadActivity": {
          "@id": "prov:hadActivity",
          "@type": "@id"
        }
      },
      "@id": "prov:qualifiedDelegation",
      "@type": "@id"
    },
    "Activity": "prov:Activity",
    "ActivityInfluence": "prov:ActivityInfluence",
    "Agent": "prov:Agent",
    "AgentInfluence": "prov:AgentInfluence",
    "Association": "prov:Association",
    "Attribution": "prov:Attribution",
    "Bundle": "prov:Bundle",
    "Collection": "prov:Collection",
    "Communication": "prov:Communication",
    "Delegation": "prov:Delegation",
    "Derivation": "prov:Derivation",
    "EmptyCollection": "prov:EmptyCollection",
    "End": "prov:End",
    "Entity": "prov:Entity",
    "EntityInfluence": "prov:EntityInfluence",
    "Generation": "prov:Generation",
    "Influence": "prov:Influence",
    "InstantaneousEvent": "prov:InstantaneousEvent",
    "Invalidation": "prov:Invalidation",
    "Location": "prov:Location",
    "Organization": "prov:Organization",
    "Person": "prov:Person",
    "Plan": "prov:Plan",
    "PrimarySource": "prov:PrimarySource",
    "Quotation": "prov:Quotation",
    "Revision": "prov:Revision",
    "Role": "prov:Role",
    "SoftwareAgent": "prov:SoftwareAgent",
    "Start": "prov:Start",
    "Usage": "prov:Usage",
    "ServiceDescription": "prov:ServiceDescription",
    "DirectQueryService": "prov:DirectQueryService",
    "Accept": "prov:Accept",
    "Contribute": "prov:Contribute",
    "Contributor": "prov:Contributor",
    "Copyright": "prov:Copyright",
    "Create": "prov:Create",
    "Creator": "prov:Creator",
    "Modify": "prov:Modify",
    "Publish": "prov:Publish",
    "Publisher": "prov:Publisher",
    "Replace": "prov:Replace",
    "RightsAssignment": "prov:RightsAssignment",
    "RightsHolder": "prov:RightsHolder",
    "Submit": "prov:Submit",
    "Dictionary": "prov:Dictionary",
    "EmptyDictionary": "prov:EmptyDictionary",
    "KeyEntityPair": "prov:KeyEntityPair",
    "Insertion": "prov:Insertion",
    "Removal": "prov:Removal",
    "generatedAtTime": {
      "@id": "prov:generatedAtTime",
      "@type": "xsd:dateTime"
    },
    "invalidatedAtTime": {
      "@id": "prov:invalidatedAtTime",
      "@type": "xsd:dateTime"
    },
    "startedAtTime": {
      "@id": "prov:startedAtTime",
      "@type": "xsd:dateTime"
    },
    "value": "prov:value",
    "provenanceUriTemplate": "prov:provenanceUriTemplate",
    "pairKey": {
      "@id": "prov:pairKey",
      "@type": "rdfs:Literal"
    },
    "removedKey": {
      "@id": "prov:removedKey",
      "@type": "rdfs:Literal"
    },
    "influenced": {
      "@id": "prov:influenced",
      "@type": "@id"
    },
    "qualifiedPrimarySource": {
      "@id": "prov:qualifiedPrimarySource",
      "@type": "@id"
    },
    "qualifiedQuotation": {
      "@id": "prov:qualifiedQuotation",
      "@type": "@id"
    },
    "qualifiedRevision": {
      "@id": "prov:qualifiedRevision",
      "@type": "@id"
    },
    "has_anchor": {
      "@id": "prov:has_anchor",
      "@type": "@id"
    },
    "has_query_service": {
      "@id": "prov:has_query_service",
      "@type": "@id"
    },
    "describesService": {
      "@id": "prov:describesService",
      "@type": "@id"
    },
    "pingback": {
      "@id": "prov:pingback",
      "@type": "@id"
    },
    "dictionary": {
      "@id": "prov:dictionary",
      "@type": "@id"
    },
    "derivedByInsertionFrom": {
      "@id": "prov:derivedByInsertionFrom",
      "@type": "@id"
    },
    "derivedByRemovalFrom": {
      "@id": "prov:derivedByRemovalFrom",
      "@type": "@id"
    },
    "insertedKeyEntityPair": {
      "@id": "prov:insertedKeyEntityPair",
      "@type": "@id"
    },
    "hadDictionaryMember": {
      "@id": "prov:hadDictionaryMember",
      "@type": "@id"
    },
    "pairEntity": {
      "@id": "prov:pairEntity",
      "@type": "@id"
    },
    "qualifiedInsertion": {
      "@id": "prov:qualifiedInsertion",
      "@type": "@id"
    },
    "qualifiedRemoval": {
      "@id": "prov:qualifiedRemoval",
      "@type": "@id"
    },
    "asInBundle": {
      "@id": "prov:asInBundle",
      "@type": "@id"
    },
    "mentionOf": {
      "@id": "prov:mentionOf",
      "@type": "@id"
    },
    "type": "@type",
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
      "@id": "geojson:features"
    },
    "prov": "http://www.w3.org/ns/prov#",
    "xsd": "http://www.w3.org/2001/XMLSchema#",
    "rdfs": "http://www.w3.org/2000/01/rdf-schema#",
    "dct": "http://purl.org/dc/terms/",
    "rdf": "http://www.w3.org/1999/02/22-rdf-syntax-ns#",
    "oa": "http://www.w3.org/ns/oa#",
    "geojson": "https://purl.org/geojson/vocab#",
    "@version": 1.1
  }
}
```

> <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Fannotated%2Fterranexus%2Fdggs%2Fapi%2Fgeojson-feature_with-prov%2Fcontext.jsonld">View on JSON-LD Playground</a>

You can find the full JSON-LD context here:
<a href="https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/geojson-feature_with-prov/context.jsonld" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/geojson-feature_with-prov/context.jsonld</a>

# References

* [Sample source document](https://example.com/sources/1)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: <a href="https://github.com/geofizzydrink/test_bblock" target="_blank">https://github.com/geofizzydrink/test_bblock</a>
* Path:
<code><a href="https://github.com/geofizzydrink/test_bblock/blob/HEAD/_sources/geojson-feature_with-prov" target="_blank">_sources/geojson-feature_with-prov</a></code>

