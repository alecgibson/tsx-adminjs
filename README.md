# `tsx-adminjs`

## Repro steps

 1. `npm i`
 2. `npm test`


## Expected result

Would expect to see "success" printed to logs.


## Actual result

Instead get an incomprehensible error:

```
Error: Parse error @:53:18
    at _e (<home_dir>/tsx-adminjs/node_modules/tsx/dist/index-c4b20163.mjs:8:8007)
    at Te (<home_dir>/tsx-adminjs/node_modules/tsx/dist/index-c4b20163.mjs:13:66)
    at ke (<home_dir>/tsx-adminjs/node_modules/tsx/dist/index-c4b20163.mjs:14:249)
    at rt (<home_dir>/tsx-adminjs/node_modules/tsx/dist/esm/index.mjs:13:1886)
    at async nextLoad (node:internal/modules/esm/hooks:833:22)
    at async Hooks.load (node:internal/modules/esm/hooks:416:20)
    at async handleMessage (node:internal/modules/esm/worker:168:18)
```
