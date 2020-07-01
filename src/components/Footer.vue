<template>
  <div class="footer">
    <div class="footer-container">
      <div class="row">
        <div class="col-sm-4 footer-each">
          <h5>Know Us</h5>
          <ul class="un-list">
            <li class=""> <b-link to="/about-us">About Us</b-link> </li>
            <li class=""> <b-link to="/terms-condition">Terms and Conditions</b-link> </li>
          </ul>
        </div>
        <div class="col-sm-4 footer-each">
          <h5>Contact Us</h5>
          <ul class="un-list">
            <li class=""> Phone: 01804001100 </li>
            <li class=""> Email: mailname@gmail.com </li>
          </ul>
        </div>
        <div class="col-sm-4 footer-each">
          <h5>Important Links</h5>
          <ul class="un-list">
            <li class=""> <b-link href="https://en.wikipedia.org/wiki/Comilla" target="_blank">Comilla in Wikipedia</b-link> </li>
            <li class=""> <b-link href="http://www.comilla.gov.bd/" target="_blank">comilla.gov.bd</b-link> </li>
          </ul>
        </div>
      </div>

      <div class="row mt-3">
        <div class="col-sm-12 text-center">
          <p>&copy; 2020 The Cumillaian, All rights Reserved</p>
        </div>
      </div>

    </div>
  </div>
</template>

<style scoped>
.footer {
  font-family: 'Roboto', sans-serif;
  font-weight: 400;
  background: #031936;
  color: #fff;
  padding: 3rem 0;
}
.footer .footer-container {
  width: 70%;
  margin: 0 auto;
}
.footer a {
  color: #fff;
}
.footer a:hover {
  text-decoration: none;
}
.footer .footer-each h5 {
  font-weight: 500;
  margin-bottom: 12px;
}
.footer .footer-each ul {
  list-style: none;
  padding: 0;
}
.footer .footer-each ul li {
  padding: 2px 0;
}

@media (max-width: 991px) {
  .footer .footer-container {
    width: 90%;
  }
}
@media (max-width: 575px) {
  .footer .footer-container {
    width: 85%;
  }
  .footer .footer-each {
    margin-bottom: .5rem;
  }
}
</style>