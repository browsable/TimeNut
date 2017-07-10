<template>
  <div class="HeaderBar">{{msg}}</div>
</template>

<script>
  export default {
    name: 'HeaderBar',
    data() {
      return {
        msg: 'hello headerbar',
      };
    },

  };
</script>

<style>
.HeaderBar{
  background-color: blue;
}
</style>
