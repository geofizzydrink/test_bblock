---
title: My Building Block (Schema)

language_tabs:
  - json: JSON
  - jsonld: JSON-LD
  - turtle: RDF/Turtle

toc_footers:
  - Version 0.1
  - <a href='#'>My Building Block</a>
  - <a href='https://blocks.ogc.org/register.html'>Building Blocks register</a>

search: true

code_clipboard: true

meta:
  - name: My Building Block (Schema)
---


# My Building Block `ogc.bbr.template.json-fg-feature_with-prov`

This Building Block serves as a template to combine a JSON-FG Feature Object with a Provenance Chain

<p class="status">
    <span data-rainbow-uri="http://www.opengis.net/def/status">Status</span>:
    <a href="http://www.opengis.net/def/status/under-development" target="_blank" data-rainbow-uri>Under development</a>
</p>

<aside class="success">
This building block is <strong><a href="https://github.com/geofizzydrink/test_bblock/blob/master/build/tests/bbr/template/json-fg-feature_with-prov/" target="_blank">valid</a></strong>
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

The content of this example. 



```json
{
  "provType": "Activity",
  "id": "surveyreg-nz:DP-1-S2",
  "endedAtTime": "2029-01-01T22:05:19+02:00",
  "wasAssociatedWith": "linz-registered-surveyors:bc-3",
  "used": {
    "provType": "Entity",
    "id": "Act3",
    "wasAttributedTo": "icsm-jurisdictions:nz",
    "links": [
      {
        "href": "https://some.gov/linktoact/",
        "rel": "related"
      }
    ]
  },
  "type": "Feature",
  "time": {
  		"date":"2023-12-10"
  },
  "place": {"type": "null"},
  "geometry": {
  		"type": "Point",
  		"coordinates": [100.0,-0.5]
  },  
  "properties": {
  		"prop1": "bla"
  }
}
```

<blockquote class="lang-specific json">
  <p class="example-links">
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/bbr/template/json-fg-feature_with-prov/example_2_1.json">Open in new window</a>
    <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=json&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Ftests%2Fbbr%2Ftemplate%2Fjson-fg-feature_with-prov%2Fexample_2_1.json&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on JSON Viewer</a></p>
</blockquote>




```json
{
  
  "id": "osm_singapore_buildings",
  "type": "Feature",  
  "time": {
  		"date":"2023-12-10"
  },
  "place": {"type": "null"},
  "geometry": {
        "type": "Polygon",
        "coordinates": [
            [
                [
                    103.9912666162932,
                    1.3595581054687
                ],
                [
                    103.9910888671875,
                    1.3591636709406
                ],
                [
                    103.9908972032733,
                    1.3587383053019
                ],
                [
                    103.9910888671875,
                    1.3586563252853
                ],
                [
                    103.9911366050398,
                    1.3586359141052
                ],
                [
                    103.9911444845097,
                    1.3586473980135
                ],
                [
                    103.9914361925445,
                    1.359266984203
                ],
                [
                    103.9915527081101,
                    1.3595581054687
                ],
                [
                    103.9916911017784,
                    1.3599040058152
                ],
                [
                    103.9919875039655,
                    1.3605287891018
                ],
                [
                    103.9920041011468,
                    1.3605675996823
                ],
                [
                    103.992068813389,
                    1.3607173096105
                ],
                [
                    103.9921689832457,
                    1.3609440120186
                ],
                [
                    103.9922510051745,
                    1.3611352987242
                ],
                [
                    103.99225980671,
                    1.3611557099042
                ],
                [
                    103.9924025173219,
                    1.3614882822112
                ],
                [
                    103.9923205792173,
                    1.3615234045292
                ],
                [
                    103.9924075048587,
                    1.3617263847034
                ],
                [
                    103.9924463154392,
                    1.3618164118383
                ],
                [
                    103.9924668942675,
                    1.3618703107654
                ],
                [
                    103.9926443499887,
                    1.3623046875
                ],
                [
                    103.9926928003462,
                    1.3624232986693
                ],
                [
                    103.9927059188253,
                    1.3624520922641
                ],
                [
                    103.9927205880512,
                    1.3624878013512
                ],
                [
                    103.9929078092856,
                    1.3629396135085
                ],
                [
                    103.992952780941,
                    1.3630425914743
                ],
                [
                    103.9929729825607,
                    1.3630917962491
                ],
                [
                    103.9929858076553,
                    1.3631220986786
                ],
                [
                    103.9931648979474,
                    1.3635009838273
                ],
                [
                    103.9931205968852,
                    1.36351841925
                ],
                [
                    103.9931648979474,
                    1.363609619923
                ],
                [
                    103.9932436926464,
                    1.3636649019486
                ],
                [
                    103.9932902988727,
                    1.3636975933662
                ],
                [
                    103.993546591205,
                    1.363888419039
                ],
                [
                    103.9935737083168,
                    1.3639053096048
                ],
                [
                    103.9935864914994,
                    1.3639152008543
                ],
                [
                    103.9938354492188,
                    1.3641061103512
                ],
                [
                    103.9939587964525,
                    1.3642007059022
                ],
                [
                    103.9939823929501,
                    1.364220991346
                ],
                [
                    103.9940919930235,
                    1.3643046059335
                ],
                [
                    103.9941722127331,
                    1.3643657137374
                ],
                [
                    103.994470794348,
                    1.364593296299
                ],
                [
                    103.9945034019416,
                    1.3646181920709
                ],
                [
                    103.9944417911928,
                    1.3646989147254
                ],
                [
                    103.9945129998065,
                    1.3647531908612
                ],
                [
                    103.9943717980293,
                    1.3649384003161
                ],
                [
                    103.9943062056336,
                    1.3648883992118
                ],
                [
                    103.9942663053391,
                    1.3649407054801
                ],
                [
                    103.9942450978297,
                    1.3649246112437
                ],
                [
                    103.9938492802032,
                    1.3646228023991
                ],
                [
                    103.9938354492188,
                    1.3646105640735
                ],
                [
                    103.9938287013749,
                    1.364604612559
                ],
                [
                    103.9938134034679,
                    1.3645930867386
                ],
                [
                    103.9934374940765,
                    1.364311102305
                ],
                [
                    103.9934060181089,
                    1.364284488138
                ],
                [
                    103.9933897981363,
                    1.3642720821641
                ],
                [
                    103.9930687097376,
                    1.3640297884645
                ],
                [
                    103.9930174093591,
                    1.3639910197961
                ],
                [
                    103.993023612346,
                    1.3639082853621
                ],
                [
                    103.9929583971589,
                    1.3638972205746
                ],
                [
                    103.9929052945612,
                    1.3638760968893
                ],
                [
                    103.9928822848326,
                    1.3638564820387
                ],
                [
                    103.9928664839807,
                    1.3638468841737
                ],
                [
                    103.9928114953397,
                    1.3637832197334
                ],
                [
                    103.9927492139977,
                    1.3636418083958
                ],
                [
                    103.9927806899653,
                    1.3636283965321
                ],
                [
                    103.9927707148917,
                    1.3636048838586
                ],
                [
                    103.9927609074664,
                    1.3635814969214
                ],
                [
                    103.9925194939203,
                    1.3630094809358
                ],
                [
                    103.9925065850015,
                    1.3629782983528
                ],
                [
                    103.992495520214,
                    1.3629526062515
                ],
                [
                    103.9922808046591,
                    1.3624520922641
                ],
                [
                    103.9922494963398,
                    1.3623792071675
                ],
                [
                    103.9922352881468,
                    1.3623372950936
                ],
                [
                    103.9922227145246,
                    1.3623072860486
                ],
                [
                    103.9922216248106,
                    1.3623046875
                ],
                [
                    103.9920831892303,
                    1.3619721151931
                ],
                [
                    103.9920432889359,
                    1.3618789027406
                ],
                [
                    103.9920263145459,
                    1.3618392958307
                ],
                [
                    103.9918421109809,
                    1.3619183000901
                ],
                [
                    103.9918048930592,
                    1.3619343105023
                ],
                [
                    103.9915833877483,
                    1.3618442833675
                ],
                [
                    103.9915551809225,
                    1.3618566055172
                ],
                [
                    103.9915224056806,
                    1.3618708137103
                ],
                [
                    103.9915934885581,
                    1.3620369112594
                ],
                [
                    103.9916304969194,
                    1.3621232920439
                ],
                [
                    103.9914364021049,
                    1.3622056073571
                ],
                [
                    103.9912027422925,
                    1.3623046875
                ],
                [
                    103.991091381912,
                    1.3623518804953
                ],
                [
                    103.9910888671875,
                    1.3623529702092
                ],
                [
                    103.9910037018532,
                    1.3623888888566
                ],
                [
                    103.9909324094154,
                    1.3624194008465
                ],
                [
                    103.9905380167994,
                    1.3625885160649
                ],
                [
                    103.9905093908528,
                    1.3626005029181
                ],
                [
                    103.9903816009393,
                    1.3626536893399
                ],
                [
                    103.9900655000775,
                    1.3627852932522
                ],
                [
                    103.9898450006563,
                    1.3628816071982
                ],
                [
                    103.9898193923791,
                    1.3628207089547
                ],
                [
                    103.9897234137297,
                    1.3625922043274
                ],
                [
                    103.9896701015716,
                    1.3626150044957
                ],
                [
                    103.9896853994787,
                    1.3626482826824
                ],
                [
                    103.989591516433,
                    1.3628873072402
                ],
                [
                    103.9895605014982,
                    1.3628987073243
                ],
                [
                    103.9893791060421,
                    1.3629731012556
                ],
                [
                    103.9893894164123,
                    1.3629954823031
                ],
                [
                    103.9894058040332,
                    1.3630371009926
                ],
                [
                    103.9894286042014,
                    1.3630925087544
                ],
                [
                    103.9894353939574,
                    1.3631088963753
                ],
                [
                    103.9896825075455,
                    1.363695204378
                ],
                [
                    103.9896962966179,
                    1.3637265126973
                ],
                [
                    103.9897024996048,
                    1.3637408047145
                ],
                [
                    103.9899053121308,
                    1.3642119802501
                ],
                [
                    103.9899478109738,
                    1.3643108927446
                ],
                [
                    103.9899670067036,
                    1.3643510025994
                ],
                [
                    103.9900227078499,
                    1.364328118607
                ],
                [
                    103.9900305873198,
                    1.364347398161
                ],
                [
                    103.9901452168421,
                    1.3646261134529
                ],
                [
                    103.9901590059145,
                    1.3646635828471
                ],
                [
                    103.9901667177361,
                    1.3646847903565
                ],
                [
                    103.990253391905,
                    1.3649034037343
                ],
                [
                    103.9902540205862,
                    1.3649637152087
                ],
                [
                    103.9902559904536,
                    1.3650150155873
                ],
                [
                    103.9902520088066,
                    1.3650441863908
                ],
                [
                    103.9902484462803,
                    1.3650512695313
                ],
                [
                    103.9902198203338,
                    1.3651084795122
                ],
                [
                    103.9901799200394,
                    1.3651483798066
                ],
                [
                    103.9901419896124,
                    1.3651863102336
                ],
                [
                    103.9901362895704,
                    1.3652189178271
                ],
                [
                    103.9901466837647,
                    1.3652399157762
                ],
                [
                    103.9902010856367,
                    1.3652418856437
                ],
                [
                    103.9901504977635,
                    1.3656856925949
                ],
                [
                    103.9901483183356,
                    1.3657048045006
                ],
                [
                    103.9901041010976,
                    1.3660813006611
                ],
                [
                    103.9901001194506,
                    1.3661080824763
                ],
                [
                    103.990086791411,
                    1.3662137847269
                ],
                [
                    103.9900693140762,
                    1.3663517173623
                ],
                [
                    103.9900227078499,
                    1.3667388172775
                ],
                [
                    103.9899870825871,
                    1.3667368054979
                ],
                [
                    103.9899797898862,
                    1.3667783822753
                ],
                [
                    103.9898825119625,
                    1.366788399261
                ],
                [
                    103.9898134827767,
                    1.3667858007124
                ],
                [
                    103.9897525007091,
                    1.3667811065601
                ],
                [
                    103.9896978892767,
                    1.3667634196649
                ],
                [
                    103.9896760111741,
                    1.36675160046
                ],
                [
                    103.9896786935468,
                    1.3667140053297
                ],
                [
                    103.989576218526,
                    1.3667099817706
                ],
                [
                    103.9895797810522,
                    1.3666894867664
                ],
                [
                    103.9896455830084,
                    1.3661579997564
                ],
                [
                    103.9896683831766,
                    1.3659921117677
                ],
                [
                    103.9896701853958,
                    1.3659771910693
                ],
                [
                    103.9897216115106,
                    1.3655550945724
                ],
                [
                    103.9897618890136,
                    1.3655599982851
                ],
                [
                    103.9897858208079,
                    1.3653122979279
                ],
                [
                    103.9898109680522,
                    1.3650512695313
                ],
                [
                    103.9898165842702,
                    1.3649930955726
                ],
                [
                    103.9897950833762,
                    1.3649373944263
                ],
                [
                    103.9897783185466,
                    1.3648982904613
                ],
                [
                    103.9895100812732,
                    1.3642732976143
                ],
                [
                    103.9894939870368,
                    1.3642331877595
                ],
                [
                    103.9894918914331,
                    1.3642279906623
                ],
                [
                    103.9892855163809,
                    1.3637369068916
                ],
                [
                    103.9892461190314,
                    1.3636431076701
                ],
                [
                    103.9892348865956,
                    1.3636183795464
                ],
                [
                    103.9892078113958,
                    1.3636296958064
                ],
                [
                    103.9891988002999,
                    1.3636081949125
                ],
                [
                    103.9890596103022,
                    1.3632754968693
                ],
                [
                    103.9890477072732,
                    1.3632534930305
                ],
                [
                    103.9889964068947,
                    1.3631321994884
                ],
                [
                    103.9889313174438,
                    1.3629782145287
                ],
                [
                    103.9888570911608,
                    1.3630094809358
                ],
                [
                    103.9888295130162,
                    1.362944391485
                ],
                [
                    103.9888202923599,
                    1.3629225133824
                ],
                [
                    103.9888523970085,
                    1.3629088919583
                ],
                [
                    103.9886655948949,
                    1.3624671806108
                ],
                [
                    103.9886150070216,
                    1.3623512099021
                ],
                [
                    103.9885968171815,
                    1.3623085853229
                ],
                [
                    103.9885951406985,
                    1.3623046875
                ],
                [
                    103.9885862972509,
                    1.3622841086717
                ],
                [
                    103.9884893965359,
                    1.3620571967032
                ],
                [
                    103.9883950105453,
                    1.3618351046233
                ],
                [
                    103.9883422851562,
                    1.3617099551704
                ],
                [
                    103.9883158805496,
                    1.3616472966198
                ],
                [
                    103.9880514153629,
                    1.3610370987349
                ],
                [
                    103.987782297936,
                    1.3603996160899
                ],
                [
                    103.9876483888596,
                    1.3600644871464
                ],
                [
                    103.9878664154684,
                    1.3599833872833
                ],
                [
                    103.9883422851562,
                    1.3610924645846
                ],
                [
                    103.9887147996697,
                    1.3619605893727
                ],
                [
                    103.9888127062745,
                    1.3619190964195
                ],
                [
                    103.988759184556,
                    1.3617905101766
                ],
                [
                    103.9889101099344,
                    1.3617257141102
                ],
                [
                    103.9889345027614,
                    1.3617819182014
                ],
                [
                    103.9890207158976,
                    1.3617449936642
                ],
                [
                    103.9891236938633,
                    1.3617009859866
                ],
                [
                    103.9891041209248,
                    1.3616552180018
                ],
                [
                    103.9892001833983,
                    1.3616141860814
                ],
                [
                    103.9893886200829,
                    1.3615337148994
                ],
                [
                    103.9897144026338,
                    1.3613944829896
                ],
                [
                    103.9900540161692,
                    1.3612495091258
                ],
                [
                    103.9904699935033,
                    1.3610718019322
                ],
                [
                    103.9908884017377,
                    1.3608930888488
                ],
                [
                    103.9910508110244,
                    1.3608248140803
                ],
                [
                    103.9910888671875,
                    1.3608083007231
                ],
                [
                    103.9912446124544,
                    1.3607409061082
                ],
                [
                    103.9912912186807,
                    1.3607207044885
                ],
                [
                    103.9913763001908,
                    1.3606839056876
                ],
                [
                    103.9914193019787,
                    1.3607829858305
                ],
                [
                    103.9913335917874,
                    1.3608202037521
                ],
                [
                    103.9912913863289,
                    1.3608383935922
                ],
                [
                    103.9914477183648,
                    1.3612039926135
                ],
                [
                    103.9913371962258,
                    1.3612511856087
                ],
                [
                    103.9913636846565,
                    1.3613156882906
                ],
                [
                    103.9913990165349,
                    1.3613972072744
                ],
                [
                    103.9918118923755,
                    1.3612117882592
                ],
                [
                    103.991672199433,
                    1.3608891910259
                ],
                [
                    103.9917120997274,
                    1.3608722166359
                ],
                [
                    103.991792319437,
                    1.3608378068232
                ],
                [
                    103.9918349859283,
                    1.3608194912469
                ],
                [
                    103.9912666162932,
                    1.3595581054687
                ]
            ]
        ]
    },
  "properties": {
        "feature::id": 2305843009240255693,
        "line::hidden": [
            {
                "contour": 0,
                "segments": [
                    {
                        "from": 1,
                        "to": 5
                    },
                    {
                        "from": 37,
                        "to": 48
                    },
                    {
                        "from": 135,
                        "to": 136
                    },
                    {
                        "from": 137,
                        "to": 139
                    },
                    {
                        "from": 141,
                        "to": 144
                    },
                    {
                        "from": 145,
                        "to": 146
                    },
                    {
                        "from": 182,
                        "to": 185
                    }
                ]
            }
        ],
        "building": "yes",
        "name": "Terminal 1",
        "name:zh": "1\u53f7\u822a\u7ad9\u697c",
        "wikidata": "Q55721632",
        "wheelchair": "yes",
        "height": "30",
        "source": "Bing",
        "aeroway": "terminal",
        "id": "2305843009240255693",
        "record_type": "Feature",
        "geometry_type": "Polygon",
        "created": 1702269810.883975,
        "x_max": -1541245.4047403825,
        "x_min": -1541983.711042499,
        "y_max": 6187279.642187475,
        "y_min": 6187082.980064715,
        "z_max": 151117.59184690585,
        "z_min": 150216.3865382559,
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
                    "T287"
                ],
                "4": [
                    "T2878"
                ],
                "5": [
                    "T28786",
                    "T28782"
                ],
                "6": [
                    "T287863",
                    "T287828"
                ],
                "7": [
                    "T2878635",
                    "T2878289"
                ],
                "8": [
                    "T28786351",
                    "T28782895"
                ],
                "9": [
                    "T287863515",
                    "T287828959",
                    "T287828957",
                    "T287828956",
                    "T287828958",
                    "T287863513",
                    "T287828954",
                    "T287863518",
                    "T287863514"
                ],
                "10": [
                    "T2878635156",
                    "T2878635157",
                    "T2878635153",
                    "T2878289598",
                    "T2878289594",
                    "T2878289593",
                    "T2878289578",
                    "T2878289574",
                    "T2878289573",
                    "T2878289568",
                    "T2878289564",
                    "T2878289562",
                    "T2878289563",
                    "T2878289572",
                    "T2878289576",
                    "T2878289577",
                    "T2878289579",
                    "T2878289589",
                    "T2878289587",
                    "T2878289588",
                    "T2878635133",
                    "T2878635132",
                    "T2878289584",
                    "T2878289583",
                    "T2878289548",
                    "T2878289547",
                    "T2878289542",
                    "T2878289541",
                    "T2878289546",
                    "T2878289585",
                    "T2878635131",
                    "T2878635136",
                    "T2878635137",
                    "T2878635139",
                    "T2878635181",
                    "T2878635138",
                    "T2878635141",
                    "T2878635151",
                    "T2878289595"
                ],
                "11": [
                    "T28786351565",
                    "T28786351572",
                    "T28786351578",
                    "T28786351577",
                    "T28786351571",
                    "T28786351539",
                    "T28786351536",
                    "T28782895985",
                    "T28782895949",
                    "T28782895947",
                    "T28782895946",
                    "T28782895941",
                    "T28782895935",
                    "T28782895789",
                    "T28782895786",
                    "T28782895782",
                    "T28782895745",
                    "T28782895739",
                    "T28782895737",
                    "T28782895732",
                    "T28782895684",
                    "T28782895682",
                    "T28782895681",
                    "T28782895645",
                    "T28782895629",
                    "T28782895627",
                    "T28782895626",
                    "T28782895636",
                    "T28782895643",
                    "T28782895647",
                    "T28782895731",
                    "T28782895721",
                    "T28782895722",
                    "T28782895726",
                    "T28782895765",
                    "T28782895776",
                    "T28782895777",
                    "T28782895795",
                    "T28782895794",
                    "T28782895797",
                    "T28782895792",
                    "T28782895796",
                    "T28782895892",
                    "T28782895893",
                    "T28782895879",
                    "T28782895889",
                    "T28782895887",
                    "T28786351333",
                    "T28786351338",
                    "T28786351332",
                    "T28786351326",
                    "T28786351331",
                    "T28782895849",
                    "T28782895842",
                    "T28782895841",
                    "T28782895835",
                    "T28782895489",
                    "T28782895487",
                    "T28782895486",
                    "T28782895476",
                    "T28782895471",
                    "T28782895429",
                    "T28782895427",
                    "T28782895428",
                    "T28782895423",
                    "T28782895419",
                    "T28782895425",
                    "T28782895462",
                    "T28782895468",
                    "T28782895473",
                    "T28782895477",
                    "T28782895479",
                    "T28782895852",
                    "T28782895857",
                    "T28786351315",
                    "T28786351314",
                    "T28786351323",
                    "T28786351324",
                    "T28786351328",
                    "T28786351364",
                    "T28786351368",
                    "T28786351373",
                    "T28786351374",
                    "T28786351378",
                    "T28786351398",
                    "T28786351813",
                    "T28786351817",
                    "T28786351814",
                    "T28786351394",
                    "T28786351372",
                    "T28786351376",
                    "T28786351386",
                    "T28786351382",
                    "T28786351384",
                    "T28786351385",
                    "T28786351415",
                    "T28786351414",
                    "T28786351416",
                    "T28786351516",
                    "T28786351518",
                    "T28786351514",
                    "T28786351513",
                    "T28782895958",
                    "T28782895955",
                    "T28782895957",
                    "T28782895959"
                ]
            }
        }
    },
  "links": [ 
  		{"rel": "self",
          "type": "application/json",
          "title": "The JSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009240255693?f=json"},
          {"rel": "alternate",
          "type": "text/html",
          "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009240255693"},
          {"rel": "alternate",
          "type": "application/vnd.ogc.fg+json",
          "title": "The JSON-FG representation of the resources served from this OGC API Implementation Endpoint",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009240255693?f=fgjson"},
          {"rel": "alternate",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009240255693?f=geojson"},
          {"rel": "queryables",
          "type": "application/json",
          "title": "The JSON representation of the Queryables for this Collection",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/queryables?f=json"},
          {"rel": "queryables",
          "type": "text/html",
          "title": "The HTML representation of the Queryables for this Collection",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/queryables"},
          {"rel": "items",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the Features contained in this Collection",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items?f=json"},
          {"rel": "items",
          "type": "application/vnd.ogc.fg+json",
          "title": "The JSON-FG representation of the Features contained in this Collection",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items?f=fgjson"},
          {"rel": "items",
          "type": "text/html",
          "title": "The HTML representation of the Features contained in this Collection",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items"},
          {"rel": "collection",
          "type": "application/geo+json",
          "title": "The GeoJSON representation of the Collection that contains this Feature",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections?f=json"},
          {"rel": "collection",
          "type": "application/vnd.ogc.fg+json",
          "title": "The JSON-FG representation of the Collection that contains this Feature",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections?f=fgjson"},
          {"rel": "collection",
          "type": "text/html",
          "title": "The HTML representation of the Collection that contains this Feature",
          "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections"}
  ],
  "wasGeneratedBy": [
    "dggsOperations:store_data_task",
    {
      "activityType": "Registration",
      "id": "terranexusProcesses:store_data_task",
      "endedAtTime": "2019-01-01T19:03:15+01:00",
      "wasAssociatedWith": "agents:TerraNexus"      
    }
  ],
  "has_provenance": [  	
    {
      "provType": "Agent",
      "name": "agents:TerraNexus",
      "agentType": "softwareAgent",
      "actedOnBehalfOf": [
      	"agents:PangaeaInnovations",
      	"agents:CCM"
      ]
    },
    {
      "provType": "Agent",
      "name": "agents:PangaeaInnovations",
      "agentType": "organization"
    },
    {
      "provType": "Agent",
      "name": "agents:CCM",
      "agentType": "organization"
    },
    {
      "provType": "Agent",
      "name": "agents:some_user",
      "agentType": "Person",
      "actedOnBehalfOf": [
      	"agents:PangaeaInnovations",
      	"agents:CCM"
      ],
      "qualifiedDelegation": [
      	{
      	"id": "roles:Contractor",
      	"type": "Delegation",
      	"agent": "agents:CCM"
      	},
      	{
      	"id": "roles:Employee",
      	"type": "Delegation",
      	"agent": "agents:PangaeaInnovations"
      	}      	
      ]
    },
    
    
    
    {
      "provType": "Activity",
      "id": "terranexusProcesses:MapDataToZones",
      "activityType": "ogcapiProcess",
      "startedAtTime": "2023-10-05T05:03:10+01:00",
      "endedAtTime": "2023-10-05T05:03:15+01:00",
      "wasAssociatedWith": [
      	"agents:TerraNexus",
      	"agents:some_user"
      ],
      "generated": "terranexusJobs:someJobID?f=json"
     },
    {
      "provType": "Activity",
      "id": "dggsOperations:map_data",
      "activityType": "dggsOperation",
      "startedAtTime": "2023-10-05T05:03:10+01:00",
      "endedAtTime": "2023-10-05T05:03:15+01:00",
      "wasAssociatedWith": [
      	"agents:TerraNexus",
      	"agents:some_user"
      ],
      "wasInformedBy": "terranexusProcesses:MapDataToZones",
      "used": "terranexusJobs:someJobID?f=json",
      "generated": "terranexusTempData:osm_singapore_buildings"
     },
    {
      "provType": "Activity",
      "id": "dggsOperations:map_data_execution",
      "activityType": "dggsOperation",
      "startedAtTime": "2023-10-05T05:03:10+01:00",
      "endedAtTime": "2023-10-05T05:03:15+01:00",
      "wasAssociatedWith": [
      	"agents:TerraNexus",
      	"agents:some_user"
      ],
      "wasInformedBy": "dggsOperations:map_data",
      "used": "terranexusJobs:someJobID?f=json"
     },
    {
      "provType": "Activity",
      "id": "dggsOperations:processData_task",
      "activityType": "dggsOperation",
      "startedAtTime": "2023-10-05T05:03:10+01:00",
      "endedAtTime": "2023-10-05T05:03:15+01:00",
      "wasAssociatedWith": [
      	"agents:TerraNexus",
      	"agents:some_user"
      ],
      "wasInformedBy": "dggsOperations:map_data_execution",
      "used": "terranexusJobs:someJobID?f=json"
     },
    {
      "provType": "Activity",
      "id": "dggsOperations:store_data_task",
      "activityType": "dggsOperation",
      "startedAtTime": "2023-10-05T05:03:10+01:00",
      "endedAtTime": "2023-10-05T05:03:15+01:00",
      "wasAssociatedWith": [
      	"agents:TerraNexus",
      	"agents:some_user"
      ],
      "wasInformedBy": "terranexusProcesses:processData_task",
      "generated": "terranexusCollections:osm_singapore_buildings",
      "used": [
      		"terranexusJobs:someJobID?f=json",
      		"terranexusTempData:osm_singapore_buildings"
      ]
     },
    {
      "provType": "Activity",
      "id": "dggsOperations:map_featureData_task",
      "activityType": "dggsOperation",
      "startedAtTime": "2023-10-05T05:03:10+01:00",
      "endedAtTime": "2023-10-05T05:03:15+01:00",
      "wasAssociatedWith": [
      	"agents:TerraNexus",
      	"agents:some_user"
      ],
      "wasInformedBy": "terranexusProcesses:store_data_task",
      "generated": "terranexusCollections:osm_singapore_buildings",
      "used": [
      		"terranexusJobs:someJobID?f=json",
      		"terranexusTempData:osm_singapore_buildings"
      ]
     },
     
     
     
  	{
      "id": "terranexusJobs:someJobID",
      "provType": "Entity",
      "featureType": "ogcapiJob",
      "wasGeneratedBy": "terranexusProcesses:MapDataToZones",
      "generatedAtTime": "2023-10-05T05:03:15+01:00",
      "wasInvalidatedBy": "dggsOperations:ogcapiJobsCleanup",
      "invalidatedAtTime": "2023-10-05T05:03:15+01:00"
    },
  	{
      "id": "terranexusTempData:osm_singapore_buildings",
      "provType": "Entity",
      "featureType": "rawData",
      "wasGeneratedBy": "dggsOperations:map_data",
      "generatedAtTime": "2023-10-05T05:03:15+01:00",
      "wasDerivedFrom": "terranexusJobs:someJobID",
      "wasInvalidatedBy": "dggsOperations:tmpDataCleanup",
      "invalidatedAtTime": "2023-10-05T05:03:15+01:00"
    },
  	{
      "id": "terranexusCollections:osm_singapore_buildings",
      "provType": "Entity",
      "featureType": "FeatureCollection",
      "wasGeneratedBy": "dggsOperations:store_data_task",
      "generatedAtTime": "2023-10-05T05:03:15+01:00",
      "wasDerivedFrom": "terranexusTempData:collectionID",
      "wasInfluencedBy": [
      	"dggsOperations:processData_task",
      	"dggsOperations:store_data_task",
      	"dggsOperations:map_featureData_task"
      ],
      "properties": {
      	"type": "Collection",
      	"hadmember": "terranexusCollections:osm_singapore_buildings/items/2305843009240255693"
      }
    },
    {
      "id": "terranexusCollections:osm_singapore_buildings/items/2305843009240255693",
      "provType": "Entity",
      "featureType": "Feature",
      "wasGeneratedBy": "dggsOperations:store_data_task",
      "generatedAtTime": "2023-10-05T05:03:15+01:00",
      "specializationOf": "terranexusTempData:osm_singapore_buildings",
      "wasInfluencedBy": [
      	"dggsOperations:processData_task",
      	"dggsOperations:store_data_task",
      	"dggsOperations:map_featureData_task"
      ]
    }
  ]
  
}
```

<blockquote class="lang-specific json">
  <p class="example-links">
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/bbr/template/json-fg-feature_with-prov/example_2_2.json">Open in new window</a>
    <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=json&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Ftests%2Fbbr%2Ftemplate%2Fjson-fg-feature_with-prov%2Fexample_2_2.json&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on JSON Viewer</a></p>
</blockquote>




```jsonld
{
  "id": "osm_singapore_buildings",
  "type": "Feature",
  "time": {
    "date": "2023-12-10"
  },
  "place": {
    "type": "null"
  },
  "geometry": {
    "type": "Polygon",
    "coordinates": [
      [
        [
          103.9912666162932,
          1.3595581054687
        ],
        [
          103.9910888671875,
          1.3591636709406
        ],
        [
          103.9908972032733,
          1.3587383053019
        ],
        [
          103.9910888671875,
          1.3586563252853
        ],
        [
          103.9911366050398,
          1.3586359141052
        ],
        [
          103.9911444845097,
          1.3586473980135
        ],
        [
          103.9914361925445,
          1.359266984203
        ],
        [
          103.9915527081101,
          1.3595581054687
        ],
        [
          103.9916911017784,
          1.3599040058152
        ],
        [
          103.9919875039655,
          1.3605287891018
        ],
        [
          103.9920041011468,
          1.3605675996823
        ],
        [
          103.992068813389,
          1.3607173096105
        ],
        [
          103.9921689832457,
          1.3609440120186
        ],
        [
          103.9922510051745,
          1.3611352987242
        ],
        [
          103.99225980671,
          1.3611557099042
        ],
        [
          103.9924025173219,
          1.3614882822112
        ],
        [
          103.9923205792173,
          1.3615234045292
        ],
        [
          103.9924075048587,
          1.3617263847034
        ],
        [
          103.9924463154392,
          1.3618164118383
        ],
        [
          103.9924668942675,
          1.3618703107654
        ],
        [
          103.9926443499887,
          1.3623046875
        ],
        [
          103.9926928003462,
          1.3624232986693
        ],
        [
          103.9927059188253,
          1.3624520922641
        ],
        [
          103.9927205880512,
          1.3624878013512
        ],
        [
          103.9929078092856,
          1.3629396135085
        ],
        [
          103.992952780941,
          1.3630425914743
        ],
        [
          103.9929729825607,
          1.3630917962491
        ],
        [
          103.9929858076553,
          1.3631220986786
        ],
        [
          103.9931648979474,
          1.3635009838273
        ],
        [
          103.9931205968852,
          1.36351841925
        ],
        [
          103.9931648979474,
          1.363609619923
        ],
        [
          103.9932436926464,
          1.3636649019486
        ],
        [
          103.9932902988727,
          1.3636975933662
        ],
        [
          103.993546591205,
          1.363888419039
        ],
        [
          103.9935737083168,
          1.3639053096048
        ],
        [
          103.9935864914994,
          1.3639152008543
        ],
        [
          103.9938354492188,
          1.3641061103512
        ],
        [
          103.9939587964525,
          1.3642007059022
        ],
        [
          103.9939823929501,
          1.364220991346
        ],
        [
          103.9940919930235,
          1.3643046059335
        ],
        [
          103.9941722127331,
          1.3643657137374
        ],
        [
          103.994470794348,
          1.364593296299
        ],
        [
          103.9945034019416,
          1.3646181920709
        ],
        [
          103.9944417911928,
          1.3646989147254
        ],
        [
          103.9945129998065,
          1.3647531908612
        ],
        [
          103.9943717980293,
          1.3649384003161
        ],
        [
          103.9943062056336,
          1.3648883992118
        ],
        [
          103.9942663053391,
          1.3649407054801
        ],
        [
          103.9942450978297,
          1.3649246112437
        ],
        [
          103.9938492802032,
          1.3646228023991
        ],
        [
          103.9938354492188,
          1.3646105640735
        ],
        [
          103.9938287013749,
          1.364604612559
        ],
        [
          103.9938134034679,
          1.3645930867386
        ],
        [
          103.9934374940765,
          1.364311102305
        ],
        [
          103.9934060181089,
          1.364284488138
        ],
        [
          103.9933897981363,
          1.3642720821641
        ],
        [
          103.9930687097376,
          1.3640297884645
        ],
        [
          103.9930174093591,
          1.3639910197961
        ],
        [
          103.993023612346,
          1.3639082853621
        ],
        [
          103.9929583971589,
          1.3638972205746
        ],
        [
          103.9929052945612,
          1.3638760968893
        ],
        [
          103.9928822848326,
          1.3638564820387
        ],
        [
          103.9928664839807,
          1.3638468841737
        ],
        [
          103.9928114953397,
          1.3637832197334
        ],
        [
          103.9927492139977,
          1.3636418083958
        ],
        [
          103.9927806899653,
          1.3636283965321
        ],
        [
          103.9927707148917,
          1.3636048838586
        ],
        [
          103.9927609074664,
          1.3635814969214
        ],
        [
          103.9925194939203,
          1.3630094809358
        ],
        [
          103.9925065850015,
          1.3629782983528
        ],
        [
          103.992495520214,
          1.3629526062515
        ],
        [
          103.9922808046591,
          1.3624520922641
        ],
        [
          103.9922494963398,
          1.3623792071675
        ],
        [
          103.9922352881468,
          1.3623372950936
        ],
        [
          103.9922227145246,
          1.3623072860486
        ],
        [
          103.9922216248106,
          1.3623046875
        ],
        [
          103.9920831892303,
          1.3619721151931
        ],
        [
          103.9920432889359,
          1.3618789027406
        ],
        [
          103.9920263145459,
          1.3618392958307
        ],
        [
          103.9918421109809,
          1.3619183000901
        ],
        [
          103.9918048930592,
          1.3619343105023
        ],
        [
          103.9915833877483,
          1.3618442833675
        ],
        [
          103.9915551809225,
          1.3618566055172
        ],
        [
          103.9915224056806,
          1.3618708137103
        ],
        [
          103.9915934885581,
          1.3620369112594
        ],
        [
          103.9916304969194,
          1.3621232920439
        ],
        [
          103.9914364021049,
          1.3622056073571
        ],
        [
          103.9912027422925,
          1.3623046875
        ],
        [
          103.991091381912,
          1.3623518804953
        ],
        [
          103.9910888671875,
          1.3623529702092
        ],
        [
          103.9910037018532,
          1.3623888888566
        ],
        [
          103.9909324094154,
          1.3624194008465
        ],
        [
          103.9905380167994,
          1.3625885160649
        ],
        [
          103.9905093908528,
          1.3626005029181
        ],
        [
          103.9903816009393,
          1.3626536893399
        ],
        [
          103.9900655000775,
          1.3627852932522
        ],
        [
          103.9898450006563,
          1.3628816071982
        ],
        [
          103.9898193923791,
          1.3628207089547
        ],
        [
          103.9897234137297,
          1.3625922043274
        ],
        [
          103.9896701015716,
          1.3626150044957
        ],
        [
          103.9896853994787,
          1.3626482826824
        ],
        [
          103.989591516433,
          1.3628873072402
        ],
        [
          103.9895605014982,
          1.3628987073243
        ],
        [
          103.9893791060421,
          1.3629731012556
        ],
        [
          103.9893894164123,
          1.3629954823031
        ],
        [
          103.9894058040332,
          1.3630371009926
        ],
        [
          103.9894286042014,
          1.3630925087544
        ],
        [
          103.9894353939574,
          1.3631088963753
        ],
        [
          103.9896825075455,
          1.363695204378
        ],
        [
          103.9896962966179,
          1.3637265126973
        ],
        [
          103.9897024996048,
          1.3637408047145
        ],
        [
          103.9899053121308,
          1.3642119802501
        ],
        [
          103.9899478109738,
          1.3643108927446
        ],
        [
          103.9899670067036,
          1.3643510025994
        ],
        [
          103.9900227078499,
          1.364328118607
        ],
        [
          103.9900305873198,
          1.364347398161
        ],
        [
          103.9901452168421,
          1.3646261134529
        ],
        [
          103.9901590059145,
          1.3646635828471
        ],
        [
          103.9901667177361,
          1.3646847903565
        ],
        [
          103.990253391905,
          1.3649034037343
        ],
        [
          103.9902540205862,
          1.3649637152087
        ],
        [
          103.9902559904536,
          1.3650150155873
        ],
        [
          103.9902520088066,
          1.3650441863908
        ],
        [
          103.9902484462803,
          1.3650512695313
        ],
        [
          103.9902198203338,
          1.3651084795122
        ],
        [
          103.9901799200394,
          1.3651483798066
        ],
        [
          103.9901419896124,
          1.3651863102336
        ],
        [
          103.9901362895704,
          1.3652189178271
        ],
        [
          103.9901466837647,
          1.3652399157762
        ],
        [
          103.9902010856367,
          1.3652418856437
        ],
        [
          103.9901504977635,
          1.3656856925949
        ],
        [
          103.9901483183356,
          1.3657048045006
        ],
        [
          103.9901041010976,
          1.3660813006611
        ],
        [
          103.9901001194506,
          1.3661080824763
        ],
        [
          103.990086791411,
          1.3662137847269
        ],
        [
          103.9900693140762,
          1.3663517173623
        ],
        [
          103.9900227078499,
          1.3667388172775
        ],
        [
          103.9899870825871,
          1.3667368054979
        ],
        [
          103.9899797898862,
          1.3667783822753
        ],
        [
          103.9898825119625,
          1.366788399261
        ],
        [
          103.9898134827767,
          1.3667858007124
        ],
        [
          103.9897525007091,
          1.3667811065601
        ],
        [
          103.9896978892767,
          1.3667634196649
        ],
        [
          103.9896760111741,
          1.36675160046
        ],
        [
          103.9896786935468,
          1.3667140053297
        ],
        [
          103.989576218526,
          1.3667099817706
        ],
        [
          103.9895797810522,
          1.3666894867664
        ],
        [
          103.9896455830084,
          1.3661579997564
        ],
        [
          103.9896683831766,
          1.3659921117677
        ],
        [
          103.9896701853958,
          1.3659771910693
        ],
        [
          103.9897216115106,
          1.3655550945724
        ],
        [
          103.9897618890136,
          1.3655599982851
        ],
        [
          103.9897858208079,
          1.3653122979279
        ],
        [
          103.9898109680522,
          1.3650512695313
        ],
        [
          103.9898165842702,
          1.3649930955726
        ],
        [
          103.9897950833762,
          1.3649373944263
        ],
        [
          103.9897783185466,
          1.3648982904613
        ],
        [
          103.9895100812732,
          1.3642732976143
        ],
        [
          103.9894939870368,
          1.3642331877595
        ],
        [
          103.9894918914331,
          1.3642279906623
        ],
        [
          103.9892855163809,
          1.3637369068916
        ],
        [
          103.9892461190314,
          1.3636431076701
        ],
        [
          103.9892348865956,
          1.3636183795464
        ],
        [
          103.9892078113958,
          1.3636296958064
        ],
        [
          103.9891988002999,
          1.3636081949125
        ],
        [
          103.9890596103022,
          1.3632754968693
        ],
        [
          103.9890477072732,
          1.3632534930305
        ],
        [
          103.9889964068947,
          1.3631321994884
        ],
        [
          103.9889313174438,
          1.3629782145287
        ],
        [
          103.9888570911608,
          1.3630094809358
        ],
        [
          103.9888295130162,
          1.362944391485
        ],
        [
          103.9888202923599,
          1.3629225133824
        ],
        [
          103.9888523970085,
          1.3629088919583
        ],
        [
          103.9886655948949,
          1.3624671806108
        ],
        [
          103.9886150070216,
          1.3623512099021
        ],
        [
          103.9885968171815,
          1.3623085853229
        ],
        [
          103.9885951406985,
          1.3623046875
        ],
        [
          103.9885862972509,
          1.3622841086717
        ],
        [
          103.9884893965359,
          1.3620571967032
        ],
        [
          103.9883950105453,
          1.3618351046233
        ],
        [
          103.9883422851562,
          1.3617099551704
        ],
        [
          103.9883158805496,
          1.3616472966198
        ],
        [
          103.9880514153629,
          1.3610370987349
        ],
        [
          103.987782297936,
          1.3603996160899
        ],
        [
          103.9876483888596,
          1.3600644871464
        ],
        [
          103.9878664154684,
          1.3599833872833
        ],
        [
          103.9883422851562,
          1.3610924645846
        ],
        [
          103.9887147996697,
          1.3619605893727
        ],
        [
          103.9888127062745,
          1.3619190964195
        ],
        [
          103.988759184556,
          1.3617905101766
        ],
        [
          103.9889101099344,
          1.3617257141102
        ],
        [
          103.9889345027614,
          1.3617819182014
        ],
        [
          103.9890207158976,
          1.3617449936642
        ],
        [
          103.9891236938633,
          1.3617009859866
        ],
        [
          103.9891041209248,
          1.3616552180018
        ],
        [
          103.9892001833983,
          1.3616141860814
        ],
        [
          103.9893886200829,
          1.3615337148994
        ],
        [
          103.9897144026338,
          1.3613944829896
        ],
        [
          103.9900540161692,
          1.3612495091258
        ],
        [
          103.9904699935033,
          1.3610718019322
        ],
        [
          103.9908884017377,
          1.3608930888488
        ],
        [
          103.9910508110244,
          1.3608248140803
        ],
        [
          103.9910888671875,
          1.3608083007231
        ],
        [
          103.9912446124544,
          1.3607409061082
        ],
        [
          103.9912912186807,
          1.3607207044885
        ],
        [
          103.9913763001908,
          1.3606839056876
        ],
        [
          103.9914193019787,
          1.3607829858305
        ],
        [
          103.9913335917874,
          1.3608202037521
        ],
        [
          103.9912913863289,
          1.3608383935922
        ],
        [
          103.9914477183648,
          1.3612039926135
        ],
        [
          103.9913371962258,
          1.3612511856087
        ],
        [
          103.9913636846565,
          1.3613156882906
        ],
        [
          103.9913990165349,
          1.3613972072744
        ],
        [
          103.9918118923755,
          1.3612117882592
        ],
        [
          103.991672199433,
          1.3608891910259
        ],
        [
          103.9917120997274,
          1.3608722166359
        ],
        [
          103.991792319437,
          1.3608378068232
        ],
        [
          103.9918349859283,
          1.3608194912469
        ],
        [
          103.9912666162932,
          1.3595581054687
        ]
      ]
    ]
  },
  "properties": {
    "feature::id": 2305843009240255693,
    "line::hidden": [
      {
        "contour": 0,
        "segments": [
          {
            "from": 1,
            "to": 5
          },
          {
            "from": 37,
            "to": 48
          },
          {
            "from": 135,
            "to": 136
          },
          {
            "from": 137,
            "to": 139
          },
          {
            "from": 141,
            "to": 144
          },
          {
            "from": 145,
            "to": 146
          },
          {
            "from": 182,
            "to": 185
          }
        ]
      }
    ],
    "building": "yes",
    "name": "Terminal 1",
    "name:zh": "1\u53f7\u822a\u7ad9\u697c",
    "wikidata": "Q55721632",
    "wheelchair": "yes",
    "height": "30",
    "source": "Bing",
    "aeroway": "terminal",
    "id": "2305843009240255693",
    "record_type": "Feature",
    "geometry_type": "Polygon",
    "created": 1702269810.883975,
    "x_max": -1541245.4047403825,
    "x_min": -1541983.711042499,
    "y_max": 6187279.642187475,
    "y_min": 6187082.980064715,
    "z_max": 151117.59184690585,
    "z_min": 150216.3865382559,
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
          "T287"
        ],
        "4": [
          "T2878"
        ],
        "5": [
          "T28786",
          "T28782"
        ],
        "6": [
          "T287863",
          "T287828"
        ],
        "7": [
          "T2878635",
          "T2878289"
        ],
        "8": [
          "T28786351",
          "T28782895"
        ],
        "9": [
          "T287863515",
          "T287828959",
          "T287828957",
          "T287828956",
          "T287828958",
          "T287863513",
          "T287828954",
          "T287863518",
          "T287863514"
        ],
        "10": [
          "T2878635156",
          "T2878635157",
          "T2878635153",
          "T2878289598",
          "T2878289594",
          "T2878289593",
          "T2878289578",
          "T2878289574",
          "T2878289573",
          "T2878289568",
          "T2878289564",
          "T2878289562",
          "T2878289563",
          "T2878289572",
          "T2878289576",
          "T2878289577",
          "T2878289579",
          "T2878289589",
          "T2878289587",
          "T2878289588",
          "T2878635133",
          "T2878635132",
          "T2878289584",
          "T2878289583",
          "T2878289548",
          "T2878289547",
          "T2878289542",
          "T2878289541",
          "T2878289546",
          "T2878289585",
          "T2878635131",
          "T2878635136",
          "T2878635137",
          "T2878635139",
          "T2878635181",
          "T2878635138",
          "T2878635141",
          "T2878635151",
          "T2878289595"
        ],
        "11": [
          "T28786351565",
          "T28786351572",
          "T28786351578",
          "T28786351577",
          "T28786351571",
          "T28786351539",
          "T28786351536",
          "T28782895985",
          "T28782895949",
          "T28782895947",
          "T28782895946",
          "T28782895941",
          "T28782895935",
          "T28782895789",
          "T28782895786",
          "T28782895782",
          "T28782895745",
          "T28782895739",
          "T28782895737",
          "T28782895732",
          "T28782895684",
          "T28782895682",
          "T28782895681",
          "T28782895645",
          "T28782895629",
          "T28782895627",
          "T28782895626",
          "T28782895636",
          "T28782895643",
          "T28782895647",
          "T28782895731",
          "T28782895721",
          "T28782895722",
          "T28782895726",
          "T28782895765",
          "T28782895776",
          "T28782895777",
          "T28782895795",
          "T28782895794",
          "T28782895797",
          "T28782895792",
          "T28782895796",
          "T28782895892",
          "T28782895893",
          "T28782895879",
          "T28782895889",
          "T28782895887",
          "T28786351333",
          "T28786351338",
          "T28786351332",
          "T28786351326",
          "T28786351331",
          "T28782895849",
          "T28782895842",
          "T28782895841",
          "T28782895835",
          "T28782895489",
          "T28782895487",
          "T28782895486",
          "T28782895476",
          "T28782895471",
          "T28782895429",
          "T28782895427",
          "T28782895428",
          "T28782895423",
          "T28782895419",
          "T28782895425",
          "T28782895462",
          "T28782895468",
          "T28782895473",
          "T28782895477",
          "T28782895479",
          "T28782895852",
          "T28782895857",
          "T28786351315",
          "T28786351314",
          "T28786351323",
          "T28786351324",
          "T28786351328",
          "T28786351364",
          "T28786351368",
          "T28786351373",
          "T28786351374",
          "T28786351378",
          "T28786351398",
          "T28786351813",
          "T28786351817",
          "T28786351814",
          "T28786351394",
          "T28786351372",
          "T28786351376",
          "T28786351386",
          "T28786351382",
          "T28786351384",
          "T28786351385",
          "T28786351415",
          "T28786351414",
          "T28786351416",
          "T28786351516",
          "T28786351518",
          "T28786351514",
          "T28786351513",
          "T28782895958",
          "T28782895955",
          "T28782895957",
          "T28782895959"
        ]
      }
    }
  },
  "links": [
    {
      "rel": "self",
      "type": "application/json",
      "title": "The JSON representation of the resources served from this OGC API Implementation Endpoint",
      "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009240255693?f=json"
    },
    {
      "rel": "alternate",
      "type": "text/html",
      "title": "The HTML representation of the resources served from this OGC API Implementation Endpoint",
      "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009240255693"
    },
    {
      "rel": "alternate",
      "type": "application/vnd.ogc.fg+json",
      "title": "The JSON-FG representation of the resources served from this OGC API Implementation Endpoint",
      "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009240255693?f=fgjson"
    },
    {
      "rel": "alternate",
      "type": "application/geo+json",
      "title": "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint",
      "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009240255693?f=geojson"
    },
    {
      "rel": "queryables",
      "type": "application/json",
      "title": "The JSON representation of the Queryables for this Collection",
      "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/queryables?f=json"
    },
    {
      "rel": "queryables",
      "type": "text/html",
      "title": "The HTML representation of the Queryables for this Collection",
      "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/queryables"
    },
    {
      "rel": "items",
      "type": "application/geo+json",
      "title": "The GeoJSON representation of the Features contained in this Collection",
      "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items?f=json"
    },
    {
      "rel": "items",
      "type": "application/vnd.ogc.fg+json",
      "title": "The JSON-FG representation of the Features contained in this Collection",
      "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items?f=fgjson"
    },
    {
      "rel": "items",
      "type": "text/html",
      "title": "The HTML representation of the Features contained in this Collection",
      "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items"
    },
    {
      "rel": "collection",
      "type": "application/geo+json",
      "title": "The GeoJSON representation of the Collection that contains this Feature",
      "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections?f=json"
    },
    {
      "rel": "collection",
      "type": "application/vnd.ogc.fg+json",
      "title": "The JSON-FG representation of the Collection that contains this Feature",
      "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections?f=fgjson"
    },
    {
      "rel": "collection",
      "type": "text/html",
      "title": "The HTML representation of the Collection that contains this Feature",
      "href": "https://terranexus.pangaeainnovations.com/ogcapi/collections"
    }
  ],
  "wasGeneratedBy": [
    "dggsOperations:store_data_task",
    {
      "activityType": "Registration",
      "id": "terranexusProcesses:store_data_task",
      "endedAtTime": "2019-01-01T19:03:15+01:00",
      "wasAssociatedWith": "agents:TerraNexus"
    }
  ],
  "has_provenance": [
    {
      "provType": "Agent",
      "name": "agents:TerraNexus",
      "agentType": "softwareAgent",
      "actedOnBehalfOf": [
        "agents:PangaeaInnovations",
        "agents:CCM"
      ]
    },
    {
      "provType": "Agent",
      "name": "agents:PangaeaInnovations",
      "agentType": "organization"
    },
    {
      "provType": "Agent",
      "name": "agents:CCM",
      "agentType": "organization"
    },
    {
      "provType": "Agent",
      "name": "agents:some_user",
      "agentType": "Person",
      "actedOnBehalfOf": [
        "agents:PangaeaInnovations",
        "agents:CCM"
      ],
      "qualifiedDelegation": [
        {
          "id": "roles:Contractor",
          "type": "Delegation",
          "agent": "agents:CCM"
        },
        {
          "id": "roles:Employee",
          "type": "Delegation",
          "agent": "agents:PangaeaInnovations"
        }
      ]
    },
    {
      "provType": "Activity",
      "id": "terranexusProcesses:MapDataToZones",
      "activityType": "ogcapiProcess",
      "startedAtTime": "2023-10-05T05:03:10+01:00",
      "endedAtTime": "2023-10-05T05:03:15+01:00",
      "wasAssociatedWith": [
        "agents:TerraNexus",
        "agents:some_user"
      ],
      "generated": "terranexusJobs:someJobID?f=json"
    },
    {
      "provType": "Activity",
      "id": "dggsOperations:map_data",
      "activityType": "dggsOperation",
      "startedAtTime": "2023-10-05T05:03:10+01:00",
      "endedAtTime": "2023-10-05T05:03:15+01:00",
      "wasAssociatedWith": [
        "agents:TerraNexus",
        "agents:some_user"
      ],
      "wasInformedBy": "terranexusProcesses:MapDataToZones",
      "used": "terranexusJobs:someJobID?f=json",
      "generated": "terranexusTempData:osm_singapore_buildings"
    },
    {
      "provType": "Activity",
      "id": "dggsOperations:map_data_execution",
      "activityType": "dggsOperation",
      "startedAtTime": "2023-10-05T05:03:10+01:00",
      "endedAtTime": "2023-10-05T05:03:15+01:00",
      "wasAssociatedWith": [
        "agents:TerraNexus",
        "agents:some_user"
      ],
      "wasInformedBy": "dggsOperations:map_data",
      "used": "terranexusJobs:someJobID?f=json"
    },
    {
      "provType": "Activity",
      "id": "dggsOperations:processData_task",
      "activityType": "dggsOperation",
      "startedAtTime": "2023-10-05T05:03:10+01:00",
      "endedAtTime": "2023-10-05T05:03:15+01:00",
      "wasAssociatedWith": [
        "agents:TerraNexus",
        "agents:some_user"
      ],
      "wasInformedBy": "dggsOperations:map_data_execution",
      "used": "terranexusJobs:someJobID?f=json"
    },
    {
      "provType": "Activity",
      "id": "dggsOperations:store_data_task",
      "activityType": "dggsOperation",
      "startedAtTime": "2023-10-05T05:03:10+01:00",
      "endedAtTime": "2023-10-05T05:03:15+01:00",
      "wasAssociatedWith": [
        "agents:TerraNexus",
        "agents:some_user"
      ],
      "wasInformedBy": "terranexusProcesses:processData_task",
      "generated": "terranexusCollections:osm_singapore_buildings",
      "used": [
        "terranexusJobs:someJobID?f=json",
        "terranexusTempData:osm_singapore_buildings"
      ]
    },
    {
      "provType": "Activity",
      "id": "dggsOperations:map_featureData_task",
      "activityType": "dggsOperation",
      "startedAtTime": "2023-10-05T05:03:10+01:00",
      "endedAtTime": "2023-10-05T05:03:15+01:00",
      "wasAssociatedWith": [
        "agents:TerraNexus",
        "agents:some_user"
      ],
      "wasInformedBy": "terranexusProcesses:store_data_task",
      "generated": "terranexusCollections:osm_singapore_buildings",
      "used": [
        "terranexusJobs:someJobID?f=json",
        "terranexusTempData:osm_singapore_buildings"
      ]
    },
    {
      "id": "terranexusJobs:someJobID",
      "provType": "Entity",
      "featureType": "ogcapiJob",
      "wasGeneratedBy": "terranexusProcesses:MapDataToZones",
      "generatedAtTime": "2023-10-05T05:03:15+01:00",
      "wasInvalidatedBy": "dggsOperations:ogcapiJobsCleanup",
      "invalidatedAtTime": "2023-10-05T05:03:15+01:00"
    },
    {
      "id": "terranexusTempData:osm_singapore_buildings",
      "provType": "Entity",
      "featureType": "rawData",
      "wasGeneratedBy": "dggsOperations:map_data",
      "generatedAtTime": "2023-10-05T05:03:15+01:00",
      "wasDerivedFrom": "terranexusJobs:someJobID",
      "wasInvalidatedBy": "dggsOperations:tmpDataCleanup",
      "invalidatedAtTime": "2023-10-05T05:03:15+01:00"
    },
    {
      "id": "terranexusCollections:osm_singapore_buildings",
      "provType": "Entity",
      "featureType": "FeatureCollection",
      "wasGeneratedBy": "dggsOperations:store_data_task",
      "generatedAtTime": "2023-10-05T05:03:15+01:00",
      "wasDerivedFrom": "terranexusTempData:collectionID",
      "wasInfluencedBy": [
        "dggsOperations:processData_task",
        "dggsOperations:store_data_task",
        "dggsOperations:map_featureData_task"
      ],
      "properties": {
        "type": "Collection",
        "hadmember": "terranexusCollections:osm_singapore_buildings/items/2305843009240255693"
      }
    },
    {
      "id": "terranexusCollections:osm_singapore_buildings/items/2305843009240255693",
      "provType": "Entity",
      "featureType": "Feature",
      "wasGeneratedBy": "dggsOperations:store_data_task",
      "generatedAtTime": "2023-10-05T05:03:15+01:00",
      "specializationOf": "terranexusTempData:osm_singapore_buildings",
      "wasInfluencedBy": [
        "dggsOperations:processData_task",
        "dggsOperations:store_data_task",
        "dggsOperations:map_featureData_task"
      ]
    }
  ],
  "@context": "https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/json-fg-feature_with-prov/context.jsonld"
}
```

<blockquote class="lang-specific jsonld">
  <p class="example-links">
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/bbr/template/json-fg-feature_with-prov/example_2_2.jsonld">Open in new window</a>
    <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Ftests%2Fbbr%2Ftemplate%2Fjson-fg-feature_with-prov%2Fexample_2_2.jsonld">View on JSON-LD Playground</a>
</blockquote>




```turtle
@prefix agents: <https://someAgentRegister.eg/> .
@prefix dct: <http://purl.org/dc/terms/> .
@prefix geojson: <https://purl.org/geojson/vocab#> .
@prefix ns1: <http://www.iana.org/assignments/> .
@prefix ns2: <name:> .
@prefix ns3: <line::> .
@prefix ns4: <feature::> .
@prefix oa: <http://www.w3.org/ns/oa#> .
@prefix prov: <http://www.w3.org/ns/prov#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix roles: <https://someRolesRegister.eg/> .
@prefix terranexusCollections: <https://terranexus.pangaeainnovations.com/ogcapi/collections/> .
@prefix terranexusJobs: <https://terranexus.pangaeainnovations.com/ogcapi/jobs/> .
@prefix terranexusProcesses: <https://terranexus.pangaeainnovations.com/ogcapi/processes/> .
@prefix terranexusTempData: <https://someTempDataRegister.eg/> .
@prefix xsd: <http://www.w3.org/2001/XMLSchema#> .

<file:///github/workspace/osm_singapore_buildings> a geojson:Feature ;
    ns4:id 2305843009240255693 ;
    rdfs:seeAlso [ rdfs:label "The HTML representation of the Queryables for this Collection" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/queryables> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/queryables> ],
        [ rdfs:label "The JSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/json" ;
            ns1:relation <http://www.iana.org/assignments/relation/self> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009240255693?f=json> ],
        [ rdfs:label "The GeoJSON representation of the Features contained in this Collection" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/items> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items?f=json> ],
        [ rdfs:label "The HTML representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009240255693> ],
        [ rdfs:label "The JSON-FG representation of the Collection that contains this Feature" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections?f=fgjson> ],
        [ rdfs:label "The GeoJSON representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009240255693?f=geojson> ],
        [ rdfs:label "The JSON-FG representation of the resources served from this OGC API Implementation Endpoint" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/alternate> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009240255693?f=fgjson> ],
        [ rdfs:label "The HTML representation of the Features contained in this Collection" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/items> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items> ],
        [ rdfs:label "The GeoJSON representation of the Collection that contains this Feature" ;
            dct:type "application/geo+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections?f=json> ],
        [ rdfs:label "The HTML representation of the Collection that contains this Feature" ;
            dct:type "text/html" ;
            ns1:relation <http://www.iana.org/assignments/relation/collection> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections> ],
        [ rdfs:label "The JSON representation of the Queryables for this Collection" ;
            dct:type "application/json" ;
            ns1:relation <http://www.iana.org/assignments/relation/queryables> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/queryables?f=json> ],
        [ rdfs:label "The JSON-FG representation of the Features contained in this Collection" ;
            dct:type "application/vnd.ogc.fg+json" ;
            ns1:relation <http://www.iana.org/assignments/relation/items> ;
            oa:hasTarget <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items?f=fgjson> ] ;
    prov:has_provenance [ a prov:Agent,
                prov:Person ;
            rdfs:label "agents:some_user" ;
            prov:actedOnBehalfOf agents:CCM,
                agents:PangaeaInnovations ;
            prov:qualifiedDelegation roles:Contractor,
                roles:Employee ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:PangaeaInnovations" ],
        [ a <file:///github/workspace/organization>,
                prov:Agent ;
            rdfs:label "agents:CCM" ],
        [ a <file:///github/workspace/softwareAgent>,
                prov:Agent ;
            rdfs:label "agents:TerraNexus" ;
            prov:actedOnBehalfOf agents:CCM,
                agents:PangaeaInnovations ],
        <dggsoperations:map_data>,
        <dggsoperations:map_data_execution>,
        <dggsoperations:map_featureData_task>,
        <dggsoperations:processData_task>,
        <dggsoperations:store_data_task>,
        terranexusTempData:osm_singapore_buildings,
        terranexusCollections:osm_singapore_buildings,
        <https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009240255693>,
        terranexusJobs:someJobID,
        terranexusProcesses:MapDataToZones ;
    prov:wasGeneratedBy <dggsoperations:store_data_task>,
        terranexusProcesses:store_data_task ;
    geojson:geometry [ a geojson:Polygon ;
            geojson:coordinates ( "[[103.9912666162932, 1.3595581054687], [103.9910888671875, 1.3591636709406], [103.9908972032733, 1.3587383053019], [103.9910888671875, 1.3586563252853], [103.9911366050398, 1.3586359141052], [103.9911444845097, 1.3586473980135], [103.9914361925445, 1.359266984203], [103.9915527081101, 1.3595581054687], [103.9916911017784, 1.3599040058152], [103.9919875039655, 1.3605287891018], [103.9920041011468, 1.3605675996823], [103.992068813389, 1.3607173096105], [103.9921689832457, 1.3609440120186], [103.9922510051745, 1.3611352987242], [103.99225980671, 1.3611557099042], [103.9924025173219, 1.3614882822112], [103.9923205792173, 1.3615234045292], [103.9924075048587, 1.3617263847034], [103.9924463154392, 1.3618164118383], [103.9924668942675, 1.3618703107654], [103.9926443499887, 1.3623046875], [103.9926928003462, 1.3624232986693], [103.9927059188253, 1.3624520922641], [103.9927205880512, 1.3624878013512], [103.9929078092856, 1.3629396135085], [103.992952780941, 1.3630425914743], [103.9929729825607, 1.3630917962491], [103.9929858076553, 1.3631220986786], [103.9931648979474, 1.3635009838273], [103.9931205968852, 1.36351841925], [103.9931648979474, 1.363609619923], [103.9932436926464, 1.3636649019486], [103.9932902988727, 1.3636975933662], [103.993546591205, 1.363888419039], [103.9935737083168, 1.3639053096048], [103.9935864914994, 1.3639152008543], [103.9938354492188, 1.3641061103512], [103.9939587964525, 1.3642007059022], [103.9939823929501, 1.364220991346], [103.9940919930235, 1.3643046059335], [103.9941722127331, 1.3643657137374], [103.994470794348, 1.364593296299], [103.9945034019416, 1.3646181920709], [103.9944417911928, 1.3646989147254], [103.9945129998065, 1.3647531908612], [103.9943717980293, 1.3649384003161], [103.9943062056336, 1.3648883992118], [103.9942663053391, 1.3649407054801], [103.9942450978297, 1.3649246112437], [103.9938492802032, 1.3646228023991], [103.9938354492188, 1.3646105640735], [103.9938287013749, 1.364604612559], [103.9938134034679, 1.3645930867386], [103.9934374940765, 1.364311102305], [103.9934060181089, 1.364284488138], [103.9933897981363, 1.3642720821641], [103.9930687097376, 1.3640297884645], [103.9930174093591, 1.3639910197961], [103.993023612346, 1.3639082853621], [103.9929583971589, 1.3638972205746], [103.9929052945612, 1.3638760968893], [103.9928822848326, 1.3638564820387], [103.9928664839807, 1.3638468841737], [103.9928114953397, 1.3637832197334], [103.9927492139977, 1.3636418083958], [103.9927806899653, 1.3636283965321], [103.9927707148917, 1.3636048838586], [103.9927609074664, 1.3635814969214], [103.9925194939203, 1.3630094809358], [103.9925065850015, 1.3629782983528], [103.992495520214, 1.3629526062515], [103.9922808046591, 1.3624520922641], [103.9922494963398, 1.3623792071675], [103.9922352881468, 1.3623372950936], [103.9922227145246, 1.3623072860486], [103.9922216248106, 1.3623046875], [103.9920831892303, 1.3619721151931], [103.9920432889359, 1.3618789027406], [103.9920263145459, 1.3618392958307], [103.9918421109809, 1.3619183000901], [103.9918048930592, 1.3619343105023], [103.9915833877483, 1.3618442833675], [103.9915551809225, 1.3618566055172], [103.9915224056806, 1.3618708137103], [103.9915934885581, 1.3620369112594], [103.9916304969194, 1.3621232920439], [103.9914364021049, 1.3622056073571], [103.9912027422925, 1.3623046875], [103.991091381912, 1.3623518804953], [103.9910888671875, 1.3623529702092], [103.9910037018532, 1.3623888888566], [103.9909324094154, 1.3624194008465], [103.9905380167994, 1.3625885160649], [103.9905093908528, 1.3626005029181], [103.9903816009393, 1.3626536893399], [103.9900655000775, 1.3627852932522], [103.9898450006563, 1.3628816071982], [103.9898193923791, 1.3628207089547], [103.9897234137297, 1.3625922043274], [103.9896701015716, 1.3626150044957], [103.9896853994787, 1.3626482826824], [103.989591516433, 1.3628873072402], [103.9895605014982, 1.3628987073243], [103.9893791060421, 1.3629731012556], [103.9893894164123, 1.3629954823031], [103.9894058040332, 1.3630371009926], [103.9894286042014, 1.3630925087544], [103.9894353939574, 1.3631088963753], [103.9896825075455, 1.363695204378], [103.9896962966179, 1.3637265126973], [103.9897024996048, 1.3637408047145], [103.9899053121308, 1.3642119802501], [103.9899478109738, 1.3643108927446], [103.9899670067036, 1.3643510025994], [103.9900227078499, 1.364328118607], [103.9900305873198, 1.364347398161], [103.9901452168421, 1.3646261134529], [103.9901590059145, 1.3646635828471], [103.9901667177361, 1.3646847903565], [103.990253391905, 1.3649034037343], [103.9902540205862, 1.3649637152087], [103.9902559904536, 1.3650150155873], [103.9902520088066, 1.3650441863908], [103.9902484462803, 1.3650512695313], [103.9902198203338, 1.3651084795122], [103.9901799200394, 1.3651483798066], [103.9901419896124, 1.3651863102336], [103.9901362895704, 1.3652189178271], [103.9901466837647, 1.3652399157762], [103.9902010856367, 1.3652418856437], [103.9901504977635, 1.3656856925949], [103.9901483183356, 1.3657048045006], [103.9901041010976, 1.3660813006611], [103.9901001194506, 1.3661080824763], [103.990086791411, 1.3662137847269], [103.9900693140762, 1.3663517173623], [103.9900227078499, 1.3667388172775], [103.9899870825871, 1.3667368054979], [103.9899797898862, 1.3667783822753], [103.9898825119625, 1.366788399261], [103.9898134827767, 1.3667858007124], [103.9897525007091, 1.3667811065601], [103.9896978892767, 1.3667634196649], [103.9896760111741, 1.36675160046], [103.9896786935468, 1.3667140053297], [103.989576218526, 1.3667099817706], [103.9895797810522, 1.3666894867664], [103.9896455830084, 1.3661579997564], [103.9896683831766, 1.3659921117677], [103.9896701853958, 1.3659771910693], [103.9897216115106, 1.3655550945724], [103.9897618890136, 1.3655599982851], [103.9897858208079, 1.3653122979279], [103.9898109680522, 1.3650512695313], [103.9898165842702, 1.3649930955726], [103.9897950833762, 1.3649373944263], [103.9897783185466, 1.3648982904613], [103.9895100812732, 1.3642732976143], [103.9894939870368, 1.3642331877595], [103.9894918914331, 1.3642279906623], [103.9892855163809, 1.3637369068916], [103.9892461190314, 1.3636431076701], [103.9892348865956, 1.3636183795464], [103.9892078113958, 1.3636296958064], [103.9891988002999, 1.3636081949125], [103.9890596103022, 1.3632754968693], [103.9890477072732, 1.3632534930305], [103.9889964068947, 1.3631321994884], [103.9889313174438, 1.3629782145287], [103.9888570911608, 1.3630094809358], [103.9888295130162, 1.362944391485], [103.9888202923599, 1.3629225133824], [103.9888523970085, 1.3629088919583], [103.9886655948949, 1.3624671806108], [103.9886150070216, 1.3623512099021], [103.9885968171815, 1.3623085853229], [103.9885951406985, 1.3623046875], [103.9885862972509, 1.3622841086717], [103.9884893965359, 1.3620571967032], [103.9883950105453, 1.3618351046233], [103.9883422851562, 1.3617099551704], [103.9883158805496, 1.3616472966198], [103.9880514153629, 1.3610370987349], [103.987782297936, 1.3603996160899], [103.9876483888596, 1.3600644871464], [103.9878664154684, 1.3599833872833], [103.9883422851562, 1.3610924645846], [103.9887147996697, 1.3619605893727], [103.9888127062745, 1.3619190964195], [103.988759184556, 1.3617905101766], [103.9889101099344, 1.3617257141102], [103.9889345027614, 1.3617819182014], [103.9890207158976, 1.3617449936642], [103.9891236938633, 1.3617009859866], [103.9891041209248, 1.3616552180018], [103.9892001833983, 1.3616141860814], [103.9893886200829, 1.3615337148994], [103.9897144026338, 1.3613944829896], [103.9900540161692, 1.3612495091258], [103.9904699935033, 1.3610718019322], [103.9908884017377, 1.3608930888488], [103.9910508110244, 1.3608248140803], [103.9910888671875, 1.3608083007231], [103.9912446124544, 1.3607409061082], [103.9912912186807, 1.3607207044885], [103.9913763001908, 1.3606839056876], [103.9914193019787, 1.3607829858305], [103.9913335917874, 1.3608202037521], [103.9912913863289, 1.3608383935922], [103.9914477183648, 1.3612039926135], [103.9913371962258, 1.3612511856087], [103.9913636846565, 1.3613156882906], [103.9913990165349, 1.3613972072744], [103.9918118923755, 1.3612117882592], [103.991672199433, 1.3608891910259], [103.9917120997274, 1.3608722166359], [103.991792319437, 1.3608378068232], [103.9918349859283, 1.3608194912469], [103.9912666162932, 1.3595581054687]]" ) ] ;
    ns3:hidden [ ] ;
    ns2:zh "1号航站楼" .

roles:Contractor a prov:Delegation ;
    prov:agent agents:CCM .

roles:Employee a prov:Delegation ;
    prov:agent agents:PangaeaInnovations .

<dggsoperations:map_data_execution> a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2023-10-05T05:03:15+01:00"^^xsd:dateTime ;
    prov:startedAtTime "2023-10-05T05:03:10+01:00"^^xsd:dateTime ;
    prov:used <https://terranexus.pangaeainnovations.com/ogcapi/jobs/someJobID?f=json> ;
    prov:wasAssociatedWith agents:TerraNexus,
        agents:some_user ;
    prov:wasInformedBy <dggsoperations:map_data> .

<https://terranexus.pangaeainnovations.com/ogcapi/collections/osm_singapore_buildings/items/2305843009240255693> a prov:Entity,
        geojson:Feature ;
    prov:generatedAtTime "2023-10-05T05:03:15+01:00"^^xsd:dateTime ;
    prov:specializationOf terranexusTempData:osm_singapore_buildings ;
    prov:wasGeneratedBy <dggsoperations:store_data_task> ;
    prov:wasInfluencedBy <dggsoperations:map_featureData_task>,
        <dggsoperations:processData_task>,
        <dggsoperations:store_data_task> .

terranexusJobs:someJobID a <file:///github/workspace/ogcapiJob>,
        prov:Entity ;
    prov:generatedAtTime "2023-10-05T05:03:15+01:00"^^xsd:dateTime ;
    prov:invalidatedAtTime "2023-10-05T05:03:15+01:00"^^xsd:dateTime ;
    prov:wasGeneratedBy terranexusProcesses:MapDataToZones ;
    prov:wasInvalidatedBy <dggsoperations:ogcapiJobsCleanup> .

terranexusProcesses:store_data_task a <file:///github/workspace/Registration> ;
    prov:endedAtTime "2019-01-01T19:03:15+01:00"^^xsd:dateTime ;
    prov:wasAssociatedWith agents:TerraNexus .

<dggsoperations:map_data> a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2023-10-05T05:03:15+01:00"^^xsd:dateTime ;
    prov:generated terranexusTempData:osm_singapore_buildings ;
    prov:startedAtTime "2023-10-05T05:03:10+01:00"^^xsd:dateTime ;
    prov:used <https://terranexus.pangaeainnovations.com/ogcapi/jobs/someJobID?f=json> ;
    prov:wasAssociatedWith agents:TerraNexus,
        agents:some_user ;
    prov:wasInformedBy terranexusProcesses:MapDataToZones .

<dggsoperations:map_featureData_task> a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2023-10-05T05:03:15+01:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings ;
    prov:startedAtTime "2023-10-05T05:03:10+01:00"^^xsd:dateTime ;
    prov:used terranexusTempData:osm_singapore_buildings,
        <https://terranexus.pangaeainnovations.com/ogcapi/jobs/someJobID?f=json> ;
    prov:wasAssociatedWith agents:TerraNexus,
        agents:some_user ;
    prov:wasInformedBy terranexusProcesses:store_data_task .

<dggsoperations:processData_task> a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2023-10-05T05:03:15+01:00"^^xsd:dateTime ;
    prov:startedAtTime "2023-10-05T05:03:10+01:00"^^xsd:dateTime ;
    prov:used <https://terranexus.pangaeainnovations.com/ogcapi/jobs/someJobID?f=json> ;
    prov:wasAssociatedWith agents:TerraNexus,
        agents:some_user ;
    prov:wasInformedBy <dggsoperations:map_data_execution> .

terranexusCollections:osm_singapore_buildings a prov:Collection,
        prov:Entity,
        geojson:FeatureCollection ;
    prov:generatedAtTime "2023-10-05T05:03:15+01:00"^^xsd:dateTime ;
    prov:wasDerivedFrom terranexusTempData:collectionID ;
    prov:wasGeneratedBy <dggsoperations:store_data_task> ;
    prov:wasInfluencedBy <dggsoperations:map_featureData_task>,
        <dggsoperations:processData_task>,
        <dggsoperations:store_data_task> .

terranexusProcesses:MapDataToZones a <file:///github/workspace/ogcapiProcess>,
        prov:Activity ;
    prov:endedAtTime "2023-10-05T05:03:15+01:00"^^xsd:dateTime ;
    prov:generated <https://terranexus.pangaeainnovations.com/ogcapi/jobs/someJobID?f=json> ;
    prov:startedAtTime "2023-10-05T05:03:10+01:00"^^xsd:dateTime ;
    prov:wasAssociatedWith agents:TerraNexus,
        agents:some_user .

terranexusTempData:osm_singapore_buildings a <file:///github/workspace/rawData>,
        prov:Entity ;
    prov:generatedAtTime "2023-10-05T05:03:15+01:00"^^xsd:dateTime ;
    prov:invalidatedAtTime "2023-10-05T05:03:15+01:00"^^xsd:dateTime ;
    prov:wasDerivedFrom terranexusJobs:someJobID ;
    prov:wasGeneratedBy <dggsoperations:map_data> ;
    prov:wasInvalidatedBy <dggsoperations:tmpDataCleanup> .

<dggsoperations:store_data_task> a <file:///github/workspace/dggsOperation>,
        prov:Activity ;
    prov:endedAtTime "2023-10-05T05:03:15+01:00"^^xsd:dateTime ;
    prov:generated terranexusCollections:osm_singapore_buildings ;
    prov:startedAtTime "2023-10-05T05:03:10+01:00"^^xsd:dateTime ;
    prov:used terranexusTempData:osm_singapore_buildings,
        <https://terranexus.pangaeainnovations.com/ogcapi/jobs/someJobID?f=json> ;
    prov:wasAssociatedWith agents:TerraNexus,
        agents:some_user ;
    prov:wasInformedBy terranexusProcesses:processData_task .


```

<blockquote class="lang-specific turtle">
  <p class="example-links">
    <a target="_blank" href="https://geofizzydrink.github.io/test_bblock/build/tests/bbr/template/json-fg-feature_with-prov/example_2_2.ttl">Open in new window</a>
</blockquote>



# JSON Schema

```yaml--schema
$schema: https://json-schema.org/draft/2020-12/schema
description: CWL Provenance Chain for DGGS actions
allOf:
- $ref: https://ogcincubator.github.io/bblock-prov-schema/build/annotated/ogc-utils/prov/schema.yaml
- $ref: https://opengeospatial.github.io/bblocks/annotated-schemas/geo/json-fg/feature/schema.yaml
- type: object
- properties:
    a:
      type: string
      format: uri
    b:
      type: number
x-jsonld-extra-terms:
  dggsOperations: https://someDGGSOperationsRegister.eg
  featureType:
    x-jsonld-id: '@type'
    x-jsonld-context:
      '@base': http://example.org/myEntities/
  activityType:
    x-jsonld-id: '@type'
    x-jsonld-context:
      '@base': http://example.org/myActivityTypes/
x-jsonld-prefixes:
  base_href: https://terranexus.pangaeainnovations.com/
  agents: https://someAgentRegister.eg/
  roles: https://someRolesRegister.eg/
  terranexusProcesses: https://terranexus.pangaeainnovations.com/ogcapi/processes/
  terranexusCollections: https://terranexus.pangaeainnovations.com/ogcapi/collections/
  terranexusJobs: https://terranexus.pangaeainnovations.com/ogcapi/jobs/
  terranexusTempData: https://someTempDataRegister.eg/

```

> <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=yaml&amp;dataUrl=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Fannotated%2Fbbr%2Ftemplate%2Fjson-fg-feature_with-prov%2Fschema.yaml&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on YAML Viewer</a>

Links to the schema:

* YAML version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/json-fg-feature_with-prov/schema.yaml" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/json-fg-feature_with-prov/schema.yaml</a>
* JSON version: <a href="https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/json-fg-feature_with-prov/schema.json" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/json-fg-feature_with-prov/schema.json</a>


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
      "@context": {},
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
    "coordinates": {
      "@container": "@list",
      "@id": "geojson:coordinates"
    },
    "dggsOperations": "https://someDGGSOperationsRegister.eg",
    "prov": "http://www.w3.org/ns/prov#",
    "xsd": "http://www.w3.org/2001/XMLSchema#",
    "rdfs": "http://www.w3.org/2000/01/rdf-schema#",
    "rdf": "http://www.w3.org/1999/02/22-rdf-syntax-ns#",
    "oa": "http://www.w3.org/ns/oa#",
    "dct": "http://purl.org/dc/terms/",
    "base_href": "https://terranexus.pangaeainnovations.com/",
    "agents": "https://someAgentRegister.eg/",
    "roles": "https://someRolesRegister.eg/",
    "terranexusProcesses": "base_href:ogcapi/processes/",
    "terranexusCollections": "base_href:ogcapi/collections/",
    "terranexusJobs": "base_href:ogcapi/jobs/",
    "terranexusTempData": "https://someTempDataRegister.eg/",
    "geojson": "https://purl.org/geojson/vocab#",
    "@version": 1.1
  }
}
```

> <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fgeofizzydrink.github.io%2Ftest_bblock%2Fbuild%2Fannotated%2Fbbr%2Ftemplate%2Fjson-fg-feature_with-prov%2Fcontext.jsonld">View on JSON-LD Playground</a>

You can find the full JSON-LD context here:
<a href="https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/json-fg-feature_with-prov/context.jsonld" target="_blank">https://geofizzydrink.github.io/test_bblock/build/annotated/bbr/template/json-fg-feature_with-prov/context.jsonld</a>

# References

* [Sample source document](https://example.com/sources/1)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: <a href="https://github.com/geofizzydrink/test_bblock" target="_blank">https://github.com/geofizzydrink/test_bblock</a>
* Path:
<code><a href="https://github.com/geofizzydrink/test_bblock/blob/HEAD/_sources/json-fg-feature_with-prov" target="_blank">_sources/json-fg-feature_with-prov</a></code>

