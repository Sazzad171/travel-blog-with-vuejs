<template>
  <div>
  <section class="hero-single-place">
    <div class="hero-container">
      <div class="row">
        <div class="col-lg-8">
          <img class="img-fluid place-img" src="../assets/Nawab_Faizunnesa_House.png"  alt="">
        </div>
      </div>
    </div>
  </section>

  <section class="single-place-desc">
    <div class="single-place-container">
      <div class="row">
        <div class="place-info col-12">
          <h4 class="place-name">নবাব ফয়জুন্নেসা জমিদার বাড়ি</h4>
          <div class="location">
            <b-icon-geo-alt></b-icon-geo-alt>
            <span>লাকসাম</span>
          </div>
          <p class="description black-clr-txt">নবাব ফয়জুন্নেসা জমিদার বাড়ি বাংলাদেশের কুমিল্লা জেলার লাকসাম উপজেলার পশ্চিমগাঁও এলাকায় অবস্থিত এক ঐতিহাসিক জমিদার বাড়ি। এই জমিদার বাড়িটি ডাকাতিয়া নদীর তীরে অবস্থিত। 
            ভারতবর্ষের একমাত্র মহিলা নবাব ফয়জুন্নেসা চৌধুরানী এই জমিদার বাড়িটি প্রতিষ্ঠা করেন। তিনি সভ্রান্ত এক মুসলিম জমিদার পরিবারে জন্মগ্রহণ করেন। বিয়ে করেন আরেক জমিদার গাজী চৌধুরীকে। কিন্তু পরবর্তীতে তাদের বিবাহ বিচ্ছেদ হয়। আর ঐ বিবাহ বিচ্ছেদের সময় পাওয়া দেনমোহরের এক লক্ষ এক টাকা দিয়ে তিনি নিজে একটি বাড়ি তৈরি করেন। ঐসময় জমিদারীর প্রশিক্ষণ নেন এবং মৃত্যুর আগ পর্যন্ত সাফল্যের সাথে জমিদারী পরিচালনা করতে থাকেন। সাহসী উদ্যোগ ও সাফল্যের কারণে তৎকালীন ব্রিটিশ রানী ভিক্টোরিয়া তাকে এক অনুষ্ঠানের মাধ্যমে "নওয়াব" উপাধিতে ভূষিত করেন। যা পুরো ভারত উপমহাদেশে একমাত্র মহিলা হিসেবে তিনি এই উপাধি পান।
          </p>
          <h5 class="what-see-heading">এই ট্যুরে যা যা দেখবেন:</h5>
          <p class="what-see black-clr-txt">
            নওয়াব ফয়জুন্নেসা জমিদার বাড়িটি লাকসাম উপজেলার পশ্চিমগাঁওয়ে ডাকাতিয়া নদীর পাড়ে অবস্থিত। এখানে তাই রাস্তার পাশে দর্শনার্থীদের বিশ্রামের জন্য কিছু বেঞ্চি বানানো হয়েছে। ছোটখাটো কিন্তু বেশ চমৎকার সুন্দর বাড়িটি যার মূল বাড়িটি দক্ষিণমুখী। তার পশ্চিম-দক্ষিণ পাশে বৈঠকখানা। বাড়ির পশ্চিমপাশে রয়েছে মসজিদ, ঈদগাহ, কবরস্থান ও নওয়াব ফয়জুন্নেসা সরকারি কলেজ। অনেকটা সময় সবুজের সান্নিধ্যে কাটানোর জন্য অনেক ভালো একটা জায়গা। দশ গম্বুজ বিশিষ্ট এই মসজিদটি ১৯০৩ সালে স্থাপিত
          </p>
          <h5 class="how-goto-heading">যেভাবে যাবেন:</h5>
          <p class="how-goto black-clr-txt">
            কুমিল্লা থেকে বাসে লাকসাম বাস স্ট্যান্ড অথবা ট্রেনে লাকসাম রেলওয়ে স্টেশন চলে যেতে হবে। সেখান থেকে অটো অথবা রিক্সা দিয়ে খুব সহজেই নবাব ফয়জুন্নেসা জমিদার বাড়ি যাওয়া যায়।
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