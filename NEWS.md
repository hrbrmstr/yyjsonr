

# yyjsonr 0.1.7 2023-09-10

* Unifed naming scheme

# yyjsonr 0.1.6 2023-09-04

* FEATURE: Added `promote_num_to_string` in `opts_read_json()` to enable 
  forced promotion of numerics to string
* BUGFIX: fixes for handling of geometry collection when reading and writing.
* TESTING: More tests included for output to geojson
* TESTING: Refactored testing of 'sf' objects

# yyjsonr 0.1.5  2023-08-31

* Bug fix for checking attributes on list columns.  This surfaced more
  errors to do with setting XYZ geometry type.
* More extensive testing of `write_geojson_str()`

# yyjsonr 0.1.4  2023-08-27

* Initial **alpha** GeoJSON support:
    * `read_geojson_str()`, `read_geojson_file()`
        * Needs more testing for corner cases
    * `write_geojson_str()`, `write_geojson_file()`
        * At a very alpha stage.

# yyjsonr 0.1.3  2023-08-21

* Added `validate_json_file()` and `validate_json_str()`

# yyjsonr 0.1.2  2023-08-20

* Added `write_ndjson_file()` and `write_ndjson_str()`

# yyjsonr 0.1.1  2023-08-19

* Update to option setting to remove overhead
* Added `read_json_raw()` to parse JSON directly from a raw vector (which
  contains UTF-8 string data)

# yyjsonr 0.1.0  2023-08-16

* Initial release
