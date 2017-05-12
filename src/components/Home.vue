<template>
  <div>

    <HeaderUp></HeaderUp>
    <div id="searchBody">
      <div class="row">
        <video autoplay muted loop style="width:100%;z-index: -999;position:absolute;" poster="/static/Cheer-Up/Snapshots/Cheer-Up.jpg">
          <source src="/static/Cheer-Up/MP4/Cheer-Up.mp4">
        </video>
        <div class="col-xs-12 col-sm-6">.col-xs-12 .col-sm-3</div>
        <div class="col-xs-12 col-sm-6">.col-xs-12 .col-sm-3</div>

      </div>


    </div>
  </div>
</template>






<script>
  import HeaderUp from './Header'
  export default {
//    components: {HeaderUp},
    name: 'home',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
<style>
  #searchBody{
    margin-top: 50px;
  }
</style>
