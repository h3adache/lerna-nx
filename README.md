1. create empty project
1. follow steps https://lerna.js.org/docs/getting-started
1. add `npmScope` to `nx.json`
1. create library `npx nx g @nrwl/js:lib lib-test --skipTsConfig --unitTestRunner none --config npm-scripts`
1. Run `lerna bootstrap`
1. Run `lerna run build`


```
npx lerna run build
lerna notice cli v5.1.4

 >  Lerna (powered by Nx)   Cannot find project '@myorg/lib-test'
```
