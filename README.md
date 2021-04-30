# vue-application

```
js
└───app
│   api.js
│   config.js
│   constants.js
│   helpers.js
│   index.js
│   states.js
│   types.js
│   window.js
│   ...
│   
└───modules
│   └───auth
│   │   └───components
│   │   │   Header.vue
│   │   │   ...
│   │   │
│   │   └───concerns
│   │   │   auth.api.js
│   │   │   auth.module.js
│   │   │   ...
│   │   │
│   │   Login.vue
│   │   Register.vue
│   │   ...
│   │
│   │
│   ...
│
└───templates
│   └───components
│   │   Header.vue
│   │   Sidebar.vue
│   │   ...
│   │
│   BasePage.vue
│   DefaultPage.vue
│   RouterWrapper.vue
│   ...
│   
└───ui
│   └───form
│   │   Input.vue
│   │   Select.vue
│   │   ...
│   │
│   └───table
│   │   Table.vue
│   │   Tr.vue
│   │   ...
│   │
│   Badge.vue
│   Card.vue
│   ...
│   
└───vue
│   app.js
│   App.vue
│   directives.js
│   event.bus.js
│   filters.js
│   i18n.js
│   index.js
│   libraries.js
│   mixins.js
│   router.js
│   store.js
│   ...
│
 app.js
```

# Naming

## `app.js`

```js
require('./app');
require('./vue');
```

## `./modules`

```
js
└───modules
│   └───orders
│   │   Index.vue
```

```js
<template>
   <div></div>
</template>
<script>
  export default {
    name: 'OrderIndex'
  }  
</script>
```

## `vue`

### `vue/app.js`

```js
import i18n from './i18n';
import App from './App.vue';

import store from './store';
import router from './router';
import i18n from './i18n';

const app = new Vue({
    render: h => h(App),
    store,
    router,
    i18n,
}).$mount('#app');

export default app;
```

### `vue/index.js`

```js
require('./app');
require('./i18n');
```
