# vue-application

```
js
└───app
└───modules
└───partials
└───templates
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
