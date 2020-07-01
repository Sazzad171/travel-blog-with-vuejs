<template>
  <div>
  <section class="hero-single-place">
    <div class="hero-container">
      <div class="row">
        <div class="col-lg-8">
          <img class="img-fluid place-img" src="../assets/war_cemetery.jpg"  alt="">
        </div>
      </div>
    </div>
  </section>

  <section class="single-place-desc">
    <div class="single-place-container">
      <div class="row">
        <div class="place-info col-12">
          <h4 class="place-name">ময়নামতি ওয়ার সিমেট্রি</h4>
          <div class="location">
            <b-icon-geo-alt></b-icon-geo-alt>
            <span>ময়নামতি</span>
          </div>
          <p class="description black-clr-txt">ময়নামতি ওয়ার সিমেট্রি বাংলাদেশের কুমিল্লাতে অবস্থিত একটি কমনওয়েলথ যুদ্ধ সমাধি। ১৯৪১-১৯৪৫ সালে বার্মায় সংঘটিত যুদ্ধে যে ৪৫০০০ কমনওয়েলথ সৈনিক নিহত হন, তাদের স্মৃতি রক্ষার্থে মায়ানমার (তৎকালীন বার্মা), আসাম, এবং বাংলাদেশে ৯টি রণ সমাধিক্ষেত্র তৈরি করা হয়েছে। কুমিল্লা শহর থেকে প্রায় ৭ কিলোমিটার দূরে কুমিল্লা ক্যান্টনমেন্টের খুব কাছেই এই যুদ্ধ সমাধির অবস্থান। প্রতিবছর প্রচুর দর্শনার্থী যুদ্ধে নিহত সৈন্যদের প্রতি সম্মান জানাতে এসকল রণ সমাধিক্ষেত্রে আসেন। </p>
          <h5 class="what-see-heading">এই ট্যুরে যা যা দেখবেন:</h5>
          <p class="what-see black-clr-txt">
            ময়নামতি ওয়ার সিমেট্রি বাংলাদেশের কুমিল্লাতে অবস্থিত একটি কমনওয়েলথ যুদ্ধ সমাধি। ১৯৪১-১৯৪৫ সালে বার্মায় সংঘটিত যুদ্ধে যে ৪৫০০০ কমনওয়েলথ সৈনিক নিহত হন, তাদের স্মৃতি রক্ষার্থে মায়ানমার (তৎকালীন বার্মা), আসাম, এবং বাংলাদেশে ৯টি রণ সমাধিক্ষেত্র তৈরি করা হয়েছে। কুমিল্লা শহর থেকে প্রায় ৭ কিলোমিটার দূরে কুমিল্লা ক্যান্টনমেন্টের খুব কাছেই এই যুদ্ধ সমাধির অবস্থান। প্রতিবছর প্রচুর দর্শনার্থী যুদ্ধে নিহত সৈন্যদের প্রতি সম্মান জানাতে এসকল রণ সমাধিক্ষেত্রে আসেন। 
          </p>
          <h5 class="how-goto-heading">যেভাবে যাবেন:</h5>
          <p class="how-goto black-clr-txt">
            কুমিল্লা শহর থেকে ৫ কিঃ মিঃ পশ্চিমে ঢাকা-চট্টগ্রাম মহাসড়ক সংলগ্ন কুমিল্লা ক্যান্টনমেন্টের টিপরা বাজারে এটি অবস্থিত। তাই যেকোনো জায়গা থেকেই কুমিল্লা ক্যান্টনমেন্ট চলে গেলে সেখান থেকে সিলেট রোডে ব্যাটারি চালিত অটোতে জনপ্রতি ৫ টাকা এবং রিকশাতে গেলে ২০ টাকা ভাড়া পড়বে।
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