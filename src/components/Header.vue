<template>
  <!--<nav class="navbar navbar-default navbar-fixed-top navbar-inverse" role="navigation">-->
    <!--<div class="container-fluid">-->
      <!--<div class="navbar-header">-->
        <!--<a class="navbar-brand" href="#">Muisc Detective</a>-->
      <!--</div>-->
      <!--<div>-->
        <!--<ul class="nav navbar-nav">-->
          <!--<li class="active"><a href="#">主页</a></li>-->
          <!--<li><a href="#">排行榜</a></li>-->
          <!--<li class="dropdown">-->
            <!--<a href="#" class="dropdown-toggle " data-toggle="dropdown">-->
              <!--播放列表 <b class="caret"></b>-->
            <!--</a>-->
            <!--<ul class="dropdown-menu">-->
              <!--<li><a href="#">jmeter</a></li>-->
              <!--<li><a href="#">EJB</a></li>-->
              <!--<li><a href="#">Jasper Report</a></li>-->
              <!--<li class="divider"></li>-->
              <!--<li><a href="#">分离的链接</a></li>-->
              <!--<li class="divider"></li>-->
              <!--<li><a href="#">另一个分离的链接</a></li>-->
            <!--</ul>-->
          <!--</li>-->
        <!--</ul>-->
      <!--</div>-->
    <!--</div>-->
  <!--</nav>-->
  <nav class="navbar navbar-default navbar-fixed-top navbar-inverse" role="navigation">
    <div class="container-fluid">
      <div class="navbar-header">
        <button type="button" class="navbar-toggle" data-toggle="collapse"
                data-target="#example-navbar-collapse">
          <span class="sr-only"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
        </button>
        <a class="navbar-brand" href="#">Music Detective</a>
      </div>

      <div class="collapse navbar-collapse" id="example-navbar-collapse">
        <ul class="nav navbar-nav">
          <li class="active"><a href="#">主页</a></li>
          <li><a href="http://www.baidu.com">排行榜</a></li>
          <li class="dropdown">
            <a href="#" class="dropdown-toggle" data-toggle="dropdown">
              播放列表 <b class="caret"></b>
            </a>
            <ul class="dropdown-menu">
              <li><a href="#">jmeter</a></li>
              <li><a href="#">EJB</a></li>
              <li><a href="#">Jasper Report</a></li>
              <li class="divider"></li>
              <li><a href="#">分离的链接</a></li>
              <li class="divider"></li>
              <li><a href="#">另一个分离的链接</a></li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
  export default{
    name:'header'
  }
</script>
