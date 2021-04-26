# argparse

Supports

* `-bool_arg_name` via `getBoolArg("bool_arg_name", argc, argv)` (will return `1`)
* `-str_arg_name some_string` via `getStrArg("str_arg_name", "default_str", argc, argv)` (will return `"some_string"`)
* `-list_arg_name some list values` via `getListArg("list_arg_name", default_list, argc, argv)` (will return `{"some", "list", "values", ""}`)

Created to solve problems, not to be awesome