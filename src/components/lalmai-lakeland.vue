<template>
  <div>
  <section class="hero-single-place">
    <div class="hero-container">
      <div class="row">
        <div class="col-lg-8">
          <img class="img-fluid place-img" src="../assets/lalmai_lakeland.png"  alt="">
        </div>
      </div>
    </div>
  </section>

  <section class="single-place-desc">
    <div class="single-place-container">
      <div class="row">
        <div class="place-info col-12">
          <h4 class="place-name">লালমাই ল্যাকল্যান্ড</h4>
          <div class="location">
            <b-icon-geo-alt></b-icon-geo-alt>
            <span>লালমাই</span>
          </div>
          <p class="description black-clr-txt">
            লালমাই ল্যাকল্যান্ড হচ্ছে একটি পর্যটন পার্ক। কুমিল্লা  শহরের অনেকটা নিকটে লালমাইতে এটি অবস্থিত। এখানে শিশু এবং বয়স্ক উভয়েরই জন্য বিনোদনের ব্যবস্থা রয়েছে।
          </p>
          <h5 class="what-see-heading">এই ট্যুরে যা যা দেখবেন:</h5>
          <p class="what-see black-clr-txt">
            লালমাই এর লাল মাটির পাহাড়ের উপর এই পার্কটি তৈরী করা হয়েছে। পার্কের গেটে ঢুকার আগেই কিছুটা উপরে উঠতে হয়। লালমাই লেকল্যান্ড এর গেটটিও বেশ সুন্দর। ভিতরে রয়েছে শিশু-বড় সবার জন্যে অনেক ধরণের বিনোদন ব্যবস্থা। পার্কটির ভিতরের দিকে রয়েছে বিশাল সবুজ গাছ-গাছালি যুক্ত পরিবেশ। পিছনের দিকটি থেকে বিশাল বিশাল লাল পাহাড়ের সৌন্দর্যও উপভোগ করা যায়।
          </p>
          <h5 class="how-goto-heading">যেভাবে যাবেন:</h5>
          <p class="how-goto black-clr-txt">
            কুমিল্লার পাদুয়ার বাজার বিশ্বরোড থেকে মিনিবাসে অথবা সিএনজিতে লালমাই কলেজ নামতে হবে। লালমাই কলেজের প্রধান গেট এর সামনে থেকে লালমাই ল্যাকলেন্ড এর অটো পাবেন। ভাড়া ১৫ টাকা। লালমাই লেকল্যান্ড এর প্রবেশ ফী ২০ টাকা এবং এই পার্কের কোনো সাপ্তাহিক বন্ধ নেই।
          </p>
        </div>
      </div>
    </div>
  </section>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
.hero-single-place {
  margin: 4rem 0 2rem;
}
.hero-single-place .hero-container {
  width: 70%;
  margin: 0 auto;
}
.hero-single-place .place-img {
  border-radius: 8px;
}
.single-place-desc {
  margin-bottom: 2rem;
}
.single-place-desc .single-place-container {
  width: 70%;
  margin: 0 auto;
}
.single-place-desc .place-name {
  font-weight: 600;
}
.single-place-desc .location {
  font-weight: 500;
  font-size: 14px;
  margin-bottom: 5px;
}
.b-icon.bi {
  margin-right: 2px;
}
.single-place-desc .what-see-heading, 
.single-place-desc .how-goto-heading {
  margin-top: 2rem;
  font-weight: 600;
}
.single-place-desc .black-clr-txt {
  color: #505050;
  line-height: 30px;
}
@media (max-width: 767px) {
  .hero-single-place .hero-container,
  .single-place-desc .single-place-container {
    width: 90%;
  }
}
</style>