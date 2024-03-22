<template>
  <div class="home">
      <div class="h-full grid grid-cols-4">
        <div class="h-screen bg-slate-100 p-3">
            <div class="">
              <div class="flex justify-between">
                <h4 class="font-bold">Personal Detail</h4>
                <span class="font-bold cursor-pointer">v</span>
              </div>
              <div>
                <label for="name">Name</label>
                <input type="text" placeholder="Your Name">
              </div>
            </div>
        </div>
        <div class="col-span-3 p-3">Right Side</div>
      </div>
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
