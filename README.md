# vue-application

```
js
└───app
│   api.service.js
│   config.js
│   constants.js
│   enums.js
│   helpers.js
│   types.js
│   
└───modules
│   └───auth
│   │   └───views
│   │   │   └───components
│   │   │   │   Header.vue
│   │   │   │   ...
│   │   │   │
│   │   │   Login.vue
│   │   │   Register.vue
│   │   │   ...
│   │   │
│   │   auth.api.js
│   │   auth.module.js
│   │   ...
│   │
│   ...
│
└───templates
│   └───components
│   │   Header.vue
│   │   Sidebar.vue
│   │   ...
│   │
│   Base.vue
│   Page.vue
│   Wrapper.vue
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
│   directives.js
│   filters.js
│   i18n.js
│   libraries.js
│   mixins.js
│   router.js
│   store.js
│   ...
    
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
