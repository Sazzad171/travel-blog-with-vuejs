<template>
  <div>
  <section class="hero-all-place">
    <h2 class="all-place-heading"> <span>Visiting Places in Cumilla</span> </h2>
  </section>

  <section class="menu-all-place">
    <div class="menu-full">
      <div class="menu-container">

        <div class="row">
           <div v-bind:key="blog.id" v-for="blog in blogs" class="col-sm-4 item-each">
              <b-link :to="blog.single_link">
                <img class="img-fluid" :src="blog.img_link" alt="">
                <div class="title">
                  <h5 class="name"> {{blog.pl_name}} </h5>
                  <div class="location">
                    <b-icon-geo-alt></b-icon-geo-alt>
                    <span> {{blog.pl_location}} </span>
                  </div>
                </div>
              </b-link>
            </div>
        </div>

      </div>
    </div>
  </section>
  <!-- menu end -->
  </div>
</template>

<script>
export default {
  name: 'home',
  data() {
    return {
      blogs: [
        {
          id: 1,
          img_link: require("@/assets/shalbon-bihar.jpg"),
          pl_name: 'শালবন বৌদ্ধ বিহার',
          pl_location: 'কোটবাড়ি',
          single_link: '/shalbon-bihar'
        },
        {
          id: 2,
          img_link: require("@/assets/war_cemetery.jpg"),
          pl_name: 'ময়নামতি ওয়ার সিমেট্রি',
          pl_location: 'ময়নামতি',
          single_link: '/war-cemetry'
        },
        {
          id: 3,
          img_link: require("@/assets/lalmai_lakeland.png"),
          pl_name: 'লালমাই ল্যাকল্যান্ড',
          pl_location: 'লালমাই',
          single_link: '/lalmai-lakeland'
        },
        {
          id: 4,
          img_link: require("@/assets/magic_paradise.png"),
          pl_name: 'ম্যাজিক প্যারাডাইজ পার্ক',
          pl_location: 'কোটবাড়ি',
          single_link: '/magic-paradise'
        },
        {
          id: 5,
          img_link: require("@/assets/Nawab_Faizunnesa_House.png"),
          pl_name: 'নবাব ফয়জুন্নেসা জমিদার বাড়ি',
          pl_location: 'লাকসাম',
          single_link: '/nawab-faisunnesa-bari'
        },
        {
          id: 6,
          img_link: require("@/assets/rupsagor.png"),
          pl_name: 'রূপসাগর',
          pl_location: 'ক্যান্টনমেন্ট, কুমিল্লা ',
          single_link: '/rup-sagor'
        }
      ]
    }
  },
  // methods: {
  //   singleId(id) {
  //     if( id == 1 ) {
  //       var singlePlRoute = "single-place";
  //     }
  //   }
  // }
}
</script>

<style scoped>
.hero-all-place {
  background: url('../assets/all-place-bg.jpg') center center;
}
.hero-all-place .all-place-heading {
  text-align: center;
  padding: 13rem 0 11rem;
  font-size: 40px;
  color: #fff;
}
.hero-all-place .all-place-heading span {
  font-family: 'Roboto', sans-serif;
  font-weight: 700;
  border-radius: 8px;
  background: #0000007a;
  padding: 1rem 2rem;
  box-shadow: 0 2px 11px 0 rgba(0,0,0,.14);
}
.menu-all-place {
  padding: 3rem 0;
  font-family: 'Roboto', sans-serif;
}
.menu-all-place .menu-container {
  width: 70%;
  margin: 0 auto;
}
.menu-all-place .item-each {
  display: flex;
  justify-content: center;
  margin: 1rem 0;
  padding: 8px;
  border-radius: 8px;
  transition: all .3s ease-in-out;
}
.menu-all-place .item-each:hover {
  transform: translateY(-5px);
  box-shadow: 0 2px 11px 0 rgba(0,0,0,.14);
}
.menu-all-place .item-each a {
  color: #1A237E !important;
}
.menu-all-place .item-each a:hover {
  color: #1A237E !important;
  text-decoration: none;
}
.menu-all-place .item-each img {
  max-height: 240px;
  border-radius: 8px;
}
.menu-all-place .item-each .title {
  margin: 1rem 6px;
}
.menu-all-place .item-each .name {
  margin: 0;
  font-weight: 600;
}
.menu-all-place .item-each .price {
  font-weight: 500;
  font-size: 14px;
  margin: 4px 0;
}
.menu-all-place .location {
  font-weight: 500;
  font-size: 14px;
  padding: 4px 0;
}
.b-icon.bi {
  margin-right: 5px;
}
@media (min-width: 1570px) {
  .menu-all-place .item-each:hover {
    box-shadow: none;
  }
}
@media (max-width: 991px) {
  .menu-all-place .menu-container {
    width: 90%;
  }
}
@media (max-width: 575px) {
  .hero-all-place .all-place-heading {
    padding: 8rem 0 6rem;
    font-size: 24px;
  }
  .menu-all-place .item-each {
    text-align: center;
    margin: 0;
  }
}
@media (max-width: 360px) {
  .hero-all-place .all-place-heading span {
    padding: 8px 14px;
  }
}
@media (max-width: 320px) {
  .hero-all-place .all-place-heading {
    font-size: 18px;
  }
}
</style>