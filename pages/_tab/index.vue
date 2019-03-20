<template>
    <div>test{{$route.params.tab}}</div>
</template>

<script>
  export default {
    name: 'index',
    created(){
      console.log('oi');
    }
  };
</script>

<style scoped>

</style>
