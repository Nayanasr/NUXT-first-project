<template>

<div>
  <nav class="navbar navbar-expand-lg bg-light">
  <div class="container-fluid">
    <NuxtLink class="navbar-brand" to="/">COSMOS</NuxtLink>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <NuxtLink class="nav-link active" aria-current="page" to="/">Home</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink class="nav-link" to="/login">Log-in</NuxtLink>
        </li>
      </ul>
    </div>
  </div>
</nav>
</div>
</template>

<script>
export default {

}
</script>

<style>

</style>