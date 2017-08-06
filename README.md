# 5e-json-schema
A JSON schema for storing D&amp;D 5th Edition data

You can use the ajv library to validate the schema, or validate data against the schema

```sh
npm install -g ajv-cli
ajv compile -s *.json  -r *.json
```