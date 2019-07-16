### Geometries

Use [GADM version 3.6](https://gadm.org/download_world.html) level 0 for country ranking. Join key: GID_0  
Use [GADM version 3.6 level](https://gadm.org/download_world.html) 1 for province ranings. Join key: GID_1  

Consider using [mapshaper](https://mapshaper.org/) to simplify the geometries for better in-browser performance. If using mapshaper, please log the settings for future reference.


### Absolute values 

used for individual indicators, grouped and overall water risk. Note that descriptions vary per indicator, as does the special category (-1). 

| cat| description | rgb | hex |
| --- | --- | --- | --- | 
| 0| Low | 255 255 153 | #FFFF99 |
|1| Low to Medium | 255 230 0 | #FFE600 |
|2| Medium to High | 255 153 0 | #FF9900 |
|3| High | 255 25 0 | #FF1900 |
|4| Extremely High | 153 0 0  | #990000 |
|-1| Arid and low water use | 128 128 128 | #808080 |
|None| No data | 78 78 78 | #4E4E4E |
|4| OLD, do not use | 204 0 20 | #CC0014 |
