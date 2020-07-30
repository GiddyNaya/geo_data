# Geo Data
Open Source Geographical Data with mapped names of Countries, Regions/States, Cities, Geolocation with longitude and latitude of each Regions-States. Available in various formats (MySQL, MsSQL, Json, Xml, Csv)

* 193 countries
* 3,888 regions/state
* 2,790,951 cities

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



<h4>[See Demo Usage](https://giddynaya.github.io/geo_data/)</h4>




![Sample page image](https://lh3.googleusercontent.com/9JR3XvOS_0M80NJWvVDgU-NYQXuFXBaX2im8lPXXF9enrS8iX4MqqnHgYKVEm4Q4lTyzP3ssVsDjNWjz1tSJ=w1280-h578)


