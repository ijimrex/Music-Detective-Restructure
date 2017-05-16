<template>
  <div>

    <HeaderUp></HeaderUp>
    <div id="searchBody">
      <div id="videobg">
        <video autoplay muted loop style="width:100%;z-index: -999;position:absolute;" poster="/static/Cheer-Up/Snapshots/Cheer-Up.jpg">
          <source src="/static/Cheer-Up/MP4/Cheer-Up.mp4">
        </video>
      </div>
      <div class="container">
      <div class="row">
        <div class="col-lg-6">
          <div class="input-group">
            <input type="text" class="form-control" placeholder="Search for...">
            <span class="input-group-btn">
        <button class="btn btn-default" type="button">Go!</button>
      </span>
          </div><!-- /input-group -->
        </div><!-- /.col-lg-6 -->
      </div>
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
  @media all and (max-width: 765px) {
    #videobg{
      display: none;
    }
    #searchBody{
      margin-top: 50px;
      background: darkslateblue;
      min-height: 400px;

    }

  }
  #searchBody{
    margin-top: 50px;

  }
  #videobg{

  }
</style>
