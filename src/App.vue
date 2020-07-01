<template>
  <div id="app">
    <Header/>
    <router-view></router-view>
    <Footer/>
  </div>
</template>

<script>
import Router from 'vue-router'
import Header from './components/Header'
import  Footer from './components/Footer'
import home from './components/Home'
import review from './components/Review'
import aboutUs from './components/About-us'
import singlePlace from './components/lalmai-lakeland'
import singlePlace2 from './components/magic-paradise'
import singlePlac3 from './components/nawab-faisunnesa-bari'
import singlePlace4 from './components/rup-sagor'
import singlePlace5 from './components/shalbon-bihar'
import singlePlace6 from './components/war-cemetry'
import termsCondition from './components/terms-condition'

const routes = [
  { path: '/', component: home },
  { path: '/home', component: home },
  { path: '/review', component: review },
  { path: '/about-us', component: aboutUs },
  { path: '/lalmai-lakeland', component: singlePlace },
  { path: '/magic-paradise', component: singlePlace2 },
  { path: '/nawab-faisunnesa-bari', component: singlePlac3 },
  { path: '/rup-sagor', component: singlePlace4 },
  { path: '/shalbon-bihar', component: singlePlace5 },
  { path: '/war-cemetry', component: singlePlace6 },
  { path: '/terms-condition', component: termsCondition },
]

const router = new Router({
  routes: routes,
  mode: 'history',

   scrollBehavior () {
    return { x: 0, y: 0 };
  }
})

export default {
  name: 'App',
  router,
  components: {
    Header,
    Footer
  }
}
</script>

<style>
  html {
  scroll-behavior: smooth;
  }
  body {
    color: #1A237E !important;
  }
  input:focus, button:focus {
    outline: none;
  }
  .form-control:focus {
    outline: none;
    box-shadow: none;
    border-color: #ced4da;
  }
  button {
    transition: all .3s ease-in-out;
  }
  button:hover {
    box-shadow: 0 2px 11px 0 rgba(63, 81, 181, 0.75);
  }
  a {
    cursor: pointer;
  }

  .open-sans-bl {
    font-family: 'Open Sans', sans-serif;
    font-weight: 700;
  }
  .open-sans-xbl {
    font-family: 'Open Sans', sans-serif;
    font-weight: 800;
  }
  .roboto-rg {
    font-family: 'Roboto', sans-serif;
    font-weight: 400;
  }
  .roboto-md {
    font-family: 'Roboto', sans-serif;
    font-weight: 500;
  }
  .roboto-bl {
    font-family: 'Roboto', sans-serif;
    font-weight: 700;
  }
</style>
