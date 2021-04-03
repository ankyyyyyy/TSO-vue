<template>

  <div id="main-container">
    <cont_header/>
    <cont_sidebar/>
    <cont_bottombar/>
  </div>

</template>

<script>
import cont_bottombar from "./components/bottombar"
import cont_sidebar from "./components/sidebar"
import cont_header from "./components/header"
export default {
  name: 'App',
  components: {
   cont_header,
   cont_sidebar,
   cont_bottombar
  }
}
</script>

<style>

</style>
