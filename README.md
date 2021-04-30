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
 App.vue
```

# Naming

## Modules

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
