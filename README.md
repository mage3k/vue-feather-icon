## This repo is no longer maintained

Recommended [vue-feather-icons](https://github.com/egoist/vue-feather-icons) for your project instead.

# vue-feather-icon

Vue component for [Feather](https://feathericons.com)

## install

```shell
npm install vue-feather-icon
```

## usage

### global component
```javascript
// main.js
import Vue = from 'vue'
import VueFeatherIcon from 'vue-feather-icon'

Vue.use(VueFeatherIcon)
```

```vue
<template>
  <feather-activity></feather-activity>
  <!-- or -->
  <feather-icon type="activity"></feather-icon>
</template>
```


### local component

```vue
<script>
  import { Activity } from 'vue-feather-icon'

  export default {
    components: {
      ActivityIcon: Activity
    }
  }
</script>

<template>
  <activity-icon></activity-icon>
</template>
```
