<template>
  <div id="app">
    <el-container>
      <el-header>
        <router-link to="/">
          <h1 class="logo">AITA</h1>
        </router-link>
        <div class="nav">
          <router-link to="/course-manage">课程管理面板</router-link>
          <router-link to="/person-info">个人信息</router-link>
        </div>
      </el-header>
      <el-main>
        <router-view />
      </el-main>
    </el-container>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  line-height: 60px;
}
.logo{
  float: left;
  margin: 0;
  color: black;
}
.el-header{
  margin-left: 20%;
  margin-right: 15%;
  font-size: 1.2em;
}
.nav a{
  float: right;
  text-decoration: none;
  color: gray;
  margin-left: 6%;
}
html, body{
  padding: 0;
  margin: 0;
}
</style>
