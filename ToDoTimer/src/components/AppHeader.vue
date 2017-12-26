<template>
  <sui-menu :widths="2" :activeIndex="clicked" :pointing="true">
    <sui-menu-item>Home</sui-menu-item>
    <sui-menu-item>About</sui-menu-item>
  </sui-menu>
</template>

<script>
  export default{
    name: 'AppHeader',

    data () {
      return {

      }
    },
    methods () {
      return {
        clicked: function(){

        }
      }
    }
  }
</script>
