# To reproduce the problem try to run in '/old' and in 'new':

```bash
yarn

yarn test:e2e
```

It will run same tests in '/old' and in 'new'. In '/old' works well, in '/new' fails with error:

```
 1) getVue cannot return DOM elements. Use Selector functions for this
      purpose.
```
