<template>
  <div class="app">
    <div class="app-header">
      <h2 class="app-welcome">Welcome to Dawn</h2>
    </div>
    <div class="app-intro">
      <img src="../assets/logo.png" class="app-logo" alt="logo" />
      <div>
        To get started, edit
        <code>src/components/App.vue</code> and save to reload.
      </div>
    </div>
    <ul class="app-links">
      <li>
        <a href="https://alibaba.github.io/dawn/">Homepage</a>
      </li>
      <li>
        <a href="https://alibaba.github.io/dawn/docs">Documents</a>
      </li>
      <li>
        <a href="https://github.com/alibaba/dawn">Git Repo</a>
      </li>
      <li>
        <a href="https://github.com/alibaba/dawn/issues">Issues</a>
      </li>
    </ul>
  </div>
</template>

<style scoped>
.app {
  text-align: center;
  width: 900px;
  margin: 50px auto;
  box-shadow: 0 0 10px 1px rgba(0, 0, 0, .15);
  overflow: hidden;
  background: white;
}

.app-logo {
  height: 80px;
}

.app-header {
  background-color: #222;
  background: url('https://alibaba.github.io/dawn/assets/banner-sm.jpg');
  background-size: 100%;
  height: 190px;
  line-height: 190px;
  padding: 0 20px;
  color: rgba(255, 255, 255, .9);
  font-size: 30px;
}

.app-welcome {
  padding: 0;
  margin: 0;
  text-shadow: 2px 2px 10px rgba(0, 0, 0, .5);
}

.app-intro {
  font-size: large;
  padding: 40px;
}

.app-links {
  text-align: center;
  margin: 0;
  padding: 30px;
  border-top: solid 1px rgba(222, 222, 222, .5);
}

.app-links li {
  display: inline-block;
}

.app-links li a {
  padding: 5px;
  color: darkcyan;
}

.app-links li a:hover {
  color: goldenrod;
}

</style>

<script>
export default {

}
</script>
