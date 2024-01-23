---
title: OGC API Features Feature with PROV Building Block (Schema)

language_tabs:
  - json: JSON
  - jsonld: JSON-LD
  - turtle: RDF/Turtle

toc_footers:
  - Version 0.1
  - <a href='#'>OGC API Features Feature with PROV Building Block</a>
  - <a href='https://blocks.ogc.org/register.html'>Building Blocks register</a>

search: true

code_clipboard: true

meta:
  - name: OGC API Features Feature with PROV Building Block (Schema)
---


# OGC API Features Feature with PROV Building Block `ogc.bbr.template.geojson-feature_with-prov`

This Building Block serves as a template to combine an OGC API Features Feature Object with a Provenance Chain

<p class="status">
    <span data-rainbow-uri="http://www.opengis.net/def/status">Status</span>:
    <a href="http://www.opengis.net/def/status/under-development" target="_blank" data-rainbow-uri>Under development</a>
</p>

<aside class="warning">
Validation for this building block has <strong><a href="https://github.com/geofizzydrink/test_bblock/blob/master/build/tests/bbr/template/geojson-feature_with-prov/" target="_blank">failed</a></strong>
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
    "id": "2305843009231960767",
    "type": "Feature",
    "geometry": {
        "type": "Polygon",
        "coordinates": [
            [
                [
                    101.5588419840376,
                    3.0544571875653
                ],
                [
                    101.5590699018958,
                    3.0550587096509
                ],
                [
                    101.5588714901377,
                    3.0551331035822
                ],
                [
                    101.558639381072,
                    3.0545296954532
                ],
                [
                    101.5588419840376,
                    3.0544571875653
                ]
            ]
        ]
    },
    "properties": {
        "feature::id": 2305843009231960767,
        "created_by": "Potlatch 0.6",
        "landuse": "residential",
        "building": "yes",
        "id": "2305843009231960767",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1705555505.121365,
        "x_max": -1276188.4441563762,
        "x_min": -1276234.706646427,
        "y_max": 6239970.810990351,
        "y_min": 6239958.167388152,
        "z_max": 337662.2796796035,
        "z_min": 337587.6448291851,
        "dggsZones": {
            "TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2": {
                "0": [
                    "T"
                ],
                "1": [
                    "T2"
                ],
                "2": [
                    "T28"
                ],
                "3": [
                    "T284"
                ],
                "4": [
                    "T2849"
                ],
                "5": [
                    "T28498"
                ],
                "6": [
                    "T284983"
                ],
                "7": [
                    "T2849832"
                ],
                "8": [
                    "T28498326"
                ],
                "9": [
                    "T284983268",
                    "T284983264"
                ],
                "10": [
                    "T2849832683",
                    "T2849832648",
                    "T2849832684"
                ],
                "11": [
                    "T28498326835",
                    "T28498326488",
                    "T28498326487",
                    "T28498326841"
                ],
                "12": [
                    "T284983268359",
                    "T284983264886",
                    "T284983264873",
                    "T284983268412"
                ],
                "13": [
                    "T2849832683597",
                    "T2849832648861",
                    "T2849832648735",
                    "T2849832684129"
                ]
            }
        }
    },
    "links": [
        {
            "rel": "self",
            "type": "application/geo+json",
            "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
            "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767/2305843009231960767?f=json"
        },
        {
            "rel": "alternate",
            "type": "application/geo+json",
            "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
            "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767/2305843009231960767?f=geojson"
        },
        {
            "rel": "alternate",
            "type": "application/vnd.ogc.fg+json",
            "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
            "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767/2305843009231960767?f=jsonfg"
        },
        {
            "rel": "alternate",
            "type": "application/ld+json",
            "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
            "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767/2305843009231960767?f=jsonld"
        },
        {
            "rel": "alternate",
            "type": "text/html",
            "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
            "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767/2305843009231960767"
        },
        {
            "rel": "collection",
            "type": "application/geo+json",
            "title": "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint",
            "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings?f=json"
        },
        {
            "rel": "collection",
            "type": "text/html",
            "title": "The HTML representation of the resources served from the OGC API Feature Collection Endpoint",
            "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings"
        }
    ],
    "wasGeneratedBy": "dggsOperations:processData_task",
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
            "name": "agents:MapDataToZones_cae879d1d789",
            "agentType": "softwareAgent",
            "actedOnBehalfOf": "agents:TerraNexus",
            "qualifiedDelegation": [
                {
                    "id": "ogcapiProcess",
                    "type": "Delegation",
                    "agent": "agents:TerraNexus",
                    "hadRole": "roles:ogcapiProcessJob",
                    "hadActivity": "terranexusProcesses:execution/MapDataToZones"
                }
            ]
        },
        {
            "provType": "Agent",
            "name": "agents:PangaeaInnovations",
            "agentType": "organization",
            "actedOnBehalfOf": NaN,
            "qualifiedDelegation": NaN
        },
        {
            "provType": "Agent",
            "name": "agents:%3COrganisation%3E",
            "agentType": "organization",
            "actedOnBehalfOf": NaN,
            "qualifiedDelegation": NaN
        },
        {
            "provType": "Activity",
            "id": "terranexusProcesses:execution/MapDataToZones",
            "activityType": "ogcapiProcess",
            "startedAtTime": "2024-01-18T05:23:20.573582+00:00",
            "wasAssociatedWith": [
                "agents:TerraNexus",
                "agents:MapDataToZones_cae879d1d789",
                "agents:admin%40terranexus.pangaeainnovations.com"
            ],
            "qualifiedAssociation": [
                {
                    "id": "agents:TerraNexus",
                    "type": "Association",
                    "agent": "agents:TerraNexus",
                    "hadRole": "roles:Software"
                },
                {
                    "id": "agents:MapDataToZones_cae879d1d789",
                    "type": "Association",
                    "agent": "agents:MapDataToZones_cae879d1d789",
                    "hadRole": "roles:ogcapiProcessJob"
                },
                {
                    "id": "agents:admin%40terranexus.pangaeainnovations.com",
                    "type": "Association",
                    "agent": "agents:admin%40terranexus.pangaeainnovations.com",
                    "hadRole": "roles:User"
                }
            ],
            "used": [
                "terranexusJobs:MapDataToZones_cae879d1d789"
            ],
            "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
            "generated": [
                "terranexusJobs:MapDataToZones_cae879d1d789",
                "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
            ],
            "wasInformedBy": NaN
        },
        {
            "provType": "Activity",
            "id": "dggsOperations:map_data",
            "activityType": "dggsOperation",
            "startedAtTime": "2024-01-18T05:23:24.720180+00:00",
            "wasAssociatedWith": [
                "agents:TerraNexus",
                "agents:MapDataToZones_cae879d1d789",
                "agents:admin%40terranexus.pangaeainnovations.com"
            ],
            "qualifiedAssociation": [
                {
                    "id": "agents:TerraNexus",
                    "type": "Association",
                    "agent": "agents:TerraNexus",
                    "hadRole": "roles:Software"
                },
                {
                    "id": "agents:MapDataToZones_cae879d1d789",
                    "type": "Association",
                    "agent": "agents:MapDataToZones_cae879d1d789",
                    "hadRole": "roles:ogcapiProcessJob"
                },
                {
                    "id": "agents:admin%40terranexus.pangaeainnovations.com",
                    "type": "Association",
                    "agent": "agents:admin%40terranexus.pangaeainnovations.com",
                    "hadRole": "roles:User"
                }
            ],
            "used": [
                "terranexusJobs:MapDataToZones_cae879d1d789"
            ],
            "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
            "generated": NaN,
            "wasInformedBy": [
                "terranexusProcesses:execution/MapDataToZones"
            ]
        },
        {
            "provType": "Activity",
            "id": "dggsOperations:map_data_execution",
            "activityType": "dggsOperation",
            "startedAtTime": "2024-01-18T05:23:24.988304+00:00",
            "wasAssociatedWith": [
                "agents:TerraNexus",
                "agents:MapDataToZones_cae879d1d789",
                "agents:admin%40terranexus.pangaeainnovations.com"
            ],
            "qualifiedAssociation": [
                {
                    "id": "agents:TerraNexus",
                    "type": "Association",
                    "agent": "agents:TerraNexus",
                    "hadRole": "roles:Software"
                },
                {
                    "id": "agents:MapDataToZones_cae879d1d789",
                    "type": "Association",
                    "agent": "agents:MapDataToZones_cae879d1d789",
                    "hadRole": "roles:ogcapiProcessJob"
                },
                {
                    "id": "agents:admin%40terranexus.pangaeainnovations.com",
                    "type": "Association",
                    "agent": "agents:admin%40terranexus.pangaeainnovations.com",
                    "hadRole": "roles:User"
                }
            ],
            "used": [
                "terranexusJobs:MapDataToZones_cae879d1d789"
            ],
            "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
            "generated": NaN,
            "wasInformedBy": [
                "terranexusProcesses:execution/MapDataToZones",
                "dggsOperations:map_data"
            ]
        },
        {
            "provType": "Activity",
            "id": "dggsOperations:processData_task",
            "activityType": "dggsOperation",
            "startedAtTime": "2024-01-18T05:23:25.145391+00:00",
            "wasAssociatedWith": [
                "agents:TerraNexus",
                "agents:MapDataToZones_cae879d1d789",
                "agents:admin%40terranexus.pangaeainnovations.com"
            ],
            "qualifiedAssociation": [
                {
                    "id": "agents:TerraNexus",
                    "type": "Association",
                    "agent": "agents:TerraNexus",
                    "hadRole": "roles:Software"
                },
                {
                    "id": "agents:MapDataToZones_cae879d1d789",
                    "type": "Association",
                    "agent": "agents:MapDataToZones_cae879d1d789",
                    "hadRole": "roles:ogcapiProcessJob"
                },
                {
                    "id": "agents:admin%40terranexus.pangaeainnovations.com",
                    "type": "Association",
                    "agent": "agents:admin%40terranexus.pangaeainnovations.com",
                    "hadRole": "roles:User"
                }
            ],
            "used": [
                "terranexusJobs:MapDataToZones_cae879d1d789",
                "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
            ],
            "endedAtTime": "2024-01-18T05:32:32.684655+00:00",
            "generated": [
                "terranexusCollections:osm_singapore_buildings",
                "terranexusCollections:osm_singapore_buildings___Properties",
                "terranexusCollections:osm_singapore_buildings/items/2305843009229499373",
                "terranexusCollections:osm_singapore_buildings/items/2305843009231960349",
                "terranexusCollections:osm_singapore_buildings/items/2305843009231960466",
                "terranexusCollections:osm_singapore_buildings/items/2305843009231960589",
                "terranexusCollections:osm_singapore_buildings/items/2305843009231960619",
                "terranexusCollections:osm_singapore_buildings/items/2305843009231960767",
                "terranexusCollections:osm_singapore_buildings/items/2305843009231960798",
                "terranexusCollections:osm_singapore_buildings/items/2305843009231960865",
                "terranexusCollections:osm_singapore_buildings/items/2305843009232899975",
                "terranexusCollections:osm_singapore_buildings/items/2305843009232900002",
                "terranexusCollections:osm_singapore_buildings/items/2305843009232901459",
                "terranexusCollections:osm_singapore_buildings/items/2305843009232901461",
                "terranexusCollections:osm_singapore_buildings/items/2305843009232901565",
                "terranexusCollections:osm_singapore_buildings/items/2305843009233038522",
                "terranexusCollections:osm_singapore_buildings/items/2305843009233494536"
            ],
            "wasInformedBy": [
                "terranexusProcesses:execution/MapDataToZones",
                "dggsOperations:map_data",
                "dggsOperations:map_data_execution"
            ]
        },
        {
            "provType": "Activity",
            "id": "dggsOperations:reorganiseData_task-2305843009231960767",
            "activityType": "dggsOperation",
            "startedAtTime": "2024-01-18T05:25:05.165396+00:00",
            "wasAssociatedWith": [
                "agents:TerraNexus",
                "agents:MapDataToZones_cae879d1d789",
                "agents:admin%40terranexus.pangaeainnovations.com"
            ],
            "qualifiedAssociation": [
                {
                    "id": "agents:TerraNexus",
                    "type": "Association",
                    "agent": "agents:TerraNexus",
                    "hadRole": "roles:Software"
                },
                {
                    "id": "agents:MapDataToZones_cae879d1d789",
                    "type": "Association",
                    "agent": "agents:MapDataToZones_cae879d1d789",
                    "hadRole": "roles:ogcapiProcessJob"
                },
                {
                    "id": "agents:admin%40terranexus.pangaeainnovations.com",
                    "type": "Association",
                    "agent": "agents:admin%40terranexus.pangaeainnovations.com",
                    "hadRole": "roles:User"
                }
            ],
            "used": [
                "terranexusJobs:MapDataToZones_cae879d1d789"
            ],
            "endedAtTime": "2024-01-18T05:25:05.226533+00:00",
            "generated": NaN,
            "wasInformedBy": [
                "terranexusProcesses:execution/MapDataToZones",
                "dggsOperations:map_data",
                "dggsOperations:map_data_execution",
                "dggsOperations:processData_task"
            ]
        },
        {
            "provType": "Activity",
            "id": "dggsOperations:map_featureData_task-2305843009231960767",
            "activityType": "dggsOperation",
            "startedAtTime": "2024-01-18T05:25:05.308776+00:00",
            "wasAssociatedWith": [
                "agents:TerraNexus",
                "agents:MapDataToZones_cae879d1d789",
                "agents:admin%40terranexus.pangaeainnovations.com"
            ],
            "qualifiedAssociation": [
                {
                    "id": "agents:TerraNexus",
                    "type": "Association",
                    "agent": "agents:TerraNexus",
                    "hadRole": "roles:Software"
                },
                {
                    "id": "agents:MapDataToZones_cae879d1d789",
                    "type": "Association",
                    "agent": "agents:MapDataToZones_cae879d1d789",
                    "hadRole": "roles:ogcapiProcessJob"
                },
                {
                    "id": "agents:admin%40terranexus.pangaeainnovations.com",
                    "type": "Association",
                    "agent": "agents:admin%40terranexus.pangaeainnovations.com",
                    "hadRole": "roles:User"
                }
            ],
            "used": [
                "terranexusJobs:MapDataToZones_cae879d1d789"
            ],
            "endedAtTime": "2024-01-18T05:25:28.430251+00:00",
            "generated": [
                "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
            ],
            "wasInformedBy": [
                "terranexusProcesses:execution/MapDataToZones",
                "dggsOperations:map_data",
                "dggsOperations:map_data_execution",
                "dggsOperations:processData_task",
                "dggsOperations:reorganiseData_task-2305843009231960767"
            ]
        },
        {
            "provType": "Entity",
            "id": "terranexusJobs:MapDataToZones_cae879d1d789",
            "entityType": "ogcapiProcessJob",
            "hadPrimarySource": [
                "agents:admin%40terranexus.pangaeainnovations.com"
            ],
            "generatedAtTime": "2024-01-18T05:23:24.651036+00:00",
            "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
            "wasDerivedFrom": NaN
        },
        {
            "provType": "Entity",
            "id": "terranexusCollections:osm_singapore_buildings",
            "entityType": "FeatureCollection",
            "hadPrimarySource": [
                "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
            ],
            "generatedAtTime": "2024-01-18T05:23:25.388490+00:00",
            "wasGeneratedBy": "dggsOperations:processData_task",
            "wasDerivedFrom": [
                "terranexusJobs:MapDataToZones_cae879d1d789",
                "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
            ]
        },
        {
            "provType": "Entity",
            "id": "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9",
            "entityType": "rawData",
            "hadPrimarySource": [
                "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
            ],
            "generatedAtTime": "2024-01-18T05:23:24.663693+00:00",
            "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
            "wasDerivedFrom": "terranexusJobs:MapDataToZones_cae879d1d789"
        },
        {
            "provType": "Entity",
            "id": "terranexusCollections:osm_singapore_buildings___Properties",
            "entityType": "FeatureCollectionProperties",
            "hadPrimarySource": [
                "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
            ],
            "generatedAtTime": "2024-01-18T05:23:25.444245+00:00",
            "wasGeneratedBy": "dggsOperations:processData_task",
            "wasDerivedFrom": [
                "terranexusJobs:MapDataToZones_cae879d1d789",
                "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
            ]
        },
        {
            "provType": "Entity",
            "id": "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
            "entityType": "FeatureCollectionDGGSZones",
            "hadPrimarySource": [
                "terranexusCollections:osm_singapore_buildings",
                "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
            ],
            "generatedAtTime": "2024-01-18T05:23:27.310511+00:00",
            "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373",
            "wasDerivedFrom": [
                "terranexusJobs:MapDataToZones_cae879d1d789",
                "terranexusCollections:osm_singapore_buildings",
                "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
            ]
        },
        {
            "provType": "Entity",
            "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960767",
            "entityType": "Feature",
            "hadPrimarySource": [
                "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
            ],
            "generatedAtTime": "2024-01-18T05:25:05.050331+00:00",
            "wasGeneratedBy": "dggsOperations:processData_task",
            "wasDerivedFrom": [
                "terranexusJobs:MapDataToZones_cae879d1d789",
                "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json",
                "terranexusCollections:osm_singapore_buildings"
            ]
        },
        {
            "provType": "Entity",
            "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
            "entityType": "DGGS",
            "hadPrimarySource": [
                "agents:TerraNexus"
            ],
            "generatedAtTime": "2024-01-18T05:23:22.485613+00:00",
            "wasGeneratedBy": NaN,
            "wasDerivedFrom": NaN
        }
    ],
    "@context": [
        "https://ogcincubator.github.io/bblock-prov-schema/build/annotated/ogc-utils/prov/context.jsonld",
        "https://opengeospatial.github.io/bblocks/annotated-schemas/geo/json-fg/feature/context.jsonld",
        {
            "base_href": "http://192.168.39.167:30560/",
            "agents": "base_href:prov/agents/",
            "roles": "base_href:prov/roles/",
            "dggsOperations": "base_href:prov/dggsOperations/",
            "terranexusProcesses": "base_href:ogcapi/processes/",
            "terranexusCollections": "base_href:ogcapi/collections/",
            "terranexusDGGS": "base_href:ogcapi/dggs/",
            "terranexusJobs": "base_href:ogcapi/jobs/",
            "terranexusTempData": "base_href:prov/tempData/"
        }
    ]
}
```

<blockquote class="lang-specific json">
  <p class="example-links">
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/bbr/template/geojson-feature_with-prov/example_2_1.json">Open in new window</a>
    <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=json&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Ftests%2Fbbr%2Ftemplate%2Fgeojson-feature_with-prov%2Fexample_2_1.json&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on JSON Viewer</a></p>
</blockquote>




```jsonld
{
  "id": "2305843009231960767",
  "type": "Feature",
  "geometry": {
    "type": "Polygon",
    "coordinates": [
      [
        [
          101.5588419840376,
          3.0544571875653
        ],
        [
          101.5590699018958,
          3.0550587096509
        ],
        [
          101.5588714901377,
          3.0551331035822
        ],
        [
          101.558639381072,
          3.0545296954532
        ],
        [
          101.5588419840376,
          3.0544571875653
        ]
      ]
    ]
  },
  "properties": {
    "feature::id": 2305843009231960767,
    "created_by": "Potlatch 0.6",
    "landuse": "residential",
    "building": "yes",
    "id": "2305843009231960767",
    "record_type": "Feature",
    "geometry_type": "Polygon",
    "created": 1705555505.121365,
    "x_max": -1276188.4441563762,
    "x_min": -1276234.706646427,
    "y_max": 6239970.810990351,
    "y_min": 6239958.167388152,
    "z_max": 337662.2796796035,
    "z_min": 337587.6448291851,
    "dggsZones": {
      "TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2": {
        "0": [
          "T"
        ],
        "1": [
          "T2"
        ],
        "2": [
          "T28"
        ],
        "3": [
          "T284"
        ],
        "4": [
          "T2849"
        ],
        "5": [
          "T28498"
        ],
        "6": [
          "T284983"
        ],
        "7": [
          "T2849832"
        ],
        "8": [
          "T28498326"
        ],
        "9": [
          "T284983268",
          "T284983264"
        ],
        "10": [
          "T2849832683",
          "T2849832648",
          "T2849832684"
        ],
        "11": [
          "T28498326835",
          "T28498326488",
          "T28498326487",
          "T28498326841"
        ],
        "12": [
          "T284983268359",
          "T284983264886",
          "T284983264873",
          "T284983268412"
        ],
        "13": [
          "T2849832683597",
          "T2849832648861",
          "T2849832648735",
          "T2849832684129"
        ]
      }
    }
  },
  "links": [
    {
      "rel": "self",
      "type": "application/geo+json",
      "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
      "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767/2305843009231960767?f=json"
    },
    {
      "rel": "alternate",
      "type": "application/geo+json",
      "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
      "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767/2305843009231960767?f=geojson"
    },
    {
      "rel": "alternate",
      "type": "application/vnd.ogc.fg+json",
      "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
      "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767/2305843009231960767?f=jsonfg"
    },
    {
      "rel": "alternate",
      "type": "application/ld+json",
      "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
      "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767/2305843009231960767?f=jsonld"
    },
    {
      "rel": "alternate",
      "type": "text/html",
      "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
      "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767/2305843009231960767"
    },
    {
      "rel": "collection",
      "type": "application/geo+json",
      "title": "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint",
      "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings?f=json"
    },
    {
      "rel": "collection",
      "type": "text/html",
      "title": "The HTML representation of the resources served from the OGC API Feature Collection Endpoint",
      "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings"
    }
  ],
  "wasGeneratedBy": "dggsOperations:processData_task",
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
      "name": "agents:MapDataToZones_cae879d1d789",
      "agentType": "softwareAgent",
      "actedOnBehalfOf": "agents:TerraNexus",
      "qualifiedDelegation": [
        {
          "id": "ogcapiProcess",
          "type": "Delegation",
          "agent": "agents:TerraNexus",
          "hadRole": "roles:ogcapiProcessJob",
          "hadActivity": "terranexusProcesses:execution/MapDataToZones"
        }
      ]
    },
    {
      "provType": "Agent",
      "name": "agents:PangaeaInnovations",
      "agentType": "organization",
      "actedOnBehalfOf": NaN,
      "qualifiedDelegation": NaN
    },
    {
      "provType": "Agent",
      "name": "agents:%3COrganisation%3E",
      "agentType": "organization",
      "actedOnBehalfOf": NaN,
      "qualifiedDelegation": NaN
    },
    {
      "provType": "Activity",
      "id": "terranexusProcesses:execution/MapDataToZones",
      "activityType": "ogcapiProcess",
      "startedAtTime": "2024-01-18T05:23:20.573582+00:00",
      "wasAssociatedWith": [
        "agents:TerraNexus",
        "agents:MapDataToZones_cae879d1d789",
        "agents:admin%40terranexus.pangaeainnovations.com"
      ],
      "qualifiedAssociation": [
        {
          "id": "agents:TerraNexus",
          "type": "Association",
          "agent": "agents:TerraNexus",
          "hadRole": "roles:Software"
        },
        {
          "id": "agents:MapDataToZones_cae879d1d789",
          "type": "Association",
          "agent": "agents:MapDataToZones_cae879d1d789",
          "hadRole": "roles:ogcapiProcessJob"
        },
        {
          "id": "agents:admin%40terranexus.pangaeainnovations.com",
          "type": "Association",
          "agent": "agents:admin%40terranexus.pangaeainnovations.com",
          "hadRole": "roles:User"
        }
      ],
      "used": [
        "terranexusJobs:MapDataToZones_cae879d1d789"
      ],
      "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
      "generated": [
        "terranexusJobs:MapDataToZones_cae879d1d789",
        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
      ],
      "wasInformedBy": NaN
    },
    {
      "provType": "Activity",
      "id": "dggsOperations:map_data",
      "activityType": "dggsOperation",
      "startedAtTime": "2024-01-18T05:23:24.720180+00:00",
      "wasAssociatedWith": [
        "agents:TerraNexus",
        "agents:MapDataToZones_cae879d1d789",
        "agents:admin%40terranexus.pangaeainnovations.com"
      ],
      "qualifiedAssociation": [
        {
          "id": "agents:TerraNexus",
          "type": "Association",
          "agent": "agents:TerraNexus",
          "hadRole": "roles:Software"
        },
        {
          "id": "agents:MapDataToZones_cae879d1d789",
          "type": "Association",
          "agent": "agents:MapDataToZones_cae879d1d789",
          "hadRole": "roles:ogcapiProcessJob"
        },
        {
          "id": "agents:admin%40terranexus.pangaeainnovations.com",
          "type": "Association",
          "agent": "agents:admin%40terranexus.pangaeainnovations.com",
          "hadRole": "roles:User"
        }
      ],
      "used": [
        "terranexusJobs:MapDataToZones_cae879d1d789"
      ],
      "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
      "generated": NaN,
      "wasInformedBy": [
        "terranexusProcesses:execution/MapDataToZones"
      ]
    },
    {
      "provType": "Activity",
      "id": "dggsOperations:map_data_execution",
      "activityType": "dggsOperation",
      "startedAtTime": "2024-01-18T05:23:24.988304+00:00",
      "wasAssociatedWith": [
        "agents:TerraNexus",
        "agents:MapDataToZones_cae879d1d789",
        "agents:admin%40terranexus.pangaeainnovations.com"
      ],
      "qualifiedAssociation": [
        {
          "id": "agents:TerraNexus",
          "type": "Association",
          "agent": "agents:TerraNexus",
          "hadRole": "roles:Software"
        },
        {
          "id": "agents:MapDataToZones_cae879d1d789",
          "type": "Association",
          "agent": "agents:MapDataToZones_cae879d1d789",
          "hadRole": "roles:ogcapiProcessJob"
        },
        {
          "id": "agents:admin%40terranexus.pangaeainnovations.com",
          "type": "Association",
          "agent": "agents:admin%40terranexus.pangaeainnovations.com",
          "hadRole": "roles:User"
        }
      ],
      "used": [
        "terranexusJobs:MapDataToZones_cae879d1d789"
      ],
      "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
      "generated": NaN,
      "wasInformedBy": [
        "terranexusProcesses:execution/MapDataToZones",
        "dggsOperations:map_data"
      ]
    },
    {
      "provType": "Activity",
      "id": "dggsOperations:processData_task",
      "activityType": "dggsOperation",
      "startedAtTime": "2024-01-18T05:23:25.145391+00:00",
      "wasAssociatedWith": [
        "agents:TerraNexus",
        "agents:MapDataToZones_cae879d1d789",
        "agents:admin%40terranexus.pangaeainnovations.com"
      ],
      "qualifiedAssociation": [
        {
          "id": "agents:TerraNexus",
          "type": "Association",
          "agent": "agents:TerraNexus",
          "hadRole": "roles:Software"
        },
        {
          "id": "agents:MapDataToZones_cae879d1d789",
          "type": "Association",
          "agent": "agents:MapDataToZones_cae879d1d789",
          "hadRole": "roles:ogcapiProcessJob"
        },
        {
          "id": "agents:admin%40terranexus.pangaeainnovations.com",
          "type": "Association",
          "agent": "agents:admin%40terranexus.pangaeainnovations.com",
          "hadRole": "roles:User"
        }
      ],
      "used": [
        "terranexusJobs:MapDataToZones_cae879d1d789",
        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
      ],
      "endedAtTime": "2024-01-18T05:32:32.684655+00:00",
      "generated": [
        "terranexusCollections:osm_singapore_buildings",
        "terranexusCollections:osm_singapore_buildings___Properties",
        "terranexusCollections:osm_singapore_buildings/items/2305843009229499373",
        "terranexusCollections:osm_singapore_buildings/items/2305843009231960349",
        "terranexusCollections:osm_singapore_buildings/items/2305843009231960466",
        "terranexusCollections:osm_singapore_buildings/items/2305843009231960589",
        "terranexusCollections:osm_singapore_buildings/items/2305843009231960619",
        "terranexusCollections:osm_singapore_buildings/items/2305843009231960767",
        "terranexusCollections:osm_singapore_buildings/items/2305843009231960798",
        "terranexusCollections:osm_singapore_buildings/items/2305843009231960865",
        "terranexusCollections:osm_singapore_buildings/items/2305843009232899975",
        "terranexusCollections:osm_singapore_buildings/items/2305843009232900002",
        "terranexusCollections:osm_singapore_buildings/items/2305843009232901459",
        "terranexusCollections:osm_singapore_buildings/items/2305843009232901461",
        "terranexusCollections:osm_singapore_buildings/items/2305843009232901565",
        "terranexusCollections:osm_singapore_buildings/items/2305843009233038522",
        "terranexusCollections:osm_singapore_buildings/items/2305843009233494536"
      ],
      "wasInformedBy": [
        "terranexusProcesses:execution/MapDataToZones",
        "dggsOperations:map_data",
        "dggsOperations:map_data_execution"
      ]
    },
    {
      "provType": "Activity",
      "id": "dggsOperations:reorganiseData_task-2305843009231960767",
      "activityType": "dggsOperation",
      "startedAtTime": "2024-01-18T05:25:05.165396+00:00",
      "wasAssociatedWith": [
        "agents:TerraNexus",
        "agents:MapDataToZones_cae879d1d789",
        "agents:admin%40terranexus.pangaeainnovations.com"
      ],
      "qualifiedAssociation": [
        {
          "id": "agents:TerraNexus",
          "type": "Association",
          "agent": "agents:TerraNexus",
          "hadRole": "roles:Software"
        },
        {
          "id": "agents:MapDataToZones_cae879d1d789",
          "type": "Association",
          "agent": "agents:MapDataToZones_cae879d1d789",
          "hadRole": "roles:ogcapiProcessJob"
        },
        {
          "id": "agents:admin%40terranexus.pangaeainnovations.com",
          "type": "Association",
          "agent": "agents:admin%40terranexus.pangaeainnovations.com",
          "hadRole": "roles:User"
        }
      ],
      "used": [
        "terranexusJobs:MapDataToZones_cae879d1d789"
      ],
      "endedAtTime": "2024-01-18T05:25:05.226533+00:00",
      "generated": NaN,
      "wasInformedBy": [
        "terranexusProcesses:execution/MapDataToZones",
        "dggsOperations:map_data",
        "dggsOperations:map_data_execution",
        "dggsOperations:processData_task"
      ]
    },
    {
      "provType": "Activity",
      "id": "dggsOperations:map_featureData_task-2305843009231960767",
      "activityType": "dggsOperation",
      "startedAtTime": "2024-01-18T05:25:05.308776+00:00",
      "wasAssociatedWith": [
        "agents:TerraNexus",
        "agents:MapDataToZones_cae879d1d789",
        "agents:admin%40terranexus.pangaeainnovations.com"
      ],
      "qualifiedAssociation": [
        {
          "id": "agents:TerraNexus",
          "type": "Association",
          "agent": "agents:TerraNexus",
          "hadRole": "roles:Software"
        },
        {
          "id": "agents:MapDataToZones_cae879d1d789",
          "type": "Association",
          "agent": "agents:MapDataToZones_cae879d1d789",
          "hadRole": "roles:ogcapiProcessJob"
        },
        {
          "id": "agents:admin%40terranexus.pangaeainnovations.com",
          "type": "Association",
          "agent": "agents:admin%40terranexus.pangaeainnovations.com",
          "hadRole": "roles:User"
        }
      ],
      "used": [
        "terranexusJobs:MapDataToZones_cae879d1d789"
      ],
      "endedAtTime": "2024-01-18T05:25:28.430251+00:00",
      "generated": [
        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
      ],
      "wasInformedBy": [
        "terranexusProcesses:execution/MapDataToZones",
        "dggsOperations:map_data",
        "dggsOperations:map_data_execution",
        "dggsOperations:processData_task",
        "dggsOperations:reorganiseData_task-2305843009231960767"
      ]
    },
    {
      "provType": "Entity",
      "id": "terranexusJobs:MapDataToZones_cae879d1d789",
      "entityType": "ogcapiProcessJob",
      "hadPrimarySource": [
        "agents:admin%40terranexus.pangaeainnovations.com"
      ],
      "generatedAtTime": "2024-01-18T05:23:24.651036+00:00",
      "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
      "wasDerivedFrom": NaN
    },
    {
      "provType": "Entity",
      "id": "terranexusCollections:osm_singapore_buildings",
      "entityType": "FeatureCollection",
      "hadPrimarySource": [
        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
      ],
      "generatedAtTime": "2024-01-18T05:23:25.388490+00:00",
      "wasGeneratedBy": "dggsOperations:processData_task",
      "wasDerivedFrom": [
        "terranexusJobs:MapDataToZones_cae879d1d789",
        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
      ]
    },
    {
      "provType": "Entity",
      "id": "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9",
      "entityType": "rawData",
      "hadPrimarySource": [
        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
      ],
      "generatedAtTime": "2024-01-18T05:23:24.663693+00:00",
      "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
      "wasDerivedFrom": "terranexusJobs:MapDataToZones_cae879d1d789"
    },
    {
      "provType": "Entity",
      "id": "terranexusCollections:osm_singapore_buildings___Properties",
      "entityType": "FeatureCollectionProperties",
      "hadPrimarySource": [
        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
      ],
      "generatedAtTime": "2024-01-18T05:23:25.444245+00:00",
      "wasGeneratedBy": "dggsOperations:processData_task",
      "wasDerivedFrom": [
        "terranexusJobs:MapDataToZones_cae879d1d789",
        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
      ]
    },
    {
      "provType": "Entity",
      "id": "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
      "entityType": "FeatureCollectionDGGSZones",
      "hadPrimarySource": [
        "terranexusCollections:osm_singapore_buildings",
        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
      ],
      "generatedAtTime": "2024-01-18T05:23:27.310511+00:00",
      "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373",
      "wasDerivedFrom": [
        "terranexusJobs:MapDataToZones_cae879d1d789",
        "terranexusCollections:osm_singapore_buildings",
        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
      ]
    },
    {
      "provType": "Entity",
      "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960767",
      "entityType": "Feature",
      "hadPrimarySource": [
        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
      ],
      "generatedAtTime": "2024-01-18T05:25:05.050331+00:00",
      "wasGeneratedBy": "dggsOperations:processData_task",
      "wasDerivedFrom": [
        "terranexusJobs:MapDataToZones_cae879d1d789",
        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json",
        "terranexusCollections:osm_singapore_buildings"
      ]
    },
    {
      "provType": "Entity",
      "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
      "entityType": "DGGS",
      "hadPrimarySource": [
        "agents:TerraNexus"
      ],
      "generatedAtTime": "2024-01-18T05:23:22.485613+00:00",
      "wasGeneratedBy": NaN,
      "wasDerivedFrom": NaN
    }
  ],
  "@context": [
    "https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/geojson-feature_with-prov/context.jsonld",
    "https://ogcincubator.github.io/bblock-prov-schema/build/annotated/ogc-utils/prov/context.jsonld",
    "https://opengeospatial.github.io/bblocks/annotated-schemas/geo/json-fg/feature/context.jsonld",
    {
      "base_href": "http://192.168.39.167:30560/",
      "agents": "base_href:prov/agents/",
      "roles": "base_href:prov/roles/",
      "dggsOperations": "base_href:prov/dggsOperations/",
      "terranexusProcesses": "base_href:ogcapi/processes/",
      "terranexusCollections": "base_href:ogcapi/collections/",
      "terranexusDGGS": "base_href:ogcapi/dggs/",
      "terranexusJobs": "base_href:ogcapi/jobs/",
      "terranexusTempData": "base_href:prov/tempData/"
    }
  ]
}
```

<blockquote class="lang-specific jsonld">
  <p class="example-links">
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/bbr/template/geojson-feature_with-prov/example_2_1.jsonld">Open in new window</a>
    <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Ftests%2Fbbr%2Ftemplate%2Fgeojson-feature_with-prov%2Fexample_2_1.jsonld">View on JSON-LD Playground</a>
</blockquote>




```turtle
@prefix agents: <http://192.168.39.167:30560/prov/agents/> .
@prefix dct: <http://purl.org/dc/terms/> .
@prefix dggsOperations: <http://192.168.39.167:30560/prov/dggsOperations/> .
@prefix geojson: <https://purl.org/geojson/vocab#> .
@prefix ns1: <http://www.iana.org/assignments/> .
@prefix ns2: <feature::> .
@prefix oa: <http://www.w3.org/ns/oa#> .
@prefix prov: <http://www.w3.org/ns/prov#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix roles: <http://192.168.39.167:30560/prov/roles/> .
@prefix terranexusCollections: <http://192.168.39.167:30560/ogcapi/collections/> .
@prefix terranexusDGGS: <http://192.168.39.167:30560/ogcapi/dggs/> .
@prefix terranexusJobs: <http://192.168.39.167:30560/ogcapi/jobs/> .
@prefix terranexusTempData: <http://192.168.39.167:30560/prov/tempData/> .
@prefix xsd: <http://www.w3.org/2001/XMLSchema#> .

<file:///github/workspace/2305843009231960767> a geojson:Feature ;
    ns2:id 2305843009231960767 ;
    rdfs:seeAlso [ rdfs:label "The HTML representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget terranexusCollections:osm_singapore_buildings ],
        [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767/2305843009231960767> ],
        [ rdfs:label "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings?f=json> ],
        [ rdfs:label "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767/2305843009231960767?f=json> ],
        [ rdfs:label "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767/2305843009231960767?f=jsonld> ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767/2305843009231960767?f=geojson> ],
        [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767/2305843009231960767?f=jsonfg> ] ;
    prov:has_provenance [ a prov:Agent,
                prov:Person ;
            rdfs:label "agents:admin%40terranexus.pangaeainnovations.com" ;
            prov:actedOnBehalfOf <http://192.168.39.167:30560/prov/agents/%3COrganisation%3E> ;
            prov:qualifiedDelegation roles:User ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:MapDataToZones_cae879d1d789" ;
            prov:actedOnBehalfOf agents:TerraNexus ;
            prov:qualifiedDelegation <file:///github/workspace/ogcapiProcess> ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:%3COrganisation%3E" ;
            prov:actedOnBehalfOf "NaN"^^xsd:double ;
            prov:qualifiedDelegation "NaN"^^xsd:double ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ;
            prov:actedOnBehalfOf "NaN"^^xsd:double ;
            prov:qualifiedDelegation "NaN"^^xsd:double ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        terranexusCollections:osm_singapore_buildings,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767>,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_cae879d1d789,
        <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:map_featureData_task-2305843009231960767,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009231960767,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9 ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( "[[101.5588419840376, 3.0544571875653], [101.5590699018958, 3.0550587096509], [101.5588714901377, 3.0551331035822], [101.558639381072, 3.0545296954532], [101.5588419840376, 3.0544571875653]]" ) ] .

dggsOperations:map_featureData_task-2305843009231960767 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:25:28.430251+00:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:25:05.308776+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009231960767 .

<file:///github/workspace/ogcapiProcess> a prov:Delegation ;
    prov:agent agents:TerraNexus ;
    prov:hadActivity <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones> .

<http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2024-01-18T05:25:05.050331+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

terranexusCollections:osm_singapore_buildings___Properties a <file:///github/workspace/FeatureCollectionProperties>,
        prov:Entity ;
    prov:generatedAtTime "2024-01-18T05:23:25.444245+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 a <file:///github/workspace/FeatureCollectionDGGSZones>,
        prov:Entity ;
    prov:generatedAtTime "2024-01-18T05:23:27.310511+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource terranexusCollections:osm_singapore_buildings,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasGeneratedBy dggsOperations:map_featureData_task-2305843009229499373 .

dggsOperations:reorganiseData_task-2305843009231960767 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:25:05.226533+00:00"^^xsd:dateTime ;
    prov:generated "NaN"^^xsd:double ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:25:05.165396+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task .

roles:Software a prov:Delegation ;
    prov:agent agents:PangaeaInnovations .

roles:User a prov:Delegation ;
    prov:agent <http://192.168.39.167:30560/prov/agents/%3COrganisation%3E> .

terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9 a <file:///github/workspace/rawData>,
        prov:Entity ;
    prov:generatedAtTime "2024-01-18T05:23:24.663693+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasGeneratedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones> .

terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 a <file:///github/workspace/DGGS>,
        prov:Entity ;
    prov:generatedAtTime "2024-01-18T05:23:22.485613+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource agents:TerraNexus ;
    prov:wasDerivedFrom "NaN"^^xsd:double ;
    prov:wasGeneratedBy "NaN"^^xsd:double .

dggsOperations:map_data_execution a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:32:32.752525+00:00"^^xsd:dateTime ;
    prov:generated "NaN"^^xsd:double ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:23:24.988304+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data .

dggsOperations:map_data a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:32:32.888834+00:00"^^xsd:dateTime ;
    prov:generated "NaN"^^xsd:double ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:23:24.720180+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones> .

terranexusCollections:osm_singapore_buildings a prov:Entity,
        geojson:FeatureCollection ;
    prov:generatedAtTime "2024-01-18T05:23:25.388490+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

dggsOperations:processData_task a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:32:32.684655+00:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373>,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349>,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466>,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589>,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619>,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767>,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798>,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865>,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975>,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002>,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901459>,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901461>,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901565>,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233038522>,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233494536>,
        terranexusCollections:osm_singapore_buildings___Properties ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:23:25.145391+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution .

<http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones> a <file:///github/workspace/ogcapiProcess>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:23:24.700855+00:00"^^xsd:dateTime ;
    prov:generated terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9 ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:23:20.573582+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy "NaN"^^xsd:double .

terranexusJobs:MapDataToZones_cae879d1d789 a <file:///github/workspace/ogcapiProcessJob>,
        prov:Entity ;
    prov:generatedAtTime "2024-01-18T05:23:24.651036+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasDerivedFrom "NaN"^^xsd:double ;
    prov:wasGeneratedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones> .

agents:MapDataToZones_cae879d1d789 a prov:Association ;
    prov:agent agents:MapDataToZones_cae879d1d789 ;
    prov:hadRole roles:ogcapiProcessJob .

agents:admin%40terranexus.pangaeainnovations.com a prov:Association ;
    prov:agent agents:admin%40terranexus.pangaeainnovations.com ;
    prov:hadRole roles:User .

agents:TerraNexus a prov:Association ;
    prov:agent agents:TerraNexus ;
    prov:hadRole roles:Software .


```

<blockquote class="lang-specific turtle">
  <p class="example-links">
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/bbr/template/geojson-feature_with-prov/example_2_1.ttl">Open in new window</a>
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

> <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=yaml&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Fannotated%2Fbbr%2Ftemplate%2Fgeojson-feature_with-prov%2Fschema.yaml&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on YAML Viewer</a>

Links to the schema:

* YAML version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/geojson-feature_with-prov/schema.yaml" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/geojson-feature_with-prov/schema.yaml</a>
* JSON version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/geojson-feature_with-prov/schema.json" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/geojson-feature_with-prov/schema.json</a>


# JSON-LD Context

```json--ldContext
{
  "@context": {
    "id": "@id",
    "featureType": "@type",
    "entityType": "@type",
    "has_provenance": {
      "@context": {
        "agentType": "@type",
        "name": "rdfs:label",
        "actedOnBehalfOf": {
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
        }
      },
      "@id": "prov:has_provenance",
      "@type": "@id"
    },
    "wasGeneratedBy": {
      "@context": {},
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
        "length": "dct:extent",
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
        }
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
        "length": "dct:extent",
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
        }
      },
      "@id": "prov:wasInvalidatedBy",
      "@type": "@id"
    },
    "wasQuotedFrom": {
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
        "length": "dct:extent",
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
        }
      },
      "@id": "prov:wasQuotedFrom",
      "@type": "@id"
    },
    "wasRevisionOf": {
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
        "length": "dct:extent",
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
        }
      },
      "@id": "prov:wasRevisionOf",
      "@type": "@id"
    },
    "mentionOf": {
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
        "length": "dct:extent",
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
        }
      },
      "@id": "prov:mentionOf",
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
          "@type": "http://www.w3.org/2001/XMLSchema#dateTime"
        }
      },
      "@id": "prov:qualifiedGeneration",
      "@type": "@id"
    },
    "qualifiedInvalidation": {
      "@context": {
        "atTime": {
          "@id": "prov:atTime",
          "@type": "http://www.w3.org/2001/XMLSchema#dateTime"
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
              "@type": "http://www.w3.org/2001/XMLSchema#dateTime"
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
              "@type": "http://www.w3.org/2001/XMLSchema#dateTime"
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
          "@context": {
            "agentType": "@type",
            "name": "rdfs:label",
            "actedOnBehalfOf": {
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
              "@id": "prov:actedOnBehalfOf",
              "@type": "@id"
            },
            "qualifiedDelegation": {
              "@context": {
                "hadActivity": {
                  "@id": "prov:hadActivity",
                  "@type": "@id"
                }
              },
              "@id": "prov:qualifiedDelegation",
              "@type": "@id"
            }
          },
          "@id": "prov:agent",
          "@type": "@id"
        }
      },
      "@id": "prov:qualifiedAttribution",
      "@type": "@id"
    },
    "wasInfluencedBy": {
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
        "length": "dct:extent",
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
        }
      },
      "@id": "prov:wasInfluencedBy",
      "@type": "@id"
    },
    "qualifiedInfluence": {
      "@context": {
        "influencer": {
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
            "length": "dct:extent",
            "agentType": "@type",
            "name": "rdfs:label",
            "actedOnBehalfOf": {
              "@id": "prov:actedOnBehalfOf",
              "@type": "@id"
            },
            "qualifiedDelegation": {
              "@context": {
                "hadActivity": {
                  "@id": "prov:hadActivity",
                  "@type": "@id"
                }
              },
              "@id": "prov:qualifiedDelegation",
              "@type": "@id"
            }
          },
          "@id": "prov:influencer",
          "@type": "@id"
        },
        "entity": {
          "@id": "prov:entity",
          "@type": "@id"
        },
        "agent": {
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
            "length": "dct:extent",
            "agentType": "@type",
            "name": "rdfs:label",
            "actedOnBehalfOf": {
              "@id": "prov:actedOnBehalfOf",
              "@type": "@id"
            },
            "qualifiedDelegation": {
              "@context": {
                "hadActivity": {
                  "@id": "prov:hadActivity",
                  "@type": "@id"
                }
              },
              "@id": "prov:qualifiedDelegation",
              "@type": "@id"
            }
          },
          "@id": "prov:agent",
          "@type": "@id"
        }
      },
      "@id": "prov:qualifiedInfluence",
      "@type": "@id"
    },
    "provType": "@type",
    "hadMember": {
      "@context": {},
      "@id": "prov:hadMember",
      "@type": "@id"
    },
    "activityType": "@type",
    "endedAtTime": {
      "@id": "prov:endedAtTime",
      "@type": "http://www.w3.org/2001/XMLSchema#dateTime"
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
        "length": "dct:extent",
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
        }
      },
      "@id": "prov:wasAssociatedWith",
      "@type": "@id"
    },
    "wasInformedBy": {
      "@id": "prov:wasInformedBy",
      "@type": "@id"
    },
    "used": {
      "@context": {},
      "@id": "prov:used",
      "@type": "@id"
    },
    "wasStartedBy": {
      "@context": {},
      "@id": "prov:wasStartedBy",
      "@type": "@id"
    },
    "wasEndedBy": {
      "@context": {},
      "@id": "prov:wasEndedBy",
      "@type": "@id"
    },
    "invalidated": {
      "@context": {},
      "@id": "prov:invalidated",
      "@type": "@id"
    },
    "generated": {
      "@context": {},
      "@id": "prov:generated",
      "@type": "@id"
    },
    "qualifiedUsage": {
      "@context": {
        "atTime": {
          "@id": "prov:atTime",
          "@type": "http://www.w3.org/2001/XMLSchema#dateTime"
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
          "@type": "http://www.w3.org/2001/XMLSchema#dateTime"
        }
      },
      "@id": "prov:qualifiedCommunication",
      "@type": "@id"
    },
    "qualifiedStart": {
      "@context": {
        "atTime": {
          "@id": "prov:atTime",
          "@type": "http://www.w3.org/2001/XMLSchema#dateTime"
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
          "@type": "http://www.w3.org/2001/XMLSchema#dateTime"
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
          "@context": {
            "agentType": "@type",
            "name": "rdfs:label",
            "actedOnBehalfOf": {
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
              "@id": "prov:actedOnBehalfOf",
              "@type": "@id"
            },
            "qualifiedDelegation": {
              "@context": {
                "hadActivity": {
                  "@id": "prov:hadActivity",
                  "@type": "@id"
                }
              },
              "@id": "prov:qualifiedDelegation",
              "@type": "@id"
            }
          },
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
      "@type": "http://www.w3.org/2001/XMLSchema#dateTime"
    },
    "invalidatedAtTime": {
      "@id": "prov:invalidatedAtTime",
      "@type": "http://www.w3.org/2001/XMLSchema#dateTime"
    },
    "startedAtTime": {
      "@id": "prov:startedAtTime",
      "@type": "http://www.w3.org/2001/XMLSchema#dateTime"
    },
    "value": "prov:value",
    "provenanceUriTemplate": "prov:provenanceUriTemplate",
    "pairKey": {
      "@id": "prov:pairKey",
      "@type": "http://www.w3.org/2000/01/rdf-schema#Literal"
    },
    "removedKey": {
      "@id": "prov:removedKey",
      "@type": "http://www.w3.org/2000/01/rdf-schema#Literal"
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
    "rdf": "http://www.w3.org/1999/02/22-rdf-syntax-ns#",
    "oa": "http://www.w3.org/ns/oa#",
    "dct": "http://purl.org/dc/terms/",
    "geojson": "https://purl.org/geojson/vocab#",
    "@version": 1.1
  }
}
```

> <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Fannotated%2Fbbr%2Ftemplate%2Fgeojson-feature_with-prov%2Fcontext.jsonld">View on JSON-LD Playground</a>

You can find the full JSON-LD context here:
<a href="https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/geojson-feature_with-prov/context.jsonld" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/geojson-feature_with-prov/context.jsonld</a>

# References

* [Sample source document](https://example.com/sources/1)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: <a href="https://github.com/geofizzydrink/test_bblock" target="_blank">https://github.com/geofizzydrink/test_bblock</a>
* Path:
<code><a href="https://github.com/geofizzydrink/test_bblock/blob/HEAD/_sources/geojson-feature_with-prov" target="_blank">_sources/geojson-feature_with-prov</a></code>

