
# OGC API Features Feature Collection with PROV Building Block (Schema)

`pangaea.terranexus.dggs.api.geojson-featureCollection_with-prov` *v0.1*

This Building Block serves as a template to combine an OGC API Features Feature Object with a Provenance Chain

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
    "id": "osm_singapore_buildings",
    "type": "FeatureCollection",
    "numberReturned": 10,
    "numberMatched": 10,
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
                "feature::id": 2305843009229499373,
                "created_by": "Potlatch 0.6",
                "landuse": "residential",
                "building": "yes",
                "id": "2305843009229499373",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1725712105.790587,
                "x_max": -1276078.7650104035,
                "x_min": -1276125.1697413276,
                "y_max": 6239991.512113506,
                "y_min": 6239978.749965917,
                "z_max": 337695.36020748876,
                "z_min": 337619.4573208119,
                "line::hidden": NaN,
                "amenity": NaN,
                "parking": NaN,
                "name": NaN,
                "is_in": NaN,
                "shop": NaN,
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
                    "id": "dggsOperations:reorganiseData_task-2305843009229499373-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-09-07T12:28:26.163972+00:00",
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
                        "terranexusCollections:osm_singapore_buildings/items/2305843009229499373"
                    ],
                    "endedAtTime": "2024-09-07T12:28:26.387716+00:00"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009229499373-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-09-07T12:28:26.836299+00:00",
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
                        "terranexusCollections:osm_singapore_buildings/items/2305843009229499373",
                        "terranexusCollections:osm_singapore_buildings___Properties",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "endedAtTime": "2024-09-07T12:29:56.372015+00:00"
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
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009229499373",
                    "entityType": "Feature",
                    "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
                    ],
                    "generatedAtTime": "2024-09-07T12:28:25.512778+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_64169fd6ebbc",
                        "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7.json",
                        "terranexusCollections:osm_singapore_buildings"
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
            "time": {
                "timestamp": "2024-09-07T12:28:25.512778+00:00"
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
                "feature::id": 2305843009231960349,
                "created_by": "Potlatch 0.6",
                "landuse": "residential",
                "building": "yes",
                "id": "2305843009231960349",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1725712196.549681,
                "x_max": -1276119.874648313,
                "x_min": -1276166.1218249332,
                "y_max": 6239983.877946686,
                "y_min": 6239970.787292116,
                "z_max": 337686.8355395783,
                "z_min": 337604.9811109423,
                "line::hidden": NaN,
                "amenity": NaN,
                "parking": NaN,
                "name": NaN,
                "is_in": NaN,
                "shop": NaN,
                "dggsZones": {
                    "TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2": {
                        "0": [
                            "T"
                        ],
                        "11": [
                            "T28498326478",
                            "T28498326498",
                            "T28498326852",
                            "T28498326477"
                        ],
                        "9": [
                            "T284983268"
                        ],
                        "10": [
                            "T2849832685"
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
                    "id": "dggsOperations:reorganiseData_task-2305843009231960349-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-09-07T12:29:56.799343+00:00",
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
                        "terranexusCollections:osm_singapore_buildings/items/2305843009231960349"
                    ],
                    "endedAtTime": "2024-09-07T12:29:56.911123+00:00"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009231960349-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-09-07T12:29:57.369261+00:00",
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
                        "terranexusCollections:osm_singapore_buildings/items/2305843009231960349",
                        "terranexusCollections:osm_singapore_buildings___Properties",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "endedAtTime": "2024-09-07T12:32:14.355554+00:00",
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ]
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
                    "provType": "Entity",
                    "id": "terranexusJobs:MapDataToZones_64169fd6ebbc",
                    "entityType": "ogcapiProcessJob",
                    "hadPrimarySource": [
                        "agents:admin%40terranexus.pangaeainnovations.com"
                    ],
                    "wasAttributedTo": [
                        "agents:MapDataToZones",
                        "agents:admin%40terranexus.pangaeainnovations.com"
                    ],
                    "generatedAtTime": "2024-09-07T12:28:22.773864+00:00",
                    "wasGeneratedBy": "terranexusProcesses:MapDataToZones"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings___Properties",
                    "entityType": "FeatureCollectionProperties",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
                    ],
                    "wasAttributedTo": "dggsOperations:processData_task",
                    "generatedAtTime": "2024-09-07T12:28:25.439676+00:00",
                    "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_64169fd6ebbc",
                        "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7.json"
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
                    "generatedAtTime": "2024-09-07T12:28:28.137746+00:00",
                    "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373-Polygon_0",
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
                    "hadPrimarySource": [
                        "terranexusCollections:osm_singapore_buildings",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "generatedAtTime": "2024-09-07T12:28:31.459547+00:00",
                    "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373-Polygon_0",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_64169fd6ebbc",
                        "terranexusCollections:osm_singapore_buildings",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960349",
                    "entityType": "Feature",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
                    ],
                    "wasAttributedTo": "dggsOperations:processData_task",
                    "generatedAtTime": "2024-09-07T12:29:56.416866+00:00",
                    "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_64169fd6ebbc",
                        "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7.json",
                        "terranexusCollections:osm_singapore_buildings"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7",
                    "entityType": "rawData",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
                    ],
                    "generatedAtTime": "2024-09-07T12:28:22.792585+00:00",
                    "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
                    "wasDerivedFrom": "terranexusJobs:MapDataToZones_64169fd6ebbc"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings",
                    "entityType": "FeatureCollection",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
                    ],
                    "wasAttributedTo": "dggsOperations:processData_task",
                    "generatedAtTime": "2024-09-07T12:28:25.304603+00:00",
                    "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_64169fd6ebbc",
                        "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7.json"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
                    "entityType": "DGGS",
                    "hadPrimarySource": [
                        "agents:TerraNexus"
                    ],
                    "generatedAtTime": "2024-09-07T12:28:21.069077+00:00",
                    "wasGeneratedBy": "dggsOperations:initialiseSurfaceDGGS_TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                }
            ],
            "time": {
                "timestamp": "2024-09-07T12:29:56.416866+00:00"
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
                "line::hidden": NaN,
                "amenity": NaN,
                "parking": NaN,
                "name": NaN,
                "is_in": NaN,
                "shop": NaN,
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
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960466"
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
                    "endedAtTime": "2024-09-07T12:33:29.106657+00:00",
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ]
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
            "time": {
                "timestamp": "2024-09-07T12:32:14.625194+00:00"
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
                "feature::id": 2305843009231960589,
                "created_by": NaN,
                "landuse": "residential",
                "building": "yes",
                "id": "2305843009231960589",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1725712409.473092,
                "x_max": -1276113.6289550927,
                "x_min": -1276163.644612229,
                "y_max": 6239990.566373775,
                "y_min": 6239976.207058218,
                "z_max": 337597.0117900565,
                "z_min": 337506.56320081395,
                "line::hidden": [
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
                "amenity": NaN,
                "parking": NaN,
                "name": NaN,
                "is_in": NaN,
                "shop": NaN,
                "dggsZones": {
                    "TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2": {
                        "0": [
                            "T"
                        ],
                        "8": [
                            "T28498327"
                        ],
                        "9": [
                            "T284983273"
                        ],
                        "10": [
                            "T2849832731"
                        ],
                        "11": [
                            "T28498327315",
                            "T28498326859",
                            "T28498326856",
                            "T28498326857"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960589"
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
                    "id": "dggsOperations:reorganiseData_task-2305843009231960589-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-09-07T12:33:29.745826+00:00",
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
                        "terranexusCollections:osm_singapore_buildings/items/2305843009231960589"
                    ],
                    "endedAtTime": "2024-09-07T12:33:29.856951+00:00"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009231960589-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-09-07T12:33:30.197145+00:00",
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
                        "terranexusCollections:osm_singapore_buildings/items/2305843009231960589",
                        "terranexusCollections:osm_singapore_buildings___Properties",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "endedAtTime": "2024-09-07T12:35:05.546432+00:00"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusJobs:MapDataToZones_64169fd6ebbc",
                    "entityType": "ogcapiProcessJob",
                    "hadPrimarySource": [
                        "agents:admin%40terranexus.pangaeainnovations.com"
                    ],
                    "wasAttributedTo": [
                        "agents:MapDataToZones",
                        "agents:admin%40terranexus.pangaeainnovations.com"
                    ],
                    "generatedAtTime": "2024-09-07T12:28:22.773864+00:00",
                    "wasGeneratedBy": "terranexusProcesses:MapDataToZones"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings___Properties",
                    "entityType": "FeatureCollectionProperties",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
                    ],
                    "wasAttributedTo": "dggsOperations:processData_task",
                    "generatedAtTime": "2024-09-07T12:28:25.439676+00:00",
                    "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_64169fd6ebbc",
                        "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7.json"
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
                    "generatedAtTime": "2024-09-07T12:28:28.137746+00:00",
                    "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373-Polygon_0",
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
                    "hadPrimarySource": [
                        "terranexusCollections:osm_singapore_buildings",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "generatedAtTime": "2024-09-07T12:28:31.459547+00:00",
                    "wasGeneratedBy": "dggsOperations:map_featureData_task-2305843009229499373-Polygon_0",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_64169fd6ebbc",
                        "terranexusCollections:osm_singapore_buildings",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960589",
                    "entityType": "Feature",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
                    ],
                    "wasAttributedTo": "dggsOperations:processData_task",
                    "generatedAtTime": "2024-09-07T12:33:29.181566+00:00",
                    "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_64169fd6ebbc",
                        "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7.json",
                        "terranexusCollections:osm_singapore_buildings"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7",
                    "entityType": "rawData",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
                    ],
                    "generatedAtTime": "2024-09-07T12:28:22.792585+00:00",
                    "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
                    "wasDerivedFrom": "terranexusJobs:MapDataToZones_64169fd6ebbc"
                },
                {
                    "provType": "Entity",
                    "id": "terranexusCollections:osm_singapore_buildings",
                    "entityType": "FeatureCollection",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
                    ],
                    "wasAttributedTo": "dggsOperations:processData_task",
                    "generatedAtTime": "2024-09-07T12:28:25.304603+00:00",
                    "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_64169fd6ebbc",
                        "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7.json"
                    ]
                },
                {
                    "provType": "Entity",
                    "id": "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2",
                    "entityType": "DGGS",
                    "hadPrimarySource": [
                        "agents:TerraNexus"
                    ],
                    "generatedAtTime": "2024-09-07T12:28:21.069077+00:00",
                    "wasGeneratedBy": "dggsOperations:initialiseSurfaceDGGS_TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                }
            ],
            "time": {
                "timestamp": "2024-09-07T12:33:29.181566+00:00"
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
                "feature::id": 2305843009231960619,
                "created_by": "Potlatch 0.6",
                "landuse": "residential",
                "building": "yes",
                "id": "2305843009231960619",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1725712507.592845,
                "x_max": -1276087.4680238087,
                "x_min": -1276136.47619351,
                "y_max": 6239995.397990122,
                "y_min": 6239981.227931422,
                "z_max": 337606.71659015486,
                "z_min": 337516.08289024205,
                "line::hidden": [
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
                "amenity": NaN,
                "parking": NaN,
                "name": NaN,
                "is_in": NaN,
                "shop": NaN,
                "dggsZones": {
                    "TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2": {
                        "0": [
                            "T"
                        ],
                        "11": [
                            "T28498327313",
                            "T28498327314",
                            "T28498326858"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960619"
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
                    "id": "dggsOperations:reorganiseData_task-2305843009231960619-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-09-07T12:35:08.565541+00:00",
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
                        "terranexusCollections:osm_singapore_buildings/items/2305843009231960619"
                    ],
                    "endedAtTime": "2024-09-07T12:35:08.728517+00:00"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009231960619-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-09-07T12:35:09.197790+00:00",
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
                        "terranexusCollections:osm_singapore_buildings/items/2305843009231960619",
                        "terranexusCollections:osm_singapore_buildings___Properties",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "endedAtTime": "2024-09-07T12:37:34.291040+00:00"
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
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960619",
                    "entityType": "Feature",
                    "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
                    ],
                    "generatedAtTime": "2024-09-07T12:35:05.912959+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_64169fd6ebbc",
                        "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7.json",
                        "terranexusCollections:osm_singapore_buildings"
                    ],
                    "wasAttributedTo": "dggsOperations:processData_task"
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
            "time": {
                "timestamp": "2024-09-07T12:35:05.912959+00:00"
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
                "feature::id": 2305843009231960767,
                "created_by": "Potlatch 0.6",
                "landuse": "residential",
                "building": "yes",
                "id": "2305843009231960767",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1725712654.436959,
                "x_max": -1276188.4441563762,
                "x_min": -1276234.706646427,
                "y_max": 6239970.810990351,
                "y_min": 6239958.167388152,
                "z_max": 337662.2796796035,
                "z_min": 337587.6448291851,
                "line::hidden": NaN,
                "amenity": NaN,
                "parking": NaN,
                "name": NaN,
                "is_in": NaN,
                "shop": NaN,
                "dggsZones": {
                    "TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2": {
                        "0": [
                            "T"
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
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960767"
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
                    "id": "dggsOperations:reorganiseData_task-2305843009231960767-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-09-07T12:37:34.548792+00:00",
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
                        "terranexusCollections:osm_singapore_buildings/items/2305843009231960767"
                    ],
                    "endedAtTime": "2024-09-07T12:37:34.632164+00:00"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009231960767-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-09-07T12:37:34.834594+00:00",
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
                        "terranexusCollections:osm_singapore_buildings/items/2305843009231960767",
                        "terranexusCollections:osm_singapore_buildings___Properties",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "endedAtTime": "2024-09-07T12:39:22.314123+00:00"
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
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960767",
                    "entityType": "Feature",
                    "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
                    ],
                    "generatedAtTime": "2024-09-07T12:37:34.340138+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_64169fd6ebbc",
                        "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7.json",
                        "terranexusCollections:osm_singapore_buildings"
                    ],
                    "wasAttributedTo": "dggsOperations:processData_task"
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
            "time": {
                "timestamp": "2024-09-07T12:37:34.340138+00:00"
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
                "feature::id": 2305843009231960798,
                "created_by": "Potlatch 0.6",
                "landuse": "residential",
                "building": "yes",
                "id": "2305843009231960798",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1725712762.511882,
                "x_max": -1276168.2156584898,
                "x_min": -1276201.2976202518,
                "y_max": 6239977.235185958,
                "y_min": 6239969.296571625,
                "z_max": 337583.2066295785,
                "z_min": 337545.6091949509,
                "line::hidden": [
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
                "amenity": NaN,
                "parking": NaN,
                "name": NaN,
                "is_in": NaN,
                "shop": NaN,
                "dggsZones": {
                    "TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2": {
                        "0": [
                            "T"
                        ],
                        "11": [
                            "T28498326846",
                            "T28498326842"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960798"
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
                    "id": "dggsOperations:reorganiseData_task-2305843009231960798-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-09-07T12:39:22.677649+00:00",
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
                        "terranexusCollections:osm_singapore_buildings/items/2305843009231960798"
                    ],
                    "endedAtTime": "2024-09-07T12:39:22.762645+00:00"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009231960798-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-09-07T12:39:22.939115+00:00",
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
                        "terranexusCollections:osm_singapore_buildings/items/2305843009231960798",
                        "terranexusCollections:osm_singapore_buildings___Properties",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "endedAtTime": "2024-09-07T12:41:05.607417+00:00"
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
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960798",
                    "entityType": "Feature",
                    "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
                    ],
                    "generatedAtTime": "2024-09-07T12:39:22.393506+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_64169fd6ebbc",
                        "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7.json",
                        "terranexusCollections:osm_singapore_buildings"
                    ],
                    "wasAttributedTo": "dggsOperations:processData_task"
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
            "time": {
                "timestamp": "2024-09-07T12:39:22.393506+00:00"
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
                "feature::id": 2305843009231960865,
                "created_by": NaN,
                "landuse": NaN,
                "building": "yes",
                "id": "2305843009231960865",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1725712865.77852,
                "x_max": -1276197.5969815229,
                "x_min": -1276265.9318077033,
                "y_max": 6239971.826792301,
                "y_min": 6239952.776008753,
                "z_max": 337647.17407459696,
                "z_min": 337531.4106530871,
                "line::hidden": [
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
                "name": NaN,
                "is_in": NaN,
                "shop": NaN,
                "dggsZones": {
                    "TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2": {
                        "0": [
                            "T"
                        ],
                        "11": [
                            "T28498326844",
                            "T28498326838"
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009231960865"
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
                    "id": "dggsOperations:reorganiseData_task-2305843009231960865-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-09-07T12:41:05.946979+00:00",
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
                        "terranexusCollections:osm_singapore_buildings/items/2305843009231960865"
                    ],
                    "endedAtTime": "2024-09-07T12:41:06.110968+00:00"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009231960865-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-09-07T12:41:06.523423+00:00",
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
                        "terranexusCollections:osm_singapore_buildings/items/2305843009231960865",
                        "terranexusCollections:osm_singapore_buildings___Properties",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "endedAtTime": "2024-09-07T12:43:50.885128+00:00"
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
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009231960865",
                    "entityType": "Feature",
                    "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
                    ],
                    "generatedAtTime": "2024-09-07T12:41:05.661235+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_64169fd6ebbc",
                        "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7.json",
                        "terranexusCollections:osm_singapore_buildings"
                    ],
                    "wasAttributedTo": "dggsOperations:processData_task"
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
            "time": {
                "timestamp": "2024-09-07T12:41:05.661235+00:00"
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
                "feature::id": 2305843009232899975,
                "created_by": NaN,
                "landuse": NaN,
                "building": "commercial",
                "id": "2305843009232899975",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1725713031.062454,
                "x_max": -1271622.3602021495,
                "x_min": -1271675.8948859423,
                "y_max": 6240964.134369386,
                "y_min": 6240954.894049214,
                "z_max": 336482.36612796935,
                "z_min": 336426.2841626774,
                "line::hidden": NaN,
                "amenity": NaN,
                "parking": NaN,
                "name": "Giant",
                "is_in": "Seksyen 18, Shah Alam, Selangor, Malaysia",
                "shop": "supermarket",
                "dggsZones": {
                    "TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2": {
                        "0": [
                            "T"
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
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009232899975"
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
                    "id": "dggsOperations:reorganiseData_task-2305843009232899975-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-09-07T12:43:51.286779+00:00",
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
                        "terranexusCollections:osm_singapore_buildings/items/2305843009232899975"
                    ],
                    "endedAtTime": "2024-09-07T12:43:51.402325+00:00"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:map_featureData_task-2305843009232899975-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-09-07T12:43:51.862389+00:00",
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
                        "terranexusCollections:osm_singapore_buildings/items/2305843009232899975",
                        "terranexusCollections:osm_singapore_buildings___Properties",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "endedAtTime": "2024-09-07T12:46:34.558053+00:00"
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
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009232899975",
                    "entityType": "Feature",
                    "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
                    ],
                    "generatedAtTime": "2024-09-07T12:43:50.942142+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_64169fd6ebbc",
                        "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7.json",
                        "terranexusCollections:osm_singapore_buildings"
                    ],
                    "wasAttributedTo": "dggsOperations:processData_task"
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
            "time": {
                "timestamp": "2024-09-07T12:43:50.942142+00:00"
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
                "feature::id": 2305843009232900002,
                "created_by": NaN,
                "landuse": NaN,
                "building": "commercial",
                "id": "2305843009232900002",
                "record_type": "Feature",
                "geometry_type": "Polygon",
                "created": 1725713195.153711,
                "x_max": -1271512.3583419316,
                "x_min": -1271549.6728737596,
                "y_max": 6240982.397314117,
                "y_min": 6240972.719726458,
                "z_max": 336596.6542250734,
                "z_min": 336509.51852749335,
                "line::hidden": NaN,
                "amenity": NaN,
                "parking": NaN,
                "name": "Mydin",
                "is_in": "Seksyen 18, Shah Alam, Selangor, Malaysia",
                "shop": "supermarket",
                "dggsZones": {
                    "TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2": {
                        "0": [
                            "T"
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
                        ]
                    }
                }
            },
            "links": [
                {
                    "rel": "self",
                    "type": "application/geo+json",
                    "title": "The GeoJSON  representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002?f=json"
                },
                {
                    "rel": "alternate",
                    "type": "application/geo+json",
                    "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002?f=geojson"
                },
                {
                    "rel": "alternate",
                    "type": "application/vnd.ogc.fg+json",
                    "title": "The Feature Geometry JSON representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002?f=jsonfg"
                },
                {
                    "rel": "alternate",
                    "type": "application/ld+json",
                    "title": "The Linked Data JSON (Feature Geometry JSON + PROV) representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002?f=jsonld"
                },
                {
                    "rel": "alternate",
                    "type": "text/html",
                    "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
                    "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009232900002"
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
                    "id": "dggsOperations:map_featureData_task-2305843009232900002-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-09-07T12:47:13.237989+00:00",
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
                        "terranexusCollections:osm_singapore_buildings/items/2305843009232900002",
                        "terranexusCollections:osm_singapore_buildings___Properties",
                        "terranexusDGGS:TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "generated": [
                        "terranexusCollections:osm_singapore_buildings___TerraNexus_S_IT9_GRS80_2d10b58e2088c7e2"
                    ],
                    "endedAtTime": "2024-09-07T12:49:38.581180+00:00"
                },
                {
                    "provType": "Activity",
                    "id": "dggsOperations:reorganiseData_task-2305843009232900002-Polygon_0",
                    "activityType": "dggsOperation",
                    "startedAtTime": "2024-09-07T12:46:36.341860+00:00",
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
                        "terranexusCollections:osm_singapore_buildings/items/2305843009232900002"
                    ],
                    "endedAtTime": "2024-09-07T12:46:37.093281+00:00"
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
                    "id": "terranexusCollections:osm_singapore_buildings/items/2305843009232900002",
                    "entityType": "Feature",
                    "wasGeneratedBy": "activities:MapDataToZones_64169fd6ebbc",
                    "hadPrimarySource": [
                        "https://maps.ecere.com/ogcapi/collections/osm:singapore:buildings/items?limit=10"
                    ],
                    "generatedAtTime": "2024-09-07T12:46:34.683109+00:00",
                    "wasDerivedFrom": [
                        "terranexusJobs:MapDataToZones_64169fd6ebbc",
                        "terranexusTempData:osm_singapore_buildings__5b50927634e602daf8844eb8dbc640f7.json",
                        "terranexusCollections:osm_singapore_buildings"
                    ],
                    "wasAttributedTo": "dggsOperations:processData_task"
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
            "time": {
                "timestamp": "2024-09-07T12:46:34.683109+00:00"
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
    "@context": "https://terranexus.pangaeainnovations.com/context/geojsonFeatureCollection.jsonld"
}
```

## Schema

```yaml
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

Links to the schema:

* YAML version: [schema.yaml](https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/geojson-featureCollection_with-prov/schema.json)
* JSON version: [schema.json](https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/geojson-featureCollection_with-prov/schema.yaml)


# JSON-LD Context

```jsonld
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

You can find the full JSON-LD context here:
[context.jsonld](https://geofizzydrink.github.io/test_bblock/build/annotated/terranexus/dggs/api/geojson-featureCollection_with-prov/context.jsonld)

## Sources

* [Sample source document](https://example.com/sources/1)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/geofizzydrink/test_bblock](https://github.com/geofizzydrink/test_bblock)
* Path: `_sources/geojson-featureCollection_with-prov`

