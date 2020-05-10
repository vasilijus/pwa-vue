# vuetest1

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).



### Extras
```
vue add vutify

npm install -g firebase-tools
```

### Generated manifest
```
https://app-manifest.firebaseapp.com/
```

### Service worker 
```
workbox wizard 
```

### Vue router
```
It is easy to integrate Vue Router in our Vue application.
1. Install the plug-in.
$npm install vue-router
2. Add VueRouter in main.js.
...
import VueRouter from 'vue-router'
...
Vue.use(VueRouter);
3. Create routes in a new routes.js file.
import HelloWorld from './components/HelloWorld.vue'
export const routes = [
  {path: ", component: HelloWorld}
];
4. Create a VueRouter instance.
const router = new VueRouter({routes});
5. Add VueRouter to Vue instance.
const app = new Vue({
  router
}).$mount('#app')
```