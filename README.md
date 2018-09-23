# jsonschema

Collection of JSON Schema.

## Commands

### sort `oneOf.$ref` kubernetes open-api spec

```sh
jq '.oneOf | sort_by(.ref)' all.json | pbcopy
```
