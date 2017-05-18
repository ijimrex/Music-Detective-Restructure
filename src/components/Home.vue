<template>
  <div>

    <HeaderUp></HeaderUp>
    <div id="searchBody">
      <div id="videobg">
        <video autoplay muted loop style="width:100%;z-index: -999;position:absolute;" poster="/static/Cheer-Up/Snapshots/Cheer-Up.jpg">
          <source src="/static/Cheer-Up/MP4/Cheer-Up.mp4">
        </video>
      </div>
      <div class="container" >
      <div class="row" >
        <div class="col-lg-12 text-center">
          <div class="input-group">
            <div class="input-group-btn">
              <button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">搜索类型<span class="caret"></span></button>
              <ul class="dropdown-menu">
                <li><a href="#">歌名</a></li>
                <li><a href="#">歌手</a></li>
                <li><a href="#">专辑</a></li>

              </ul>
            </div><!-- /btn-group -->
            <input type="text" class="form-control" aria-label="...">
            <span class="input-group-btn">
        <button class="btn btn-default" type="button">搜索</button>
      </span>
          </div><!-- /input-group -->


        </div><!-- /.col-lg-6 -->
      </div>

      </div>
    </div>

    <div id="rank">

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
    height: 100%;

  }
  #videobg{

  }
  .toMiddle{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);

  }
</style>
