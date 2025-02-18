# trove-ned-periodicals

Examples of SQLite databases created by extracting and indexing the text content of NED periodicals. Includes custom metadata files for Datasette configuration.

These datasets were generated using notebooks in the [trove-ned](https://github.com/GLAM-Workbench/trove-ned/) repository.

For more information and documentation see the [Searchable database of content from The Triangle](https://glam-workbench.net/trove-ned/the-triangle/) section of the [GLAM Workbench](https://glam-workbench.net).

## Dataset summary
- [the-triangle.db](https://github.com/GLAM-Workbench/trove-ned-periodicals/blob/main/dbs/the-triangle/the-triangle.db) (41.5 MB, db)
- [metadata.json](https://github.com/GLAM-Workbench/trove-ned-periodicals/blob/main/dbs/the-triangle/metadata.json) (986 Bytes, application/json)


## Dataset details

### [the-triangle.db](https://github.com/GLAM-Workbench/trove-ned-periodicals/blob/main/dbs/the-triangle/the-triangle.db)

|                |                                                                                                                                                                                                                                                         |
|:---------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| date harvested | 2025-02-16                                                                                                                                                                                                                                              |
| file size      | 41.5 MB                                                                                                                                                                                                                                                 |
| format         | db                                                                                                                                                                                                                                                      |
| created by     | <a href='https://github.com/GLAM-Workbench/trove-ned/blob/master/create-searchable-database.ipynb'>Create a searchable database from issues of a NED periodical</a> ([documentation](https://glam-workbench.net/trove-ned/create-searchable-database/)) |
| query          | `nla.obj-3121636851`                                                                                                                                                                                                                                    |



### [metadata.json](https://github.com/GLAM-Workbench/trove-ned-periodicals/blob/main/dbs/the-triangle/metadata.json)

|                |                                                                                                                                                                                                                                                         |
|:---------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| date harvested | 2025-02-16                                                                                                                                                                                                                                              |
| file size      | 986 Bytes                                                                                                                                                                                                                                               |
| format         | application/json                                                                                                                                                                                                                                        |
| created by     | <a href='https://github.com/GLAM-Workbench/trove-ned/blob/master/create-searchable-database.ipynb'>Create a searchable database from issues of a NED periodical</a> ([documentation](https://glam-workbench.net/trove-ned/create-searchable-database/)) |
| query          | `nla.obj-3121636851`                                                                                                                                                                                                                                    |

## Examples of use

- [Explore using Datasette](https://glam-workbench.net/datasette-lite-search/?url=https%3A%2F%2Fgithub.com%2FGLAM-Workbench%2Ftrove-ned-periodicals%2Fblob%2Fmain%2Fdbs%2Fthe-triangle%2Fthe-triangle.db&install=datasette-template-sql&metadata=https://github.com/GLAM-Workbench/trove-ned-periodicals/blob/main/dbs/the-triangle/metadata.json)


----
Created by [Tim Sherratt](https://timsherratt.au) for the [GLAM Workbench](https://glam-workbench.net)