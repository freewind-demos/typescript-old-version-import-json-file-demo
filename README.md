TypeScript(< 2.9) Import Json File Demo
=======================================

Typescript 2.9 has `resolveJsonModule` support, which makes importing json file in typescript easily.
But old versions don't have, so we have to define some typings for json files.

```
npm install
npx tsc
node hello.js
```

It will print `{ name: 'typescript' }`

Notice
------

I was using `ts-node` to run ts files without compilation, but seems not work well with `.json` importing with old versions of typescript.
See this demo: https://github.com/freewind-demos/ts-node-import-json-file-issue-demo

So I use `tsc` in this demo.

