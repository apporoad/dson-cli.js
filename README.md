# dson-cli.js
cli for dson

```bash
npm i -g dson-cli.js

dson '{"abc"：1}' abc

dson data.json  abc.c

dson http://xxxxxx/abc.json  n1[0].abc -o yaml

dson abc.json  n1[0].abc -o yaml

dson '[{"name":"hi"},{"name":"hello"}]'  '' -o table

dson data.json dson.js -t result.json

dson data.json dson.js -t result.yaml

```