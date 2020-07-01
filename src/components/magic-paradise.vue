<template>
  <div>
  <section class="hero-single-place">
    <div class="hero-container">
      <div class="row">
        <div class="col-lg-8">
          <img class="img-fluid place-img" src="../assets/magic_paradise.png"  alt="">
        </div>
      </div>
    </div>
  </section>

  <section class="single-place-desc">
    <div class="single-place-container">
      <div class="row">
        <div class="place-info col-12">
          <h4 class="place-name">ম্যাজিক প্যারাডাইজ পার্ক</h4>
          <div class="location">
            <b-icon-geo-alt></b-icon-geo-alt>
            <span>কোটবাড়ি</span>
          </div>
          <p class="description black-clr-txt">ম্যাজিক প্যারাডাইস পার্ক কুমিল্লার কোটবাড়ি এলাকায় অবস্থিত। এই পার্কটি কুমিল্লার সবচেয়ে সুন্দর ও বড় এমিউজমেন্ট পার্ক।মনোরম পরিবেশের এই পার্কটি ছোট বড় সবার জন্যেই। ঢোকার মুখে গেট দেখেই অবাক হওয়ার মতো, কারণ গেটটি বানানো হয়েছে পৃথিবীর সবচেয়ে বড় থিম পার্ক ডিজনিল্যান্ডের আদলে। পার্কের বিশালত্ব সত্যিই মুগ্ধ হওয়ার মতো। ম্যাজিক প্যারাডাইস পার্কের আরেকটি বিশেষত্ব হলো এই পার্কটিতে শুধু কৃত্রিমতা রাখা হয়নি। পার্কের মধ্যে রয়েছে প্রকৃতির ছোঁয়াও।</p>
          <h5 class="what-see-heading">এই ট্যুরে যা যা দেখবেন:</h5>
          <p class="what-see black-clr-txt">
            ওয়াটার পার্ক, ২০টির অধিক রাইড, ডাইনোসর পার্ক, পিকনিক স্পট সহ এই পার্কটি কুমিল্লার সবচেয়ে সুন্দর ও বড় এমিউজমেন্ট পার্ক। বিদেশি কার্টুন ডিজনিকের আদলে প্যারাডাইজ পার্কের বিশাল ফটক বেশ আকর্ষনীয় ভাবে তৈরি করা হয়েছে। যার সামনেই তিনটি ডাইনোসর কিবোর্ড, ড্রাম ও গিটার বাজিয়ে আপনাকে স্বাগতম জানাতে ব্যস্ত। ভিতরে ঢুকতেই বিশাল এক নাগরদোলা। চুড়ায় বসে পুরো পার্কের দৃশ্য দেখার মত। দেশের সবচেয়ে বড় কৃত্রিম ওয়েভ পুল রয়েছে এই পার্কটিতে। আর বাচ্চাদের জন্য তো রয়েছে বিশেষ বিশেষ রাইড। বিশেষ করে ডাইনোসর পার্ক দেখে মনে হবে সত্যিই ডাইনোসরের রাজ্যে চলে এসেছে।
          </p>
          <h5 class="how-goto-heading">যেভাবে যাবেন:</h5>
          <p class="how-goto black-clr-txt">
            কুমিল্লা কোটবাড়ি থেকে সরাসরি অটোতে করে যেতে পারেন পার্কটির সামনে। অথবা কোটবাড়ি থেকে শালবন বিহার অটোতে ১০ টাকা করে গিয়ে শালবন বিহার ঘুরে আবার অটোতে চলে যেতে পারেন পার্কটির সামনে। ভাড়া ৫/১০ টাকা নিতে পারে জনপ্রতি।
            পার্কটির প্রবেশের ক্ষেত্রে টিকিট এর বিভিন্ন প্যাকেজ রয়েছে। তা ছাড়া আপনি শুধু ঢুকার টিকিট নিয়ে ভিতরে অন্য রাইড আবার কিনতে পারেন।
            পার্কটির টিকেট সংক্রান্ত এবং যাবতীয় সকল তথ্য তাদের অফিসিয়াল ওয়েবসাইটেই পাবেন।
            Link: http://www.magicparadisebd.com/ticket-price.php

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