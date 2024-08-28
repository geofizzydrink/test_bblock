---
title: JSON-FG Feature Collection with PROV Building Block (Schema)

language_tabs:
  - json: JSON
  - jsonld: JSON-LD
  - turtle: RDF/Turtle

toc_footers:
  - Version 0.1
  - <a href='#'>JSON-FG Feature Collection with PROV Building Block</a>
  - <a href='https://blocks.ogc.org/register.html'>Building Blocks register</a>

search: true

code_clipboard: true

meta:
  - name: JSON-FG Feature Collection with PROV Building Block (Schema)
---


# JSON-FG Feature Collection with PROV Building Block `pangaea.terranexus.dggs.api.json-fg-feature-collection_with-prov`

This Building Block serves as a template to combine a JSON-FG Feature Object with a Provenance Chain

<p class="status">
    <span data-rainbow-uri="http://www.opengis.net/def/status">Status</span>:
    <a href="http://www.opengis.net/def/status/under-development" target="_blank" data-rainbow-uri>Under development</a>
</p>

<aside class="success">
This building block is <strong><a href="https://github.com/geofizzydrink/test_bblock/blob/master/build/tests/terranexus/dggs/api/json-fg-feature-collection_with-prov/" target="_blank">valid</a></strong>
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

## Feature Collection



```json
{
    "id": "osm_singapore_buildings",
    "type": "FeatureCollection",
    "numberReturned": 15,
    "numberMatched": 15,
    "features": [
        {
            "id": "2305843009229499373",
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            101.5578365133831,
                            3.0547452911617
                        ],
                        [
                            101.5580674069986,
                            3.0553611890887
                        ],
                        [
                            101.557876707062,
                            3.0554326910869
                        ],
                        [
                            101.5576354192522,
                            3.0548172122807
                        ],
                        [
                            101.5578365133831,
                            3.0547452911617
                        ]
                    ]
                ]
            },
            "properties": {
                "feature-id": 2305843009229499373,
                "created_by": "Potlatch 0.6",
                "landuse": "residential",
                "building": "yes",
                "id": "2305843009229499373",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1705555405.84978,
                "x_max": -1276078.7650104035,
                "x_min": -1276125.1697413276,
                "y_max": 6239991.512113506,
                "y_min": 6239978.749965917,
                "z_max": 337695.36020748876,
                "z_min": 337619.4573208119,
                "line-hidden": "null",
                "amenity": "null",
                "parking": "null",
                "name": "null",
                "is_in": "null",
                "shop": "null",
                "name-zh": "null",
                "addr:city": "null",
                "addr:place": "null",
                "name-en": "null",
                "name-it": "null",
                "leisure": "null",
                "sport": "null",
                "emergency": "null",
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
                            "T284983264"
                        ],
                        "10": [
                            "T2849832649",
                            "T2849832647"
                        ],
                        "11": [
                            "T28498326497",
                            "T28498326474",
                            "T28498326491"
                        ],
                        "12": [
                            "T284983264976",
                            "T284983264749",
                            "T284983264914",
                            "T284983264974"
                        ],
                        "13": [
                            "T2849832649769",
                            "T2849832647499",
                            "T2849832649144",
                            "T2849832649749"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373"
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
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Agent",
                    "name": "agents:%3COrganisation%3E",
                    "agentType": "organization",
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:reorganiseData_task-2305843009229499373",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:23:26.077610+00:00",
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:23:26.385690+00:00",
                    "generated": "null"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009229499373",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:23:26.493850+00:00",
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task",
                        "dggsOperations:reorganiseData_task-2305843009229499373"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:23:41.340327+00:00",
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ]
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
                    "wasInformedBy": "null",
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
                    "generated": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
                    ]
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution"
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
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9",
                    "entityType": "rawData",
                    "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:24.663693+00:00",
                    "wasDerivedFrom": "terranexusJobs:MapDataToZones_cae879d1d789"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings___Properties",
                    "entityType": "FeatureCollectionProperties",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:25.444245+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009229499373",
                    "entityType": "Feature",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:25.507396+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json",
                        "terranexusCollections:osm_singapore_buildings"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
                    "entityType": "FeatureCollectionDGGSZones",
                    "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373",
                    "hadPrimarySource": [
                        "terranexusCollections:osm_singapore_buildings",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:27.310511+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusCollections:osm_singapore_buildings",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusJobs:MapDataToZones_cae879d1d789",
                    "entityType": "ogcapiProcessJob",
                    "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
                    "hadPrimarySource": [
                        "agents:admin%40terranexus.pangaeainnovations.com"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:24.651036+00:00",
                    "wasDerivedFrom": "null"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings",
                    "entityType": "FeatureCollection",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:25.388490+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
                    "entityType": "DGGS",
                    "wasGeneratedBy": "null",
                    "hadPrimarySource": [
                        "agents:TerraNexus"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:22.485613+00:00",
                    "wasDerivedFrom": "null"
                }
            ],
            "time": {
                "timestamp": "2024-01-18T05:23:25.507396+00:00"
            },
            "place": {
                "type": "null"
            }
        },
        {
            "id": "2305843009231960349",
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            101.5582514848274,
                            3.0553554890466
                        ],
                        [
                            101.5580114962919,
                            3.0546887098619
                        ],
                        [
                            101.5581993881195,
                            3.0546141901944
                        ],
                        [
                            101.5584426877089,
                            3.0552926209357
                        ],
                        [
                            101.5582514848274,
                            3.0553554890466
                        ]
                    ]
                ]
            },
            "properties": {
                "feature-id": 2305843009231960349,
                "created_by": "Potlatch 0.6",
                "landuse": "residential",
                "building": "yes",
                "id": "2305843009231960349",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1705555421.512603,
                "x_max": -1276119.874648313,
                "x_min": -1276166.1218249332,
                "y_max": 6239983.877946686,
                "y_min": 6239970.787292116,
                "z_max": 337686.8355395783,
                "z_min": 337604.9811109423,
                "line-hidden": "null",
                "amenity": "null",
                "parking": "null",
                "name": "null",
                "is_in": "null",
                "shop": "null",
                "name-zh": "null",
                "addr:city": "null",
                "addr:place": "null",
                "name-en": "null",
                "name-it": "null",
                "leisure": "null",
                "sport": "null",
                "emergency": "null",
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
                            "T284983264",
                            "T284983268"
                        ],
                        "10": [
                            "T2849832647",
                            "T2849832649",
                            "T2849832685"
                        ],
                        "11": [
                            "T28498326478",
                            "T28498326498",
                            "T28498326852",
                            "T28498326477"
                        ],
                        "12": [
                            "T284983264783",
                            "T284983264984",
                            "T284983268521",
                            "T284983264772"
                        ],
                        "13": [
                            "T2849832647834",
                            "T2849832649848",
                            "T2849832685211",
                            "T2849832647725"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349"
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
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Agent",
                    "name": "agents:%3COrganisation%3E",
                    "agentType": "organization",
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
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
                    "wasInformedBy": "null",
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
                    "generated": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
                    ]
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution"
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
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:reorganiseData_task-2305843009231960349",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:23:41.708387+00:00",
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:23:41.969677+00:00",
                    "generated": "null"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009231960349",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:23:42.120315+00:00",
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task",
                        "dggsOperations:reorganiseData_task-2305843009231960349"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:23:57.807022+00:00",
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
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
                    "wasDerivedFrom": "null"
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
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960349",
                    "entityType": "Feature",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:41.381234+00:00",
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
                    "wasGeneratedBy": "null",
                    "wasDerivedFrom": "null"
                }
            ],
            "time": {
                "timestamp": "2024-01-18T05:23:41.381234+00:00"
            },
            "place": {
                "type": "null"
            }
        },
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
                "feature-id": 2305843009231960466,
                "created_by": "Potlatch 0.6",
                "landuse": "residential",
                "building": "yes",
                "id": "2305843009231960466",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1705555437.893201,
                "x_max": -1276146.633556901,
                "x_min": -1276196.2185377243,
                "y_max": 6239978.947472959,
                "y_min": 6239965.272903057,
                "z_max": 337676.8530694004,
                "z_min": 337594.5358394981,
                "line-hidden": "null",
                "amenity": "null",
                "parking": "null",
                "name": "null",
                "is_in": "null",
                "shop": "null",
                "name-zh": "null",
                "addr:city": "null",
                "addr:place": "null",
                "name-en": "null",
                "name-it": "null",
                "leisure": "null",
                "sport": "null",
                "emergency": "null",
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
                            "T2849832685",
                            "T2849832647"
                        ],
                        "11": [
                            "T28498326851",
                            "T28498326476",
                            "T28498326477"
                        ],
                        "12": [
                            "T284983268516",
                            "T284983264769",
                            "T284983264772",
                            "T284983268515"
                        ],
                        "13": [
                            "T2849832685168",
                            "T2849832647696",
                            "T2849832647726",
                            "T2849832685157"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466"
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
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Agent",
                    "name": "agents:%3COrganisation%3E",
                    "agentType": "organization",
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
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
                    "wasInformedBy": "null"
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
                    "generated": "null",
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
                    "generated": "null",
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
                    "id": "dggsOperations:reorganiseData_task-2305843009231960466",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:23:57.943043+00:00",
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
                    "endedAtTime": "2024-01-18T05:23:58.034751+00:00",
                    "generated": "null",
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task"
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009231960466",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:23:58.134275+00:00",
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
                    "endedAtTime": "2024-01-18T05:24:15.523878+00:00",
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task",
                        "dggsOperations:reorganiseData_task-2305843009231960466"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9",
                    "entityType": "rawData",
                    "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:24.663693+00:00",
                    "wasDerivedFrom": "terranexusJobs:MapDataToZones_cae879d1d789"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings___Properties",
                    "entityType": "FeatureCollectionProperties",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:25.444245+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
                    "entityType": "FeatureCollectionDGGSZones",
                    "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373",
                    "hadPrimarySource": [
                        "terranexusCollections:osm_singapore_buildings",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:27.310511+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusCollections:osm_singapore_buildings",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusJobs:MapDataToZones_cae879d1d789",
                    "entityType": "ogcapiProcessJob",
                    "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
                    "hadPrimarySource": [
                        "agents:admin%40terranexus.pangaeainnovations.com"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:24.651036+00:00",
                    "wasDerivedFrom": "null"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings",
                    "entityType": "FeatureCollection",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:25.388490+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960466",
                    "entityType": "Feature",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:57.834082+00:00",
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
                    "wasGeneratedBy": "null",
                    "hadPrimarySource": [
                        "agents:TerraNexus"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:22.485613+00:00",
                    "wasDerivedFrom": "null"
                }
            ],
            "time": {
                "timestamp": "2024-01-18T05:23:57.834082+00:00"
            },
            "place": {
                "type": "null"
            }
        },
        {
            "id": "2305843009231960589",
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            101.5579443950615,
                            3.0537888995459
                        ],
                        [
                            101.5581246169796,
                            3.0537228880294
                        ],
                        [
                            101.5583058447874,
                            3.05419921875
                        ],
                        [
                            101.5584110860051,
                            3.0544757965261
                        ],
                        [
                            101.5582260022865,
                            3.054542017603
                        ],
                        [
                            101.5580978351643,
                            3.05419921875
                        ],
                        [
                            101.5579443950615,
                            3.0537888995459
                        ]
                    ]
                ]
            },
            "properties": {
                "feature-id": 2305843009231960589,
                "created_by": "null",
                "landuse": "residential",
                "building": "yes",
                "id": "2305843009231960589",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1705555455.655527,
                "x_max": -1276113.6289550927,
                "x_min": -1276163.644612229,
                "y_max": 6239990.566373775,
                "y_min": 6239976.207058218,
                "z_max": 337597.0117900565,
                "z_min": 337506.56320081395,
                "line-hidden": [
                    {
                        "contour": 0,
                        "segments": [
                            {
                                "from": 0,
                                "to": 5
                            },
                            {
                                "from": 5,
                                "to": 6
                            }
                        ]
                    }
                ],
                "amenity": "null",
                "parking": "null",
                "name": "null",
                "is_in": "null",
                "shop": "null",
                "name-zh": "null",
                "addr:city": "null",
                "addr:place": "null",
                "name-en": "null",
                "name-it": "null",
                "leisure": "null",
                "sport": "null",
                "emergency": "null",
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
                            "T28498327",
                            "T28498326"
                        ],
                        "9": [
                            "T284983273",
                            "T284983268"
                        ],
                        "10": [
                            "T2849832731",
                            "T2849832685"
                        ],
                        "11": [
                            "T28498327315",
                            "T28498326859",
                            "T28498326856",
                            "T28498326851",
                            "T28498326852",
                            "T28498326857"
                        ],
                        "12": [
                            "T284983273151",
                            "T284983268597",
                            "T284983268562",
                            "T284983268517",
                            "T284983268521",
                            "T284983268571"
                        ],
                        "13": [
                            "T2849832731514",
                            "T2849832685976",
                            "T2849832685629",
                            "T2849832685177",
                            "T2849832685218",
                            "T2849832685713"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589"
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
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Agent",
                    "name": "agents:%3COrganisation%3E",
                    "agentType": "organization",
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
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
                    "wasInformedBy": "null"
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
                    "generated": "null",
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
                    "generated": "null",
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
                    "id": "dggsOperations:map_featureData_task-2305843009231960589",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:24:16.109523+00:00",
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
                    "endedAtTime": "2024-01-18T05:24:39.010138+00:00",
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task",
                        "dggsOperations:reorganiseData_task-2305843009231960589"
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:reorganiseData_task-2305843009231960589",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:24:15.745664+00:00",
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
                    "endedAtTime": "2024-01-18T05:24:15.882453+00:00",
                    "generated": "null",
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9",
                    "entityType": "rawData",
                    "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:24.663693+00:00",
                    "wasDerivedFrom": "terranexusJobs:MapDataToZones_cae879d1d789"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings___Properties",
                    "entityType": "FeatureCollectionProperties",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:25.444245+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
                    "entityType": "FeatureCollectionDGGSZones",
                    "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373",
                    "hadPrimarySource": [
                        "terranexusCollections:osm_singapore_buildings",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:27.310511+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusCollections:osm_singapore_buildings",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960589",
                    "entityType": "Feature",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:24:15.553951+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json",
                        "terranexusCollections:osm_singapore_buildings"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusJobs:MapDataToZones_cae879d1d789",
                    "entityType": "ogcapiProcessJob",
                    "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
                    "hadPrimarySource": [
                        "agents:admin%40terranexus.pangaeainnovations.com"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:24.651036+00:00",
                    "wasDerivedFrom": "null"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings",
                    "entityType": "FeatureCollection",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:25.388490+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
                    "entityType": "DGGS",
                    "wasGeneratedBy": "null",
                    "hadPrimarySource": [
                        "agents:TerraNexus"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:22.485613+00:00",
                    "wasDerivedFrom": "null"
                }
            ],
            "time": {
                "timestamp": "2024-01-18T05:24:15.553951+00:00"
            },
            "place": {
                "type": "null"
            }
        },
        {
            "id": "2305843009231960619",
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            101.5577051190312,
                            3.053875112682
                        ],
                        [
                            101.557886891696,
                            3.0538091011655
                        ],
                        [
                            101.5580292250992,
                            3.05419921875
                        ],
                        [
                            101.5581625893186,
                            3.0545648177712
                        ],
                        [
                            101.5579808166538,
                            3.0546299072221
                        ],
                        [
                            101.5578234787281,
                            3.05419921875
                        ],
                        [
                            101.5577051190312,
                            3.053875112682
                        ]
                    ]
                ]
            },
            "properties": {
                "feature-id": 2305843009231960619,
                "created_by": "Potlatch 0.6",
                "landuse": "residential",
                "building": "yes",
                "id": "2305843009231960619",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1705555479.150384,
                "x_max": -1276087.4680238087,
                "x_min": -1276136.47619351,
                "y_max": 6239995.397990122,
                "y_min": 6239981.227931422,
                "z_max": 337606.71659015486,
                "z_min": 337516.08289024205,
                "line-hidden": [
                    {
                        "contour": 0,
                        "segments": [
                            {
                                "from": 0,
                                "to": 5
                            },
                            {
                                "from": 5,
                                "to": 6
                            }
                        ]
                    }
                ],
                "amenity": "null",
                "parking": "null",
                "name": "null",
                "is_in": "null",
                "shop": "null",
                "name-zh": "null",
                "addr:city": "null",
                "addr:place": "null",
                "name-en": "null",
                "name-it": "null",
                "leisure": "null",
                "sport": "null",
                "emergency": "null",
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
                            "T28498327",
                            "T28498326"
                        ],
                        "9": [
                            "T284983273",
                            "T284983268",
                            "T284983264"
                        ],
                        "10": [
                            "T2849832731",
                            "T2849832685",
                            "T2849832649"
                        ],
                        "11": [
                            "T28498327313",
                            "T28498327314",
                            "T28498326858",
                            "T28498326852",
                            "T28498326498"
                        ],
                        "12": [
                            "T284983273138",
                            "T284983273141",
                            "T284983268581",
                            "T284983268521",
                            "T284983264988",
                            "T284983268583"
                        ],
                        "13": [
                            "T2849832731386",
                            "T2849832731416",
                            "T2849832685816",
                            "T2849832685217",
                            "T2849832649888",
                            "T2849832685835"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619"
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
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Agent",
                    "name": "agents:%3COrganisation%3E",
                    "agentType": "organization",
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
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
                    "wasInformedBy": "null",
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
                    "generated": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
                    ]
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution"
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
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:reorganiseData_task-2305843009231960619",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:24:39.221754+00:00",
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:24:39.307410+00:00",
                    "generated": "null"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009231960619",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:24:39.449608+00:00",
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task",
                        "dggsOperations:reorganiseData_task-2305843009231960619"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:25:05.015295+00:00",
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
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
                    "wasDerivedFrom": "null"
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
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960619",
                    "entityType": "Feature",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:24:39.057589+00:00",
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
                    "wasGeneratedBy": "null",
                    "wasDerivedFrom": "null"
                }
            ],
            "time": {
                "timestamp": "2024-01-18T05:24:39.057589+00:00"
            },
            "place": {
                "type": "null"
            }
        },
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
                "feature-id": 2305843009231960767,
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
                "line-hidden": "null",
                "amenity": "null",
                "parking": "null",
                "name": "null",
                "is_in": "null",
                "shop": "null",
                "name-zh": "null",
                "addr:city": "null",
                "addr:place": "null",
                "name-en": "null",
                "name-it": "null",
                "leisure": "null",
                "sport": "null",
                "emergency": "null",
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
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767"
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
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Agent",
                    "name": "agents:%3COrganisation%3E",
                    "agentType": "organization",
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task",
                        "dggsOperations:reorganiseData_task-2305843009231960767"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:25:28.430251+00:00",
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ]
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
                    "wasInformedBy": "null",
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
                    "generated": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
                    ]
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:25:05.226533+00:00",
                    "generated": "null"
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
                    "wasDerivedFrom": "null"
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
                    "wasGeneratedBy": "null",
                    "wasDerivedFrom": "null"
                }
            ],
            "time": {
                "timestamp": "2024-01-18T05:25:05.050331+00:00"
            },
            "place": {
                "type": "null"
            }
        },
        {
            "id": "2305843009231960798",
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            101.5584495193769,
                            3.054149385294
                        ],
                        [
                            101.5586538826496,
                            3.0540765001974
                        ],
                        [
                            101.5587004050517,
                            3.05419921875
                        ],
                        [
                            101.5587553936928,
                            3.0543444021742
                        ],
                        [
                            101.5585524135185,
                            3.0544169938863
                        ],
                        [
                            101.5584686731947,
                            3.05419921875
                        ],
                        [
                            101.5584495193769,
                            3.054149385294
                        ]
                    ]
                ]
            },
            "properties": {
                "feature-id": 2305843009231960798,
                "created_by": "Potlatch 0.6",
                "landuse": "residential",
                "building": "yes",
                "id": "2305843009231960798",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1705555528.572812,
                "x_max": -1276168.2156584898,
                "x_min": -1276201.2976202518,
                "y_max": 6239977.235185958,
                "y_min": 6239969.296571625,
                "z_max": 337583.2066295785,
                "z_min": 337545.6091949509,
                "line-hidden": [
                    {
                        "contour": 0,
                        "segments": [
                            {
                                "from": 0,
                                "to": 5
                            },
                            {
                                "from": 5,
                                "to": 6
                            }
                        ]
                    }
                ],
                "amenity": "null",
                "parking": "null",
                "name": "null",
                "is_in": "null",
                "shop": "null",
                "name-zh": "null",
                "addr:city": "null",
                "addr:place": "null",
                "name-en": "null",
                "name-it": "null",
                "leisure": "null",
                "sport": "null",
                "emergency": "null",
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
                            "T284983268"
                        ],
                        "10": [
                            "T2849832684"
                        ],
                        "11": [
                            "T28498326846",
                            "T28498326842",
                            "T28498326841"
                        ],
                        "12": [
                            "T284983268466",
                            "T284983268465",
                            "T284983268427",
                            "T284983268421",
                            "T284983268417",
                            "T284983268462"
                        ],
                        "13": [
                            "T2849832684663",
                            "T2849832684653",
                            "T2849832684273",
                            "T2849832684218",
                            "T2849832684178",
                            "T2849832684623"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798"
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
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Agent",
                    "name": "agents:%3COrganisation%3E",
                    "agentType": "organization",
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:reorganiseData_task-2305843009231960798",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:25:28.624522+00:00",
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:25:28.676283+00:00",
                    "generated": "null"
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
                    "wasInformedBy": "null",
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
                    "generated": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
                    ]
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution"
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
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009231960798",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:25:28.765830+00:00",
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task",
                        "dggsOperations:reorganiseData_task-2305843009231960798"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:25:59.513697+00:00",
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
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
                    "wasDerivedFrom": "null"
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
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960798",
                    "entityType": "Feature",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:25:28.478210+00:00",
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
                    "wasGeneratedBy": "null",
                    "wasDerivedFrom": "null"
                }
            ],
            "time": {
                "timestamp": "2024-01-18T05:25:28.478210+00:00"
            },
            "place": {
                "type": "null"
            }
        },
        {
            "id": "2305843009231960865",
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            101.5587754276641,
                            3.05419921875
                        ],
                        [
                            101.5587182176832,
                            3.0540495088218
                        ],
                        [
                            101.5590028844896,
                            3.0539479139545
                        ],
                        [
                            101.5590964322386,
                            3.05419921875
                        ],
                        [
                            101.5593548201747,
                            3.0548932826949
                        ],
                        [
                            101.559080212266,
                            3.0549963025727
                        ],
                        [
                            101.5587754276641,
                            3.05419921875
                        ]
                    ]
                ]
            },
            "properties": {
                "feature-id": 2305843009231960865,
                "created_by": "null",
                "landuse": "null",
                "building": "yes",
                "id": "2305843009231960865",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1705555559.635015,
                "x_max": -1276197.5969815229,
                "x_min": -1276265.9318077033,
                "y_max": 6239971.826792301,
                "y_min": 6239952.776008753,
                "z_max": 337647.17407459696,
                "z_min": 337531.4106530871,
                "line-hidden": [
                    {
                        "contour": 0,
                        "segments": [
                            {
                                "from": 0,
                                "to": 5
                            },
                            {
                                "from": 5,
                                "to": 6
                            }
                        ]
                    }
                ],
                "amenity": "parking",
                "parking": "multi-storey",
                "name": "null",
                "is_in": "null",
                "shop": "null",
                "name-zh": "null",
                "addr:city": "null",
                "addr:place": "null",
                "name-en": "null",
                "name-it": "null",
                "leisure": "null",
                "sport": "null",
                "emergency": "null",
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
                            "T2849832684",
                            "T2849832683",
                            "T2849832648"
                        ],
                        "11": [
                            "T28498326842",
                            "T28498326844",
                            "T28498326838",
                            "T28498326488"
                        ],
                        "12": [
                            "T284983268426",
                            "T284983268429",
                            "T284983268446",
                            "T284983268389",
                            "T284983264885",
                            "T284983264886"
                        ],
                        "13": [
                            "T2849832684266",
                            "T2849832684299",
                            "T2849832684463",
                            "T2849832683893",
                            "T2849832648855",
                            "T2849832648862"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865"
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
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Agent",
                    "name": "agents:%3COrganisation%3E",
                    "agentType": "organization",
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
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
                    "wasInformedBy": "null",
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
                    "generated": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
                    ]
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution"
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
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:reorganiseData_task-2305843009231960865",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:25:59.715125+00:00",
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:25:59.783035+00:00",
                    "generated": "null"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009231960865",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:25:59.882233+00:00",
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task",
                        "dggsOperations:reorganiseData_task-2305843009231960865"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:26:25.791311+00:00",
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
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
                    "wasDerivedFrom": "null"
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
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960865",
                    "entityType": "Feature",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:25:59.542518+00:00",
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
                    "wasGeneratedBy": "null",
                    "wasDerivedFrom": "null"
                }
            ],
            "time": {
                "timestamp": "2024-01-18T05:25:59.542518+00:00"
            },
            "place": {
                "type": "null"
            }
        },
        {
            "id": "2305843009232899975",
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            101.5170950017292,
                            3.0440544012461
                        ],
                        [
                            101.5169714030231,
                            3.0444474945879
                        ],
                        [
                            101.5166065165071,
                            3.0443326974173
                        ],
                        [
                            101.5167301152133,
                            3.0439396040755
                        ],
                        [
                            101.5170950017292,
                            3.0440544012461
                        ]
                    ]
                ]
            },
            "properties": {
                "feature-id": 2305843009232899975,
                "created_by": "null",
                "landuse": "null",
                "building": "commercial",
                "id": "2305843009232899975",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1705555585.872302,
                "x_max": -1271622.3602021495,
                "x_min": -1271675.8948859423,
                "y_max": 6240964.134369386,
                "y_min": 6240954.894049214,
                "z_max": 336482.36612796935,
                "z_min": 336426.2841626774,
                "line-hidden": "null",
                "amenity": "null",
                "parking": "null",
                "name": "Giant",
                "is_in": "Seksyen 18, Shah Alam, Selangor, Malaysia",
                "shop": "supermarket",
                "name-zh": "null",
                "addr:city": "null",
                "addr:place": "null",
                "name-en": "null",
                "name-it": "null",
                "leisure": "null",
                "sport": "null",
                "emergency": "null",
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
                            "T284982"
                        ],
                        "7": [
                            "T2849826",
                            "T2849827"
                        ],
                        "8": [
                            "T28498268",
                            "T28498273"
                        ],
                        "9": [
                            "T284982688",
                            "T284982733"
                        ],
                        "10": [
                            "T2849826889",
                            "T2849827335"
                        ],
                        "11": [
                            "T28498268897",
                            "T28498268893",
                            "T28498268895",
                            "T28498273353"
                        ],
                        "12": [
                            "T284982688973",
                            "T284982688933",
                            "T284982688957",
                            "T284982733533"
                        ],
                        "13": [
                            "T2849826889732",
                            "T2849826889339",
                            "T2849826889571",
                            "T2849827335338"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975"
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
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Agent",
                    "name": "agents:%3COrganisation%3E",
                    "agentType": "organization",
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
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
                    "wasInformedBy": "null",
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
                    "generated": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
                    ]
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution"
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
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:reorganiseData_task-2305843009232899975",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:26:25.925281+00:00",
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:26:25.997827+00:00",
                    "generated": "null"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009232899975",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:26:26.115242+00:00",
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task",
                        "dggsOperations:reorganiseData_task-2305843009232899975"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:26:50.496862+00:00",
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
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
                    "wasDerivedFrom": "null"
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
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009232899975",
                    "entityType": "Feature",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:26:25.820867+00:00",
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
                    "wasGeneratedBy": "null",
                    "wasDerivedFrom": "null"
                }
            ],
            "time": {
                "timestamp": "2024-01-18T05:26:25.820867+00:00"
            },
            "place": {
                "type": "null"
            }
        },
        {
            "id": "2305843009232900002",
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            101.5158121988813,
                            3.0451234106047
                        ],
                        [
                            101.5159503829892,
                            3.0453711109619
                        ],
                        [
                            101.5157614852718,
                            3.0454825132545
                        ],
                        [
                            101.5156056980929,
                            3.0451745852471
                        ],
                        [
                            101.5156228820432,
                            3.0449524931671
                        ],
                        [
                            101.5157057841255,
                            3.0446933927258
                        ],
                        [
                            101.5158238085258,
                            3.0447117083022
                        ],
                        [
                            101.5158601043818,
                            3.0447487166635
                        ],
                        [
                            101.5158121988813,
                            3.0451234106047
                        ]
                    ]
                ]
            },
            "properties": {
                "feature-id": 2305843009232900002,
                "created_by": "null",
                "landuse": "null",
                "building": "commercial",
                "id": "2305843009232900002",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1705555610.592237,
                "x_max": -1271512.3583419316,
                "x_min": -1271549.6728737596,
                "y_max": 6240982.397314117,
                "y_min": 6240972.719726458,
                "z_max": 336596.6542250734,
                "z_min": 336509.51852749335,
                "line-hidden": "null",
                "amenity": "null",
                "parking": "null",
                "name": "Mydin",
                "is_in": "Seksyen 18, Shah Alam, Selangor, Malaysia",
                "shop": "supermarket",
                "name-zh": "null",
                "addr:city": "null",
                "addr:place": "null",
                "name-en": "null",
                "name-it": "null",
                "leisure": "null",
                "sport": "null",
                "emergency": "null",
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
                            "T284982"
                        ],
                        "7": [
                            "T2849826",
                            "T2849827"
                        ],
                        "8": [
                            "T28498268",
                            "T28498273"
                        ],
                        "9": [
                            "T284982688",
                            "T284982733"
                        ],
                        "10": [
                            "T2849826888",
                            "T2849826884",
                            "T2849827333"
                        ],
                        "11": [
                            "T28498268885",
                            "T28498268884",
                            "T28498268849",
                            "T28498273331",
                            "T28498273332",
                            "T28498273333"
                        ],
                        "12": [
                            "T284982688859",
                            "T284982688841",
                            "T284982688498",
                            "T284982733312",
                            "T284982733324",
                            "T284982733329",
                            "T284982733339",
                            "T284982733338"
                        ],
                        "13": [
                            "T2849826888597",
                            "T2849826888417",
                            "T2849826884982",
                            "T2849827333129",
                            "T2849827333244",
                            "T2849827333299",
                            "T2849827333395",
                            "T2849827333387"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002"
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
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Agent",
                    "name": "agents:%3COrganisation%3E",
                    "agentType": "organization",
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009232900002",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:26:50.744858+00:00",
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task",
                        "dggsOperations:reorganiseData_task-2305843009232900002"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:27:20.122235+00:00",
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ]
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
                    "wasInformedBy": "null",
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
                    "generated": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
                    ]
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution"
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
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:reorganiseData_task-2305843009232900002",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:26:50.630396+00:00",
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:26:50.678018+00:00",
                    "generated": "null"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9",
                    "entityType": "rawData",
                    "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:24.663693+00:00",
                    "wasDerivedFrom": "terranexusJobs:MapDataToZones_cae879d1d789"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings___Properties",
                    "entityType": "FeatureCollectionProperties",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:25.444245+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
                    "entityType": "FeatureCollectionDGGSZones",
                    "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373",
                    "hadPrimarySource": [
                        "terranexusCollections:osm_singapore_buildings",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:27.310511+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusCollections:osm_singapore_buildings",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009232900002",
                    "entityType": "Feature",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:26:50.531820+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json",
                        "terranexusCollections:osm_singapore_buildings"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusJobs:MapDataToZones_cae879d1d789",
                    "entityType": "ogcapiProcessJob",
                    "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
                    "hadPrimarySource": [
                        "agents:admin%40terranexus.pangaeainnovations.com"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:24.651036+00:00",
                    "wasDerivedFrom": "null"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings",
                    "entityType": "FeatureCollection",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:25.388490+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
                    "entityType": "DGGS",
                    "wasGeneratedBy": "null",
                    "hadPrimarySource": [
                        "agents:TerraNexus"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:22.485613+00:00",
                    "wasDerivedFrom": "null"
                }
            ],
            "time": {
                "timestamp": "2024-01-18T05:26:50.531820+00:00"
            },
            "place": {
                "type": "null"
            }
        },
        {
            "id": "2305843009232901459",
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            101.5499142093375,
                            3.0774648205698
                        ],
                        [
                            101.5500360058245,
                            3.0770293960334
                        ],
                        [
                            101.5501728906581,
                            3.0765117819199
                        ],
                        [
                            101.5514844032767,
                            3.0768443123147
                        ],
                        [
                            101.5512397205888,
                            3.0778124812234
                        ],
                        [
                            101.5499142093375,
                            3.0774648205698
                        ]
                    ]
                ]
            },
            "properties": {
                "feature-id": 2305843009232901459,
                "created_by": "null",
                "landuse": "null",
                "building": "yes",
                "id": "2305843009232901459",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1705555640.254449,
                "x_max": -1275211.0286367147,
                "x_min": -1275382.774143958,
                "y_max": 6240032.180374823,
                "y_min": 6240000.655100508,
                "z_max": 340166.5166379938,
                "z_min": 340022.89597160293,
                "line-hidden": "null",
                "amenity": "null",
                "parking": "null",
                "name": "Tesco Extra",
                "is_in": "null",
                "shop": "supermarket",
                "name-zh": "\u7279\u6613\u8d2d\u7279\u5927\u5e97",
                "addr:city": "Shah Alam",
                "addr:place": "Section 13",
                "name-en": "null",
                "name-it": "null",
                "leisure": "null",
                "sport": "null",
                "emergency": "null",
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
                            "T2849831"
                        ],
                        "8": [
                            "T28498316",
                            "T28498312"
                        ],
                        "9": [
                            "T284983165",
                            "T284983129"
                        ],
                        "10": [
                            "T2849831653",
                            "T2849831654",
                            "T2849831299",
                            "T2849831297"
                        ],
                        "11": [
                            "T28498316537",
                            "T28498316543",
                            "T28498316549",
                            "T28498312997",
                            "T28498312974"
                        ],
                        "12": [
                            "T284983165372",
                            "T284983165438",
                            "T284983165493",
                            "T284983129975",
                            "T284983129745"
                        ],
                        "13": [
                            "T2849831653725",
                            "T2849831654389",
                            "T2849831654934",
                            "T2849831299756",
                            "T2849831297453"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901459?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901459?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901459?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901459?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901459"
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
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Agent",
                    "name": "agents:%3COrganisation%3E",
                    "agentType": "organization",
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
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
                    "wasInformedBy": "null"
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
                    "generated": "null",
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
                    "generated": "null",
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
                    "id": "dggsOperations:reorganiseData_task-2305843009232901459",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:27:20.294670+00:00",
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
                    "endedAtTime": "2024-01-18T05:27:20.349755+00:00",
                    "generated": "null",
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task"
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009232901459",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:27:20.429685+00:00",
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
                    "endedAtTime": "2024-01-18T05:27:56.040859+00:00",
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task",
                        "dggsOperations:reorganiseData_task-2305843009232901459"
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
                    "wasDerivedFrom": "null"
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
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009232901459",
                    "entityType": "Feature",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:27:20.169756+00:00",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json",
                        "terranexusCollections:osm_singapore_buildings"
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
                    "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
                    "entityType": "DGGS",
                    "hadPrimarySource": [
                        "agents:TerraNexus"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:22.485613+00:00",
                    "wasGeneratedBy": "null",
                    "wasDerivedFrom": "null"
                }
            ],
            "time": {
                "timestamp": "2024-01-18T05:27:20.169756+00:00"
            },
            "place": {
                "type": "null"
            }
        },
        {
            "id": "2305843009232901461",
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            101.5474172137068,
                            3.0795437851748
                        ],
                        [
                            101.547719902705,
                            3.0798328946611
                        ],
                        [
                            101.5477292071854,
                            3.0803091834696
                        ],
                        [
                            101.5474367028212,
                            3.0806104893694
                        ],
                        [
                            101.5469939017597,
                            3.0806296850993
                        ],
                        [
                            101.5466431815247,
                            3.0802798869299
                        ],
                        [
                            101.546638780757,
                            3.0798953855634
                        ],
                        [
                            101.5469557198603,
                            3.0795484793271
                        ],
                        [
                            101.5474172137068,
                            3.0795437851748
                        ]
                    ]
                ]
            },
            "properties": {
                "feature-id": 2305843009232901461,
                "created_by": "null",
                "landuse": "null",
                "building": "yes",
                "id": "2305843009232901461",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1705555676.293127,
                "x_max": -1274851.4132282431,
                "x_min": -1274969.6793106755,
                "y_max": 6240090.927641856,
                "y_min": 6240064.255301031,
                "z_max": 340477.58617624646,
                "z_min": 340357.68355863984,
                "line-hidden": "null",
                "amenity": "null",
                "parking": "null",
                "name": "Stadium Malawati",
                "is_in": "Seksyen 13, Shah Alam, Selangor, Malaysia",
                "shop": "null",
                "name-zh": "null",
                "addr:city": "null",
                "addr:place": "null",
                "name-en": "Malawati Stadium",
                "name-it": "Malawati",
                "leisure": "stadium",
                "sport": "null",
                "emergency": "null",
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
                            "T2849831"
                        ],
                        "8": [
                            "T28498316"
                        ],
                        "9": [
                            "T284983163"
                        ],
                        "10": [
                            "T2849831638",
                            "T2849831634",
                            "T2849831633",
                            "T2849831632",
                            "T2849831636",
                            "T2849831637"
                        ],
                        "11": [
                            "T28498316383",
                            "T28498316343",
                            "T28498316334",
                            "T28498316336",
                            "T28498316327",
                            "T28498316363",
                            "T28498316368",
                            "T28498316376"
                        ],
                        "12": [
                            "T284983163831",
                            "T284983163439",
                            "T284983163348",
                            "T284983163362",
                            "T284983163271",
                            "T284983163638",
                            "T284983163685",
                            "T284983163761"
                        ],
                        "13": [
                            "T2849831638315",
                            "T2849831634393",
                            "T2849831633485",
                            "T2849831633621",
                            "T2849831632712",
                            "T2849831636384",
                            "T2849831636858",
                            "T2849831637611"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901461?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901461?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901461?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901461?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901461"
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
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Agent",
                    "name": "agents:%3COrganisation%3E",
                    "agentType": "organization",
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
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
                    "wasInformedBy": "null"
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
                    "generated": "null",
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
                    "generated": "null",
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
                    "id": "dggsOperations:reorganiseData_task-2305843009232901461",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:27:56.373833+00:00",
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
                    "endedAtTime": "2024-01-18T05:27:56.452169+00:00",
                    "generated": "null",
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task"
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009232901461",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:27:56.535404+00:00",
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
                    "endedAtTime": "2024-01-18T05:28:38.749898+00:00",
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task",
                        "dggsOperations:reorganiseData_task-2305843009232901461"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9",
                    "entityType": "rawData",
                    "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:24.663693+00:00",
                    "wasDerivedFrom": "terranexusJobs:MapDataToZones_cae879d1d789"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings___Properties",
                    "entityType": "FeatureCollectionProperties",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:25.444245+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
                    "entityType": "FeatureCollectionDGGSZones",
                    "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373",
                    "hadPrimarySource": [
                        "terranexusCollections:osm_singapore_buildings",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:27.310511+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusCollections:osm_singapore_buildings",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009232901461",
                    "entityType": "Feature",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:27:56.109661+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json",
                        "terranexusCollections:osm_singapore_buildings"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusJobs:MapDataToZones_cae879d1d789",
                    "entityType": "ogcapiProcessJob",
                    "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
                    "hadPrimarySource": [
                        "agents:admin%40terranexus.pangaeainnovations.com"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:24.651036+00:00",
                    "wasDerivedFrom": "null"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings",
                    "entityType": "FeatureCollection",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:25.388490+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
                    "entityType": "DGGS",
                    "wasGeneratedBy": "null",
                    "hadPrimarySource": [
                        "agents:TerraNexus"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:22.485613+00:00",
                    "wasDerivedFrom": "null"
                }
            ],
            "time": {
                "timestamp": "2024-01-18T05:27:56.109661+00:00"
            },
            "place": {
                "type": "null"
            }
        },
        {
            "id": "2305843009232901565",
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            101.5364629064063,
                            3.0734719830191
                        ],
                        [
                            101.5364628225822,
                            3.0734252929688
                        ],
                        [
                            101.5364627806701,
                            3.073414689214
                        ],
                        [
                            101.5371518989903,
                            3.0734177068834
                        ],
                        [
                            101.5371518989903,
                            3.0734252929688
                        ],
                        [
                            101.5371500967711,
                            3.0743803014862
                        ],
                        [
                            101.5370101942682,
                            3.0743807206069
                        ],
                        [
                            101.5370130023771,
                            3.0746557057242
                        ],
                        [
                            101.5367290899881,
                            3.0746546998344
                        ],
                        [
                            101.5364644990651,
                            3.0743823970899
                        ],
                        [
                            101.5364585056385,
                            3.074256116011
                        ],
                        [
                            101.5362406885901,
                            3.0742590917683
                        ],
                        [
                            101.5361587923976,
                            3.074154688792
                        ],
                        [
                            101.5361548107506,
                            3.0739649109211
                        ],
                        [
                            101.5360478930499,
                            3.0739372070402
                        ],
                        [
                            101.5359929044088,
                            3.0738530895077
                        ],
                        [
                            101.535977103557,
                            3.0737419805996
                        ],
                        [
                            101.53600828614,
                            3.073635104811
                        ],
                        [
                            101.536264410824,
                            3.0734742881832
                        ],
                        [
                            101.5364629064063,
                            3.0734719830191
                        ]
                    ]
                ]
            },
            "properties": {
                "feature-id": 2305843009232901565,
                "created_by": "Potlatch 0.6a",
                "landuse": "null",
                "building": "yes",
                "id": "2305843009232901565",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1705555718.837784,
                "x_max": -1273697.530244064,
                "x_min": -1273825.8672269937,
                "y_max": 6240363.829780593,
                "y_min": 6240334.043873932,
                "z_max": 339817.9513805314,
                "z_min": 339680.9203773574,
                "line-hidden": [
                    {
                        "contour": 0,
                        "segments": [
                            {
                                "from": 0,
                                "to": 2
                            },
                            {
                                "from": 3,
                                "to": 4
                            },
                            {
                                "from": 5,
                                "to": 12
                            },
                            {
                                "from": 13,
                                "to": 18
                            },
                            {
                                "from": 18,
                                "to": 19
                            }
                        ]
                    }
                ],
                "amenity": "null",
                "parking": "null",
                "name": "Pusat Akuatik Darul Ehsan",
                "is_in": "null",
                "shop": "null",
                "name-zh": "null",
                "addr:city": "null",
                "addr:place": "null",
                "name-en": "Darul Ehsan Aquatic Center",
                "name-it": "null",
                "leisure": "stadium",
                "sport": "swimming",
                "emergency": "null",
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
                            "T284982"
                        ],
                        "7": [
                            "T2849821"
                        ],
                        "8": [
                            "T28498219",
                            "T28498217"
                        ],
                        "9": [
                            "T284982193",
                            "T284982192",
                            "T284982174",
                            "T284982178"
                        ],
                        "10": [
                            "T2849821931",
                            "T2849821921",
                            "T2849821749",
                            "T2849821785",
                            "T2849821784"
                        ],
                        "11": [
                            "T28498219314",
                            "T28498219211",
                            "T28498219311",
                            "T28498217496",
                            "T28498217494",
                            "T28498217493",
                            "T28498217495",
                            "T28498217851",
                            "T28498217852",
                            "T28498217842",
                            "T28498217846",
                            "T28498217847",
                            "T28498217849",
                            "T28498219315"
                        ],
                        "12": [
                            "T284982193141",
                            "T284982193142",
                            "T284982192119",
                            "T284982193117",
                            "T284982174965",
                            "T284982174945",
                            "T284982174934",
                            "T284982174952",
                            "T284982178517",
                            "T284982178523",
                            "T284982178425",
                            "T284982178463",
                            "T284982178469",
                            "T284982178474",
                            "T284982178478",
                            "T284982178493",
                            "T284982178497",
                            "T284982193153"
                        ],
                        "13": [
                            "T2849821931412",
                            "T2849821931418",
                            "T2849821931423",
                            "T2849821921191",
                            "T2849821931175",
                            "T2849821749654",
                            "T2849821749459",
                            "T2849821749344",
                            "T2849821749521",
                            "T2849821785171",
                            "T2849821785235",
                            "T2849821784257",
                            "T2849821784636",
                            "T2849821784693",
                            "T2849821784743",
                            "T2849821784784",
                            "T2849821784938",
                            "T2849821784976",
                            "T2849821931533"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901565?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901565?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901565?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901565?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901565"
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
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Agent",
                    "name": "agents:%3COrganisation%3E",
                    "agentType": "organization",
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
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
                    "wasInformedBy": "null"
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
                    "generated": "null",
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
                    "generated": "null",
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
                    "id": "dggsOperations:reorganiseData_task-2305843009232901565",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:28:38.881281+00:00",
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
                    "endedAtTime": "2024-01-18T05:28:39.005025+00:00",
                    "generated": "null",
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task"
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009232901565",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:28:39.093872+00:00",
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
                    "endedAtTime": "2024-01-18T05:29:59.930166+00:00",
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task",
                        "dggsOperations:reorganiseData_task-2305843009232901565"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9",
                    "entityType": "rawData",
                    "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:24.663693+00:00",
                    "wasDerivedFrom": "terranexusJobs:MapDataToZones_cae879d1d789"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings___Properties",
                    "entityType": "FeatureCollectionProperties",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:25.444245+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
                    "entityType": "FeatureCollectionDGGSZones",
                    "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373",
                    "hadPrimarySource": [
                        "terranexusCollections:osm_singapore_buildings",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:27.310511+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusCollections:osm_singapore_buildings",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009232901565",
                    "entityType": "Feature",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:28:38.783226+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json",
                        "terranexusCollections:osm_singapore_buildings"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusJobs:MapDataToZones_cae879d1d789",
                    "entityType": "ogcapiProcessJob",
                    "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
                    "hadPrimarySource": [
                        "agents:admin%40terranexus.pangaeainnovations.com"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:24.651036+00:00",
                    "wasDerivedFrom": "null"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings",
                    "entityType": "FeatureCollection",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:25.388490+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
                    "entityType": "DGGS",
                    "wasGeneratedBy": "null",
                    "hadPrimarySource": [
                        "agents:TerraNexus"
                    ],
                    "generatedAtTime": "2024-01-18T05:23:22.485613+00:00",
                    "wasDerivedFrom": "null"
                }
            ],
            "time": {
                "timestamp": "2024-01-18T05:28:38.783226+00:00"
            },
            "place": {
                "type": "null"
            }
        },
        {
            "id": "2305843009233038522",
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            101.5933582115208,
                            3.0778352813916
                        ],
                        [
                            101.5939204200811,
                            3.0778352813916
                        ],
                        [
                            101.5939204200811,
                            3.0786624161714
                        ],
                        [
                            101.5933582115208,
                            3.0786622904352
                        ],
                        [
                            101.5933582115208,
                            3.0778352813916
                        ]
                    ]
                ]
            },
            "properties": {
                "feature-id": 2305843009233038522,
                "created_by": "null",
                "landuse": "null",
                "building": "yes",
                "id": "2305843009233038522",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1705555800.169564,
                "x_max": -1279940.6802046662,
                "x_min": -1280002.8871373793,
                "y_max": 6239061.315056953,
                "y_min": 6239043.944169954,
                "z_max": 340260.36469540495,
                "z_min": 340169.0341863229,
                "line-hidden": "null",
                "amenity": "hospital",
                "parking": "null",
                "name": "Sime Darby Medical Hospital Subang Jaya",
                "is_in": "null",
                "shop": "null",
                "name-zh": "null",
                "addr:city": "null",
                "addr:place": "null",
                "name-en": "null",
                "name-it": "null",
                "leisure": "null",
                "sport": "null",
                "emergency": "yes",
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
                            "T28494"
                        ],
                        "6": [
                            "T284948"
                        ],
                        "7": [
                            "T2849484"
                        ],
                        "8": [
                            "T28494845"
                        ],
                        "9": [
                            "T284948457",
                            "T284948456"
                        ],
                        "10": [
                            "T2849484573",
                            "T2849484564",
                            "T2849484568"
                        ],
                        "11": [
                            "T28494845733",
                            "T28494845731",
                            "T28494845648",
                            "T28494845681"
                        ],
                        "12": [
                            "T284948457335",
                            "T284948457316",
                            "T284948456481",
                            "T284948456818"
                        ],
                        "13": [
                            "T2849484573353",
                            "T2849484573165",
                            "T2849484564812",
                            "T2849484568182"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233038522?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233038522?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233038522?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233038522?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233038522"
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
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Agent",
                    "name": "agents:%3COrganisation%3E",
                    "agentType": "organization",
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:reorganiseData_task-2305843009233038522",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:30:00.242274+00:00",
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:30:00.413889+00:00",
                    "generated": "null"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009233038522",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:30:00.750806+00:00",
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task",
                        "dggsOperations:reorganiseData_task-2305843009233038522"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:31:22.112248+00:00",
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ]
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
                    "wasInformedBy": "null",
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
                    "generated": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
                    ]
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution"
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
                    "wasDerivedFrom": "null"
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
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009233038522",
                    "entityType": "Feature",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:29:59.992287+00:00",
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
                    "wasGeneratedBy": "null",
                    "wasDerivedFrom": "null"
                }
            ],
            "time": {
                "timestamp": "2024-01-18T05:29:59.992287+00:00"
            },
            "place": {
                "type": "null"
            }
        },
        {
            "id": "2305843009233494536",
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            101.5378867014711,
                            3.0720647851357
                        ],
                        [
                            101.5383911132813,
                            3.0714835065818
                        ],
                        [
                            101.5386065832535,
                            3.0712352194556
                        ],
                        [
                            101.5387849191283,
                            3.0712233164266
                        ],
                        [
                            101.5394376996803,
                            3.0718156178559
                        ],
                        [
                            101.5386484953275,
                            3.0727402820318
                        ],
                        [
                            101.5383911132813,
                            3.0725120707891
                        ],
                        [
                            101.5381551902169,
                            3.0723028876279
                        ],
                        [
                            101.5378867014711,
                            3.0720647851357
                        ]
                    ]
                ]
            },
            "properties": {
                "feature-id": 2305843009233494536,
                "created_by": "null",
                "landuse": "null",
                "building": "yes",
                "id": "2305843009233494536",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1705555882.279658,
                "x_max": -1273907.5017266115,
                "x_min": -1274076.722548753,
                "y_max": 6240331.116519038,
                "y_min": 6240298.076200732,
                "z_max": 339606.45337933605,
                "z_min": 339438.95221485576,
                "line-hidden": [
                    {
                        "contour": 0,
                        "segments": [
                            {
                                "from": 0,
                                "to": 3
                            },
                            {
                                "from": 5,
                                "to": 7
                            },
                            {
                                "from": 7,
                                "to": 8
                            }
                        ]
                    }
                ],
                "amenity": "null",
                "parking": "null",
                "name": "Tesco",
                "is_in": "Seksyen 13, Shah Alam, Selangor, Malaysia",
                "shop": "supermarket",
                "name-zh": "null",
                "addr:city": "null",
                "addr:place": "null",
                "name-en": "null",
                "name-it": "null",
                "leisure": "null",
                "sport": "null",
                "emergency": "null",
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
                            "T284982"
                        ],
                        "7": [
                            "T2849821"
                        ],
                        "8": [
                            "T28498219"
                        ],
                        "9": [
                            "T284982192",
                            "T284982191"
                        ],
                        "10": [
                            "T2849821923",
                            "T2849821924",
                            "T2849821925",
                            "T2849821919",
                            "T2849821918"
                        ],
                        "11": [
                            "T28498219236",
                            "T28498219242",
                            "T28498219246",
                            "T28498219256",
                            "T28498219193",
                            "T28498219183",
                            "T28498219184",
                            "T28498219232"
                        ],
                        "12": [
                            "T284982192367",
                            "T284982192426",
                            "T284982192466",
                            "T284982192563",
                            "T284982191933",
                            "T284982191832",
                            "T284982191847",
                            "T284982192322"
                        ],
                        "13": [
                            "T2849821923673",
                            "T2849821924268",
                            "T2849821924662",
                            "T2849821925636",
                            "T2849821919339",
                            "T2849821918329",
                            "T2849821918478",
                            "T2849821923227"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233494536?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233494536?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233494536?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233494536?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233494536"
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
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Agent",
                    "name": "agents:%3COrganisation%3E",
                    "agentType": "organization",
                    "actedOnBehalfOf": "null",
                    "qualifiedDelegation": "null"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:reorganiseData_task-2305843009233494536",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:31:22.345165+00:00",
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:31:22.431125+00:00",
                    "generated": "null"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009233494536",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-01-18T05:31:22.519324+00:00",
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution",
                        "dggsOperations:processData_task",
                        "dggsOperations:reorganiseData_task-2305843009233494536"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.644262+00:00",
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ]
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
                    "wasInformedBy": "null",
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
                    "generated": [
                        "terranexusJobs:MapDataToZones_cae879d1d789",
                        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
                    ]
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data"
                    ],
                    "used": [
                        "terranexusJobs:MapDataToZones_cae879d1d789"
                    ],
                    "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
                    "generated": "null"
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
                    "wasInformedBy": [
                        "terranexusProcesses:execution/MapDataToZones",
                        "dggsOperations:map_data",
                        "dggsOperations:map_data_execution"
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
                    "wasDerivedFrom": "null"
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
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009233494536",
                    "entityType": "Feature",
                    "hadPrimarySource": [
                        "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
                    ],
                    "generatedAtTime": "2024-01-18T05:31:22.172753+00:00",
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
                    "wasGeneratedBy": "null",
                    "wasDerivedFrom": "null"
                }
            ],
            "time": {
                "timestamp": "2024-01-18T05:31:22.172753+00:00"
            },
            "place": {
                "type": "null"
            }
        }
    ],
    "links": [
        {
            "rel": "self",
            "type": "application/geo+json",
            "title": "The JSON representation of the resources served from this OGC API Implementation Endpoint",
            "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items?f=json"
        },
        {
            "rel": "alternate",
            "type": "application/geo+json",
            "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
            "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items?f=geojson"
        },
        {
            "rel": "alternate",
            "type": "application/vnd.ogc.fg+json",
            "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
            "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items?f=jsonfg"
        },
        {
            "rel": "alternate",
            "type": "application/ld+json",
            "title": "The Linked Data JSON representation of the resources served from this OGC API Implementation Endpoint",
            "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items?f=jsonld"
        },
        {
            "rel": "alternate",
            "type": "text/html",
            "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
            "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items"
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
            "actedOnBehalfOf": "null",
            "qualifiedDelegation": "null"
        },
        {
            "provType": "Agent",
            "name": "agents:%3COrganisation%3E",
            "agentType": "organization",
            "actedOnBehalfOf": "null",
            "qualifiedDelegation": "null"
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
            "wasInformedBy": "null",
            "used": [
                "terranexusJobs:MapDataToZones_cae879d1d789"
            ],
            "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
            "generated": [
                "terranexusJobs:MapDataToZones_cae879d1d789",
                "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
            ]
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
            "wasInformedBy": [
                "terranexusProcesses:execution/MapDataToZones"
            ],
            "used": [
                "terranexusJobs:MapDataToZones_cae879d1d789"
            ],
            "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
            "generated": "null"
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
            "wasInformedBy": [
                "terranexusProcesses:execution/MapDataToZones",
                "dggsOperations:map_data"
            ],
            "used": [
                "terranexusJobs:MapDataToZones_cae879d1d789"
            ],
            "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
            "generated": "null"
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
            "wasInformedBy": [
                "terranexusProcesses:execution/MapDataToZones",
                "dggsOperations:map_data",
                "dggsOperations:map_data_execution"
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
            "wasDerivedFrom": "null"
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
            "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
            "entityType": "DGGS",
            "hadPrimarySource": [
                "agents:TerraNexus"
            ],
            "generatedAtTime": "2024-01-18T05:23:22.485613+00:00",
            "wasGeneratedBy": "null",
            "wasDerivedFrom": "null"
        }
    ],
    "@context": [
        "https://ogcincubator.github.io/bblock-prov-schema/build/annotated/ogc-utils/prov/context.jsonld",
        "https://opengeospatial.github.io/bblocks/annotated-schemas/geo/json-fg/featureCollection/context.jsonld",
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
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/terranexus/dggs/api/json-fg-feature-collection_with-prov/example_1_1.json">Open in new window</a>
    <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=json&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Ftests%2Fterranexus%2Fdggs%2Fapi%2Fjson-fg-feature-collection_with-prov%2Fexample_1_1.json&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on JSON Viewer</a></p>
</blockquote>




```jsonld
{
  "id": "osm_singapore_buildings",
  "type": "FeatureCollection",
  "numberReturned": 15,
  "numberMatched": 15,
  "features": [
    {
      "id": "2305843009229499373",
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              101.5578365133831,
              3.0547452911617
            ],
            [
              101.5580674069986,
              3.0553611890887
            ],
            [
              101.557876707062,
              3.0554326910869
            ],
            [
              101.5576354192522,
              3.0548172122807
            ],
            [
              101.5578365133831,
              3.0547452911617
            ]
          ]
        ]
      },
      "properties": {
        "feature-id": 2305843009229499373,
        "created_by": "Potlatch 0.6",
        "landuse": "residential",
        "building": "yes",
        "id": "2305843009229499373",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1705555405.84978,
        "x_max": -1276078.7650104035,
        "x_min": -1276125.1697413276,
        "y_max": 6239991.512113506,
        "y_min": 6239978.749965917,
        "z_max": 337695.36020748876,
        "z_min": 337619.4573208119,
        "line-hidden": "null",
        "amenity": "null",
        "parking": "null",
        "name": "null",
        "is_in": "null",
        "shop": "null",
        "name-zh": "null",
        "addr:city": "null",
        "addr:place": "null",
        "name-en": "null",
        "name-it": "null",
        "leisure": "null",
        "sport": "null",
        "emergency": "null",
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
              "T284983264"
            ],
            "10": [
              "T2849832649",
              "T2849832647"
            ],
            "11": [
              "T28498326497",
              "T28498326474",
              "T28498326491"
            ],
            "12": [
              "T284983264976",
              "T284983264749",
              "T284983264914",
              "T284983264974"
            ],
            "13": [
              "T2849832649769",
              "T2849832647499",
              "T2849832649144",
              "T2849832649749"
            ]
          }
        }
      },
      "links": [
        {
          "rel": "self",
          "type": "application/geo+json",
          "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=json"
        },
        {
          "rel": "alternate",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=geojson"
        },
        {
          "rel": "alternate",
          "type": "application/vnd.ogc.fg+json",
          "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=jsonfg"
        },
        {
          "rel": "alternate",
          "type": "application/ld+json",
          "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=jsonld"
        },
        {
          "rel": "alternate",
          "type": "text/html",
          "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373"
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
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Agent",
          "name": "agents:%3COrganisation%3E",
          "agentType": "organization",
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:reorganiseData_task-2305843009229499373",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:23:26.077610+00:00",
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:23:26.385690+00:00",
          "generated": "null"
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_featureData_task-2305843009229499373",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:23:26.493850+00:00",
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task",
            "dggsOperations:reorganiseData_task-2305843009229499373"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:23:41.340327+00:00",
          "generated": [
            "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ]
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
          "wasInformedBy": "null",
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
          "generated": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
          ]
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution"
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
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9",
          "entityType": "rawData",
          "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:24.663693+00:00",
          "wasDerivedFrom": "terranexusJobs:MapDataToZones_cae879d1d789"
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings___Properties",
          "entityType": "FeatureCollectionProperties",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:25.444245+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings/items/2305843009229499373",
          "entityType": "Feature",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:25.507396+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json",
            "terranexusCollections:osm_singapore_buildings"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
          "entityType": "FeatureCollectionDGGSZones",
          "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373",
          "hadPrimarySource": [
            "terranexusCollections:osm_singapore_buildings",
            "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ],
          "generatedAtTime": "2024-01-18T05:23:27.310511+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusCollections:osm_singapore_buildings",
            "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusJobs:MapDataToZones_cae879d1d789",
          "entityType": "ogcapiProcessJob",
          "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
          "hadPrimarySource": [
            "agents:admin%40terranexus.pangaeainnovations.com"
          ],
          "generatedAtTime": "2024-01-18T05:23:24.651036+00:00",
          "wasDerivedFrom": "null"
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings",
          "entityType": "FeatureCollection",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:25.388490+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
          "entityType": "DGGS",
          "wasGeneratedBy": "null",
          "hadPrimarySource": [
            "agents:TerraNexus"
          ],
          "generatedAtTime": "2024-01-18T05:23:22.485613+00:00",
          "wasDerivedFrom": "null"
        }
      ],
      "time": {
        "timestamp": "2024-01-18T05:23:25.507396+00:00"
      },
      "place": {
        "type": "null"
      }
    },
    {
      "id": "2305843009231960349",
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              101.5582514848274,
              3.0553554890466
            ],
            [
              101.5580114962919,
              3.0546887098619
            ],
            [
              101.5581993881195,
              3.0546141901944
            ],
            [
              101.5584426877089,
              3.0552926209357
            ],
            [
              101.5582514848274,
              3.0553554890466
            ]
          ]
        ]
      },
      "properties": {
        "feature-id": 2305843009231960349,
        "created_by": "Potlatch 0.6",
        "landuse": "residential",
        "building": "yes",
        "id": "2305843009231960349",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1705555421.512603,
        "x_max": -1276119.874648313,
        "x_min": -1276166.1218249332,
        "y_max": 6239983.877946686,
        "y_min": 6239970.787292116,
        "z_max": 337686.8355395783,
        "z_min": 337604.9811109423,
        "line-hidden": "null",
        "amenity": "null",
        "parking": "null",
        "name": "null",
        "is_in": "null",
        "shop": "null",
        "name-zh": "null",
        "addr:city": "null",
        "addr:place": "null",
        "name-en": "null",
        "name-it": "null",
        "leisure": "null",
        "sport": "null",
        "emergency": "null",
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
              "T284983264",
              "T284983268"
            ],
            "10": [
              "T2849832647",
              "T2849832649",
              "T2849832685"
            ],
            "11": [
              "T28498326478",
              "T28498326498",
              "T28498326852",
              "T28498326477"
            ],
            "12": [
              "T284983264783",
              "T284983264984",
              "T284983268521",
              "T284983264772"
            ],
            "13": [
              "T2849832647834",
              "T2849832649848",
              "T2849832685211",
              "T2849832647725"
            ]
          }
        }
      },
      "links": [
        {
          "rel": "self",
          "type": "application/geo+json",
          "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=json"
        },
        {
          "rel": "alternate",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=geojson"
        },
        {
          "rel": "alternate",
          "type": "application/vnd.ogc.fg+json",
          "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=jsonfg"
        },
        {
          "rel": "alternate",
          "type": "application/ld+json",
          "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=jsonld"
        },
        {
          "rel": "alternate",
          "type": "text/html",
          "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349"
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
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Agent",
          "name": "agents:%3COrganisation%3E",
          "agentType": "organization",
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
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
          "wasInformedBy": "null",
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
          "generated": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
          ]
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution"
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
          ]
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:reorganiseData_task-2305843009231960349",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:23:41.708387+00:00",
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:23:41.969677+00:00",
          "generated": "null"
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_featureData_task-2305843009231960349",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:23:42.120315+00:00",
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task",
            "dggsOperations:reorganiseData_task-2305843009231960349"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:23:57.807022+00:00",
          "generated": [
            "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
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
          "wasDerivedFrom": "null"
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
          "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960349",
          "entityType": "Feature",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:41.381234+00:00",
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
          "wasGeneratedBy": "null",
          "wasDerivedFrom": "null"
        }
      ],
      "time": {
        "timestamp": "2024-01-18T05:23:41.381234+00:00"
      },
      "place": {
        "type": "null"
      }
    },
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
        "feature-id": 2305843009231960466,
        "created_by": "Potlatch 0.6",
        "landuse": "residential",
        "building": "yes",
        "id": "2305843009231960466",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1705555437.893201,
        "x_max": -1276146.633556901,
        "x_min": -1276196.2185377243,
        "y_max": 6239978.947472959,
        "y_min": 6239965.272903057,
        "z_max": 337676.8530694004,
        "z_min": 337594.5358394981,
        "line-hidden": "null",
        "amenity": "null",
        "parking": "null",
        "name": "null",
        "is_in": "null",
        "shop": "null",
        "name-zh": "null",
        "addr:city": "null",
        "addr:place": "null",
        "name-en": "null",
        "name-it": "null",
        "leisure": "null",
        "sport": "null",
        "emergency": "null",
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
              "T2849832685",
              "T2849832647"
            ],
            "11": [
              "T28498326851",
              "T28498326476",
              "T28498326477"
            ],
            "12": [
              "T284983268516",
              "T284983264769",
              "T284983264772",
              "T284983268515"
            ],
            "13": [
              "T2849832685168",
              "T2849832647696",
              "T2849832647726",
              "T2849832685157"
            ]
          }
        }
      },
      "links": [
        {
          "rel": "self",
          "type": "application/geo+json",
          "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466?f=json"
        },
        {
          "rel": "alternate",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466?f=geojson"
        },
        {
          "rel": "alternate",
          "type": "application/vnd.ogc.fg+json",
          "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466?f=jsonfg"
        },
        {
          "rel": "alternate",
          "type": "application/ld+json",
          "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466?f=jsonld"
        },
        {
          "rel": "alternate",
          "type": "text/html",
          "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466"
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
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Agent",
          "name": "agents:%3COrganisation%3E",
          "agentType": "organization",
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
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
          "wasInformedBy": "null"
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
          "generated": "null",
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
          "generated": "null",
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
          "id": "dggsOperations:reorganiseData_task-2305843009231960466",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:23:57.943043+00:00",
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
          "endedAtTime": "2024-01-18T05:23:58.034751+00:00",
          "generated": "null",
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task"
          ]
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_featureData_task-2305843009231960466",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:23:58.134275+00:00",
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
          "endedAtTime": "2024-01-18T05:24:15.523878+00:00",
          "generated": [
            "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ],
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task",
            "dggsOperations:reorganiseData_task-2305843009231960466"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9",
          "entityType": "rawData",
          "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:24.663693+00:00",
          "wasDerivedFrom": "terranexusJobs:MapDataToZones_cae879d1d789"
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings___Properties",
          "entityType": "FeatureCollectionProperties",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:25.444245+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
          "entityType": "FeatureCollectionDGGSZones",
          "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373",
          "hadPrimarySource": [
            "terranexusCollections:osm_singapore_buildings",
            "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ],
          "generatedAtTime": "2024-01-18T05:23:27.310511+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusCollections:osm_singapore_buildings",
            "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusJobs:MapDataToZones_cae879d1d789",
          "entityType": "ogcapiProcessJob",
          "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
          "hadPrimarySource": [
            "agents:admin%40terranexus.pangaeainnovations.com"
          ],
          "generatedAtTime": "2024-01-18T05:23:24.651036+00:00",
          "wasDerivedFrom": "null"
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings",
          "entityType": "FeatureCollection",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:25.388490+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960466",
          "entityType": "Feature",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:57.834082+00:00",
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
          "wasGeneratedBy": "null",
          "hadPrimarySource": [
            "agents:TerraNexus"
          ],
          "generatedAtTime": "2024-01-18T05:23:22.485613+00:00",
          "wasDerivedFrom": "null"
        }
      ],
      "time": {
        "timestamp": "2024-01-18T05:23:57.834082+00:00"
      },
      "place": {
        "type": "null"
      }
    },
    {
      "id": "2305843009231960589",
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              101.5579443950615,
              3.0537888995459
            ],
            [
              101.5581246169796,
              3.0537228880294
            ],
            [
              101.5583058447874,
              3.05419921875
            ],
            [
              101.5584110860051,
              3.0544757965261
            ],
            [
              101.5582260022865,
              3.054542017603
            ],
            [
              101.5580978351643,
              3.05419921875
            ],
            [
              101.5579443950615,
              3.0537888995459
            ]
          ]
        ]
      },
      "properties": {
        "feature-id": 2305843009231960589,
        "created_by": "null",
        "landuse": "residential",
        "building": "yes",
        "id": "2305843009231960589",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1705555455.655527,
        "x_max": -1276113.6289550927,
        "x_min": -1276163.644612229,
        "y_max": 6239990.566373775,
        "y_min": 6239976.207058218,
        "z_max": 337597.0117900565,
        "z_min": 337506.56320081395,
        "line-hidden": [
          {
            "contour": 0,
            "segments": [
              {
                "from": 0,
                "to": 5
              },
              {
                "from": 5,
                "to": 6
              }
            ]
          }
        ],
        "amenity": "null",
        "parking": "null",
        "name": "null",
        "is_in": "null",
        "shop": "null",
        "name-zh": "null",
        "addr:city": "null",
        "addr:place": "null",
        "name-en": "null",
        "name-it": "null",
        "leisure": "null",
        "sport": "null",
        "emergency": "null",
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
              "T28498327",
              "T28498326"
            ],
            "9": [
              "T284983273",
              "T284983268"
            ],
            "10": [
              "T2849832731",
              "T2849832685"
            ],
            "11": [
              "T28498327315",
              "T28498326859",
              "T28498326856",
              "T28498326851",
              "T28498326852",
              "T28498326857"
            ],
            "12": [
              "T284983273151",
              "T284983268597",
              "T284983268562",
              "T284983268517",
              "T284983268521",
              "T284983268571"
            ],
            "13": [
              "T2849832731514",
              "T2849832685976",
              "T2849832685629",
              "T2849832685177",
              "T2849832685218",
              "T2849832685713"
            ]
          }
        }
      },
      "links": [
        {
          "rel": "self",
          "type": "application/geo+json",
          "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589?f=json"
        },
        {
          "rel": "alternate",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589?f=geojson"
        },
        {
          "rel": "alternate",
          "type": "application/vnd.ogc.fg+json",
          "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589?f=jsonfg"
        },
        {
          "rel": "alternate",
          "type": "application/ld+json",
          "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589?f=jsonld"
        },
        {
          "rel": "alternate",
          "type": "text/html",
          "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589"
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
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Agent",
          "name": "agents:%3COrganisation%3E",
          "agentType": "organization",
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
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
          "wasInformedBy": "null"
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
          "generated": "null",
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
          "generated": "null",
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
          "id": "dggsOperations:map_featureData_task-2305843009231960589",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:24:16.109523+00:00",
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
          "endedAtTime": "2024-01-18T05:24:39.010138+00:00",
          "generated": [
            "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ],
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task",
            "dggsOperations:reorganiseData_task-2305843009231960589"
          ]
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:reorganiseData_task-2305843009231960589",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:24:15.745664+00:00",
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
          "endedAtTime": "2024-01-18T05:24:15.882453+00:00",
          "generated": "null",
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9",
          "entityType": "rawData",
          "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:24.663693+00:00",
          "wasDerivedFrom": "terranexusJobs:MapDataToZones_cae879d1d789"
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings___Properties",
          "entityType": "FeatureCollectionProperties",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:25.444245+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
          "entityType": "FeatureCollectionDGGSZones",
          "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373",
          "hadPrimarySource": [
            "terranexusCollections:osm_singapore_buildings",
            "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ],
          "generatedAtTime": "2024-01-18T05:23:27.310511+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusCollections:osm_singapore_buildings",
            "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960589",
          "entityType": "Feature",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:24:15.553951+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json",
            "terranexusCollections:osm_singapore_buildings"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusJobs:MapDataToZones_cae879d1d789",
          "entityType": "ogcapiProcessJob",
          "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
          "hadPrimarySource": [
            "agents:admin%40terranexus.pangaeainnovations.com"
          ],
          "generatedAtTime": "2024-01-18T05:23:24.651036+00:00",
          "wasDerivedFrom": "null"
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings",
          "entityType": "FeatureCollection",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:25.388490+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
          "entityType": "DGGS",
          "wasGeneratedBy": "null",
          "hadPrimarySource": [
            "agents:TerraNexus"
          ],
          "generatedAtTime": "2024-01-18T05:23:22.485613+00:00",
          "wasDerivedFrom": "null"
        }
      ],
      "time": {
        "timestamp": "2024-01-18T05:24:15.553951+00:00"
      },
      "place": {
        "type": "null"
      }
    },
    {
      "id": "2305843009231960619",
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              101.5577051190312,
              3.053875112682
            ],
            [
              101.557886891696,
              3.0538091011655
            ],
            [
              101.5580292250992,
              3.05419921875
            ],
            [
              101.5581625893186,
              3.0545648177712
            ],
            [
              101.5579808166538,
              3.0546299072221
            ],
            [
              101.5578234787281,
              3.05419921875
            ],
            [
              101.5577051190312,
              3.053875112682
            ]
          ]
        ]
      },
      "properties": {
        "feature-id": 2305843009231960619,
        "created_by": "Potlatch 0.6",
        "landuse": "residential",
        "building": "yes",
        "id": "2305843009231960619",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1705555479.150384,
        "x_max": -1276087.4680238087,
        "x_min": -1276136.47619351,
        "y_max": 6239995.397990122,
        "y_min": 6239981.227931422,
        "z_max": 337606.71659015486,
        "z_min": 337516.08289024205,
        "line-hidden": [
          {
            "contour": 0,
            "segments": [
              {
                "from": 0,
                "to": 5
              },
              {
                "from": 5,
                "to": 6
              }
            ]
          }
        ],
        "amenity": "null",
        "parking": "null",
        "name": "null",
        "is_in": "null",
        "shop": "null",
        "name-zh": "null",
        "addr:city": "null",
        "addr:place": "null",
        "name-en": "null",
        "name-it": "null",
        "leisure": "null",
        "sport": "null",
        "emergency": "null",
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
              "T28498327",
              "T28498326"
            ],
            "9": [
              "T284983273",
              "T284983268",
              "T284983264"
            ],
            "10": [
              "T2849832731",
              "T2849832685",
              "T2849832649"
            ],
            "11": [
              "T28498327313",
              "T28498327314",
              "T28498326858",
              "T28498326852",
              "T28498326498"
            ],
            "12": [
              "T284983273138",
              "T284983273141",
              "T284983268581",
              "T284983268521",
              "T284983264988",
              "T284983268583"
            ],
            "13": [
              "T2849832731386",
              "T2849832731416",
              "T2849832685816",
              "T2849832685217",
              "T2849832649888",
              "T2849832685835"
            ]
          }
        }
      },
      "links": [
        {
          "rel": "self",
          "type": "application/geo+json",
          "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619?f=json"
        },
        {
          "rel": "alternate",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619?f=geojson"
        },
        {
          "rel": "alternate",
          "type": "application/vnd.ogc.fg+json",
          "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619?f=jsonfg"
        },
        {
          "rel": "alternate",
          "type": "application/ld+json",
          "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619?f=jsonld"
        },
        {
          "rel": "alternate",
          "type": "text/html",
          "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619"
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
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Agent",
          "name": "agents:%3COrganisation%3E",
          "agentType": "organization",
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
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
          "wasInformedBy": "null",
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
          "generated": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
          ]
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution"
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
          ]
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:reorganiseData_task-2305843009231960619",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:24:39.221754+00:00",
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:24:39.307410+00:00",
          "generated": "null"
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_featureData_task-2305843009231960619",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:24:39.449608+00:00",
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task",
            "dggsOperations:reorganiseData_task-2305843009231960619"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:25:05.015295+00:00",
          "generated": [
            "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
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
          "wasDerivedFrom": "null"
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
          "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960619",
          "entityType": "Feature",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:24:39.057589+00:00",
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
          "wasGeneratedBy": "null",
          "wasDerivedFrom": "null"
        }
      ],
      "time": {
        "timestamp": "2024-01-18T05:24:39.057589+00:00"
      },
      "place": {
        "type": "null"
      }
    },
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
        "feature-id": 2305843009231960767,
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
        "line-hidden": "null",
        "amenity": "null",
        "parking": "null",
        "name": "null",
        "is_in": "null",
        "shop": "null",
        "name-zh": "null",
        "addr:city": "null",
        "addr:place": "null",
        "name-en": "null",
        "name-it": "null",
        "leisure": "null",
        "sport": "null",
        "emergency": "null",
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
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767?f=json"
        },
        {
          "rel": "alternate",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767?f=geojson"
        },
        {
          "rel": "alternate",
          "type": "application/vnd.ogc.fg+json",
          "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767?f=jsonfg"
        },
        {
          "rel": "alternate",
          "type": "application/ld+json",
          "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767?f=jsonld"
        },
        {
          "rel": "alternate",
          "type": "text/html",
          "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767"
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
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Agent",
          "name": "agents:%3COrganisation%3E",
          "agentType": "organization",
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task",
            "dggsOperations:reorganiseData_task-2305843009231960767"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:25:28.430251+00:00",
          "generated": [
            "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ]
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
          "wasInformedBy": "null",
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
          "generated": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
          ]
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:25:05.226533+00:00",
          "generated": "null"
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
          "wasDerivedFrom": "null"
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
          "wasGeneratedBy": "null",
          "wasDerivedFrom": "null"
        }
      ],
      "time": {
        "timestamp": "2024-01-18T05:25:05.050331+00:00"
      },
      "place": {
        "type": "null"
      }
    },
    {
      "id": "2305843009231960798",
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              101.5584495193769,
              3.054149385294
            ],
            [
              101.5586538826496,
              3.0540765001974
            ],
            [
              101.5587004050517,
              3.05419921875
            ],
            [
              101.5587553936928,
              3.0543444021742
            ],
            [
              101.5585524135185,
              3.0544169938863
            ],
            [
              101.5584686731947,
              3.05419921875
            ],
            [
              101.5584495193769,
              3.054149385294
            ]
          ]
        ]
      },
      "properties": {
        "feature-id": 2305843009231960798,
        "created_by": "Potlatch 0.6",
        "landuse": "residential",
        "building": "yes",
        "id": "2305843009231960798",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1705555528.572812,
        "x_max": -1276168.2156584898,
        "x_min": -1276201.2976202518,
        "y_max": 6239977.235185958,
        "y_min": 6239969.296571625,
        "z_max": 337583.2066295785,
        "z_min": 337545.6091949509,
        "line-hidden": [
          {
            "contour": 0,
            "segments": [
              {
                "from": 0,
                "to": 5
              },
              {
                "from": 5,
                "to": 6
              }
            ]
          }
        ],
        "amenity": "null",
        "parking": "null",
        "name": "null",
        "is_in": "null",
        "shop": "null",
        "name-zh": "null",
        "addr:city": "null",
        "addr:place": "null",
        "name-en": "null",
        "name-it": "null",
        "leisure": "null",
        "sport": "null",
        "emergency": "null",
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
              "T284983268"
            ],
            "10": [
              "T2849832684"
            ],
            "11": [
              "T28498326846",
              "T28498326842",
              "T28498326841"
            ],
            "12": [
              "T284983268466",
              "T284983268465",
              "T284983268427",
              "T284983268421",
              "T284983268417",
              "T284983268462"
            ],
            "13": [
              "T2849832684663",
              "T2849832684653",
              "T2849832684273",
              "T2849832684218",
              "T2849832684178",
              "T2849832684623"
            ]
          }
        }
      },
      "links": [
        {
          "rel": "self",
          "type": "application/geo+json",
          "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798?f=json"
        },
        {
          "rel": "alternate",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798?f=geojson"
        },
        {
          "rel": "alternate",
          "type": "application/vnd.ogc.fg+json",
          "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798?f=jsonfg"
        },
        {
          "rel": "alternate",
          "type": "application/ld+json",
          "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798?f=jsonld"
        },
        {
          "rel": "alternate",
          "type": "text/html",
          "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798"
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
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Agent",
          "name": "agents:%3COrganisation%3E",
          "agentType": "organization",
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:reorganiseData_task-2305843009231960798",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:25:28.624522+00:00",
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:25:28.676283+00:00",
          "generated": "null"
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
          "wasInformedBy": "null",
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
          "generated": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
          ]
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution"
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
          ]
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_featureData_task-2305843009231960798",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:25:28.765830+00:00",
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task",
            "dggsOperations:reorganiseData_task-2305843009231960798"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:25:59.513697+00:00",
          "generated": [
            "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
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
          "wasDerivedFrom": "null"
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
          "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960798",
          "entityType": "Feature",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:25:28.478210+00:00",
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
          "wasGeneratedBy": "null",
          "wasDerivedFrom": "null"
        }
      ],
      "time": {
        "timestamp": "2024-01-18T05:25:28.478210+00:00"
      },
      "place": {
        "type": "null"
      }
    },
    {
      "id": "2305843009231960865",
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              101.5587754276641,
              3.05419921875
            ],
            [
              101.5587182176832,
              3.0540495088218
            ],
            [
              101.5590028844896,
              3.0539479139545
            ],
            [
              101.5590964322386,
              3.05419921875
            ],
            [
              101.5593548201747,
              3.0548932826949
            ],
            [
              101.559080212266,
              3.0549963025727
            ],
            [
              101.5587754276641,
              3.05419921875
            ]
          ]
        ]
      },
      "properties": {
        "feature-id": 2305843009231960865,
        "created_by": "null",
        "landuse": "null",
        "building": "yes",
        "id": "2305843009231960865",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1705555559.635015,
        "x_max": -1276197.5969815229,
        "x_min": -1276265.9318077033,
        "y_max": 6239971.826792301,
        "y_min": 6239952.776008753,
        "z_max": 337647.17407459696,
        "z_min": 337531.4106530871,
        "line-hidden": [
          {
            "contour": 0,
            "segments": [
              {
                "from": 0,
                "to": 5
              },
              {
                "from": 5,
                "to": 6
              }
            ]
          }
        ],
        "amenity": "parking",
        "parking": "multi-storey",
        "name": "null",
        "is_in": "null",
        "shop": "null",
        "name-zh": "null",
        "addr:city": "null",
        "addr:place": "null",
        "name-en": "null",
        "name-it": "null",
        "leisure": "null",
        "sport": "null",
        "emergency": "null",
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
              "T2849832684",
              "T2849832683",
              "T2849832648"
            ],
            "11": [
              "T28498326842",
              "T28498326844",
              "T28498326838",
              "T28498326488"
            ],
            "12": [
              "T284983268426",
              "T284983268429",
              "T284983268446",
              "T284983268389",
              "T284983264885",
              "T284983264886"
            ],
            "13": [
              "T2849832684266",
              "T2849832684299",
              "T2849832684463",
              "T2849832683893",
              "T2849832648855",
              "T2849832648862"
            ]
          }
        }
      },
      "links": [
        {
          "rel": "self",
          "type": "application/geo+json",
          "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865?f=json"
        },
        {
          "rel": "alternate",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865?f=geojson"
        },
        {
          "rel": "alternate",
          "type": "application/vnd.ogc.fg+json",
          "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865?f=jsonfg"
        },
        {
          "rel": "alternate",
          "type": "application/ld+json",
          "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865?f=jsonld"
        },
        {
          "rel": "alternate",
          "type": "text/html",
          "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865"
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
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Agent",
          "name": "agents:%3COrganisation%3E",
          "agentType": "organization",
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
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
          "wasInformedBy": "null",
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
          "generated": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
          ]
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution"
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
          ]
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:reorganiseData_task-2305843009231960865",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:25:59.715125+00:00",
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:25:59.783035+00:00",
          "generated": "null"
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_featureData_task-2305843009231960865",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:25:59.882233+00:00",
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task",
            "dggsOperations:reorganiseData_task-2305843009231960865"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:26:25.791311+00:00",
          "generated": [
            "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
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
          "wasDerivedFrom": "null"
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
          "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960865",
          "entityType": "Feature",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:25:59.542518+00:00",
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
          "wasGeneratedBy": "null",
          "wasDerivedFrom": "null"
        }
      ],
      "time": {
        "timestamp": "2024-01-18T05:25:59.542518+00:00"
      },
      "place": {
        "type": "null"
      }
    },
    {
      "id": "2305843009232899975",
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              101.5170950017292,
              3.0440544012461
            ],
            [
              101.5169714030231,
              3.0444474945879
            ],
            [
              101.5166065165071,
              3.0443326974173
            ],
            [
              101.5167301152133,
              3.0439396040755
            ],
            [
              101.5170950017292,
              3.0440544012461
            ]
          ]
        ]
      },
      "properties": {
        "feature-id": 2305843009232899975,
        "created_by": "null",
        "landuse": "null",
        "building": "commercial",
        "id": "2305843009232899975",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1705555585.872302,
        "x_max": -1271622.3602021495,
        "x_min": -1271675.8948859423,
        "y_max": 6240964.134369386,
        "y_min": 6240954.894049214,
        "z_max": 336482.36612796935,
        "z_min": 336426.2841626774,
        "line-hidden": "null",
        "amenity": "null",
        "parking": "null",
        "name": "Giant",
        "is_in": "Seksyen 18, Shah Alam, Selangor, Malaysia",
        "shop": "supermarket",
        "name-zh": "null",
        "addr:city": "null",
        "addr:place": "null",
        "name-en": "null",
        "name-it": "null",
        "leisure": "null",
        "sport": "null",
        "emergency": "null",
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
              "T284982"
            ],
            "7": [
              "T2849826",
              "T2849827"
            ],
            "8": [
              "T28498268",
              "T28498273"
            ],
            "9": [
              "T284982688",
              "T284982733"
            ],
            "10": [
              "T2849826889",
              "T2849827335"
            ],
            "11": [
              "T28498268897",
              "T28498268893",
              "T28498268895",
              "T28498273353"
            ],
            "12": [
              "T284982688973",
              "T284982688933",
              "T284982688957",
              "T284982733533"
            ],
            "13": [
              "T2849826889732",
              "T2849826889339",
              "T2849826889571",
              "T2849827335338"
            ]
          }
        }
      },
      "links": [
        {
          "rel": "self",
          "type": "application/geo+json",
          "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975?f=json"
        },
        {
          "rel": "alternate",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975?f=geojson"
        },
        {
          "rel": "alternate",
          "type": "application/vnd.ogc.fg+json",
          "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975?f=jsonfg"
        },
        {
          "rel": "alternate",
          "type": "application/ld+json",
          "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975?f=jsonld"
        },
        {
          "rel": "alternate",
          "type": "text/html",
          "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975"
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
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Agent",
          "name": "agents:%3COrganisation%3E",
          "agentType": "organization",
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
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
          "wasInformedBy": "null",
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
          "generated": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
          ]
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution"
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
          ]
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:reorganiseData_task-2305843009232899975",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:26:25.925281+00:00",
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:26:25.997827+00:00",
          "generated": "null"
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_featureData_task-2305843009232899975",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:26:26.115242+00:00",
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task",
            "dggsOperations:reorganiseData_task-2305843009232899975"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:26:50.496862+00:00",
          "generated": [
            "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
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
          "wasDerivedFrom": "null"
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
          "id": "terranexusCollections:osm_singapore_buildings/items/2305843009232899975",
          "entityType": "Feature",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:26:25.820867+00:00",
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
          "wasGeneratedBy": "null",
          "wasDerivedFrom": "null"
        }
      ],
      "time": {
        "timestamp": "2024-01-18T05:26:25.820867+00:00"
      },
      "place": {
        "type": "null"
      }
    },
    {
      "id": "2305843009232900002",
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              101.5158121988813,
              3.0451234106047
            ],
            [
              101.5159503829892,
              3.0453711109619
            ],
            [
              101.5157614852718,
              3.0454825132545
            ],
            [
              101.5156056980929,
              3.0451745852471
            ],
            [
              101.5156228820432,
              3.0449524931671
            ],
            [
              101.5157057841255,
              3.0446933927258
            ],
            [
              101.5158238085258,
              3.0447117083022
            ],
            [
              101.5158601043818,
              3.0447487166635
            ],
            [
              101.5158121988813,
              3.0451234106047
            ]
          ]
        ]
      },
      "properties": {
        "feature-id": 2305843009232900002,
        "created_by": "null",
        "landuse": "null",
        "building": "commercial",
        "id": "2305843009232900002",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1705555610.592237,
        "x_max": -1271512.3583419316,
        "x_min": -1271549.6728737596,
        "y_max": 6240982.397314117,
        "y_min": 6240972.719726458,
        "z_max": 336596.6542250734,
        "z_min": 336509.51852749335,
        "line-hidden": "null",
        "amenity": "null",
        "parking": "null",
        "name": "Mydin",
        "is_in": "Seksyen 18, Shah Alam, Selangor, Malaysia",
        "shop": "supermarket",
        "name-zh": "null",
        "addr:city": "null",
        "addr:place": "null",
        "name-en": "null",
        "name-it": "null",
        "leisure": "null",
        "sport": "null",
        "emergency": "null",
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
              "T284982"
            ],
            "7": [
              "T2849826",
              "T2849827"
            ],
            "8": [
              "T28498268",
              "T28498273"
            ],
            "9": [
              "T284982688",
              "T284982733"
            ],
            "10": [
              "T2849826888",
              "T2849826884",
              "T2849827333"
            ],
            "11": [
              "T28498268885",
              "T28498268884",
              "T28498268849",
              "T28498273331",
              "T28498273332",
              "T28498273333"
            ],
            "12": [
              "T284982688859",
              "T284982688841",
              "T284982688498",
              "T284982733312",
              "T284982733324",
              "T284982733329",
              "T284982733339",
              "T284982733338"
            ],
            "13": [
              "T2849826888597",
              "T2849826888417",
              "T2849826884982",
              "T2849827333129",
              "T2849827333244",
              "T2849827333299",
              "T2849827333395",
              "T2849827333387"
            ]
          }
        }
      },
      "links": [
        {
          "rel": "self",
          "type": "application/geo+json",
          "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002?f=json"
        },
        {
          "rel": "alternate",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002?f=geojson"
        },
        {
          "rel": "alternate",
          "type": "application/vnd.ogc.fg+json",
          "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002?f=jsonfg"
        },
        {
          "rel": "alternate",
          "type": "application/ld+json",
          "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002?f=jsonld"
        },
        {
          "rel": "alternate",
          "type": "text/html",
          "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002"
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
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Agent",
          "name": "agents:%3COrganisation%3E",
          "agentType": "organization",
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_featureData_task-2305843009232900002",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:26:50.744858+00:00",
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task",
            "dggsOperations:reorganiseData_task-2305843009232900002"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:27:20.122235+00:00",
          "generated": [
            "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ]
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
          "wasInformedBy": "null",
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
          "generated": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
          ]
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution"
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
          ]
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:reorganiseData_task-2305843009232900002",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:26:50.630396+00:00",
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:26:50.678018+00:00",
          "generated": "null"
        },
        {
          "provType": "Entity",
          "id": "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9",
          "entityType": "rawData",
          "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:24.663693+00:00",
          "wasDerivedFrom": "terranexusJobs:MapDataToZones_cae879d1d789"
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings___Properties",
          "entityType": "FeatureCollectionProperties",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:25.444245+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
          "entityType": "FeatureCollectionDGGSZones",
          "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373",
          "hadPrimarySource": [
            "terranexusCollections:osm_singapore_buildings",
            "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ],
          "generatedAtTime": "2024-01-18T05:23:27.310511+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusCollections:osm_singapore_buildings",
            "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings/items/2305843009232900002",
          "entityType": "Feature",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:26:50.531820+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json",
            "terranexusCollections:osm_singapore_buildings"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusJobs:MapDataToZones_cae879d1d789",
          "entityType": "ogcapiProcessJob",
          "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
          "hadPrimarySource": [
            "agents:admin%40terranexus.pangaeainnovations.com"
          ],
          "generatedAtTime": "2024-01-18T05:23:24.651036+00:00",
          "wasDerivedFrom": "null"
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings",
          "entityType": "FeatureCollection",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:25.388490+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
          "entityType": "DGGS",
          "wasGeneratedBy": "null",
          "hadPrimarySource": [
            "agents:TerraNexus"
          ],
          "generatedAtTime": "2024-01-18T05:23:22.485613+00:00",
          "wasDerivedFrom": "null"
        }
      ],
      "time": {
        "timestamp": "2024-01-18T05:26:50.531820+00:00"
      },
      "place": {
        "type": "null"
      }
    },
    {
      "id": "2305843009232901459",
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              101.5499142093375,
              3.0774648205698
            ],
            [
              101.5500360058245,
              3.0770293960334
            ],
            [
              101.5501728906581,
              3.0765117819199
            ],
            [
              101.5514844032767,
              3.0768443123147
            ],
            [
              101.5512397205888,
              3.0778124812234
            ],
            [
              101.5499142093375,
              3.0774648205698
            ]
          ]
        ]
      },
      "properties": {
        "feature-id": 2305843009232901459,
        "created_by": "null",
        "landuse": "null",
        "building": "yes",
        "id": "2305843009232901459",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1705555640.254449,
        "x_max": -1275211.0286367147,
        "x_min": -1275382.774143958,
        "y_max": 6240032.180374823,
        "y_min": 6240000.655100508,
        "z_max": 340166.5166379938,
        "z_min": 340022.89597160293,
        "line-hidden": "null",
        "amenity": "null",
        "parking": "null",
        "name": "Tesco Extra",
        "is_in": "null",
        "shop": "supermarket",
        "name-zh": "\u7279\u6613\u8d2d\u7279\u5927\u5e97",
        "addr:city": "Shah Alam",
        "addr:place": "Section 13",
        "name-en": "null",
        "name-it": "null",
        "leisure": "null",
        "sport": "null",
        "emergency": "null",
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
              "T2849831"
            ],
            "8": [
              "T28498316",
              "T28498312"
            ],
            "9": [
              "T284983165",
              "T284983129"
            ],
            "10": [
              "T2849831653",
              "T2849831654",
              "T2849831299",
              "T2849831297"
            ],
            "11": [
              "T28498316537",
              "T28498316543",
              "T28498316549",
              "T28498312997",
              "T28498312974"
            ],
            "12": [
              "T284983165372",
              "T284983165438",
              "T284983165493",
              "T284983129975",
              "T284983129745"
            ],
            "13": [
              "T2849831653725",
              "T2849831654389",
              "T2849831654934",
              "T2849831299756",
              "T2849831297453"
            ]
          }
        }
      },
      "links": [
        {
          "rel": "self",
          "type": "application/geo+json",
          "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901459?f=json"
        },
        {
          "rel": "alternate",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901459?f=geojson"
        },
        {
          "rel": "alternate",
          "type": "application/vnd.ogc.fg+json",
          "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901459?f=jsonfg"
        },
        {
          "rel": "alternate",
          "type": "application/ld+json",
          "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901459?f=jsonld"
        },
        {
          "rel": "alternate",
          "type": "text/html",
          "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901459"
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
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Agent",
          "name": "agents:%3COrganisation%3E",
          "agentType": "organization",
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
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
          "wasInformedBy": "null"
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
          "generated": "null",
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
          "generated": "null",
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
          "id": "dggsOperations:reorganiseData_task-2305843009232901459",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:27:20.294670+00:00",
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
          "endedAtTime": "2024-01-18T05:27:20.349755+00:00",
          "generated": "null",
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task"
          ]
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_featureData_task-2305843009232901459",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:27:20.429685+00:00",
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
          "endedAtTime": "2024-01-18T05:27:56.040859+00:00",
          "generated": [
            "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ],
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task",
            "dggsOperations:reorganiseData_task-2305843009232901459"
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
          "wasDerivedFrom": "null"
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
          "id": "terranexusCollections:osm_singapore_buildings/items/2305843009232901459",
          "entityType": "Feature",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:27:20.169756+00:00",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json",
            "terranexusCollections:osm_singapore_buildings"
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
          "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
          "entityType": "DGGS",
          "hadPrimarySource": [
            "agents:TerraNexus"
          ],
          "generatedAtTime": "2024-01-18T05:23:22.485613+00:00",
          "wasGeneratedBy": "null",
          "wasDerivedFrom": "null"
        }
      ],
      "time": {
        "timestamp": "2024-01-18T05:27:20.169756+00:00"
      },
      "place": {
        "type": "null"
      }
    },
    {
      "id": "2305843009232901461",
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              101.5474172137068,
              3.0795437851748
            ],
            [
              101.547719902705,
              3.0798328946611
            ],
            [
              101.5477292071854,
              3.0803091834696
            ],
            [
              101.5474367028212,
              3.0806104893694
            ],
            [
              101.5469939017597,
              3.0806296850993
            ],
            [
              101.5466431815247,
              3.0802798869299
            ],
            [
              101.546638780757,
              3.0798953855634
            ],
            [
              101.5469557198603,
              3.0795484793271
            ],
            [
              101.5474172137068,
              3.0795437851748
            ]
          ]
        ]
      },
      "properties": {
        "feature-id": 2305843009232901461,
        "created_by": "null",
        "landuse": "null",
        "building": "yes",
        "id": "2305843009232901461",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1705555676.293127,
        "x_max": -1274851.4132282431,
        "x_min": -1274969.6793106755,
        "y_max": 6240090.927641856,
        "y_min": 6240064.255301031,
        "z_max": 340477.58617624646,
        "z_min": 340357.68355863984,
        "line-hidden": "null",
        "amenity": "null",
        "parking": "null",
        "name": "Stadium Malawati",
        "is_in": "Seksyen 13, Shah Alam, Selangor, Malaysia",
        "shop": "null",
        "name-zh": "null",
        "addr:city": "null",
        "addr:place": "null",
        "name-en": "Malawati Stadium",
        "name-it": "Malawati",
        "leisure": "stadium",
        "sport": "null",
        "emergency": "null",
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
              "T2849831"
            ],
            "8": [
              "T28498316"
            ],
            "9": [
              "T284983163"
            ],
            "10": [
              "T2849831638",
              "T2849831634",
              "T2849831633",
              "T2849831632",
              "T2849831636",
              "T2849831637"
            ],
            "11": [
              "T28498316383",
              "T28498316343",
              "T28498316334",
              "T28498316336",
              "T28498316327",
              "T28498316363",
              "T28498316368",
              "T28498316376"
            ],
            "12": [
              "T284983163831",
              "T284983163439",
              "T284983163348",
              "T284983163362",
              "T284983163271",
              "T284983163638",
              "T284983163685",
              "T284983163761"
            ],
            "13": [
              "T2849831638315",
              "T2849831634393",
              "T2849831633485",
              "T2849831633621",
              "T2849831632712",
              "T2849831636384",
              "T2849831636858",
              "T2849831637611"
            ]
          }
        }
      },
      "links": [
        {
          "rel": "self",
          "type": "application/geo+json",
          "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901461?f=json"
        },
        {
          "rel": "alternate",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901461?f=geojson"
        },
        {
          "rel": "alternate",
          "type": "application/vnd.ogc.fg+json",
          "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901461?f=jsonfg"
        },
        {
          "rel": "alternate",
          "type": "application/ld+json",
          "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901461?f=jsonld"
        },
        {
          "rel": "alternate",
          "type": "text/html",
          "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901461"
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
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Agent",
          "name": "agents:%3COrganisation%3E",
          "agentType": "organization",
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
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
          "wasInformedBy": "null"
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
          "generated": "null",
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
          "generated": "null",
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
          "id": "dggsOperations:reorganiseData_task-2305843009232901461",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:27:56.373833+00:00",
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
          "endedAtTime": "2024-01-18T05:27:56.452169+00:00",
          "generated": "null",
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task"
          ]
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_featureData_task-2305843009232901461",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:27:56.535404+00:00",
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
          "endedAtTime": "2024-01-18T05:28:38.749898+00:00",
          "generated": [
            "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ],
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task",
            "dggsOperations:reorganiseData_task-2305843009232901461"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9",
          "entityType": "rawData",
          "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:24.663693+00:00",
          "wasDerivedFrom": "terranexusJobs:MapDataToZones_cae879d1d789"
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings___Properties",
          "entityType": "FeatureCollectionProperties",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:25.444245+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
          "entityType": "FeatureCollectionDGGSZones",
          "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373",
          "hadPrimarySource": [
            "terranexusCollections:osm_singapore_buildings",
            "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ],
          "generatedAtTime": "2024-01-18T05:23:27.310511+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusCollections:osm_singapore_buildings",
            "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings/items/2305843009232901461",
          "entityType": "Feature",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:27:56.109661+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json",
            "terranexusCollections:osm_singapore_buildings"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusJobs:MapDataToZones_cae879d1d789",
          "entityType": "ogcapiProcessJob",
          "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
          "hadPrimarySource": [
            "agents:admin%40terranexus.pangaeainnovations.com"
          ],
          "generatedAtTime": "2024-01-18T05:23:24.651036+00:00",
          "wasDerivedFrom": "null"
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings",
          "entityType": "FeatureCollection",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:25.388490+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
          "entityType": "DGGS",
          "wasGeneratedBy": "null",
          "hadPrimarySource": [
            "agents:TerraNexus"
          ],
          "generatedAtTime": "2024-01-18T05:23:22.485613+00:00",
          "wasDerivedFrom": "null"
        }
      ],
      "time": {
        "timestamp": "2024-01-18T05:27:56.109661+00:00"
      },
      "place": {
        "type": "null"
      }
    },
    {
      "id": "2305843009232901565",
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              101.5364629064063,
              3.0734719830191
            ],
            [
              101.5364628225822,
              3.0734252929688
            ],
            [
              101.5364627806701,
              3.073414689214
            ],
            [
              101.5371518989903,
              3.0734177068834
            ],
            [
              101.5371518989903,
              3.0734252929688
            ],
            [
              101.5371500967711,
              3.0743803014862
            ],
            [
              101.5370101942682,
              3.0743807206069
            ],
            [
              101.5370130023771,
              3.0746557057242
            ],
            [
              101.5367290899881,
              3.0746546998344
            ],
            [
              101.5364644990651,
              3.0743823970899
            ],
            [
              101.5364585056385,
              3.074256116011
            ],
            [
              101.5362406885901,
              3.0742590917683
            ],
            [
              101.5361587923976,
              3.074154688792
            ],
            [
              101.5361548107506,
              3.0739649109211
            ],
            [
              101.5360478930499,
              3.0739372070402
            ],
            [
              101.5359929044088,
              3.0738530895077
            ],
            [
              101.535977103557,
              3.0737419805996
            ],
            [
              101.53600828614,
              3.073635104811
            ],
            [
              101.536264410824,
              3.0734742881832
            ],
            [
              101.5364629064063,
              3.0734719830191
            ]
          ]
        ]
      },
      "properties": {
        "feature-id": 2305843009232901565,
        "created_by": "Potlatch 0.6a",
        "landuse": "null",
        "building": "yes",
        "id": "2305843009232901565",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1705555718.837784,
        "x_max": -1273697.530244064,
        "x_min": -1273825.8672269937,
        "y_max": 6240363.829780593,
        "y_min": 6240334.043873932,
        "z_max": 339817.9513805314,
        "z_min": 339680.9203773574,
        "line-hidden": [
          {
            "contour": 0,
            "segments": [
              {
                "from": 0,
                "to": 2
              },
              {
                "from": 3,
                "to": 4
              },
              {
                "from": 5,
                "to": 12
              },
              {
                "from": 13,
                "to": 18
              },
              {
                "from": 18,
                "to": 19
              }
            ]
          }
        ],
        "amenity": "null",
        "parking": "null",
        "name": "Pusat Akuatik Darul Ehsan",
        "is_in": "null",
        "shop": "null",
        "name-zh": "null",
        "addr:city": "null",
        "addr:place": "null",
        "name-en": "Darul Ehsan Aquatic Center",
        "name-it": "null",
        "leisure": "stadium",
        "sport": "swimming",
        "emergency": "null",
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
              "T284982"
            ],
            "7": [
              "T2849821"
            ],
            "8": [
              "T28498219",
              "T28498217"
            ],
            "9": [
              "T284982193",
              "T284982192",
              "T284982174",
              "T284982178"
            ],
            "10": [
              "T2849821931",
              "T2849821921",
              "T2849821749",
              "T2849821785",
              "T2849821784"
            ],
            "11": [
              "T28498219314",
              "T28498219211",
              "T28498219311",
              "T28498217496",
              "T28498217494",
              "T28498217493",
              "T28498217495",
              "T28498217851",
              "T28498217852",
              "T28498217842",
              "T28498217846",
              "T28498217847",
              "T28498217849",
              "T28498219315"
            ],
            "12": [
              "T284982193141",
              "T284982193142",
              "T284982192119",
              "T284982193117",
              "T284982174965",
              "T284982174945",
              "T284982174934",
              "T284982174952",
              "T284982178517",
              "T284982178523",
              "T284982178425",
              "T284982178463",
              "T284982178469",
              "T284982178474",
              "T284982178478",
              "T284982178493",
              "T284982178497",
              "T284982193153"
            ],
            "13": [
              "T2849821931412",
              "T2849821931418",
              "T2849821931423",
              "T2849821921191",
              "T2849821931175",
              "T2849821749654",
              "T2849821749459",
              "T2849821749344",
              "T2849821749521",
              "T2849821785171",
              "T2849821785235",
              "T2849821784257",
              "T2849821784636",
              "T2849821784693",
              "T2849821784743",
              "T2849821784784",
              "T2849821784938",
              "T2849821784976",
              "T2849821931533"
            ]
          }
        }
      },
      "links": [
        {
          "rel": "self",
          "type": "application/geo+json",
          "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901565?f=json"
        },
        {
          "rel": "alternate",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901565?f=geojson"
        },
        {
          "rel": "alternate",
          "type": "application/vnd.ogc.fg+json",
          "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901565?f=jsonfg"
        },
        {
          "rel": "alternate",
          "type": "application/ld+json",
          "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901565?f=jsonld"
        },
        {
          "rel": "alternate",
          "type": "text/html",
          "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901565"
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
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Agent",
          "name": "agents:%3COrganisation%3E",
          "agentType": "organization",
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
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
          "wasInformedBy": "null"
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
          "generated": "null",
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
          "generated": "null",
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
          "id": "dggsOperations:reorganiseData_task-2305843009232901565",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:28:38.881281+00:00",
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
          "endedAtTime": "2024-01-18T05:28:39.005025+00:00",
          "generated": "null",
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task"
          ]
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_featureData_task-2305843009232901565",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:28:39.093872+00:00",
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
          "endedAtTime": "2024-01-18T05:29:59.930166+00:00",
          "generated": [
            "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ],
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task",
            "dggsOperations:reorganiseData_task-2305843009232901565"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9",
          "entityType": "rawData",
          "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:24.663693+00:00",
          "wasDerivedFrom": "terranexusJobs:MapDataToZones_cae879d1d789"
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings___Properties",
          "entityType": "FeatureCollectionProperties",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:25.444245+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
          "entityType": "FeatureCollectionDGGSZones",
          "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373",
          "hadPrimarySource": [
            "terranexusCollections:osm_singapore_buildings",
            "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ],
          "generatedAtTime": "2024-01-18T05:23:27.310511+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusCollections:osm_singapore_buildings",
            "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings/items/2305843009232901565",
          "entityType": "Feature",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:28:38.783226+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json",
            "terranexusCollections:osm_singapore_buildings"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusJobs:MapDataToZones_cae879d1d789",
          "entityType": "ogcapiProcessJob",
          "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
          "hadPrimarySource": [
            "agents:admin%40terranexus.pangaeainnovations.com"
          ],
          "generatedAtTime": "2024-01-18T05:23:24.651036+00:00",
          "wasDerivedFrom": "null"
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings",
          "entityType": "FeatureCollection",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:23:25.388490+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
          "entityType": "DGGS",
          "wasGeneratedBy": "null",
          "hadPrimarySource": [
            "agents:TerraNexus"
          ],
          "generatedAtTime": "2024-01-18T05:23:22.485613+00:00",
          "wasDerivedFrom": "null"
        }
      ],
      "time": {
        "timestamp": "2024-01-18T05:28:38.783226+00:00"
      },
      "place": {
        "type": "null"
      }
    },
    {
      "id": "2305843009233038522",
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              101.5933582115208,
              3.0778352813916
            ],
            [
              101.5939204200811,
              3.0778352813916
            ],
            [
              101.5939204200811,
              3.0786624161714
            ],
            [
              101.5933582115208,
              3.0786622904352
            ],
            [
              101.5933582115208,
              3.0778352813916
            ]
          ]
        ]
      },
      "properties": {
        "feature-id": 2305843009233038522,
        "created_by": "null",
        "landuse": "null",
        "building": "yes",
        "id": "2305843009233038522",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1705555800.169564,
        "x_max": -1279940.6802046662,
        "x_min": -1280002.8871373793,
        "y_max": 6239061.315056953,
        "y_min": 6239043.944169954,
        "z_max": 340260.36469540495,
        "z_min": 340169.0341863229,
        "line-hidden": "null",
        "amenity": "hospital",
        "parking": "null",
        "name": "Sime Darby Medical Hospital Subang Jaya",
        "is_in": "null",
        "shop": "null",
        "name-zh": "null",
        "addr:city": "null",
        "addr:place": "null",
        "name-en": "null",
        "name-it": "null",
        "leisure": "null",
        "sport": "null",
        "emergency": "yes",
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
              "T28494"
            ],
            "6": [
              "T284948"
            ],
            "7": [
              "T2849484"
            ],
            "8": [
              "T28494845"
            ],
            "9": [
              "T284948457",
              "T284948456"
            ],
            "10": [
              "T2849484573",
              "T2849484564",
              "T2849484568"
            ],
            "11": [
              "T28494845733",
              "T28494845731",
              "T28494845648",
              "T28494845681"
            ],
            "12": [
              "T284948457335",
              "T284948457316",
              "T284948456481",
              "T284948456818"
            ],
            "13": [
              "T2849484573353",
              "T2849484573165",
              "T2849484564812",
              "T2849484568182"
            ]
          }
        }
      },
      "links": [
        {
          "rel": "self",
          "type": "application/geo+json",
          "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233038522?f=json"
        },
        {
          "rel": "alternate",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233038522?f=geojson"
        },
        {
          "rel": "alternate",
          "type": "application/vnd.ogc.fg+json",
          "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233038522?f=jsonfg"
        },
        {
          "rel": "alternate",
          "type": "application/ld+json",
          "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233038522?f=jsonld"
        },
        {
          "rel": "alternate",
          "type": "text/html",
          "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233038522"
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
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Agent",
          "name": "agents:%3COrganisation%3E",
          "agentType": "organization",
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:reorganiseData_task-2305843009233038522",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:30:00.242274+00:00",
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:30:00.413889+00:00",
          "generated": "null"
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_featureData_task-2305843009233038522",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:30:00.750806+00:00",
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task",
            "dggsOperations:reorganiseData_task-2305843009233038522"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:31:22.112248+00:00",
          "generated": [
            "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ]
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
          "wasInformedBy": "null",
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
          "generated": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
          ]
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution"
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
          "wasDerivedFrom": "null"
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
          "id": "terranexusCollections:osm_singapore_buildings/items/2305843009233038522",
          "entityType": "Feature",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:29:59.992287+00:00",
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
          "wasGeneratedBy": "null",
          "wasDerivedFrom": "null"
        }
      ],
      "time": {
        "timestamp": "2024-01-18T05:29:59.992287+00:00"
      },
      "place": {
        "type": "null"
      }
    },
    {
      "id": "2305843009233494536",
      "type": "Feature",
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
            [
              101.5378867014711,
              3.0720647851357
            ],
            [
              101.5383911132813,
              3.0714835065818
            ],
            [
              101.5386065832535,
              3.0712352194556
            ],
            [
              101.5387849191283,
              3.0712233164266
            ],
            [
              101.5394376996803,
              3.0718156178559
            ],
            [
              101.5386484953275,
              3.0727402820318
            ],
            [
              101.5383911132813,
              3.0725120707891
            ],
            [
              101.5381551902169,
              3.0723028876279
            ],
            [
              101.5378867014711,
              3.0720647851357
            ]
          ]
        ]
      },
      "properties": {
        "feature-id": 2305843009233494536,
        "created_by": "null",
        "landuse": "null",
        "building": "yes",
        "id": "2305843009233494536",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1705555882.279658,
        "x_max": -1273907.5017266115,
        "x_min": -1274076.722548753,
        "y_max": 6240331.116519038,
        "y_min": 6240298.076200732,
        "z_max": 339606.45337933605,
        "z_min": 339438.95221485576,
        "line-hidden": [
          {
            "contour": 0,
            "segments": [
              {
                "from": 0,
                "to": 3
              },
              {
                "from": 5,
                "to": 7
              },
              {
                "from": 7,
                "to": 8
              }
            ]
          }
        ],
        "amenity": "null",
        "parking": "null",
        "name": "Tesco",
        "is_in": "Seksyen 13, Shah Alam, Selangor, Malaysia",
        "shop": "supermarket",
        "name-zh": "null",
        "addr:city": "null",
        "addr:place": "null",
        "name-en": "null",
        "name-it": "null",
        "leisure": "null",
        "sport": "null",
        "emergency": "null",
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
              "T284982"
            ],
            "7": [
              "T2849821"
            ],
            "8": [
              "T28498219"
            ],
            "9": [
              "T284982192",
              "T284982191"
            ],
            "10": [
              "T2849821923",
              "T2849821924",
              "T2849821925",
              "T2849821919",
              "T2849821918"
            ],
            "11": [
              "T28498219236",
              "T28498219242",
              "T28498219246",
              "T28498219256",
              "T28498219193",
              "T28498219183",
              "T28498219184",
              "T28498219232"
            ],
            "12": [
              "T284982192367",
              "T284982192426",
              "T284982192466",
              "T284982192563",
              "T284982191933",
              "T284982191832",
              "T284982191847",
              "T284982192322"
            ],
            "13": [
              "T2849821923673",
              "T2849821924268",
              "T2849821924662",
              "T2849821925636",
              "T2849821919339",
              "T2849821918329",
              "T2849821918478",
              "T2849821923227"
            ]
          }
        }
      },
      "links": [
        {
          "rel": "self",
          "type": "application/geo+json",
          "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233494536?f=json"
        },
        {
          "rel": "alternate",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233494536?f=geojson"
        },
        {
          "rel": "alternate",
          "type": "application/vnd.ogc.fg+json",
          "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233494536?f=jsonfg"
        },
        {
          "rel": "alternate",
          "type": "application/ld+json",
          "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233494536?f=jsonld"
        },
        {
          "rel": "alternate",
          "type": "text/html",
          "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
          "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233494536"
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
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Agent",
          "name": "agents:%3COrganisation%3E",
          "agentType": "organization",
          "actedOnBehalfOf": "null",
          "qualifiedDelegation": "null"
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:reorganiseData_task-2305843009233494536",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:31:22.345165+00:00",
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:31:22.431125+00:00",
          "generated": "null"
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_featureData_task-2305843009233494536",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-01-18T05:31:22.519324+00:00",
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution",
            "dggsOperations:processData_task",
            "dggsOperations:reorganiseData_task-2305843009233494536"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.644262+00:00",
          "generated": [
            "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ]
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
          "wasInformedBy": "null",
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
          "generated": [
            "terranexusJobs:MapDataToZones_cae879d1d789",
            "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
          ]
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data"
          ],
          "used": [
            "terranexusJobs:MapDataToZones_cae879d1d789"
          ],
          "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
          "generated": "null"
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
          "wasInformedBy": [
            "terranexusProcesses:execution/MapDataToZones",
            "dggsOperations:map_data",
            "dggsOperations:map_data_execution"
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
          "wasDerivedFrom": "null"
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
          "id": "terranexusCollections:osm_singapore_buildings/items/2305843009233494536",
          "entityType": "Feature",
          "hadPrimarySource": [
            "https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json"
          ],
          "generatedAtTime": "2024-01-18T05:31:22.172753+00:00",
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
          "wasGeneratedBy": "null",
          "wasDerivedFrom": "null"
        }
      ],
      "time": {
        "timestamp": "2024-01-18T05:31:22.172753+00:00"
      },
      "place": {
        "type": "null"
      }
    }
  ],
  "links": [
    {
      "rel": "self",
      "type": "application/geo+json",
      "title": "The JSON representation of the resources served from this OGC API Implementation Endpoint",
      "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items?f=json"
    },
    {
      "rel": "alternate",
      "type": "application/geo+json",
      "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
      "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items?f=geojson"
    },
    {
      "rel": "alternate",
      "type": "application/vnd.ogc.fg+json",
      "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
      "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items?f=jsonfg"
    },
    {
      "rel": "alternate",
      "type": "application/ld+json",
      "title": "The Linked Data JSON representation of the resources served from this OGC API Implementation Endpoint",
      "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items?f=jsonld"
    },
    {
      "rel": "alternate",
      "type": "text/html",
      "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
      "href": "http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items"
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
      "actedOnBehalfOf": "null",
      "qualifiedDelegation": "null"
    },
    {
      "provType": "Agent",
      "name": "agents:%3COrganisation%3E",
      "agentType": "organization",
      "actedOnBehalfOf": "null",
      "qualifiedDelegation": "null"
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
      "wasInformedBy": "null",
      "used": [
        "terranexusJobs:MapDataToZones_cae879d1d789"
      ],
      "endedAtTime": "2024-01-18T05:23:24.700855+00:00",
      "generated": [
        "terranexusJobs:MapDataToZones_cae879d1d789",
        "terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9"
      ]
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
      "wasInformedBy": [
        "terranexusProcesses:execution/MapDataToZones"
      ],
      "used": [
        "terranexusJobs:MapDataToZones_cae879d1d789"
      ],
      "endedAtTime": "2024-01-18T05:32:32.888834+00:00",
      "generated": "null"
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
      "wasInformedBy": [
        "terranexusProcesses:execution/MapDataToZones",
        "dggsOperations:map_data"
      ],
      "used": [
        "terranexusJobs:MapDataToZones_cae879d1d789"
      ],
      "endedAtTime": "2024-01-18T05:32:32.752525+00:00",
      "generated": "null"
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
      "wasInformedBy": [
        "terranexusProcesses:execution/MapDataToZones",
        "dggsOperations:map_data",
        "dggsOperations:map_data_execution"
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
      "wasDerivedFrom": "null"
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
      "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
      "entityType": "DGGS",
      "hadPrimarySource": [
        "agents:TerraNexus"
      ],
      "generatedAtTime": "2024-01-18T05:23:22.485613+00:00",
      "wasGeneratedBy": "null",
      "wasDerivedFrom": "null"
    }
  ],
  "@context": [
    "https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/json-fg-feature-collection_with-prov/context.jsonld",
    "https://ogcincubator.github.io/bblock-prov-schema/build/annotated/ogc-utils/prov/context.jsonld",
    "https://opengeospatial.github.io/bblocks/annotated-schemas/geo/json-fg/featureCollection/context.jsonld",
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
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/terranexus/dggs/api/json-fg-feature-collection_with-prov/example_1_1.jsonld">Open in new window</a>
    <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Ftests%2Fterranexus%2Fdggs%2Fapi%2Fjson-fg-feature-collection_with-prov%2Fexample_1_1.jsonld">View on JSON-LD Playground</a>
</blockquote>




```turtle
@prefix agents: <http://192.168.39.167:30560/prov/agents/> .
@prefix dct: <http://purl.org/dc/terms/> .
@prefix dggsOperations: <http://192.168.39.167:30560/prov/dggsOperations/> .
@prefix geojson: <https://purl.org/geojson/vocab#> .
@prefix ns1: <http://www.iana.org/assignments/> .
@prefix ns2: <addr:> .
@prefix oa: <http://www.w3.org/ns/oa#> .
@prefix prov: <http://www.w3.org/ns/prov#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix roles: <http://192.168.39.167:30560/prov/roles/> .
@prefix terranexusCollections: <http://192.168.39.167:30560/ogcapi/collections/> .
@prefix terranexusDGGS: <http://192.168.39.167:30560/ogcapi/dggs/> .
@prefix terranexusJobs: <http://192.168.39.167:30560/ogcapi/jobs/> .
@prefix terranexusTempData: <http://192.168.39.167:30560/prov/tempData/> .
@prefix time: <http://www.w3.org/2006/time#> .
@prefix xsd: <http://www.w3.org/2001/XMLSchema#> .

<file:///github/workspace/osm_singapore_buildings> a geojson:FeatureCollection ;
    dct:provenance [ a prov:Agent,
                prov:Person ;
            rdfs:label "agents:admin%40terranexus.pangaeainnovations.com" ;
            prov:actedOnBehalfOf <http://192.168.39.167:30560/prov/agents/%3COrganisation%3E> ;
            prov:qualifiedDelegation roles:User ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:%3COrganisation%3E" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:MapDataToZones_cae879d1d789" ;
            prov:actedOnBehalfOf agents:TerraNexus ;
            prov:qualifiedDelegation <file:///github/workspace/ogcapiProcess> ],
        terranexusCollections:osm_singapore_buildings,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_cae879d1d789,
        <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9 ;
    rdfs:seeAlso [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items?f=jsonfg> ],
        [ rdfs:label "The JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items?f=json> ],
        [ rdfs:label "The Linked Data JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items?f=jsonld> ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items?f=geojson> ],
        [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items> ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:features <file:///github/workspace/2305843009229499373>,
        <file:///github/workspace/2305843009231960349>,
        <file:///github/workspace/2305843009231960466>,
        <file:///github/workspace/2305843009231960589>,
        <file:///github/workspace/2305843009231960619>,
        <file:///github/workspace/2305843009231960767>,
        <file:///github/workspace/2305843009231960798>,
        <file:///github/workspace/2305843009231960865>,
        <file:///github/workspace/2305843009232899975>,
        <file:///github/workspace/2305843009232900002>,
        <file:///github/workspace/2305843009232901459>,
        <file:///github/workspace/2305843009232901461>,
        <file:///github/workspace/2305843009232901565>,
        <file:///github/workspace/2305843009233038522>,
        <file:///github/workspace/2305843009233494536> .

<file:///github/workspace/2305843009229499373> a geojson:Feature ;
    rdfs:label "null" ;
    ns2:city "null" ;
    ns2:place "null" ;
    dct:provenance [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        [ a prov:Agent,
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
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        terranexusCollections:osm_singapore_buildings,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373>,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_cae879d1d789,
        <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:map_featureData_task-2305843009229499373,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009229499373,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9 ;
    dct:spatial [ a <file:///github/workspace/null> ] ;
    dct:time [ time:hasTime "2024-01-18T05:23:25.507396+00:00"^^xsd:dateTime ] ;
    rdfs:seeAlso [ rdfs:label "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=jsonld> ],
        [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=jsonfg> ],
        [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373> ],
        [ rdfs:label "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings?f=json> ],
        [ rdfs:label "The HTML representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget terranexusCollections:osm_singapore_buildings ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=geojson> ],
        [ rdfs:label "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=json> ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( ( ( 1.015578e+02 3.054745e+00 ) ( 1.015581e+02 3.055361e+00 ) ( 1.015579e+02 3.055433e+00 ) ( 1.015576e+02 3.054817e+00 ) ( 1.015578e+02 3.054745e+00 ) ) ) ] .

<file:///github/workspace/2305843009231960349> a geojson:Feature ;
    rdfs:label "null" ;
    ns2:city "null" ;
    ns2:place "null" ;
    dct:provenance [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:%3COrganisation%3E" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:MapDataToZones_cae879d1d789" ;
            prov:actedOnBehalfOf agents:TerraNexus ;
            prov:qualifiedDelegation <file:///github/workspace/ogcapiProcess> ],
        [ a prov:Agent,
                prov:Person ;
            rdfs:label "agents:admin%40terranexus.pangaeainnovations.com" ;
            prov:actedOnBehalfOf <http://192.168.39.167:30560/prov/agents/%3COrganisation%3E> ;
            prov:qualifiedDelegation roles:User ],
        terranexusCollections:osm_singapore_buildings,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349>,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_cae879d1d789,
        <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:map_featureData_task-2305843009231960349,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009231960349,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9 ;
    dct:spatial [ a <file:///github/workspace/null> ] ;
    dct:time [ time:hasTime "2024-01-18T05:23:41.381234+00:00"^^xsd:dateTime ] ;
    rdfs:seeAlso [ rdfs:label "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=jsonld> ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=geojson> ],
        [ rdfs:label "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings?f=json> ],
        [ rdfs:label "The HTML representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget terranexusCollections:osm_singapore_buildings ],
        [ rdfs:label "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=json> ],
        [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=jsonfg> ],
        [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349> ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( ( ( 1.015583e+02 3.055355e+00 ) ( 1.01558e+02 3.054689e+00 ) ( 1.015582e+02 3.054614e+00 ) ( 1.015584e+02 3.055293e+00 ) ( 1.015583e+02 3.055355e+00 ) ) ) ] .

<file:///github/workspace/2305843009231960466> a geojson:Feature ;
    rdfs:label "null" ;
    ns2:city "null" ;
    ns2:place "null" ;
    dct:provenance [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:%3COrganisation%3E" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:MapDataToZones_cae879d1d789" ;
            prov:actedOnBehalfOf agents:TerraNexus ;
            prov:qualifiedDelegation <file:///github/workspace/ogcapiProcess> ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        [ a prov:Agent,
                prov:Person ;
            rdfs:label "agents:admin%40terranexus.pangaeainnovations.com" ;
            prov:actedOnBehalfOf <http://192.168.39.167:30560/prov/agents/%3COrganisation%3E> ;
            prov:qualifiedDelegation roles:User ],
        terranexusCollections:osm_singapore_buildings,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466>,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_cae879d1d789,
        <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:map_featureData_task-2305843009231960466,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009231960466,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9 ;
    dct:spatial [ a <file:///github/workspace/null> ] ;
    dct:time [ time:hasTime "2024-01-18T05:23:57.834082+00:00"^^xsd:dateTime ] ;
    rdfs:seeAlso [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466> ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466?f=geojson> ],
        [ rdfs:label "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466?f=json> ],
        [ rdfs:label "The HTML representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget terranexusCollections:osm_singapore_buildings ],
        [ rdfs:label "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466?f=jsonld> ],
        [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466?f=jsonfg> ],
        [ rdfs:label "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings?f=json> ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( ( ( 1.015585e+02 3.05452e+00 ) ( 1.015587e+02 3.055186e+00 ) ( 1.015585e+02 3.055265e+00 ) ( 1.015583e+02 3.054599e+00 ) ( 1.015585e+02 3.05452e+00 ) ) ) ] .

<file:///github/workspace/2305843009231960589> a geojson:Feature ;
    rdfs:label "null" ;
    ns2:city "null" ;
    ns2:place "null" ;
    dct:provenance [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:%3COrganisation%3E" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a prov:Agent,
                prov:Person ;
            rdfs:label "agents:admin%40terranexus.pangaeainnovations.com" ;
            prov:actedOnBehalfOf <http://192.168.39.167:30560/prov/agents/%3COrganisation%3E> ;
            prov:qualifiedDelegation roles:User ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:MapDataToZones_cae879d1d789" ;
            prov:actedOnBehalfOf agents:TerraNexus ;
            prov:qualifiedDelegation <file:///github/workspace/ogcapiProcess> ],
        terranexusCollections:osm_singapore_buildings,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589>,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_cae879d1d789,
        <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:map_featureData_task-2305843009231960589,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009231960589,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9 ;
    dct:spatial [ a <file:///github/workspace/null> ] ;
    dct:time [ time:hasTime "2024-01-18T05:24:15.553951+00:00"^^xsd:dateTime ] ;
    rdfs:seeAlso [ rdfs:label "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589?f=json> ],
        [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589> ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589?f=geojson> ],
        [ rdfs:label "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings?f=json> ],
        [ rdfs:label "The HTML representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget terranexusCollections:osm_singapore_buildings ],
        [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589?f=jsonfg> ],
        [ rdfs:label "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589?f=jsonld> ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( ( ( 1.015579e+02 3.053789e+00 ) ( 1.015581e+02 3.053723e+00 ) ( 1.015583e+02 3.054199e+00 ) ( 1.015584e+02 3.054476e+00 ) ( 1.015582e+02 3.054542e+00 ) ( 1.015581e+02 3.054199e+00 ) ( 1.015579e+02 3.053789e+00 ) ) ) ] .

<file:///github/workspace/2305843009231960619> a geojson:Feature ;
    rdfs:label "null" ;
    ns2:city "null" ;
    ns2:place "null" ;
    dct:provenance [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        [ a prov:Agent,
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
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        terranexusCollections:osm_singapore_buildings,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619>,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_cae879d1d789,
        <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:map_featureData_task-2305843009231960619,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009231960619,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9 ;
    dct:spatial [ a <file:///github/workspace/null> ] ;
    dct:time [ time:hasTime "2024-01-18T05:24:39.057589+00:00"^^xsd:dateTime ] ;
    rdfs:seeAlso [ rdfs:label "The HTML representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget terranexusCollections:osm_singapore_buildings ],
        [ rdfs:label "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619?f=jsonld> ],
        [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619?f=jsonfg> ],
        [ rdfs:label "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings?f=json> ],
        [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619> ],
        [ rdfs:label "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619?f=json> ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619?f=geojson> ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( ( ( 1.015577e+02 3.053875e+00 ) ( 1.015579e+02 3.053809e+00 ) ( 1.01558e+02 3.054199e+00 ) ( 1.015582e+02 3.054565e+00 ) ( 1.01558e+02 3.05463e+00 ) ( 1.015578e+02 3.054199e+00 ) ( 1.015577e+02 3.053875e+00 ) ) ) ] .

<file:///github/workspace/2305843009231960767> a geojson:Feature ;
    rdfs:label "null" ;
    ns2:city "null" ;
    ns2:place "null" ;
    dct:provenance [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:%3COrganisation%3E" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:MapDataToZones_cae879d1d789" ;
            prov:actedOnBehalfOf agents:TerraNexus ;
            prov:qualifiedDelegation <file:///github/workspace/ogcapiProcess> ],
        [ a prov:Agent,
                prov:Person ;
            rdfs:label "agents:admin%40terranexus.pangaeainnovations.com" ;
            prov:actedOnBehalfOf <http://192.168.39.167:30560/prov/agents/%3COrganisation%3E> ;
            prov:qualifiedDelegation roles:User ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
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
    dct:spatial [ a <file:///github/workspace/null> ] ;
    dct:time [ time:hasTime "2024-01-18T05:25:05.050331+00:00"^^xsd:dateTime ] ;
    rdfs:seeAlso [ rdfs:label "The HTML representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget terranexusCollections:osm_singapore_buildings ],
        [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767?f=jsonfg> ],
        [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767> ],
        [ rdfs:label "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767?f=jsonld> ],
        [ rdfs:label "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings?f=json> ],
        [ rdfs:label "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767?f=json> ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767?f=geojson> ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( ( ( 1.015588e+02 3.054457e+00 ) ( 1.015591e+02 3.055059e+00 ) ( 1.015589e+02 3.055133e+00 ) ( 1.015586e+02 3.05453e+00 ) ( 1.015588e+02 3.054457e+00 ) ) ) ] .

<file:///github/workspace/2305843009231960798> a geojson:Feature ;
    rdfs:label "null" ;
    ns2:city "null" ;
    ns2:place "null" ;
    dct:provenance [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:%3COrganisation%3E" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:MapDataToZones_cae879d1d789" ;
            prov:actedOnBehalfOf agents:TerraNexus ;
            prov:qualifiedDelegation <file:///github/workspace/ogcapiProcess> ],
        [ a prov:Agent,
                prov:Person ;
            rdfs:label "agents:admin%40terranexus.pangaeainnovations.com" ;
            prov:actedOnBehalfOf <http://192.168.39.167:30560/prov/agents/%3COrganisation%3E> ;
            prov:qualifiedDelegation roles:User ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        terranexusCollections:osm_singapore_buildings,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798>,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_cae879d1d789,
        <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:map_featureData_task-2305843009231960798,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009231960798,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9 ;
    dct:spatial [ a <file:///github/workspace/null> ] ;
    dct:time [ time:hasTime "2024-01-18T05:25:28.478210+00:00"^^xsd:dateTime ] ;
    rdfs:seeAlso [ rdfs:label "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798?f=json> ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798?f=geojson> ],
        [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798?f=jsonfg> ],
        [ rdfs:label "The HTML representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget terranexusCollections:osm_singapore_buildings ],
        [ rdfs:label "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798?f=jsonld> ],
        [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798> ],
        [ rdfs:label "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings?f=json> ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( ( ( 1.015584e+02 3.054149e+00 ) ( 1.015587e+02 3.054077e+00 ) ( 1.015587e+02 3.054199e+00 ) ( 1.015588e+02 3.054344e+00 ) ( 1.015586e+02 3.054417e+00 ) ( 1.015585e+02 3.054199e+00 ) ( 1.015584e+02 3.054149e+00 ) ) ) ] .

<file:///github/workspace/2305843009231960865> a geojson:Feature ;
    rdfs:label "null" ;
    ns2:city "null" ;
    ns2:place "null" ;
    dct:provenance [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:%3COrganisation%3E" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a prov:Agent,
                prov:Person ;
            rdfs:label "agents:admin%40terranexus.pangaeainnovations.com" ;
            prov:actedOnBehalfOf <http://192.168.39.167:30560/prov/agents/%3COrganisation%3E> ;
            prov:qualifiedDelegation roles:User ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:MapDataToZones_cae879d1d789" ;
            prov:actedOnBehalfOf agents:TerraNexus ;
            prov:qualifiedDelegation <file:///github/workspace/ogcapiProcess> ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        terranexusCollections:osm_singapore_buildings,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865>,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_cae879d1d789,
        <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:map_featureData_task-2305843009231960865,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009231960865,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9 ;
    dct:spatial [ a <file:///github/workspace/null> ] ;
    dct:time [ time:hasTime "2024-01-18T05:25:59.542518+00:00"^^xsd:dateTime ] ;
    rdfs:seeAlso [ rdfs:label "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865?f=jsonld> ],
        [ rdfs:label "The HTML representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget terranexusCollections:osm_singapore_buildings ],
        [ rdfs:label "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865?f=json> ],
        [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865> ],
        [ rdfs:label "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings?f=json> ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865?f=geojson> ],
        [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865?f=jsonfg> ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( ( ( 1.015588e+02 3.054199e+00 ) ( 1.015587e+02 3.05405e+00 ) ( 1.01559e+02 3.053948e+00 ) ( 1.015591e+02 3.054199e+00 ) ( 1.015594e+02 3.054893e+00 ) ( 1.015591e+02 3.054996e+00 ) ( 1.015588e+02 3.054199e+00 ) ) ) ] .

<file:///github/workspace/2305843009232899975> a geojson:Feature ;
    rdfs:label "Giant" ;
    ns2:city "null" ;
    ns2:place "null" ;
    dct:provenance [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:MapDataToZones_cae879d1d789" ;
            prov:actedOnBehalfOf agents:TerraNexus ;
            prov:qualifiedDelegation <file:///github/workspace/ogcapiProcess> ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:%3COrganisation%3E" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        [ a prov:Agent,
                prov:Person ;
            rdfs:label "agents:admin%40terranexus.pangaeainnovations.com" ;
            prov:actedOnBehalfOf <http://192.168.39.167:30560/prov/agents/%3COrganisation%3E> ;
            prov:qualifiedDelegation roles:User ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        terranexusCollections:osm_singapore_buildings,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975>,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_cae879d1d789,
        <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:map_featureData_task-2305843009232899975,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009232899975,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9 ;
    dct:spatial [ a <file:///github/workspace/null> ] ;
    dct:time [ time:hasTime "2024-01-18T05:26:25.820867+00:00"^^xsd:dateTime ] ;
    rdfs:seeAlso [ rdfs:label "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975?f=jsonld> ],
        [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975> ],
        [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975?f=jsonfg> ],
        [ rdfs:label "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings?f=json> ],
        [ rdfs:label "The HTML representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget terranexusCollections:osm_singapore_buildings ],
        [ rdfs:label "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975?f=json> ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975?f=geojson> ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( ( ( 1.015171e+02 3.044054e+00 ) ( 1.01517e+02 3.044447e+00 ) ( 1.015166e+02 3.044333e+00 ) ( 1.015167e+02 3.04394e+00 ) ( 1.015171e+02 3.044054e+00 ) ) ) ] .

<file:///github/workspace/2305843009232900002> a geojson:Feature ;
    rdfs:label "Mydin" ;
    ns2:city "null" ;
    ns2:place "null" ;
    dct:provenance [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:MapDataToZones_cae879d1d789" ;
            prov:actedOnBehalfOf agents:TerraNexus ;
            prov:qualifiedDelegation <file:///github/workspace/ogcapiProcess> ],
        [ a prov:Agent,
                prov:Person ;
            rdfs:label "agents:admin%40terranexus.pangaeainnovations.com" ;
            prov:actedOnBehalfOf <http://192.168.39.167:30560/prov/agents/%3COrganisation%3E> ;
            prov:qualifiedDelegation roles:User ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:%3COrganisation%3E" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        terranexusCollections:osm_singapore_buildings,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002>,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_cae879d1d789,
        <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:map_featureData_task-2305843009232900002,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009232900002,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9 ;
    dct:spatial [ a <file:///github/workspace/null> ] ;
    dct:time [ time:hasTime "2024-01-18T05:26:50.531820+00:00"^^xsd:dateTime ] ;
    rdfs:seeAlso [ rdfs:label "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002?f=jsonld> ],
        [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002> ],
        [ rdfs:label "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings?f=json> ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002?f=geojson> ],
        [ rdfs:label "The HTML representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget terranexusCollections:osm_singapore_buildings ],
        [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002?f=jsonfg> ],
        [ rdfs:label "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002?f=json> ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( ( ( 1.015158e+02 3.045123e+00 ) ( 1.01516e+02 3.045371e+00 ) ( 1.015158e+02 3.045483e+00 ) ( 1.015156e+02 3.045175e+00 ) ( 1.015156e+02 3.044952e+00 ) ( 1.015157e+02 3.044693e+00 ) ( 1.015158e+02 3.044712e+00 ) ( 1.015159e+02 3.044749e+00 ) ( 1.015158e+02 3.045123e+00 ) ) ) ] .

<file:///github/workspace/2305843009232901459> a geojson:Feature ;
    rdfs:label "Tesco Extra" ;
    ns2:city "Shah Alam" ;
    ns2:place "Section 13" ;
    dct:provenance [ a prov:Agent,
                prov:Person ;
            rdfs:label "agents:admin%40terranexus.pangaeainnovations.com" ;
            prov:actedOnBehalfOf <http://192.168.39.167:30560/prov/agents/%3COrganisation%3E> ;
            prov:qualifiedDelegation roles:User ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:%3COrganisation%3E" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:MapDataToZones_cae879d1d789" ;
            prov:actedOnBehalfOf agents:TerraNexus ;
            prov:qualifiedDelegation <file:///github/workspace/ogcapiProcess> ],
        terranexusCollections:osm_singapore_buildings,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901459>,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_cae879d1d789,
        <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:map_featureData_task-2305843009232901459,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009232901459,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9 ;
    dct:spatial [ a <file:///github/workspace/null> ] ;
    dct:time [ time:hasTime "2024-01-18T05:27:20.169756+00:00"^^xsd:dateTime ] ;
    rdfs:seeAlso [ rdfs:label "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings?f=json> ],
        [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901459> ],
        [ rdfs:label "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901459?f=json> ],
        [ rdfs:label "The HTML representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget terranexusCollections:osm_singapore_buildings ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901459?f=geojson> ],
        [ rdfs:label "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901459?f=jsonld> ],
        [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901459?f=jsonfg> ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( ( ( 1.015499e+02 3.077465e+00 ) ( 1.0155e+02 3.077029e+00 ) ( 1.015502e+02 3.076512e+00 ) ( 1.015515e+02 3.076844e+00 ) ( 1.015512e+02 3.077812e+00 ) ( 1.015499e+02 3.077465e+00 ) ) ) ] .

<file:///github/workspace/2305843009232901461> a geojson:Feature ;
    rdfs:label "Stadium Malawati" ;
    ns2:city "null" ;
    ns2:place "null" ;
    dct:provenance [ a prov:Agent,
                prov:Person ;
            rdfs:label "agents:admin%40terranexus.pangaeainnovations.com" ;
            prov:actedOnBehalfOf <http://192.168.39.167:30560/prov/agents/%3COrganisation%3E> ;
            prov:qualifiedDelegation roles:User ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:MapDataToZones_cae879d1d789" ;
            prov:actedOnBehalfOf agents:TerraNexus ;
            prov:qualifiedDelegation <file:///github/workspace/ogcapiProcess> ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:%3COrganisation%3E" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        terranexusCollections:osm_singapore_buildings,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901461>,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_cae879d1d789,
        <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:map_featureData_task-2305843009232901461,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009232901461,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9 ;
    dct:spatial [ a <file:///github/workspace/null> ] ;
    dct:time [ time:hasTime "2024-01-18T05:27:56.109661+00:00"^^xsd:dateTime ] ;
    rdfs:seeAlso [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901461> ],
        [ rdfs:label "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901461?f=jsonld> ],
        [ rdfs:label "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901461?f=json> ],
        [ rdfs:label "The HTML representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget terranexusCollections:osm_singapore_buildings ],
        [ rdfs:label "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings?f=json> ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901461?f=geojson> ],
        [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901461?f=jsonfg> ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( ( ( 1.015474e+02 3.079544e+00 ) ( 1.015477e+02 3.079833e+00 ) ( 1.015477e+02 3.080309e+00 ) ( 1.015474e+02 3.08061e+00 ) ( 1.01547e+02 3.08063e+00 ) ( 1.015466e+02 3.08028e+00 ) ( 1.015466e+02 3.079895e+00 ) ( 1.01547e+02 3.079548e+00 ) ( 1.015474e+02 3.079544e+00 ) ) ) ] .

<file:///github/workspace/2305843009232901565> a geojson:Feature ;
    rdfs:label "Pusat Akuatik Darul Ehsan" ;
    ns2:city "null" ;
    ns2:place "null" ;
    dct:provenance [ a prov:Agent,
                prov:Person ;
            rdfs:label "agents:admin%40terranexus.pangaeainnovations.com" ;
            prov:actedOnBehalfOf <http://192.168.39.167:30560/prov/agents/%3COrganisation%3E> ;
            prov:qualifiedDelegation roles:User ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:%3COrganisation%3E" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:MapDataToZones_cae879d1d789" ;
            prov:actedOnBehalfOf agents:TerraNexus ;
            prov:qualifiedDelegation <file:///github/workspace/ogcapiProcess> ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        terranexusCollections:osm_singapore_buildings,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901565>,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_cae879d1d789,
        <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:map_featureData_task-2305843009232901565,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009232901565,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9 ;
    dct:spatial [ a <file:///github/workspace/null> ] ;
    dct:time [ time:hasTime "2024-01-18T05:28:38.783226+00:00"^^xsd:dateTime ] ;
    rdfs:seeAlso [ rdfs:label "The HTML representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget terranexusCollections:osm_singapore_buildings ],
        [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901565?f=jsonfg> ],
        [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901565> ],
        [ rdfs:label "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901565?f=json> ],
        [ rdfs:label "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901565?f=jsonld> ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901565?f=geojson> ],
        [ rdfs:label "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings?f=json> ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( ( ( 1.015365e+02 3.073472e+00 ) ( 1.015365e+02 3.073425e+00 ) ( 1.015365e+02 3.073415e+00 ) ( 1.015372e+02 3.073418e+00 ) ( 1.015372e+02 3.073425e+00 ) ( 1.015372e+02 3.07438e+00 ) ( 1.01537e+02 3.074381e+00 ) ( 1.01537e+02 3.074656e+00 ) ( 1.015367e+02 3.074655e+00 ) ( 1.015365e+02 3.074382e+00 ) ( 1.015365e+02 3.074256e+00 ) ( 1.015362e+02 3.074259e+00 ) ( 1.015362e+02 3.074155e+00 ) ( 1.015362e+02 3.073965e+00 ) ( 1.01536e+02 3.073937e+00 ) ( 1.01536e+02 3.073853e+00 ) ( 1.01536e+02 3.073742e+00 ) ( 1.01536e+02 3.073635e+00 ) ( 1.015363e+02 3.073474e+00 ) ( 1.015365e+02 3.073472e+00 ) ) ) ] .

<file:///github/workspace/2305843009233038522> a geojson:Feature ;
    rdfs:label "Sime Darby Medical Hospital Subang Jaya" ;
    ns2:city "null" ;
    ns2:place "null" ;
    dct:provenance [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:MapDataToZones_cae879d1d789" ;
            prov:actedOnBehalfOf agents:TerraNexus ;
            prov:qualifiedDelegation <file:///github/workspace/ogcapiProcess> ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        [ a prov:Agent,
                prov:Person ;
            rdfs:label "agents:admin%40terranexus.pangaeainnovations.com" ;
            prov:actedOnBehalfOf <http://192.168.39.167:30560/prov/agents/%3COrganisation%3E> ;
            prov:qualifiedDelegation roles:User ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:%3COrganisation%3E" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        terranexusCollections:osm_singapore_buildings,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233038522>,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_cae879d1d789,
        <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:map_featureData_task-2305843009233038522,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009233038522,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9 ;
    dct:spatial [ a <file:///github/workspace/null> ] ;
    dct:time [ time:hasTime "2024-01-18T05:29:59.992287+00:00"^^xsd:dateTime ] ;
    rdfs:seeAlso [ rdfs:label "The HTML representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget terranexusCollections:osm_singapore_buildings ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233038522?f=geojson> ],
        [ rdfs:label "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233038522?f=json> ],
        [ rdfs:label "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233038522?f=jsonld> ],
        [ rdfs:label "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings?f=json> ],
        [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233038522?f=jsonfg> ],
        [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233038522> ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( ( ( 1.015934e+02 3.077835e+00 ) ( 1.015939e+02 3.077835e+00 ) ( 1.015939e+02 3.078662e+00 ) ( 1.015934e+02 3.078662e+00 ) ( 1.015934e+02 3.077835e+00 ) ) ) ] .

<file:///github/workspace/2305843009233494536> a geojson:Feature ;
    rdfs:label "Tesco" ;
    ns2:city "null" ;
    ns2:place "null" ;
    dct:provenance [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:%3COrganisation%3E" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        [ a prov:Agent,
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
            rdfs:label "agents:PangaeaInnovations" ;
            prov:actedOnBehalfOf <file:///github/workspace/null> ;
            prov:qualifiedDelegation <file:///github/workspace/null> ],
        terranexusCollections:osm_singapore_buildings,
        <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233494536>,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_cae879d1d789,
        <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:map_featureData_task-2305843009233494536,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009233494536,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9 ;
    dct:spatial [ a <file:///github/workspace/null> ] ;
    dct:time [ time:hasTime "2024-01-18T05:31:22.172753+00:00"^^xsd:dateTime ] ;
    rdfs:seeAlso [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233494536?f=geojson> ],
        [ rdfs:label "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233494536?f=json> ],
        [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233494536?f=jsonfg> ],
        [ rdfs:label "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233494536?f=jsonld> ],
        [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233494536> ],
        [ rdfs:label "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings?f=json> ],
        [ rdfs:label "The HTML representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget terranexusCollections:osm_singapore_buildings ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( ( ( 1.015379e+02 3.072065e+00 ) ( 1.015384e+02 3.071484e+00 ) ( 1.015386e+02 3.071235e+00 ) ( 1.015388e+02 3.071223e+00 ) ( 1.015394e+02 3.071816e+00 ) ( 1.015386e+02 3.07274e+00 ) ( 1.015384e+02 3.072512e+00 ) ( 1.015382e+02 3.072303e+00 ) ( 1.015379e+02 3.072065e+00 ) ) ) ] .

dggsOperations:map_featureData_task-2305843009231960349 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:23:57.807022+00:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:23:42.120315+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009231960349 .

dggsOperations:map_featureData_task-2305843009231960466 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:24:15.523878+00:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:23:58.134275+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009231960466 .

dggsOperations:map_featureData_task-2305843009231960589 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:24:39.010138+00:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:24:16.109523+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009231960589 .

dggsOperations:map_featureData_task-2305843009231960619 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:25:05.015295+00:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:24:39.449608+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009231960619 .

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

dggsOperations:map_featureData_task-2305843009231960798 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:25:59.513697+00:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:25:28.765830+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009231960798 .

dggsOperations:map_featureData_task-2305843009231960865 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:26:25.791311+00:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:25:59.882233+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009231960865 .

dggsOperations:map_featureData_task-2305843009232899975 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:26:50.496862+00:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:26:26.115242+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009232899975 .

dggsOperations:map_featureData_task-2305843009232900002 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:27:20.122235+00:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:26:50.744858+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009232900002 .

dggsOperations:map_featureData_task-2305843009232901459 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:27:56.040859+00:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:27:20.429685+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009232901459 .

dggsOperations:map_featureData_task-2305843009232901461 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:28:38.749898+00:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:27:56.535404+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009232901461 .

dggsOperations:map_featureData_task-2305843009232901565 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:29:59.930166+00:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:28:39.093872+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009232901565 .

dggsOperations:map_featureData_task-2305843009233038522 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:31:22.112248+00:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:30:00.750806+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009233038522 .

dggsOperations:map_featureData_task-2305843009233494536 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:32:32.644262+00:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:31:22.519324+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009233494536 .

dggsOperations:map_featureData_task-2305843009229499373 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:23:41.340327+00:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:23:26.493850+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009229499373 .

dggsOperations:reorganiseData_task-2305843009229499373 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:23:26.385690+00:00"^^xsd:dateTime ;
    prov:generated <file:///github/workspace/null> ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:23:26.077610+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task .

dggsOperations:reorganiseData_task-2305843009231960349 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:23:41.969677+00:00"^^xsd:dateTime ;
    prov:generated <file:///github/workspace/null> ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:23:41.708387+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task .

dggsOperations:reorganiseData_task-2305843009231960466 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:23:58.034751+00:00"^^xsd:dateTime ;
    prov:generated <file:///github/workspace/null> ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:23:57.943043+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task .

dggsOperations:reorganiseData_task-2305843009231960589 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:24:15.882453+00:00"^^xsd:dateTime ;
    prov:generated <file:///github/workspace/null> ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:24:15.745664+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task .

dggsOperations:reorganiseData_task-2305843009231960619 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:24:39.307410+00:00"^^xsd:dateTime ;
    prov:generated <file:///github/workspace/null> ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:24:39.221754+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task .

dggsOperations:reorganiseData_task-2305843009231960767 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:25:05.226533+00:00"^^xsd:dateTime ;
    prov:generated <file:///github/workspace/null> ;
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

dggsOperations:reorganiseData_task-2305843009231960798 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:25:28.676283+00:00"^^xsd:dateTime ;
    prov:generated <file:///github/workspace/null> ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:25:28.624522+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task .

dggsOperations:reorganiseData_task-2305843009231960865 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:25:59.783035+00:00"^^xsd:dateTime ;
    prov:generated <file:///github/workspace/null> ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:25:59.715125+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task .

dggsOperations:reorganiseData_task-2305843009232899975 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:26:25.997827+00:00"^^xsd:dateTime ;
    prov:generated <file:///github/workspace/null> ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:26:25.925281+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task .

dggsOperations:reorganiseData_task-2305843009232900002 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:26:50.678018+00:00"^^xsd:dateTime ;
    prov:generated <file:///github/workspace/null> ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:26:50.630396+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task .

dggsOperations:reorganiseData_task-2305843009232901459 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:27:20.349755+00:00"^^xsd:dateTime ;
    prov:generated <file:///github/workspace/null> ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:27:20.294670+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task .

dggsOperations:reorganiseData_task-2305843009232901461 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:27:56.452169+00:00"^^xsd:dateTime ;
    prov:generated <file:///github/workspace/null> ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:27:56.373833+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task .

dggsOperations:reorganiseData_task-2305843009232901565 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:28:39.005025+00:00"^^xsd:dateTime ;
    prov:generated <file:///github/workspace/null> ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:28:38.881281+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task .

dggsOperations:reorganiseData_task-2305843009233038522 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:30:00.413889+00:00"^^xsd:dateTime ;
    prov:generated <file:///github/workspace/null> ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:30:00.242274+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task .

dggsOperations:reorganiseData_task-2305843009233494536 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:31:22.431125+00:00"^^xsd:dateTime ;
    prov:generated <file:///github/workspace/null> ;
    prov:qualifiedAssociation agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-01-18T05:31:22.345165+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasAssociatedWith agents:MapDataToZones_cae879d1d789,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task .

<http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2024-01-18T05:23:25.507396+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

<http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2024-01-18T05:23:41.381234+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

<http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2024-01-18T05:23:57.834082+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

<http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2024-01-18T05:24:15.553951+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

<http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2024-01-18T05:24:39.057589+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

<http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2024-01-18T05:25:05.050331+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

<http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2024-01-18T05:25:28.478210+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

<http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2024-01-18T05:25:59.542518+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

<http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2024-01-18T05:26:25.820867+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

<http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2024-01-18T05:26:50.531820+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

<http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901459> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2024-01-18T05:27:20.169756+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

<http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901461> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2024-01-18T05:27:56.109661+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

<http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009232901565> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2024-01-18T05:28:38.783226+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

<http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233038522> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2024-01-18T05:29:59.992287+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

<http://192.168.39.167:30560/ogcapi/collections/osm_singapore_buildings/items/2305843009233494536> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2024-01-18T05:31:22.172753+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

<file:///github/workspace/ogcapiProcess> a prov:Delegation ;
    prov:agent agents:TerraNexus ;
    prov:hadActivity <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones> .

terranexusCollections:osm_singapore_buildings___Properties a <file:///github/workspace/FeatureCollectionProperties>,
        prov:Entity ;
    prov:generatedAtTime "2024-01-18T05:23:25.444245+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.gnosis.earth/ogcapi/collections/osm:singapore:buildings/items?limit=15&f=json> ;
    prov:wasDerivedFrom terranexusJobs:MapDataToZones_cae879d1d789,
        terranexusTempData:osm_singapore_buildings__b9b766419fa051bf99d2808a7ff55ae9.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

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
    prov:wasDerivedFrom <file:///github/workspace/null> ;
    prov:wasGeneratedBy <file:///github/workspace/null> .

terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 a <file:///github/workspace/FeatureCollectionDGGSZones>,
        prov:Entity ;
    prov:generatedAtTime "2024-01-18T05:23:27.310511+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource terranexusCollections:osm_singapore_buildings,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_cae879d1d789 ;
    prov:wasGeneratedBy dggsOperations:map_featureData_task-2305843009229499373 .

dggsOperations:map_data_execution a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-01-18T05:32:32.752525+00:00"^^xsd:dateTime ;
    prov:generated <file:///github/workspace/null> ;
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
    prov:generated <file:///github/workspace/null> ;
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
    prov:wasInformedBy <file:///github/workspace/null> .

agents:MapDataToZones_cae879d1d789 a prov:Association ;
    prov:agent agents:MapDataToZones_cae879d1d789 ;
    prov:hadRole roles:ogcapiProcessJob .

terranexusJobs:MapDataToZones_cae879d1d789 a <file:///github/workspace/ogcapiProcessJob>,
        prov:Entity ;
    prov:generatedAtTime "2024-01-18T05:23:24.651036+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasDerivedFrom <file:///github/workspace/null> ;
    prov:wasGeneratedBy <http://192.168.39.167:30560/ogcapi/processes/execution/MapDataToZones> .

agents:admin%40terranexus.pangaeainnovations.com a prov:Association ;
    prov:agent agents:admin%40terranexus.pangaeainnovations.com ;
    prov:hadRole roles:User .

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

agents:TerraNexus a prov:Association ;
    prov:agent agents:TerraNexus ;
    prov:hadRole roles:Software .


```

<blockquote class="lang-specific turtle">
  <p class="example-links">
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/terranexus/dggs/api/json-fg-feature-collection_with-prov/example_1_1.ttl">Open in new window</a>
</blockquote>


Terranexus derived Feature Collection with provenance


# JSON Schema

```yaml--schema
$schema: https://json-schema.org/draft/2020-12/schema
description: CWL Provenance Chain for DGGS actions
allOf:
- $ref: https://ogcincubator.github.io/bblock-prov-schema/build/annotated/ogc-utils/prov/schema.yaml
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

> <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=yaml&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Fannotated%2Fterranexus%2Fdggs%2Fapi%2Fjson-fg-feature-collection_with-prov%2Fschema.yaml&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on YAML Viewer</a>

Links to the schema:

* YAML version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/json-fg-feature-collection_with-prov/schema.yaml" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/json-fg-feature-collection_with-prov/schema.yaml</a>
* JSON version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/json-fg-feature-collection_with-prov/schema.json" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/json-fg-feature-collection_with-prov/schema.json</a>


# JSON-LD Context

```json--ldContext
{
  "@context": {
    "id": "@id",
    "featureType": "geojson:collectionFeatureType",
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
    "prov": "http://www.w3.org/ns/prov#",
    "xsd": "http://www.w3.org/2001/XMLSchema#",
    "rdfs": "http://www.w3.org/2000/01/rdf-schema#",
    "dct": "http://purl.org/dc/terms/",
    "rdf": "http://www.w3.org/1999/02/22-rdf-syntax-ns#",
    "oa": "http://www.w3.org/ns/oa#",
    "geojson": "https://purl.org/geojson/vocab#",
    "owlTime": "http://www.w3.org/2006/time#",
    "@version": 1.1
  }
}
```

> <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Fannotated%2Fterranexus%2Fdggs%2Fapi%2Fjson-fg-feature-collection_with-prov%2Fcontext.jsonld">View on JSON-LD Playground</a>

You can find the full JSON-LD context here:
<a href="https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/json-fg-feature-collection_with-prov/context.jsonld" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/json-fg-feature-collection_with-prov/context.jsonld</a>

# References

* [Sample source document](https://example.com/sources/1)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: <a href="https://github.com/geofizzydrink/test_bblock" target="_blank">https://github.com/geofizzydrink/test_bblock</a>
* Path:
<code><a href="https://github.com/geofizzydrink/test_bblock/blob/HEAD/_sources/json-fg-feature-collection_with-prov" target="_blank">_sources/json-fg-feature-collection_with-prov</a></code>

