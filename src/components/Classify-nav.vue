<template>
  <div class="container navbar-collapse">
      <nav class="navbar">
          <ul class="nav-box">
              <li>
                  <router-link :to="{name:'all'}">全部</router-link>
              </li>
              <li>
                  <router-link :to="{name:'elasticsearch'}">Elasticsearch</router-link>
              </li>
              <li>
                  <router-link :to="{name:'logstash'}">Logstash</router-link>
              </li>
              <li>
                  <router-link :to="{name:'kibana'}">Kibana</router-link>
              </li>
              <li>
                  <router-link :to="{name:'beats'}">Beats</router-link>
              </li>
              <li>
                  <router-link :to="{name:'job'}">求职招聘</router-link>
              </li>
              <li>
                  <router-link :to="{name:'dynamic'}">资讯动态</router-link>
              </li>
              <li>
                  <router-link :to="{name:'activityII'}">活动</router-link>
              </li>
              <li>
                  <router-link :to="{name:'daily'}">Elastic日报</router-link>
              </li>
          </ul>
      </nav>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.container{
    margin-bottom: 20px;
}
.navbar{
    min-height: 30px;
    margin-bottom: 0px;
}
    .nav-box li{
        float: left;
        margin: 0px 10px 10px 0px;
        /* height: 30px;
        line-height: 30px;
        text-align: center;
        border-radius: 5px; */

    }
    .nav-box li a{
        display: inline-block;
        height: 30px;
        line-height: 30px;
        text-align: center;
        border-radius: 5px;
        color: rgb(58, 54, 54);
        padding: 0px 10px;
    }
    .nav-box li a.active,.nav-box li a:hover{
        text-decoration: none;
        color: #fff;
         background-color: #494a4b;
    }
    /* .nav-box li:hover{
        background-color: #494a4b;
    } */
</style>