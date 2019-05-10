# scan2deploy-android-schema

This repo stores the JSON schema used by [Scan2Deploy Android](https://github.com/datalogic/scan2deploy-android). The latest "stable" version of the schema is also available at [schemastore.org](http://json.schemastore.org/datalogic-scan2deploy-android). The schema follows the conventions of [SchemaVer](https://github.com/snowplow/iglu/wiki/SchemaVer), provided here for convenience:

SchemaVer is defined as follows: MODEL-REVISION-ADDITION

* MODEL when you make a breaking schema change which will prevent interaction with any historical data
* REVISION when you introduce a schema change which may prevent interaction with some historical data
* ADDITION when you make a schema change that is compatible with all historical data

The [schema.json](schema.json) file doesn't contain any indication of it's version on it's own. Instead, we use Github's [releases](releases) to version the schema.