<template>
  <div class="home">
    <!-- <HelloWorld msg="Meu primeiro projeto com vue.js"/> -->
    <h1> {{name}} </h1>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'Home',
  data() {
    return {
      name: 'teste',
    };
  },
  components: {
    // HelloWorld,

  },
};
</script>
