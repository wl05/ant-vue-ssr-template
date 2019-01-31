<template>
    <div class="welcome">
        welcome to {{welcome}}
    </div>
</template>

<script>
  export default {
    name : 'welcome',
    props : {
      name : {
        type : String,
        default : ''
      }
    },
    data () {
      return {
        welcome : 'blog'
      };
    }
  };
</script>

<style lang="scss">

</style>
