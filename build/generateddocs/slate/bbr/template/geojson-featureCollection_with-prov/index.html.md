---
title: OGC API Features Feature Collection with PROV Building Block (Schema)

language_tabs:
  - json: JSON
  - jsonld: JSON-LD
  - turtle: RDF/Turtle

toc_footers:
  - Version 0.1
  - <a href='#'>OGC API Features Feature Collection with PROV Building Block</a>
  - <a href='https://blocks.ogc.org/register.html'>Building Blocks register</a>

search: true

code_clipboard: true

meta:
  - name: OGC API Features Feature Collection with PROV Building Block (Schema)
---


# OGC API Features Feature Collection with PROV Building Block `ogc.bbr.template.geojson-featureCollection_with-prov`

This Building Block serves as a template to combine an OGC API Features Feature Object with a Provenance Chain

<p class="status">
    <span data-rainbow-uri="http://www.opengis.net/def/status">Status</span>:
    <a href="http://www.opengis.net/def/status/under-development" target="_blank" data-rainbow-uri>Under development</a>
</p>

<aside class="success">
This building block is <strong><a href="https://github.com/geofizzydrink/test_bblock/blob/master/build/tests/bbr/template/geojson-featureCollection_with-prov/" target="_blank">valid</a></strong>
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
    "id": "osm_singapore_buildings",
    "type": "FeatureCollection",
    "numberReturned": 2,
    "numberMatched": 2,
    "features": [
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
                "feature::id": 2305843009231960349,
                "created_by": "Potlatch 0.6",
                "landuse": "residential",
                "building": "yes",
                "id": "2305843009231960349",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1722494293.623151,
                "x_max": NaN,
                "x_min": NaN,
                "y_max": NaN,
                "y_min": NaN,
                "z_max": NaN,
                "z_min": NaN,
                "dggsZones": {
                    "TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2": {
                        "0": [
                            "T"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349"
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
                    "name": "agents:MapDataToZones_47fbab073054",
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
                    "agentType": "organization"
                },
                {
                    "provType": "Agent",
                    "name": "agents:%3COrganisation%3E",
                    "agentType": "organization"
                },
                {
                    "provType": "Activity",
                    "id": "terranexusProcesses:execution/MapDataToZones",
                    "activityType": "ogcapiProcess",
                    "startedAtTime": "2024-08-01T06:36:14.966889+00:00",
                    "wasAssociatedWith": [
                        "agents:TerraNexus",
                        "agents:MapDataToZones_47fbab073054",
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
                            "id": "agents:MapDataToZones_47fbab073054",
                            "type": "Association",
                            "agent": "agents:MapDataToZones_47fbab073054",
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
                        "terranexusJobs:MapDataToZones_47fbab073054"
                    ],
                    "endedAtTime": "2024-08-01T06:36:19.266405+00:00",
                    "generated": [
                        "terranexusJobs:MapDataToZones_47fbab073054",
                        "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605"
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_data",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-08-01T06:36:19.306985+00:00",
                    "wasAssociatedWith": [
                        "agents:TerraNexus",
                        "agents:MapDataToZones_47fbab073054",
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
                            "id": "agents:MapDataToZones_47fbab073054",
                            "type": "Association",
                            "agent": "agents:MapDataToZones_47fbab073054",
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
                        "terranexusJobs:MapDataToZones_47fbab073054"
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_data_execution",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-08-01T06:36:20.113007+00:00",
                    "wasAssociatedWith": [
                        "agents:TerraNexus",
                        "agents:MapDataToZones_47fbab073054",
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
                            "id": "agents:MapDataToZones_47fbab073054",
                            "type": "Association",
                            "agent": "agents:MapDataToZones_47fbab073054",
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
                        "terranexusJobs:MapDataToZones_47fbab073054"
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:processData_task",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-08-01T06:36:21.653215+00:00",
                    "wasAssociatedWith": [
                        "agents:TerraNexus",
                        "agents:MapDataToZones_47fbab073054",
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
                            "id": "agents:MapDataToZones_47fbab073054",
                            "type": "Association",
                            "agent": "agents:MapDataToZones_47fbab073054",
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
                        "terranexusJobs:MapDataToZones_47fbab073054",
                        "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json"
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:reorganiseData_task-2305843009231960349-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-08-01T06:38:14.249362+00:00",
                    "wasAssociatedWith": [
                        "agents:TerraNexus",
                        "agents:MapDataToZones_47fbab073054",
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
                            "id": "agents:MapDataToZones_47fbab073054",
                            "type": "Association",
                            "agent": "agents:MapDataToZones_47fbab073054",
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
                        "terranexusJobs:MapDataToZones_47fbab073054"
                    ],
                    "endedAtTime": "2024-08-01T06:38:14.382261+00:00"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009231960349-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-08-01T06:38:14.748519+00:00",
                    "wasAssociatedWith": [
                        "agents:TerraNexus",
                        "agents:MapDataToZones_47fbab073054",
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
                            "id": "agents:MapDataToZones_47fbab073054",
                            "type": "Association",
                            "agent": "agents:MapDataToZones_47fbab073054",
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
                        "terranexusJobs:MapDataToZones_47fbab073054"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings",
                    "entityType": "FeatureCollection",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
                    ],
                    "generatedAtTime": "2024-08-01T06:36:23.016609+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_47fbab073054",
                        "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusJobs:MapDataToZones_47fbab073054",
                    "entityType": "ogcapiProcessJob",
                    "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
                    "hadPrimarySource": [
                        "agents:admin%40terranexus.pangaeainnovations.com"
                    ],
                    "generatedAtTime": "2024-08-01T06:36:19.115272+00:00"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605",
                    "entityType": "rawData",
                    "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
                    ],
                    "generatedAtTime": "2024-08-01T06:36:19.145246+00:00",
                    "wasDerivedFrom": "terranexusJobs:MapDataToZones_47fbab073054"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings___Properties",
                    "entityType": "FeatureCollectionProperties",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
                    ],
                    "generatedAtTime": "2024-08-01T06:36:24.173862+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_47fbab073054",
                        "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json"
                    ]
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
                    "generatedAtTime": "2024-08-01T06:36:28.014547+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_47fbab073054",
                        "terranexusCollections:osm_singapore_buildings",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960349",
                    "entityType": "Feature",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
                    ],
                    "generatedAtTime": "2024-08-01T06:38:13.428950+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_47fbab073054",
                        "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json",
                        "terranexusCollections:osm_singapore_buildings"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
                    "entityType": "DGGS",
                    "wasGeneratedBy": "agents:TerraNexus",
                    "hadPrimarySource": [
                        "agents:TerraNexus"
                    ],
                    "generatedAtTime": "2024-07-30T20:54:30.425150+00:00"
                }
            ],
            "time": {
                "timestamp": "2024-08-01T06:38:13.428950+00:00"
            },
            "place": {
                "type": "null"
            }
        },
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
                "feature::id": 2305843009229499373,
                "created_by": "Potlatch 0.6",
                "landuse": "residential",
                "building": "yes",
                "id": "2305843009229499373",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1722494185.352338,
                "x_max": -1276078.7650104035,
                "x_min": -1276125.1697413276,
                "y_max": 6239991.512113506,
                "y_min": 6239978.749965917,
                "z_max": 337695.36020748876,
                "z_min": 337619.4573208119,
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
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373"
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
                    "name": "agents:MapDataToZones_47fbab073054",
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
                    "agentType": "organization"
                },
                {
                    "provType": "Agent",
                    "name": "agents:%3COrganisation%3E",
                    "agentType": "organization"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:reorganiseData_task-2305843009229499373-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-08-01T06:36:25.624668+00:00",
                    "wasAssociatedWith": [
                        "agents:TerraNexus",
                        "agents:MapDataToZones_47fbab073054",
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
                            "id": "agents:MapDataToZones_47fbab073054",
                            "type": "Association",
                            "agent": "agents:MapDataToZones_47fbab073054",
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
                        "terranexusJobs:MapDataToZones_47fbab073054"
                    ],
                    "endedAtTime": "2024-08-01T06:36:25.776828+00:00"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009229499373-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-08-01T06:36:26.142218+00:00",
                    "wasAssociatedWith": [
                        "agents:TerraNexus",
                        "agents:MapDataToZones_47fbab073054",
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
                            "id": "agents:MapDataToZones_47fbab073054",
                            "type": "Association",
                            "agent": "agents:MapDataToZones_47fbab073054",
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
                        "terranexusJobs:MapDataToZones_47fbab073054"
                    ],
                    "endedAtTime": "2024-08-01T06:38:13.351488+00:00",
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "terranexusProcesses:execution/MapDataToZones",
                    "activityType": "ogcapiProcess",
                    "startedAtTime": "2024-08-01T06:36:14.966889+00:00",
                    "wasAssociatedWith": [
                        "agents:TerraNexus",
                        "agents:MapDataToZones_47fbab073054",
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
                            "id": "agents:MapDataToZones_47fbab073054",
                            "type": "Association",
                            "agent": "agents:MapDataToZones_47fbab073054",
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
                        "terranexusJobs:MapDataToZones_47fbab073054"
                    ],
                    "endedAtTime": "2024-08-01T06:36:19.266405+00:00",
                    "generated": [
                        "terranexusJobs:MapDataToZones_47fbab073054",
                        "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605"
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_data",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-08-01T06:36:19.306985+00:00",
                    "wasAssociatedWith": [
                        "agents:TerraNexus",
                        "agents:MapDataToZones_47fbab073054",
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
                            "id": "agents:MapDataToZones_47fbab073054",
                            "type": "Association",
                            "agent": "agents:MapDataToZones_47fbab073054",
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
                        "terranexusJobs:MapDataToZones_47fbab073054"
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_data_execution",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-08-01T06:36:20.113007+00:00",
                    "wasAssociatedWith": [
                        "agents:TerraNexus",
                        "agents:MapDataToZones_47fbab073054",
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
                            "id": "agents:MapDataToZones_47fbab073054",
                            "type": "Association",
                            "agent": "agents:MapDataToZones_47fbab073054",
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
                        "terranexusJobs:MapDataToZones_47fbab073054"
                    ]
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:processData_task",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-08-01T06:36:21.653215+00:00",
                    "wasAssociatedWith": [
                        "agents:TerraNexus",
                        "agents:MapDataToZones_47fbab073054",
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
                            "id": "agents:MapDataToZones_47fbab073054",
                            "type": "Association",
                            "agent": "agents:MapDataToZones_47fbab073054",
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
                        "terranexusJobs:MapDataToZones_47fbab073054",
                        "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings",
                    "entityType": "FeatureCollection",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
                    ],
                    "generatedAtTime": "2024-08-01T06:36:23.016609+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_47fbab073054",
                        "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusJobs:MapDataToZones_47fbab073054",
                    "entityType": "ogcapiProcessJob",
                    "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
                    "hadPrimarySource": [
                        "agents:admin%40terranexus.pangaeainnovations.com"
                    ],
                    "generatedAtTime": "2024-08-01T06:36:19.115272+00:00"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605",
                    "entityType": "rawData",
                    "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
                    ],
                    "generatedAtTime": "2024-08-01T06:36:19.145246+00:00",
                    "wasDerivedFrom": "terranexusJobs:MapDataToZones_47fbab073054"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings___Properties",
                    "entityType": "FeatureCollectionProperties",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
                    ],
                    "generatedAtTime": "2024-08-01T06:36:24.173862+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_47fbab073054",
                        "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009229499373",
                    "entityType": "Feature",
                    "wasGeneratedBy": "dggsOperations:processData_task",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
                    ],
                    "generatedAtTime": "2024-08-01T06:36:24.345926+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_47fbab073054",
                        "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json",
                        "terranexusCollections:osm_singapore_buildings"
                    ]
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
                    "generatedAtTime": "2024-08-01T06:36:28.014547+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_47fbab073054",
                        "terranexusCollections:osm_singapore_buildings",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
                    "entityType": "DGGS",
                    "wasGeneratedBy": "agents:TerraNexus",
                    "hadPrimarySource": [
                        "agents:TerraNexus"
                    ],
                    "generatedAtTime": "2024-07-30T20:54:30.425150+00:00"
                }
            ],
            "time": {
                "timestamp": "2024-08-01T06:36:24.345926+00:00"
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
            "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items?f=json"
        },
        {
            "rel": "alternate",
            "type": "application/geo+json",
            "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
            "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items?f=geojson"
        },
        {
            "rel": "alternate",
            "type": "application/vnd.ogc.fg+json",
            "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
            "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items?f=jsonfg"
        },
        {
            "rel": "alternate",
            "type": "application/ld+json",
            "title": "The Linked Data JSON representation of the resources served from this OGC API Implementation Endpoint",
            "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items?f=jsonld"
        },
        {
            "rel": "alternate",
            "type": "text/html",
            "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
            "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items"
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
            "name": "agents:MapDataToZones_47fbab073054",
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
            "agentType": "organization"
        },
        {
            "provType": "Agent",
            "name": "agents:%3COrganisation%3E",
            "agentType": "organization"
        },
        {
            "provType": "Activity",
            "id": "terranexusProcesses:execution/MapDataToZones",
            "activityType": "ogcapiProcess",
            "startedAtTime": "2024-08-01T06:36:14.966889+00:00",
            "wasAssociatedWith": [
                "agents:TerraNexus",
                "agents:MapDataToZones_47fbab073054",
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
                    "id": "agents:MapDataToZones_47fbab073054",
                    "type": "Association",
                    "agent": "agents:MapDataToZones_47fbab073054",
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
                "terranexusJobs:MapDataToZones_47fbab073054"
            ],
            "endedAtTime": "2024-08-01T06:36:19.266405+00:00",
            "generated": [
                "terranexusJobs:MapDataToZones_47fbab073054",
                "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605"
            ]
        },
        {
            "provType": "Activity",
            "id": "dggsOperations:map_data",
            "activityType": "dggsOperation",
            "startedAtTime": "2024-08-01T06:36:19.306985+00:00",
            "wasAssociatedWith": [
                "agents:TerraNexus",
                "agents:MapDataToZones_47fbab073054",
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
                    "id": "agents:MapDataToZones_47fbab073054",
                    "type": "Association",
                    "agent": "agents:MapDataToZones_47fbab073054",
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
                "terranexusJobs:MapDataToZones_47fbab073054"
            ]
        },
        {
            "provType": "Activity",
            "id": "dggsOperations:map_data_execution",
            "activityType": "dggsOperation",
            "startedAtTime": "2024-08-01T06:36:20.113007+00:00",
            "wasAssociatedWith": [
                "agents:TerraNexus",
                "agents:MapDataToZones_47fbab073054",
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
                    "id": "agents:MapDataToZones_47fbab073054",
                    "type": "Association",
                    "agent": "agents:MapDataToZones_47fbab073054",
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
                "terranexusJobs:MapDataToZones_47fbab073054"
            ]
        },
        {
            "provType": "Activity",
            "id": "dggsOperations:processData_task",
            "activityType": "dggsOperation",
            "startedAtTime": "2024-08-01T06:36:21.653215+00:00",
            "wasAssociatedWith": [
                "agents:TerraNexus",
                "agents:MapDataToZones_47fbab073054",
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
                    "id": "agents:MapDataToZones_47fbab073054",
                    "type": "Association",
                    "agent": "agents:MapDataToZones_47fbab073054",
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
                "terranexusJobs:MapDataToZones_47fbab073054",
                "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json"
            ]
        },
        {
            "provType": "Entity",
            "id": "terranexusCollections:osm_singapore_buildings",
            "entityType": "FeatureCollection",
            "wasGeneratedBy": "dggsOperations:processData_task",
            "hadPrimarySource": [
                "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
            ],
            "generatedAtTime": "2024-08-01T06:36:23.016609+00:00",
            "wasDerivedFrom": [
                "terranexusJobs:MapDataToZones_47fbab073054",
                "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json"
            ]
        },
        {
            "provType": "Entity",
            "id": "terranexusJobs:MapDataToZones_47fbab073054",
            "entityType": "ogcapiProcessJob",
            "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
            "hadPrimarySource": [
                "agents:admin%40terranexus.pangaeainnovations.com"
            ],
            "generatedAtTime": "2024-08-01T06:36:19.115272+00:00"
        },
        {
            "provType": "Entity",
            "id": "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605",
            "entityType": "rawData",
            "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
            "hadPrimarySource": [
                "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
            ],
            "generatedAtTime": "2024-08-01T06:36:19.145246+00:00",
            "wasDerivedFrom": "terranexusJobs:MapDataToZones_47fbab073054"
        },
        {
            "provType": "Entity",
            "id": "terranexusCollections:osm_singapore_buildings___Properties",
            "entityType": "FeatureCollectionProperties",
            "wasGeneratedBy": "dggsOperations:processData_task",
            "hadPrimarySource": [
                "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
            ],
            "generatedAtTime": "2024-08-01T06:36:24.173862+00:00",
            "wasDerivedFrom": [
                "terranexusJobs:MapDataToZones_47fbab073054",
                "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json"
            ]
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
            "generatedAtTime": "2024-08-01T06:36:28.014547+00:00",
            "wasDerivedFrom": [
                "terranexusJobs:MapDataToZones_47fbab073054",
                "terranexusCollections:osm_singapore_buildings",
                "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
            ]
        },
        {
            "provType": "Entity",
            "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
            "entityType": "DGGS",
            "wasGeneratedBy": "agents:TerraNexus",
            "hadPrimarySource": [
                "agents:TerraNexus"
            ],
            "generatedAtTime": "2024-07-30T20:54:30.425150+00:00"
        }
    ],
    "@context": [
        "https://ogcincubator.github.io/bblock-prov-schema/build/annotated/ogc-utils/prov/context.jsonld",
        "https://opengeospatial.github.io/bblocks/annotated-schemas/geo/json-fg/featureCollection/context.jsonld",
        {
            "base_href": "https://terranexus.pangaeainnovations.com/",
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
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/bbr/template/geojson-featureCollection_with-prov/example_2_1.json">Open in new window</a>
    <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=json&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Ftests%2Fbbr%2Ftemplate%2Fgeojson-featureCollection_with-prov%2Fexample_2_1.json&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on JSON Viewer</a></p>
</blockquote>




```jsonld
{
  "id": "osm_singapore_buildings",
  "type": "FeatureCollection",
  "numberReturned": 2,
  "numberMatched": 2,
  "features": [
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
        "feature::id": 2305843009231960349,
        "created_by": "Potlatch 0.6",
        "landuse": "residential",
        "building": "yes",
        "id": "2305843009231960349",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1722494293.623151,
        "x_max": "NaN",
        "x_min": "NaN",
        "y_max": "NaN",
        "y_min": "NaN",
        "z_max": "NaN",
        "z_min": "NaN",
        "dggsZones": {
          "TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2": {
            "0": [
              "T"
            ]
          }
        }
      },
      "links": [
        {
          "rel": "self",
          "type": "application/geo+json",
          "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=json"
        },
        {
          "rel": "alternate",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=geojson"
        },
        {
          "rel": "alternate",
          "type": "application/vnd.ogc.fg+json",
          "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=jsonfg"
        },
        {
          "rel": "alternate",
          "type": "application/ld+json",
          "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=jsonld"
        },
        {
          "rel": "alternate",
          "type": "text/html",
          "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349"
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
          "name": "agents:MapDataToZones_47fbab073054",
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
          "agentType": "organization"
        },
        {
          "provType": "Agent",
          "name": "agents:%3COrganisation%3E",
          "agentType": "organization"
        },
        {
          "provType": "Activity",
          "id": "terranexusProcesses:execution/MapDataToZones",
          "activityType": "ogcapiProcess",
          "startedAtTime": "2024-08-01T06:36:14.966889+00:00",
          "wasAssociatedWith": [
            "agents:TerraNexus",
            "agents:MapDataToZones_47fbab073054",
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
              "id": "agents:MapDataToZones_47fbab073054",
              "type": "Association",
              "agent": "agents:MapDataToZones_47fbab073054",
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
            "terranexusJobs:MapDataToZones_47fbab073054"
          ],
          "endedAtTime": "2024-08-01T06:36:19.266405+00:00",
          "generated": [
            "terranexusJobs:MapDataToZones_47fbab073054",
            "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605"
          ]
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_data",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-08-01T06:36:19.306985+00:00",
          "wasAssociatedWith": [
            "agents:TerraNexus",
            "agents:MapDataToZones_47fbab073054",
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
              "id": "agents:MapDataToZones_47fbab073054",
              "type": "Association",
              "agent": "agents:MapDataToZones_47fbab073054",
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
            "terranexusJobs:MapDataToZones_47fbab073054"
          ]
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_data_execution",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-08-01T06:36:20.113007+00:00",
          "wasAssociatedWith": [
            "agents:TerraNexus",
            "agents:MapDataToZones_47fbab073054",
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
              "id": "agents:MapDataToZones_47fbab073054",
              "type": "Association",
              "agent": "agents:MapDataToZones_47fbab073054",
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
            "terranexusJobs:MapDataToZones_47fbab073054"
          ]
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:processData_task",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-08-01T06:36:21.653215+00:00",
          "wasAssociatedWith": [
            "agents:TerraNexus",
            "agents:MapDataToZones_47fbab073054",
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
              "id": "agents:MapDataToZones_47fbab073054",
              "type": "Association",
              "agent": "agents:MapDataToZones_47fbab073054",
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
            "terranexusJobs:MapDataToZones_47fbab073054",
            "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json"
          ]
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:reorganiseData_task-2305843009231960349-Polygon_0",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-08-01T06:38:14.249362+00:00",
          "wasAssociatedWith": [
            "agents:TerraNexus",
            "agents:MapDataToZones_47fbab073054",
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
              "id": "agents:MapDataToZones_47fbab073054",
              "type": "Association",
              "agent": "agents:MapDataToZones_47fbab073054",
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
            "terranexusJobs:MapDataToZones_47fbab073054"
          ],
          "endedAtTime": "2024-08-01T06:38:14.382261+00:00"
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_featureData_task-2305843009231960349-Polygon_0",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-08-01T06:38:14.748519+00:00",
          "wasAssociatedWith": [
            "agents:TerraNexus",
            "agents:MapDataToZones_47fbab073054",
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
              "id": "agents:MapDataToZones_47fbab073054",
              "type": "Association",
              "agent": "agents:MapDataToZones_47fbab073054",
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
            "terranexusJobs:MapDataToZones_47fbab073054"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings",
          "entityType": "FeatureCollection",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
          ],
          "generatedAtTime": "2024-08-01T06:36:23.016609+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_47fbab073054",
            "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusJobs:MapDataToZones_47fbab073054",
          "entityType": "ogcapiProcessJob",
          "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
          "hadPrimarySource": [
            "agents:admin%40terranexus.pangaeainnovations.com"
          ],
          "generatedAtTime": "2024-08-01T06:36:19.115272+00:00"
        },
        {
          "provType": "Entity",
          "id": "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605",
          "entityType": "rawData",
          "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
          "hadPrimarySource": [
            "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
          ],
          "generatedAtTime": "2024-08-01T06:36:19.145246+00:00",
          "wasDerivedFrom": "terranexusJobs:MapDataToZones_47fbab073054"
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings___Properties",
          "entityType": "FeatureCollectionProperties",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
          ],
          "generatedAtTime": "2024-08-01T06:36:24.173862+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_47fbab073054",
            "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json"
          ]
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
          "generatedAtTime": "2024-08-01T06:36:28.014547+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_47fbab073054",
            "terranexusCollections:osm_singapore_buildings",
            "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960349",
          "entityType": "Feature",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
          ],
          "generatedAtTime": "2024-08-01T06:38:13.428950+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_47fbab073054",
            "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json",
            "terranexusCollections:osm_singapore_buildings"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
          "entityType": "DGGS",
          "wasGeneratedBy": "agents:TerraNexus",
          "hadPrimarySource": [
            "agents:TerraNexus"
          ],
          "generatedAtTime": "2024-07-30T20:54:30.425150+00:00"
        }
      ],
      "time": {
        "timestamp": "2024-08-01T06:38:13.428950+00:00"
      },
      "place": {
        "type": "null"
      }
    },
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
        "feature::id": 2305843009229499373,
        "created_by": "Potlatch 0.6",
        "landuse": "residential",
        "building": "yes",
        "id": "2305843009229499373",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1722494185.352338,
        "x_max": -1276078.7650104035,
        "x_min": -1276125.1697413276,
        "y_max": 6239991.512113506,
        "y_min": 6239978.749965917,
        "z_max": 337695.36020748876,
        "z_min": 337619.4573208119,
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
            ]
          }
        }
      },
      "links": [
        {
          "rel": "self",
          "type": "application/geo+json",
          "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=json"
        },
        {
          "rel": "alternate",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=geojson"
        },
        {
          "rel": "alternate",
          "type": "application/vnd.ogc.fg+json",
          "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=jsonfg"
        },
        {
          "rel": "alternate",
          "type": "application/ld+json",
          "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=jsonld"
        },
        {
          "rel": "alternate",
          "type": "text/html",
          "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373"
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
          "name": "agents:MapDataToZones_47fbab073054",
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
          "agentType": "organization"
        },
        {
          "provType": "Agent",
          "name": "agents:%3COrganisation%3E",
          "agentType": "organization"
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:reorganiseData_task-2305843009229499373-Polygon_0",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-08-01T06:36:25.624668+00:00",
          "wasAssociatedWith": [
            "agents:TerraNexus",
            "agents:MapDataToZones_47fbab073054",
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
              "id": "agents:MapDataToZones_47fbab073054",
              "type": "Association",
              "agent": "agents:MapDataToZones_47fbab073054",
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
            "terranexusJobs:MapDataToZones_47fbab073054"
          ],
          "endedAtTime": "2024-08-01T06:36:25.776828+00:00"
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_featureData_task-2305843009229499373-Polygon_0",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-08-01T06:36:26.142218+00:00",
          "wasAssociatedWith": [
            "agents:TerraNexus",
            "agents:MapDataToZones_47fbab073054",
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
              "id": "agents:MapDataToZones_47fbab073054",
              "type": "Association",
              "agent": "agents:MapDataToZones_47fbab073054",
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
            "terranexusJobs:MapDataToZones_47fbab073054"
          ],
          "endedAtTime": "2024-08-01T06:38:13.351488+00:00",
          "generated": [
            "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ]
        },
        {
          "provType": "Activity",
          "id": "terranexusProcesses:execution/MapDataToZones",
          "activityType": "ogcapiProcess",
          "startedAtTime": "2024-08-01T06:36:14.966889+00:00",
          "wasAssociatedWith": [
            "agents:TerraNexus",
            "agents:MapDataToZones_47fbab073054",
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
              "id": "agents:MapDataToZones_47fbab073054",
              "type": "Association",
              "agent": "agents:MapDataToZones_47fbab073054",
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
            "terranexusJobs:MapDataToZones_47fbab073054"
          ],
          "endedAtTime": "2024-08-01T06:36:19.266405+00:00",
          "generated": [
            "terranexusJobs:MapDataToZones_47fbab073054",
            "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605"
          ]
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_data",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-08-01T06:36:19.306985+00:00",
          "wasAssociatedWith": [
            "agents:TerraNexus",
            "agents:MapDataToZones_47fbab073054",
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
              "id": "agents:MapDataToZones_47fbab073054",
              "type": "Association",
              "agent": "agents:MapDataToZones_47fbab073054",
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
            "terranexusJobs:MapDataToZones_47fbab073054"
          ]
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:map_data_execution",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-08-01T06:36:20.113007+00:00",
          "wasAssociatedWith": [
            "agents:TerraNexus",
            "agents:MapDataToZones_47fbab073054",
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
              "id": "agents:MapDataToZones_47fbab073054",
              "type": "Association",
              "agent": "agents:MapDataToZones_47fbab073054",
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
            "terranexusJobs:MapDataToZones_47fbab073054"
          ]
        },
        {
          "provType": "Activity",
          "id": "dggsOperations:processData_task",
          "activityType": "dggsOperation",
          "startedAtTime": "2024-08-01T06:36:21.653215+00:00",
          "wasAssociatedWith": [
            "agents:TerraNexus",
            "agents:MapDataToZones_47fbab073054",
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
              "id": "agents:MapDataToZones_47fbab073054",
              "type": "Association",
              "agent": "agents:MapDataToZones_47fbab073054",
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
            "terranexusJobs:MapDataToZones_47fbab073054",
            "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings",
          "entityType": "FeatureCollection",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
          ],
          "generatedAtTime": "2024-08-01T06:36:23.016609+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_47fbab073054",
            "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusJobs:MapDataToZones_47fbab073054",
          "entityType": "ogcapiProcessJob",
          "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
          "hadPrimarySource": [
            "agents:admin%40terranexus.pangaeainnovations.com"
          ],
          "generatedAtTime": "2024-08-01T06:36:19.115272+00:00"
        },
        {
          "provType": "Entity",
          "id": "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605",
          "entityType": "rawData",
          "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
          "hadPrimarySource": [
            "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
          ],
          "generatedAtTime": "2024-08-01T06:36:19.145246+00:00",
          "wasDerivedFrom": "terranexusJobs:MapDataToZones_47fbab073054"
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings___Properties",
          "entityType": "FeatureCollectionProperties",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
          ],
          "generatedAtTime": "2024-08-01T06:36:24.173862+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_47fbab073054",
            "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusCollections:osm_singapore_buildings/items/2305843009229499373",
          "entityType": "Feature",
          "wasGeneratedBy": "dggsOperations:processData_task",
          "hadPrimarySource": [
            "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
          ],
          "generatedAtTime": "2024-08-01T06:36:24.345926+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_47fbab073054",
            "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json",
            "terranexusCollections:osm_singapore_buildings"
          ]
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
          "generatedAtTime": "2024-08-01T06:36:28.014547+00:00",
          "wasDerivedFrom": [
            "terranexusJobs:MapDataToZones_47fbab073054",
            "terranexusCollections:osm_singapore_buildings",
            "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
          ]
        },
        {
          "provType": "Entity",
          "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
          "entityType": "DGGS",
          "wasGeneratedBy": "agents:TerraNexus",
          "hadPrimarySource": [
            "agents:TerraNexus"
          ],
          "generatedAtTime": "2024-07-30T20:54:30.425150+00:00"
        }
      ],
      "time": {
        "timestamp": "2024-08-01T06:36:24.345926+00:00"
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
      "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items?f=json"
    },
    {
      "rel": "alternate",
      "type": "application/geo+json",
      "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
      "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items?f=geojson"
    },
    {
      "rel": "alternate",
      "type": "application/vnd.ogc.fg+json",
      "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
      "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items?f=jsonfg"
    },
    {
      "rel": "alternate",
      "type": "application/ld+json",
      "title": "The Linked Data JSON representation of the resources served from this OGC API Implementation Endpoint",
      "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items?f=jsonld"
    },
    {
      "rel": "alternate",
      "type": "text/html",
      "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
      "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items"
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
      "name": "agents:MapDataToZones_47fbab073054",
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
      "agentType": "organization"
    },
    {
      "provType": "Agent",
      "name": "agents:%3COrganisation%3E",
      "agentType": "organization"
    },
    {
      "provType": "Activity",
      "id": "terranexusProcesses:execution/MapDataToZones",
      "activityType": "ogcapiProcess",
      "startedAtTime": "2024-08-01T06:36:14.966889+00:00",
      "wasAssociatedWith": [
        "agents:TerraNexus",
        "agents:MapDataToZones_47fbab073054",
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
          "id": "agents:MapDataToZones_47fbab073054",
          "type": "Association",
          "agent": "agents:MapDataToZones_47fbab073054",
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
        "terranexusJobs:MapDataToZones_47fbab073054"
      ],
      "endedAtTime": "2024-08-01T06:36:19.266405+00:00",
      "generated": [
        "terranexusJobs:MapDataToZones_47fbab073054",
        "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605"
      ]
    },
    {
      "provType": "Activity",
      "id": "dggsOperations:map_data",
      "activityType": "dggsOperation",
      "startedAtTime": "2024-08-01T06:36:19.306985+00:00",
      "wasAssociatedWith": [
        "agents:TerraNexus",
        "agents:MapDataToZones_47fbab073054",
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
          "id": "agents:MapDataToZones_47fbab073054",
          "type": "Association",
          "agent": "agents:MapDataToZones_47fbab073054",
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
        "terranexusJobs:MapDataToZones_47fbab073054"
      ]
    },
    {
      "provType": "Activity",
      "id": "dggsOperations:map_data_execution",
      "activityType": "dggsOperation",
      "startedAtTime": "2024-08-01T06:36:20.113007+00:00",
      "wasAssociatedWith": [
        "agents:TerraNexus",
        "agents:MapDataToZones_47fbab073054",
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
          "id": "agents:MapDataToZones_47fbab073054",
          "type": "Association",
          "agent": "agents:MapDataToZones_47fbab073054",
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
        "terranexusJobs:MapDataToZones_47fbab073054"
      ]
    },
    {
      "provType": "Activity",
      "id": "dggsOperations:processData_task",
      "activityType": "dggsOperation",
      "startedAtTime": "2024-08-01T06:36:21.653215+00:00",
      "wasAssociatedWith": [
        "agents:TerraNexus",
        "agents:MapDataToZones_47fbab073054",
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
          "id": "agents:MapDataToZones_47fbab073054",
          "type": "Association",
          "agent": "agents:MapDataToZones_47fbab073054",
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
        "terranexusJobs:MapDataToZones_47fbab073054",
        "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json"
      ]
    },
    {
      "provType": "Entity",
      "id": "terranexusCollections:osm_singapore_buildings",
      "entityType": "FeatureCollection",
      "wasGeneratedBy": "dggsOperations:processData_task",
      "hadPrimarySource": [
        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
      ],
      "generatedAtTime": "2024-08-01T06:36:23.016609+00:00",
      "wasDerivedFrom": [
        "terranexusJobs:MapDataToZones_47fbab073054",
        "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json"
      ]
    },
    {
      "provType": "Entity",
      "id": "terranexusJobs:MapDataToZones_47fbab073054",
      "entityType": "ogcapiProcessJob",
      "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
      "hadPrimarySource": [
        "agents:admin%40terranexus.pangaeainnovations.com"
      ],
      "generatedAtTime": "2024-08-01T06:36:19.115272+00:00"
    },
    {
      "provType": "Entity",
      "id": "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605",
      "entityType": "rawData",
      "wasGeneratedBy": "terranexusProcesses:execution/MapDataToZones",
      "hadPrimarySource": [
        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
      ],
      "generatedAtTime": "2024-08-01T06:36:19.145246+00:00",
      "wasDerivedFrom": "terranexusJobs:MapDataToZones_47fbab073054"
    },
    {
      "provType": "Entity",
      "id": "terranexusCollections:osm_singapore_buildings___Properties",
      "entityType": "FeatureCollectionProperties",
      "wasGeneratedBy": "dggsOperations:processData_task",
      "hadPrimarySource": [
        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5"
      ],
      "generatedAtTime": "2024-08-01T06:36:24.173862+00:00",
      "wasDerivedFrom": [
        "terranexusJobs:MapDataToZones_47fbab073054",
        "terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json"
      ]
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
      "generatedAtTime": "2024-08-01T06:36:28.014547+00:00",
      "wasDerivedFrom": [
        "terranexusJobs:MapDataToZones_47fbab073054",
        "terranexusCollections:osm_singapore_buildings",
        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
      ]
    },
    {
      "provType": "Entity",
      "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
      "entityType": "DGGS",
      "wasGeneratedBy": "agents:TerraNexus",
      "hadPrimarySource": [
        "agents:TerraNexus"
      ],
      "generatedAtTime": "2024-07-30T20:54:30.425150+00:00"
    }
  ],
  "@context": [
    "https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/geojson-featureCollection_with-prov/context.jsonld",
    "https://ogcincubator.github.io/bblock-prov-schema/build/annotated/ogc-utils/prov/context.jsonld",
    "https://opengeospatial.github.io/bblocks/annotated-schemas/geo/json-fg/featureCollection/context.jsonld",
    {
      "base_href": "https://terranexus.pangaeainnovations.com/",
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
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/bbr/template/geojson-featureCollection_with-prov/example_2_1.jsonld">Open in new window</a>
    <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Ftests%2Fbbr%2Ftemplate%2Fgeojson-featureCollection_with-prov%2Fexample_2_1.jsonld">View on JSON-LD Playground</a>
</blockquote>




```turtle
@prefix agents: <https://terranexus.pangaeainnovations.com/prov/agents/> .
@prefix dct: <http://purl.org/dc/terms/> .
@prefix dggsOperations: <https://terranexus.pangaeainnovations.com/prov/dggsOperations/> .
@prefix geojson: <https://purl.org/geojson/vocab#> .
@prefix ns1: <http://www.iana.org/assignments/> .
@prefix ns2: <feature::> .
@prefix oa: <http://www.w3.org/ns/oa#> .
@prefix prov: <http://www.w3.org/ns/prov#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix roles: <https://terranexus.pangaeainnovations.com/prov/roles/> .
@prefix terranexusCollections: <https://terranexus.pangaeainnovations.com/ogcapi/collections/> .
@prefix terranexusDGGS: <https://terranexus.pangaeainnovations.com/ogcapi/dggs/> .
@prefix terranexusJobs: <https://terranexus.pangaeainnovations.com/ogcapi/jobs/> .
@prefix terranexusTempData: <https://terranexus.pangaeainnovations.com/prov/tempData/> .
@prefix time: <http://www.w3.org/2006/time#> .
@prefix xsd: <http://www.w3.org/2001/XMLSchema#> .

<file:///github/workspace/osm_singapore_buildings> a geojson:FeatureCollection ;
    dct:provenance [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:%3COrganisation%3E" ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:MapDataToZones_47fbab073054" ;
            prov:actedOnBehalfOf agents:TerraNexus ;
            prov:qualifiedDelegation <file:///github/workspace/ogcapiProcess> ],
        [ a prov:Agent,
                prov:Person ;
            rdfs:label "agents:admin%40terranexus.pangaeainnovations.com" ;
            prov:actedOnBehalfOf <https://terranexus.pangaeainnovations.com/prov/agents/%3COrganisation%3E> ;
            prov:qualifiedDelegation roles:User ],
        terranexusCollections:osm_singapore_buildings,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_47fbab073054,
        <https://terranexus.pangaeainnovations.com/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605 ;
    rdfs:seeAlso [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items> ],
        [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items?f=jsonfg> ],
        [ rdfs:label "The JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items?f=json> ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items?f=geojson> ],
        [ rdfs:label "The Linked Data JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items?f=jsonld> ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:features <file:///github/workspace/2305843009229499373>,
        <file:///github/workspace/2305843009231960349> .

<file:///github/workspace/2305843009229499373> a geojson:Feature ;
    ns2:id 2305843009229499373 ;
    dct:provenance [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:MapDataToZones_47fbab073054" ;
            prov:actedOnBehalfOf agents:TerraNexus ;
            prov:qualifiedDelegation <file:///github/workspace/ogcapiProcess> ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:%3COrganisation%3E" ],
        [ a prov:Agent,
                prov:Person ;
            rdfs:label "agents:admin%40terranexus.pangaeainnovations.com" ;
            prov:actedOnBehalfOf <https://terranexus.pangaeainnovations.com/prov/agents/%3COrganisation%3E> ;
            prov:qualifiedDelegation roles:User ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        terranexusCollections:osm_singapore_buildings,
        <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373>,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_47fbab073054,
        <https://terranexus.pangaeainnovations.com/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:map_featureData_task-2305843009229499373-Polygon_0,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009229499373-Polygon_0,
        terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605 ;
    dct:spatial [ a <file:///github/workspace/null> ] ;
    dct:time [ time:hasTime "2024-08-01T06:36:24.345926+00:00"^^xsd:dateTime ] ;
    rdfs:seeAlso [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=jsonfg> ],
        [ rdfs:label "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=json> ],
        [ rdfs:label "The HTML representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget terranexusCollections:osm_singapore_buildings ],
        [ rdfs:label "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings?f=json> ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=geojson> ],
        [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373> ],
        [ rdfs:label "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373?f=jsonld> ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( ( ( 1.015578e+02 3.054745e+00 ) ( 1.015581e+02 3.055361e+00 ) ( 1.015579e+02 3.055433e+00 ) ( 1.015576e+02 3.054817e+00 ) ( 1.015578e+02 3.054745e+00 ) ) ) ] .

<file:///github/workspace/2305843009231960349> a geojson:Feature ;
    ns2:id 2305843009231960349 ;
    dct:provenance [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:MapDataToZones_47fbab073054" ;
            prov:actedOnBehalfOf agents:TerraNexus ;
            prov:qualifiedDelegation <file:///github/workspace/ogcapiProcess> ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:%3COrganisation%3E" ],
        [ a prov:Agent,
                prov:Person ;
            rdfs:label "agents:admin%40terranexus.pangaeainnovations.com" ;
            prov:actedOnBehalfOf <https://terranexus.pangaeainnovations.com/prov/agents/%3COrganisation%3E> ;
            prov:qualifiedDelegation roles:User ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Software ],
        terranexusCollections:osm_singapore_buildings,
        <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349>,
        terranexusCollections:osm_singapore_buildings___Properties,
        terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_47fbab073054,
        <https://terranexus.pangaeainnovations.com/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:map_featureData_task-2305843009231960349-Polygon_0,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009231960349-Polygon_0,
        terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605 ;
    dct:spatial [ a <file:///github/workspace/null> ] ;
    dct:time [ time:hasTime "2024-08-01T06:38:13.428950+00:00"^^xsd:dateTime ] ;
    rdfs:seeAlso [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=geojson> ],
        [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349> ],
        [ rdfs:label "The HTML representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget terranexusCollections:osm_singapore_buildings ],
        [ rdfs:label "The GeoJSON representation of the resources served from the OGC API Feature Collection Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings?f=json> ],
        [ rdfs:label "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=json> ],
        [ rdfs:label "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/ld+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=jsonld> ],
        [ rdfs:label "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349?f=jsonfg> ] ;
    prov:wasGeneratedBy dggsOperations:processData_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( ( ( 1.015583e+02 3.055355e+00 ) ( 1.01558e+02 3.054689e+00 ) ( 1.015582e+02 3.054614e+00 ) ( 1.015584e+02 3.055293e+00 ) ( 1.015583e+02 3.055355e+00 ) ) ) ] .

dggsOperations:map_featureData_task-2305843009231960349-Polygon_0 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:qualifiedAssociation agents:MapDataToZones_47fbab073054,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-08-01T06:38:14.748519+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_47fbab073054 ;
    prov:wasAssociatedWith agents:MapDataToZones_47fbab073054,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <https://terranexus.pangaeainnovations.com/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009231960349 .

dggsOperations:reorganiseData_task-2305843009229499373-Polygon_0 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-08-01T06:36:25.776828+00:00"^^xsd:dateTime ;
    prov:qualifiedAssociation agents:MapDataToZones_47fbab073054,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-08-01T06:36:25.624668+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_47fbab073054 ;
    prov:wasAssociatedWith agents:MapDataToZones_47fbab073054,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <https://terranexus.pangaeainnovations.com/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task .

dggsOperations:reorganiseData_task-2305843009231960349-Polygon_0 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-08-01T06:38:14.382261+00:00"^^xsd:dateTime ;
    prov:qualifiedAssociation agents:MapDataToZones_47fbab073054,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-08-01T06:38:14.249362+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_47fbab073054 ;
    prov:wasAssociatedWith agents:MapDataToZones_47fbab073054,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <https://terranexus.pangaeainnovations.com/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task .

<https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009229499373> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2024-08-01T06:36:24.345926+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5> ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusJobs:MapDataToZones_47fbab073054,
        terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

<https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960349> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2024-08-01T06:38:13.428950+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5> ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusJobs:MapDataToZones_47fbab073054,
        terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

dggsOperations:map_featureData_task-2305843009229499373-Polygon_0 a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2024-08-01T06:38:13.351488+00:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:qualifiedAssociation agents:MapDataToZones_47fbab073054,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-08-01T06:36:26.142218+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_47fbab073054 ;
    prov:wasAssociatedWith agents:MapDataToZones_47fbab073054,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <https://terranexus.pangaeainnovations.com/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution,
        dggsOperations:processData_task,
        dggsOperations:reorganiseData_task-2305843009229499373 .

terranexusCollections:osm_singapore_buildings___Properties a <file:///github/workspace/FeatureCollectionProperties>,
        prov:Entity ;
    prov:generatedAtTime "2024-08-01T06:36:24.173862+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5> ;
    prov:wasDerivedFrom terranexusJobs:MapDataToZones_47fbab073054,
        terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

<file:///github/workspace/ogcapiProcess> a prov:Delegation ;
    prov:agent agents:TerraNexus ;
    prov:hadActivity <https://terranexus.pangaeainnovations.com/ogcapi/processes/execution/MapDataToZones> .

terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 a <file:///github/workspace/FeatureCollectionDGGSZones>,
        prov:Entity ;
    prov:generatedAtTime "2024-08-01T06:36:28.014547+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource terranexusCollections:osm_singapore_buildings,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 ;
    prov:wasDerivedFrom terranexusCollections:osm_singapore_buildings,
        terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2,
        terranexusJobs:MapDataToZones_47fbab073054 ;
    prov:wasGeneratedBy dggsOperations:map_featureData_task-2305843009229499373-Polygon_0 .

roles:Software a prov:Delegation ;
    prov:agent agents:PangaeaInnovations .

roles:User a prov:Delegation ;
    prov:agent <https://terranexus.pangaeainnovations.com/prov/agents/%3COrganisation%3E> .

terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605 a <file:///github/workspace/rawData>,
        prov:Entity ;
    prov:generatedAtTime "2024-08-01T06:36:19.145246+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5> ;
    prov:wasDerivedFrom terranexusJobs:MapDataToZones_47fbab073054 ;
    prov:wasGeneratedBy <https://terranexus.pangaeainnovations.com/ogcapi/processes/execution/MapDataToZones> .

terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2 a <file:///github/workspace/DGGS>,
        prov:Entity ;
    prov:generatedAtTime "2024-07-30T20:54:30.425150+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource agents:TerraNexus ;
    prov:wasGeneratedBy agents:TerraNexus .

dggsOperations:map_data_execution a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:qualifiedAssociation agents:MapDataToZones_47fbab073054,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-08-01T06:36:20.113007+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_47fbab073054 ;
    prov:wasAssociatedWith agents:MapDataToZones_47fbab073054,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <https://terranexus.pangaeainnovations.com/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data .

terranexusCollections:osm_singapore_buildings a prov:Entity,
        geojson:FeatureCollection ;
    prov:generatedAtTime "2024-08-01T06:36:23.016609+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource <https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=5> ;
    prov:wasDerivedFrom terranexusJobs:MapDataToZones_47fbab073054,
        terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json ;
    prov:wasGeneratedBy dggsOperations:processData_task .

dggsOperations:map_data a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:qualifiedAssociation agents:MapDataToZones_47fbab073054,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-08-01T06:36:19.306985+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_47fbab073054 ;
    prov:wasAssociatedWith agents:MapDataToZones_47fbab073054,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <https://terranexus.pangaeainnovations.com/ogcapi/processes/execution/MapDataToZones> .

<https://terranexus.pangaeainnovations.com/ogcapi/processes/execution/MapDataToZones> a <file:///github/workspace/ogcapiProcess>,
        prov:Activity ;
    prov:endedAtTime "2024-08-01T06:36:19.266405+00:00"^^xsd:dateTime ;
    prov:generated terranexusJobs:MapDataToZones_47fbab073054,
        terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605 ;
    prov:qualifiedAssociation agents:MapDataToZones_47fbab073054,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-08-01T06:36:14.966889+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_47fbab073054 ;
    prov:wasAssociatedWith agents:MapDataToZones_47fbab073054,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com .

dggsOperations:processData_task a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:qualifiedAssociation agents:MapDataToZones_47fbab073054,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:startedAtTime "2024-08-01T06:36:21.653215+00:00"^^xsd:dateTime ;
    prov:used terranexusJobs:MapDataToZones_47fbab073054,
        terranexusTempData:osm_singapore_buildings__f58dba1aa47069ba0a88713a14b14605.json ;
    prov:wasAssociatedWith agents:MapDataToZones_47fbab073054,
        agents:TerraNexus,
        agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasInformedBy <https://terranexus.pangaeainnovations.com/ogcapi/processes/execution/MapDataToZones>,
        dggsOperations:map_data,
        dggsOperations:map_data_execution .

agents:MapDataToZones_47fbab073054 a prov:Association ;
    prov:agent agents:MapDataToZones_47fbab073054 ;
    prov:hadRole roles:ogcapiProcessJob .

terranexusJobs:MapDataToZones_47fbab073054 a <file:///github/workspace/ogcapiProcessJob>,
        prov:Entity ;
    prov:generatedAtTime "2024-08-01T06:36:19.115272+00:00"^^xsd:dateTime ;
    prov:hadPrimarySource agents:admin%40terranexus.pangaeainnovations.com ;
    prov:wasGeneratedBy <https://terranexus.pangaeainnovations.com/ogcapi/processes/execution/MapDataToZones> .

agents:admin%40terranexus.pangaeainnovations.com a prov:Association ;
    prov:agent agents:admin%40terranexus.pangaeainnovations.com ;
    prov:hadRole roles:User .

agents:TerraNexus a prov:Association ;
    prov:agent agents:TerraNexus ;
    prov:hadRole roles:Software .


```

<blockquote class="lang-specific turtle">
  <p class="example-links">
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/bbr/template/geojson-featureCollection_with-prov/example_2_1.ttl">Open in new window</a>
</blockquote>


The content of this example. 


# JSON Schema

```yaml--schema
$schema: https://json-schema.org/draft/2020-12/schema
description: CWL Provenance Chain for DGGS actions
allOf:
- $ref: https://ogcincubator.github.io/bblock-prov-schema/build/annotated/ogc-utils/prov/schema.yaml
- $ref: https://opengeospatial.github.io/bblocks/annotated-schemas/geo/features/featureCollection/schema.yaml
- type: object
- properties:
    a:
      type: string
      format: uri
    b:
      type: number

```

> <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=yaml&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Fannotated%2Fbbr%2Ftemplate%2Fgeojson-featureCollection_with-prov%2Fschema.yaml&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on YAML Viewer</a>

Links to the schema:

* YAML version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/geojson-featureCollection_with-prov/schema.yaml" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/geojson-featureCollection_with-prov/schema.yaml</a>
* JSON version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/geojson-featureCollection_with-prov/schema.json" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/geojson-featureCollection_with-prov/schema.json</a>


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

> <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Fannotated%2Fbbr%2Ftemplate%2Fgeojson-featureCollection_with-prov%2Fcontext.jsonld">View on JSON-LD Playground</a>

You can find the full JSON-LD context here:
<a href="https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/geojson-featureCollection_with-prov/context.jsonld" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/geojson-featureCollection_with-prov/context.jsonld</a>

# References

* [Sample source document](https://example.com/sources/1)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: <a href="https://github.com/geofizzydrink/test_bblock" target="_blank">https://github.com/geofizzydrink/test_bblock</a>
* Path:
<code><a href="https://github.com/geofizzydrink/test_bblock/blob/HEAD/_sources/geojson-featureCollection_with-prov" target="_blank">_sources/geojson-featureCollection_with-prov</a></code>

