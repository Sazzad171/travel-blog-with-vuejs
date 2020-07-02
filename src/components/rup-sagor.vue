<template>
  <div>
  <section class="hero-single-place">
    <div class="hero-container">
      <div class="row">
        <div class="col-lg-8">
          <img class="img-fluid place-img" src="../assets/rupsagor.png"  alt="">
        </div>
      </div>
    </div>
  </section>

  <section class="single-place-desc">
    <div class="single-place-container">
      <div class="row">
        <div class="place-info col-12">
          <h4 class="place-name">রূপসাগর</h4>
          <div class="location">
            <b-icon-geo-alt></b-icon-geo-alt>
            <span>ক্যান্টনমেন্ট, কুমিল্লা</span>
          </div>
          <p class="description black-clr-txt">সেনাবাহিনী দ্বারা পরিচালিত একটি পার্ক এটি। সবুজ ছায়া ঘেরা পার্কটি নিমিষেই দূর করে দেয় সকল ক্লান্তি। রূপসাগরে লেকটি ই সেখানে মূল আকর্ষণ। শিশুদের নিয়ে বেড়ানোর জন্য চমৎকার জায়গা। মাঝে বন্ধ থাকলেও পার্কটি এখন সবার জন্য উন্মুক্ত আছে। দূরে ছোট ছোট পাহাড় পার্কের সৌন্দর্য বাড়িয়ে দিয়েছে বহুগুণে। সেখানে বড় একটি ক্যাফেটোরিয়া আছে যেখানে পাবেন সুস্বাদু খাবার।</p>
          <h5 class="what-see-heading">এই ট্যুরে যা যা দেখবেন:</h5>
          <p class="what-see black-clr-txt">
            রূপসাগরে দেখা যায় বিশাল একটি লেক এবং সেই লেক এর মাঝে কৃত্রিম তৈরী অনেকগুলো ঘোড়ার সুন্দর প্রতিচ্ছবি। লেকের চারধারে হেটে পার্কের সুন্দর পরিবেশ উপভোগ করা যাই। লেক এ রয়েছে প্যাডেল বোট, যেটি ঘন্টা হিসেবে ভাড়া নিয়ে নিজেই চালানো যায়। রূপসাগরের অন্য এক সৌন্দর্য হলো লেক এর ধরে অবস্থিত ক্যাফেটোরিয়া যেটি দেখতে জাহাজ আকৃতির। ক্যাফেটোরিয়া উপর থেকে পুরো রূপসাগরের সৌন্দর্য উপভোগ করা যায়। ক্যাফেটোরিয়া এর পাশেই রয়েছে শিশুদের খেলার জন্যে ইনডোর জোন।
          </p>
          <h5 class="how-goto-heading">যেভাবে যাবেন:</h5>
          <p class="how-goto black-clr-txt">
            কুমিল্লা ক্যান্টনমেন্ট থেকে পশ্চিম দিকের রাস্তা অর্থাৎ যে সড়কটি ঢাকার দিকে এসেছে সেদিকে ১০ মিনিট হাঁটলেই পাবেন নাজিরা বাজার। অথবা কুমিল্লা ক্যান্টনমেন্ট এর সামনে থেকে রিকশা দিয়েও আসতে পারেন। এখান থেকে সেনাবাহিনী চেকাপ পয়েন্টের ভেতর দিয়ে এগিয়ে যেতে হবে। তবে সেনাবাহিনীকে আপনি সেখানে ঘুরতে যাচ্ছেন এই বলে অনুমতি নিয়ে গেটে প্রবেশ করতে হবে।
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