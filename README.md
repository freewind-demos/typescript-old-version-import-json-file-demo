TypeScript Import Json File Demo
================================

```
npm install
npx tsc
node hello.js
```

It will print `{ name: 'typescript' }`

Notice
------

I was using `ts-node` to run ts files without compilation, but seems it do not work well with `.json` importing.
See this demo: https://github.com/freewind-demos/ts-node-import-json-file-issue-demo

So I use `tsc` in this demo.

