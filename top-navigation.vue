<template>
     <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
      <a class="navbar-brand" href="#">Navbar</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarsExampleDefault" aria-controls="navbarsExampleDefault" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarsExampleDefault">
        <ul class="navbar-nav mr-auto">
           <router-link active-class="active" tag="li" class="nav-item" to="home">
            <a class="nav-link">Hem</a>
          </router-link>
          <router-link active-class="active" tag="li" class="nav-item" to="foo">
            <a class="nav-link">Foo2</a>
          </router-link>
          <router-link active-class="active" tag="li" class="nav-item" to="bar">
            <a class="nav-link">Bar</a>
          </router-link>
          
        </ul>        
      </div>
    </nav>
</template>

<script>
module.exports = {
  data: function() {
    return {};
  }
};
</script>

<style>
/* Move down content because we have a fixed navbar that is 3.5rem tall */
body {
  padding-top: 3.5rem;
}
</style>