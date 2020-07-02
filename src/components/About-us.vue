<template>
  <div>
    <!-- about us start -->
  <section class="about-us">
    <div class="about-us-container">
      <h2 class="heading">About Us</h2>
      <p>
        We are The Cumillaian team and The Cumillaian is a platform which is based on Cumilla district. Here famous travelling places in Cumilla's are included on it. We works to merge
        all item of places in one place so that travel lovers can find their favorite places. Also they can see and post ratings and comments about our site.
        <br><br>
        The Cumillaian has started its journey from 2020. It has invested its effort to all information about travelling places in cumilla. The Cumillaian would
        like to make travel lovers smile.
        <br>
        And off course! we bring this kind of site for the first time in Cumilla.
      </p>
    </div>
  </section>
  <!-- about us end -->

  <!-- objective start -->
  <section class="objective">
    <div class="objective-container">
      <h2 class="heading">Objective</h2>
      <ul>
        <li>
          Find travellers favorite place
        </li>
        <li>
          Get all beautiful places in one place
        </li>
        <li>
          See review and find a best place for your tour
        </li>
      </ul>
    </div>
  </section>
  <!-- objective end -->
  </div>
</template>

<style scoped>
.about-us {
  margin: 3rem 0 4rem;
  font-family: 'Roboto', sans-serif;
}
.about-us .about-us-container {
  width: 70%;
  margin: 0 auto;
}
.about-us .heading {
  padding-bottom: .5rem;
}
.about-us p {
  color: #505050;
}

/* objective */
.objective {
  margin-bottom: 4rem;
  font-family: 'Roboto', sans-serif;
}
.objective .objective-container {
  width: 70%;
  margin: 0 auto;
}
.objective .heading {
  padding-bottom: .5rem;
}
.objective ul {
  color: #505050;
  padding-left: 1rem;
}
@media (max-width: 767px) {
  /* about us */
  .about-us .about-us-container {
    width: 90% !important;
  }
  .objective .objective-container {
    width: 90% !important;
  }
}
</style>