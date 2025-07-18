<template>
  <hello-world />
</template>

<script>
  import HelloWorld from '../components/HelloWorld'

  export default {
    name: 'HomeView',

    components: {
      HelloWorld,
    },
  }
</script>
<template>
  <v-container>
    <ProductList />
  </v-container>
</template>

<script>
  import ProductList from '@/components/ProductList.vue' //ProductList.vueをインポート

  export default {
    name: 'HomeView',

    components: {
      ProductList,
    },
  }
</script>
