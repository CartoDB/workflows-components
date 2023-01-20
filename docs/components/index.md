 # Components list

  CARTO Workflows is currently available in beta for BigQuery and CARTO Data Warehouse connections,
  and it might be subject to changes. To learn more about this tool please check our
  [product documentation](https://docs.carto.com/carto-user-manual/workflows)

  ### Compatibility Mode

| Component              | BigQuery | Snowflake | Redshift | PostgreSQL |
| :--------------------- | :------: | :-------: | :------: | :--------: |
| [Buffer](./alteryx.buffer.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [Distance](./alteryx.distance.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [Join](./alteryx.join.md)|:heavy_check_mark:|:x:|:x:|:x: |
| [Union ](./ateryx.union.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [Append Fields](./alteryx.appendfields.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [Create Points](./alteryx.createpoints.md)|:heavy_check_mark:|:x:|:x:|:x: |
| [Find Nearest](./alteryx.findnearest.md)|:heavy_check_mark:|:x:|:x:|:x: |
| [Generalize](./alteryx.generalize.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [Poly-Build](./alteryx.polybuild.md)|:heavy_check_mark:|:x:|:x:|:x: |
| [Poly-Split](./alteryx.polysplit.md)|:heavy_check_mark:|:x:|:x:|:x: |
| [Create Points](./alteryx.createpoints.md)|:heavy_check_mark:|:x:|:x:|:x: |
| [Spatial Match](./alteryx.spatialmatch.md)|:heavy_check_mark:|:x:|:x:|:x: |
| [Spatial Process](./alteryx.spatialprocess.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [Trade Areas](./alteryx.tradeareas.md)|:heavy_check_mark:|:x:|:x:|:x: |
### Spatial Operations

| Component              | BigQuery | Snowflake | Redshift | PostgreSQL |
| :--------------------- | :------: | :-------: | :------: | :--------: |
| [ST_AREA](./native.area.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_BOUNDINGBOX](./native.boundingbox.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_CENTROID](./native.centroid.md)|:heavy_check_mark:|:x:|:heavy_check_mark:|:heavy_check_mark: |
| [CLIP_WITH_POLYGONS](./native.clipwithpolygons.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_CONCAVEHULL](./native.concavehull.md)|:heavy_check_mark:|:x:|:x:|:x: |
| [ST_CONVEXHULL](./native.convexhull.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_EXTENT](./native.extent.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_BUFFER](./native.buffer.md)|:heavy_check_mark:|:x:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_LENGTH](./native.length.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_PERIMETER](./native.perimeter.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_SIMPLIFY](./native.simplify.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_SNAPTOGRID](./native.snaptogrid.md)|:heavy_check_mark:|:x:|:x:|:heavy_check_mark: |
### Parsers

| Component              | BigQuery | Snowflake | Redshift | PostgreSQL |
| :--------------------- | :------: | :-------: | :------: | :--------: |
| [ST_ASGEOJSON](./native.asgeojson.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_ASTEXT](./native.aswkt.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_GEOCODE](./native.geocode.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x: |
| [ST_GEOGFROMTEXT](./native.geogfromtext.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_GEOGPOINT](./native.geogpoint.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [TABLE_FROM_GEOJSON](./native.tablefromgeojson.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
### Basic SQL

| Component              | BigQuery | Snowflake | Redshift | PostgreSQL |
| :--------------------- | :------: | :-------: | :------: | :--------: |
| [SIMPLE_FILTER](./native.wheresimplified.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [COUNT](./native.count.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [CROSS_JOIN](./native.crossjoin.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [SELECT_DISTINCT](./native.distinct.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [DROP_COLUMN](./native.dropcolumn.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [GROUP BY](./native.groupby.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [JOIN](./native.join.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [LIMIT](./native.limit.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ORDER_BY](./native.orderby.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [RENAME_COLUMN](./native.renamecolumn.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [SELECT](./native.select.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [CREATE_COLUMN](./native.selectexpression.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [WHERE](./native.where.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [UNION_ALL](./native.unionall.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [UNNEST](./native.unnest.md)|:heavy_check_mark:|:x:|:x:|:x: |
### Geographic Tools

| Component              | BigQuery | Snowflake | Redshift | PostgreSQL |
| :--------------------- | :------: | :-------: | :------: | :--------: |
| [ST_BOUNDARY](./native.boundary.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [BBOX_FROM_VALUES](./native.bboxfromvalues.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [CREATE_GRID](./native.creategrid.md)|:heavy_check_mark:|:x:|:x:|:heavy_check_mark: |
| [CREATE_TILESET](./native.createtileset.md)|:heavy_check_mark:|:x:|:x:|:x: |
| [ST_DESTINATION](./native.destination.md)|:heavy_check_mark:|:x:|:x:|:x: |
| [ST_DIFFERENCE](./native.difference.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_DISTANCE](./native.distance.md)|:heavy_check_mark:|:x:|:x:|:x: |
| [DISTANCE_MATRIX](./native.distancematrix.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_DUMP](./native.dump.md)|:heavy_check_mark:|:x:|:x:|:x: |
| [ST_GEOGFROMSTATICTEXT](./native.geogfromstatictext.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_GEOMETRYTYPE](./native.geometrytype.md)|:heavy_check_mark:|:x:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_INTERSECTION](./native.intersection.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [CREATE_ISOLINES](./native.isolines.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x: |
| [KNN_NEIGHBORS](./native.knn.md)|:heavy_check_mark:|:x:|:x:|:x: |
| [ST_MAKELINE](./native.makeline.md)|:heavy_check_mark:|:x:|:x:|:heavy_check_mark: |
| [ST_MAKEPOLYGON](./native.makepolygon.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_NUMGEOMETRIES](./native.numgeometries.md)|:heavy_check_mark:|:x:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_NUMPOINTS](./native.numpoints.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [POINT_FROM_STATIC_LATLON](./native.pointfromstaticlatlon.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_POINTN](./native.pointn.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [POINT_STATS_IN_POLYGONS](./native.pointstatsinpolygons.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_POLYGONIZE](./native.polygonize.md)|:heavy_check_mark:|:x:|:x:|:x: |
| [REMOVE_HOLES](./native.removeholes.md)|:heavy_check_mark:|:x:|:x:|:heavy_check_mark: |
| [ST_SetSRID](./native.setsrid.md)|:x:|:x:|:heavy_check_mark:|:heavy_check_mark: |
| [SPATIAL_FILTER](./native.spatialfilter.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [SPATIAL_JOIN](./native.spatialjoin.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_X/ST_Y](./native.xycoords.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
### Custom SQL

| Component              | BigQuery | Snowflake | Redshift | PostgreSQL |
| :--------------------- | :------: | :-------: | :------: | :--------: |
| [CALL_PROCEDURE](./native.call.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [CUSTOM_SQL_SELECT](./native.customsql.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
### Other Components

| Component              | BigQuery | Snowflake | Redshift | PostgreSQL |
| :--------------------- | :------: | :-------: | :------: | :--------: |
| [CAST](./native.cast.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_GENERATEPOINTS](./native.generatepoints.md)|:heavy_check_mark:|:x:|:x:|:x: |
| [GENERATE_UUID](./native.generateuuid.md)|:heavy_check_mark:|:heavy_check_mark:|:x:|:x: |
| [ST_LINE_INTERPOLATE_POINT](./native.lineinterpolatepoint.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [NORMALIZE](./native.normalize.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [REMOVE_DUPLICATED](./native.removeduplicatedrows.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [SAMPLE](./native.sample.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
### Spatial Analysis

| Component              | BigQuery | Snowflake | Redshift | PostgreSQL |
| :--------------------- | :------: | :-------: | :------: | :--------: |
| [ST_CLUSTERDBSCAN](./native.clusterdbscan.md)|:heavy_check_mark:|:x:|:x:|:x: |
| [ST_CLUSTERKMEANS](./native.clusterkmeans.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_COUNT_POINTSINPOLYGONS](./native.countpointsinpolygons.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_DELAUNAYPOLYGONS](./native.delaunay.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [ST_VORONOI](./native.voronoi.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
### Spatial Indexes

| Component              | BigQuery | Snowflake | Redshift | PostgreSQL |
| :--------------------- | :------: | :-------: | :------: | :--------: |
| [H3_BOUNDARY](./native.h3boundary.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x: |
| [H3_CENTER](./native.h3center.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x: |
| [H3_FROMGEOGPOINT](./native.h3frompoint.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x: |
| [H3_POLYFILL](./native.h3polyfill.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x: |
| [QUADBIN_BOUNDARY](./native.quadbinboundary.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [QUADBIN_CENTER](./native.quadbincenter.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [QUADBIN_FROMGEOGPOINT](./native.quadbinfrompoint.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [QUADBIN_POLYFILL](./native.quadbinpolyfill.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
### Import/Export

| Component              | BigQuery | Snowflake | Redshift | PostgreSQL |
| :--------------------- | :------: | :-------: | :------: | :--------: |
| [IMPORT_FROM_URL](./native.importurl.md)|:heavy_check_mark:|:x:|:x:|:x: |
| [SAVE_AS_TABLE](./native.saveastable.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
| [SEND_BY_EMAIL](./SaveToBucketAndNotify.md)|:heavy_check_mark:|:x:|:x:|:x: |
### __internal

| Component              | BigQuery | Snowflake | Redshift | PostgreSQL |
| :--------------------- | :------: | :-------: | :------: | :--------: |
| [READ_TABLE](./ReadTable.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark: |
