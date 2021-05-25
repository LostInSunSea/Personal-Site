[<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <a class="navbar-item" href="https://bulma.io">
        <img src="https://bulma.io/images/bulma-logo.png" width="112" height="28">
      </a>
      <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false"
        data-target="navbar-main">
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>
    <div id="navbar-main" class="navbar-menu">
      <div class="navbar-start">
        <a class="navbar-item">
          Home
        </a>
        <a class="navbar-item">
          Projects
        </a>
        <a class="navbar-item">
          About Me
        </a>
        <a class="navbar-item">
          Blogs
        </a>
      </div>
    </div>
  </nav>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .navbar{
        background-color: #273c77;
    }
    .navbar-item{
        color: #E7ECEF;
    }
</style>
