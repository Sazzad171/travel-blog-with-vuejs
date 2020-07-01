<template>
  <div>
  <!-- review & comments start -->
  <section class="review-rating-read-sin-food">
    <h2 class="headline">Review and Rating</h2>
    <div class="review-rating-container">

      <div class="single-comment" v-for="review in reviews" :key="review.id">
        <div class="row">
          <div class="col">
            <h5 class="person-name"> {{review.name}}</h5>
          </div>
        </div>
        <div class="date">
          <span class="review-date"> {{review.date}} </span>
          <hr>
        </div>
        <p class="black-clr-txt"> {{review.desc}} </p>
      </div>

    </div>
  </section>
  <!-- review & comments end -->
  <!-- submit review start -->
  <section class="submit-review-single-food">
    <h2 class="headline">Submit a review about our blog</h2>
    <div class="review-container">

      <form @submit="addReview">
        <div class="row">
          <div class="col-sm-6">
            <input class="form-control" type="text" placeholder="Your name" v-model="name">
          </div>
          <div class="col-sm-6">
            <input class="form-control" type="email" placeholder="Your Email" v-model="email">
          </div>
        </div>
        <div class="row">
          <div class="col-sm-6">
            <textarea class="form-control" rows="5" placeholder="Your comment about this food" v-model="desc"></textarea>
          </div>
        </div>
        <div class="text-center">
          <input type="submit" value="Submit" class="review-btn">
        </div>
      </form>
      
    </div>
  </section>
  <!-- submit review end -->
  </div>
</template>

<script>
import { uuid } from "vue-uuid";

var today = new Date();
var date = today.getDate();
var month = today.toLocaleString('default', { month: 'long' });
var year = today.getFullYear();
var fullDate = "" + date + " " + month + " " +  year;

export default {
  name: 'review',
  data() {
    return {
      name: '',
      email: '',
      desc: '',
      fullDate: fullDate,
      reviews: [
        {
          id: 1,
          name: 'Imran Khan',
          email: 'imran@gmail.com',
          desc: 'Best website for all travel places in cumilla. I always visit here befor going a tour.',
          date: '18 Feb 2020'
        },
        {
          id: 2,
          name: 'PS Pronab',
          email: 'pronab@gmail.com',
          desc: 'My favourite platform. I always visit this platform. You can know all of travel places in cumilla from here. Recommend it for you.',
          date: '6 march 2020'
        },
        {
          id: 3,
          name: 'Al-amin Hossain Akash',
          email: 'alamin@gmail.com',
          desc: 'Good design and also well arranged website. Very easy to find any place and details about a place. Thank you The Cumillaian team.',
          date: '25 May 2020'
        }
      ]
    }
  },
  methods: {
    addReview(e) {
      e.preventDefault();
      const newReview = {
        id: uuid.v4(),
        name: this.name,
        email: this.email,
        desc: this.desc,
        date: this.fullDate
      };
      this.reviews = [...this.reviews, newReview];
      this.name = '';
      this.email = '';
      this.desc = '';
    }
  }
}
</script>

<style scoped>
/* submit review */
.submit-review-single-food {
  padding: 3rem 0;
  background: #F7F7F7;
}
.submit-review-single-food .headline {
  font-family: 'Open Sans', sans-serif;
  font-weight: 700;
  text-align: center;
}
.submit-review-single-food .review-container {
  width: 65%;
  margin: 0 auto;
  margin-top: 2rem;
  padding: 2rem;
  border-radius: 8px;
  box-shadow: 0 2px 14px -6px rgba(63, 81, 181, 0.75);
}
.submit-review-single-food .form-control {
  margin-bottom: 1rem;
}
.submit-review-single-food .review-btn {
  font-family: 'Roboto', sans-serif;
  font-weight: 400;
  color: #fff;
  border: none;
  padding: 8px 50px;
  border-radius: 8px;
  background-image: linear-gradient(to right, #1A437B, #1D245C);
}

/* review & comments */
.review-rating-read-sin-food {
  padding: 3rem 0;
  font-family: 'Roboto', sans-serif;
}
.review-rating-read-sin-food .headline {
  font-family: 'Open Sans', sans-serif;
  font-weight: 700;
  text-align: center;
}
.review-rating-read-sin-food .review-rating-container {
  width: 70%;
  margin: 0 auto;
}
.review-rating-read-sin-food .single-comment {
  margin-top: 2rem;
  padding: 1rem 2rem;
  border-radius: 8px;
  box-shadow: 0 2px 11px 0 rgba(0,0,0,.14);
}
.review-rating-read-sin-food .person-name {
  font-weight: 500;
}
.review-rating-read-sin-food .date {
  position: relative;
}
.review-rating-read-sin-food .review-date {
  position: absolute;
  left: 0;
  top: -15px;
  background: #fff;
  padding: 5px;
}
.review-rating-read-sin-food .black-clr-txt,
.hero-single-food .black-clr-txt {
  color: #505050;
}
@media (max-width: 991px) {
  .hero-single-food .hero-container {
    width: 90%;
  }
  .submit-review-single-food .review-container {
    width: 90%;
  }
  .review-rating-read-sin-food .review-rating-container {
    width: 95%;
  }
}
@media (max-width: 360px) {
  .submit-review-single-food .headline,
  .review-rating-read-sin-food .headline {
    font-size: 30px;
  }
}
</style>