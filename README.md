Install deps.

Then run `yarn build`

```
% yarn build
yarn run v1.22.10
$ next build

> Build error occurred
Error: Cannot find module 'terser-webpack-plugin'
Require stack:
- my-app-yarn/node_modules/next-pwa/build-custom-worker.js
- my-app-yarn/node_modules/next-pwa/index.js
- my-app-yarn/next.config.js
```

(Using npm produces exactly the same problem)
