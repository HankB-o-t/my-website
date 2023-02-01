<template>
  <div class="topnav">
    <a>💻 Portfolio.js</a>
    <a>Site by slaim</a>
    <button class="a" @click="funni()">Click me</button>
  </div>
</template>

<script setup>

function funni() {
  alert("Funni button")
}

</script>

<style>
.topnav {
  background-color: #333;
  overflow: hidden;
  border-radius: 10px;
}

/* Style the links inside the navigation bar */
.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}
.topnav button {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}


/* Change the color of links on hover */
.topnav a:hover {
  background-color: #ddd;
  cursor: pointer;
  color: black;
}


.topnav a.active {
  background-color: #ffe284;
  color: white;
}
</style>