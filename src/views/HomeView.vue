<template>
  <div class="home">
    <a href="https://github.com/ladjeek-actions">
      <button class="mdui-btn mdui-color-teal mdui-ripple-blue">GitHub</button>
    </a>
    <router-link to="/about/">
      <button class="mdui-btn mdui-color-teal mdui-ripple-blue">About</button>
    </router-link>
    <router-link to="/games/">
      <button class="mdui-btn mdui-color-teal mdui-ripple-blue">Games</button>
    </router-link>
    <HelloWorld class="all" msg="我的项目" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>
