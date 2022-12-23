<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div :style="`position: absolute; background-color: #222; width:100%; height: 100%;`"></div>
 <div class="text-inverse">
  <nav class="navbar navbar-expand-lg">
  <div class="container-fluid">
    <a class="navbar-brand text-inverse" href="#">LongerCharts.com</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo02" aria-controls="navbarTogglerDemo02" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
      </ul>
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="text" placeholder="Username" aria-label="Search">
        <input class="form-control me-2" type="password" placeholder="Password" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Login</button>
      </form>
    </div>
  </div>
</nav>
<div class="">

  <div class="row justify-content-md-center m-auto">

    <h2>


    </h2>

    <div class="input-group input-group-lg">
      <input type="text" class="form-control" aria-label="Sizing example input" aria-describedby="inputGroup-sizing-lg" placeholder="Enter chart ticker...">
    </div>

  </div>


</div>



 </div>

</template>

<style scoped>
.bg-inverse { background-color: #222; }
.text-inverse { color: #fafafa !important }

.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
