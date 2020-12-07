<template>
  <div class="home">
    <post-list></post-list>
  </div>
</template>

<script>
import PostList from '../components/PostList.vue';
// @ is an alias to /src

export default {
  name: "Home",
  components: {
    PostList
  }
};
</script>
<style>
    
</style>