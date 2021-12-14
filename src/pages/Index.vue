<template>
  <q-page class="">
    <Item  v-for="i in 10" :key="i" :title="i" />
  </q-page>
</template>

<script>
import Item from '../components/Item.vue';

export default{
  name: 'PageIndex',
  components:{
    Item
  }
}
</script>
