<template>
  <div>
    <b-navbar toggleable="md" class="nav-custom">
      <b-container>
        <b-navbar-brand> <h3> The Cumillaian </h3> </b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>

          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-nav-item to="/home">Home</b-nav-item>
            <b-nav-item to="/review">Review</b-nav-item>
            <b-nav-item to="/about-us">About Us</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-container>
    </b-navbar>
  </div>
</template>

<style scoped>
  .nav-custom {
    background: #ffffffd9;
    box-shadow: 0px 5px 5px -5px #b9b9b9;
  }
  .navbar-brand  {
    color: #1A237E !important;
  }
  .nav-custom .container {
    width: 85%;
    margin: 0 auto;
  }
  .navbar-light .navbar-nav .nav-link {
    color: #1A237E;
    font-family: 'Open Sans', sans-serif;
    font-weight: 700;
    padding: 0;
    margin: 8px 1rem !important;
  }
</style>