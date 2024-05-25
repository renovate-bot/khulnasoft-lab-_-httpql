# HTTPQL

[<img alt="github" src="https://img.shields.io/badge/github-khulnasoft/httpql-8da0cb?style=for-the-badge&labelColor=555555&logo=github" height="20">](https://github.com/khulnasoft-lab/httpql)
[<img alt="crates.io" src="https://img.shields.io/npm/v/@khulnasoft/httpql?style=for-the-badge" height="20">](https://www.npmjs.com/package/@khulnasoft/httpql)

This is the JS parser for the [HTTPQL language](https://docs.khulnasoft.com/internals/httpql.html).

```typescript
import { deserialize, serialize } from "@khulnasoft/httpql";

const parsed = deserialize('req.ext.cont:"HELLO"');
console.log(parsed);
const result = serialize(parsed);
console.log(result);
```
