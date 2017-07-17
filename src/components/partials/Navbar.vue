<template>
  <nav class="navbar navbar-toggleable-md navbar-light bg-faded sticky-top">
    <a class="navbar-brand" href="#">Navbar</a>
  
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <router-link class="nav-link" :to="{ path: '/hello' }">入口頁面</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" :to="{ path: '/static' }">樣板頁面</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" :to="{ path: '/chatroom' }">聊天室</router-link>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'navbar',
  data() {
    return {
      data: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
