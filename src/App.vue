<template>
  <div>
  <NavbarComponents></NavbarComponents>
  <HeadingComponents></HeadingComponents>
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#00cba9" fill-opacity="0.7" d="M0,160L17.1,160C34.3,160,69,160,103,144C137.1,128,171,96,206,122.7C240,149,274,235,309,224C342.9,213,377,107,411,90.7C445.7,75,480,149,514,149.3C548.6,149,583,75,617,42.7C651.4,11,686,21,720,26.7C754.3,32,789,32,823,64C857.1,96,891,160,926,165.3C960,171,994,117,1029,122.7C1062.9,128,1097,192,1131,202.7C1165.7,213,1200,171,1234,144C1268.6,117,1303,107,1337,117.3C1371.4,128,1406,160,1423,176L1440,192L1440,320L1422.9,320C1405.7,320,1371,320,1337,320C1302.9,320,1269,320,1234,320C1200,320,1166,320,1131,320C1097.1,320,1063,320,1029,320C994.3,320,960,320,926,320C891.4,320,857,320,823,320C788.6,320,754,320,720,320C685.7,320,651,320,617,320C582.9,320,549,320,514,320C480,320,446,320,411,320C377.1,320,343,320,309,320C274.3,320,240,320,206,320C171.4,320,137,320,103,320C68.6,320,34,320,17,320L0,320Z"></path></svg>
  <br>
  <br>
  <hr>
  <br>
  <br>
  <ContentComponents></ContentComponents>
  <br>
  <br>
  <FooterComponents></FooterComponents>
  </div>
</template>

<script>
  import NavbarComponents from './components/NavbarComponents.vue';
  import HeadingComponents from './components/HeadingComponents.vue';
  import ContentComponents from './components/ContentComponents.vue';
  import FooterComponents from './components/FooterComponents.vue'

  export default {
    components:{
    NavbarComponents,
    HeadingComponents,
    ContentComponents,
    FooterComponents
}
  }
</script>