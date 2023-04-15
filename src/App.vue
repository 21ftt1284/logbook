<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <!-- <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" /> -->

  <div class="bg-gradient-to-r from-pink-100 to-blue-700 p-10">
    <div class="md:flex md:flex-cols-2 place-content-center justify-center items-center">
    <!-- <div class="flex place-content-center justify-center items-center "> -->
    <div class="flex place-content-center justify-center items-center">
        <!-- <img class="border-solid border-4 w-2/4 md:w-full border-black md:border-white rounded-xl sm:rounded-3xl" src="/public/img/photo.jpg" alt="Student Image"> -->
    </div>
      <div>
        <table class="bg-gradient-to-r from-indigo-100 to-black p-5 m-5">
          <thead>
            <tr>
              <th class="bg-black"></th>
              <th class="p-5 bg-gradient-to-r from-black to-gray-800">Student Information</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <th class="bg-indigo-800 p-5">Name: </th>
              <td>Koh Pee Lie</td>
            </tr>
            <tr>
              <th class="bg-indigo-800 p-5">Course: </th>
              <td>Level 5 Diploma in Web Development</td>
            </tr>
            <tr>
              <th class="bg-indigo-800 p-5">IC Number: </th>
            </tr>
            <tr>
              <th class="bg-indigo-800 p-5">Address: </th>
            </tr>
            <tr>
              <th class="bg-indigo-800 p-5">Student ID: </th>
              <td>21FTT1284</td>
            </tr>
            <tr>
              <th class="bg-indigo-800 p-5">Student Email: </th>
              <td>21FTT1284@student.pb.edu.bn</td>
            </tr>
            <tr>
              <th class="bg-indigo-800 p-5">Phone Number: </th>
              <td>7327103</td>
            </tr>
          </tbody>
      </table>
    </div>
    </div>
</div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
