<template>
  <div id="app">
    <v-header></v-header>
    <div class="header">
       I am header!
    </div>
    <div class="tab">
      I am TAB!
    </div>
    <div class="content">
      CONTENT
    </div>
  </div>
</template>

<script>
import header from './components/header/header.vue';

export default{
    components: {
        'v-header': header
    }
};
</script>

<style>

</style>
