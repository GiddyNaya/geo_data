# Geo Data
Open Source Geographical Data with mapped names of Countries, Regions/States, Cities, Geolocation with longitude and latitude of each Regions-States. Available in various formats (MySQL, MsSQL, Json, Xml, Csv)

* 193 countries
* 3,888 regions/state
* 2,790,951 cities

<br/>

<h4>Available formats</h4>

* [Data as Json](https://github.com/GiddyNaya/geo_data/tree/master/json_db)
* [Data as MySql Database](https://github.com/GiddyNaya/geo_data/tree/master/mysql_db)
* [Data as MsSql Database](https://github.com/GiddyNaya/geo_data/tree/master/mssql_db)

<h4>Table map</h4>

Countries
| id (pk) | name | country_code |
|---------|------|--------------|

Regions/States
| id (pk) | name | region_code | country_id (fk) |
|---------|------|-------------|-----------------|

Cities
| id (pk) | name | longitude | latitude | region_id (fk) | country_id (fk) |
|---------|------|-----------|----------|----------------|-----------------|

 <br /> 
   <br />
   
[👀 See Sample Usage](https://giddynaya.github.io/geo_data/)

<br /> 
   <br />
   
<h1>Data Breakdown</h1>
 <h3>Africa</h3>
 <h4>Central Africa</h4>

    Burundi (5925 records)
    Chad (10356 records)
    Congo, Republic of the (4962 records)
    Congo, Democratic Republic of the (30080 records)
    Central African Republic (5255 records)
    Rwanda (6731 records)

 <h4>Eastern Africa</h4>

    Djibouti (49 records)
    Eritrea (1343 records)
    Ethiopia (9427 records)
    Kenya (2993 records)
    Somalia (4237 records)
    South Sudan (4852 records)
    Tanzania, United Republic of (7173 records)
    Uganda (5660 records)

 <h4>Indian Ocean</h4>

    Comoros (373 records)
    Madagascar (15180 records)
    Mayotte (153 records)
    Mauritius (538 records)
    Reunion (324 records)
    Seychelles (26 records)

 <h4>Northern Africa</h4>

    Algeria (8095 records)
    Egypt (4421 records)
    Libya (866 records)
    Morocco (37114 records)
    Sudan (7132 records)
    Tunisia (1802 records)
    Western Sahara (32 records)

 <h4>Southern Africa</h4>

    Angola (14192 records)
    Botswana (1670 records)
    Lesotho (292 records)
    Malawi (4365 records)
    Mozambique (19553 records)
    South Africa (11551 records)
    Namibia (1940 records)
    Swaziland (98 records)
    Zambia (11085 records)
    Zimbabwe (2018 records)

 <h4>Western Africa</h4>

    Benin (3555 records)
    Cameroon (12129 records)
    Cape Verde (286 records)
    Equatorial Guinea (1578 records)
    Gambia, The (1876 records)
    Gabon (3494 records)
    Ghana (9127 records)
    Guinea (6034 records)
    Cote d'Ivoire (10034 records)
    Liberia (6007 records)
    Mali (12996 records)
    Mauritania (1025 records)
    Niger (11686 records)
    Nigeria (46432 records)
    Guinea-Bissau (3903 records)
    Senegal (9067 records)
    Sierra Leone (8606 records)
    Togo (3912 records)
    Sao Tome and Principe (226 records)
    Burkina Faso (8478 records)

 
 <h3>Americas</h3>
 <h4>Central America</h4>

    Belize (457 records)
    Costa Rica (2029 records)
    El Salvador (3117 records)
    Guatemala (6271 records)
    Honduras (9240 records)
    Mexico (146490 records)
    Nicaragua (2530 records)
    Panama (5905 records)

 <h4>North America</h4>

    Canada (18595 records)
    Greenland (238 records)
    Saint Pierre and Miquelon (5 records)
    United States (191040 records)

 <h4>South America</h4>

    Argentina (6715 records)
    Bolivia (11826 records)
    Brazil (41632 records)
    Chile (3768 records)
    Colombia (24642 records)
    Ecuador (6526 records)
    French Guiana (582 records)
    Falkland Islands (Islas Malvinas) (55 records)
    Guyana (544 records)
    Suriname (520 records)
    Paraguay (1962 records)
    Peru (34271 records)
    Uruguay (1055 records)
    Venezuela (18710 records)

 <h4>West Indies</h4>

    Aruba (104 records)
    Antigua and Barbuda (123 records)
    Anguilla (37 records)
    Barbados (518 records)
    Bermuda (23 records)
    Bahamas, The (337 records)
    Cayman Islands (63 records)
    Cuba (10389 records)
    Dominica (111 records)
    Dominican Republic (7281 records)
    Grenada (270 records)
    Guadeloupe (379 records)
    Haiti (9586 records)
    Jamaica (2102 records)
    Martinique (500 records)
    Montserrat (82 records)
    Saint Martin (54 records)
    Saint Kitts and Nevis (119 records)
    Saint Lucia (191 records)
    Trinidad and Tobago (452 records)
    Turks and Caicos Islands (37 records)
    Saint Vincent and the Grenadines (71 records)
    British Virgin Islands (22 records)

 
 <h3>Antarctica</h3>
 <h4>Atlantic Ocean</h4>

    Saint Helena (13 records)
    South Georgia and the Islands (2 records)

 
 <h3>Asia</h3>
 <h4>Central Asia</h4>

    Kyrgyzstan (2319 records)
    Kazakhstan (9950 records)
    Tajikistan (2508 records)
    Turkmenistan (1141 records)
    Uzbekistan (5775 records)

 <h4>East Asia</h4>

    China (389952 records)
    Hong Kong (1133 records)
    Japan (36502 records)
    Korea, North (24797 records)
    Korea, South (40233 records)
    Macau (7 records)
    Taiwan (12308 records)

 <h4>Northern Asia</h4>

    Mongolia (1498 records)
    Russia (159037 records)

 <h4>South Asia</h4>

    Afghanistan (28994 records)
    Bangladesh (38177 records)
    Bhutan (241 records)
    Sri Lanka (15951 records)
    India (308949 records)
    British Indian Ocean Territory (4 records)
    Maldives (96 records)
    Nepal (55734 records)
    Pakistan (95629 records)

 <h4>South East Asia</h4>

    Myanmar (31533 records)
    Brunei (218 records)
    Cambodia (7050 records)
    Cocos (Keeling) Islands (2 records)
    Indonesia (162063 records)
    Christmas Island (6 records)
    Laos (13059 records)
    Malaysia (18304 records)
    Philippines (35268 records)
    Singapore (359 records)
    Thailand (67833 records)
    East Timor (3255 records)
    Vietnam (35658 records)

 <h4>South West Asia</h4>

    United Arab Emirates (633 records)
    Azerbaijan (4962 records)
    Armenia (1986 records)
    Bahrain (122 records)
    Cyprus (690 records)
    Georgia (4971 records)
    Israel (1531 records)
    Iran (68472 records)
    Iraq (22815 records)
    Jordan (1254 records)
    Kuwait (115 records)
    Lebanon (3440 records)
    Oman (2264 records)
    Qatar (221 records)
    Saudi Arabia (3046 records)
    Syrian Arab Republic (10035 records)
    Turkey (49087 records)
    Yemen (34780 records)

 
 <h3>Europe</h3>
 <h4>Central Europe</h4>

    Austria (13621 records)
    Czech Republic (14847 records)
    Hungary (15063 records)
    Slovakia (4847 records)
    Liechtenstein (354 records)
    Switzerland (12353 records)

 <h4>Eastern Europe</h4>

    Belarus (21014 records)
    Estonia (6533 records)
    Latvia (4440 records)
    Lithuania (6736 records)
    Moldova, Republic of (1785 records)
    Poland (40651 records)
    Ukraine (28449 records)

 <h4>Northern Europe</h4>

    Åland Islands (332 records)
    Denmark (6446 records)
    Finland (13277 records)
    Faroe Islands (183 records)
    Iceland (132 records)
    Svalbard (10 records)
    Norway (11411 records)
    Sweden (24785 records)

 <h4>South East Europe</h4>

    Albania (4158 records)
    Bosnia and Herzegovina (14434 records)
    Bulgaria (6396 records)
    Greece (13940 records)
    Croatia (8910 records)
    Kosovo (0 records)
    Montenegro (3766 records)
    The Former Yugoslav Republic of Macedonia (2723 records)
    Serbia (7452 records)
    Romania (17270 records)
    Slovenia (6628 records)

 <h4>South West Europe</h4>

    Andorra (57 records)
    Gibraltar (4 records)
    Portugal (14625 records)
    Spain (26960 records)

 <h4>Southern Europe</h4>

    Italy (55387 records)
    Malta (282 records)
    San Marino (24 records)

 <h4>Western Europe</h4>

    Belgium (11045 records)
    Ireland (8943 records)
    France (55609 records)
    United Kingdom (16028 records)
    Germany (67465 records)
    Isle of Man (37 records)
    Jersey (85 records)
    Luxembourg (639 records)
    Monaco (8 records)
    Netherlands (7291 records)

 
 <h3>Oceania</h3>
 <h4>Pacific </h4>

    Australia (15478 records)
    Solomon Islands (2926 records)
    Cook Islands (39 records)
    Fiji (1560 records)
    Micronesia, Federated States of (436 records)
    French Polynesia (305 records)
    Kiribati (187 records)
    New Caledonia (615 records)
    Niue (42 records)
    Norfolk Island (4 records)
    Vanuatu (1279 records)
    Nauru (11 records)
    New Zealand (2959 records)
    Pitcairn Islands (2 records)
    Papua New Guinea (11304 records)
    Palau (84 records)
    Marshall Islands (98 records)
    Tokelau (5 records)
    Tonga (140 records)
    Tuvalu (27 records)
    Wallis and Futuna (56 records)
    Samoa (405 records)


 <br /> 
   <br />
   
[👀 See Sample Usage](https://giddynaya.github.io/geo_data/)

 <br /> 
   <br />
   
<h4>TODO</h4>

* Data as CSV
* Data as XML
