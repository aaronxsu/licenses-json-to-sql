# licenses-json-to-sql

This repo contains Scala code to simply transform [SPDX licenses](https://github.com/sindresorhus/spdx-license-list/blob/master/spdx.json) from json to a string to be inserted into the sql command.

## How to use:
1. `cd spdx-license-json-to-sql-string`
2. Modify the Json string in `src/main/scala/Main.scala`. It should have the following fields: short_name, name, url, osi_approved.
3. `sbt`
4. `~run`
5. Copy the output.
