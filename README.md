# oatsSwaggerTest
swaggering oaty fella


error i currently get
```
(node:1452) UnhandledPromiseRejectionWarning: SyntaxError: Error resolving $ref pointer "/go/src/github.com/influxdata/swaggerTest/paths/signin.yml#/components/schemas/Error". 
Token "components" does not exist.
    at Pointer.resolve (/go/src/github.com/influxdata/influxdb/ui/node_modules/json-schema-ref-parser/lib/pointer.js:87:17)
    at $Ref.resolve (/go/src/github.com/influxdata/influxdb/ui/node_modules/json-schema-ref-parser/lib/ref.js:83:18)
    at $Refs._resolve (/go/src/github.com/influxdata/influxdb/ui/node_modules/json-schema-ref-parser/lib/refs.js:155:15)
    at inventory$Ref (/go/src/github.com/influxdata/influxdb/ui/node_modules/json-schema-ref-parser/lib/bundle.js:99:23)
    at crawl (/go/src/github.com/influxdata/influxdb/ui/node_modules/json-schema-ref-parser/lib/bundle.js:74:11)
    at crawl (/go/src/github.com/influxdata/influxdb/ui/node_modules/json-schema-ref-parser/lib/bundle.js:77:11)
    at crawl (/go/src/github.com/influxdata/influxdb/ui/node_modules/json-schema-ref-parser/lib/bundle.js:77:11)
    at crawl (/go/src/github.com/influxdata/influxdb/ui/node_modules/json-schema-ref-parser/lib/bundle.js:77:11)
    at crawl (/go/src/github.com/influxdata/influxdb/ui/node_modules/json-schema-ref-parser/lib/bundle.js:77:11)
(node:1452) UnhandledPromiseRejectionWarning: Unhandled promise rejection. This error originated either by throwing inside of an async function without a catch block, or by rejecting a promise which was not handled with .catch(). To terminate the node process on unhandled promise rejection, use the CLI flag `--unhandled-rejections=strict` (see https://nodejs.org/api/cli.html#cli_unhandled_rejections_mode). (rejection id: 2)
(node:1452) [DEP0018] DeprecationWarning: Unhandled promise rejections are deprecated. In the future, promise rejections that are not handled will terminate the Node.js process with a non-zero exit code.
```
