# vue-cli

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).

### Directives

* All the `v-` stuff
* Can create your own `v-directive`
* `v-` notifies Vue that this is a directive

#### Hooks
* Directives have 5 Hooks (lifecycle type functions)
1. Bind - fired when directive is attached
    * el - element
    * binding - arguments, modifiers
    * vnode - node on the virtual node
2. Inserted - fired when inserted in Parent Node
    * el - element
    * binding
    * vnode
3. Update - fires when component is updated (without Children)
    * el
    * binding
    * vnode
    * oldVnode - the old version of the node
4. componentUpdated - fires when component **AND** children have been updated
    * el
    * binding
    * vnode
    * oldVnode
5. unbind - once directive is removed
    * el
    * binding
    * vnode


    