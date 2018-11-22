### snippets

- cln

```
    className=""
```

- dva

```
    export default {
        namespace: '${1:namespace}',
        state: {},
        reducers: {
            save(state, { payload }) {
            }
        },
        effects: {
            * ${2:effect} ({ payload }, { put, call }) {

            }
        }
    };
```
