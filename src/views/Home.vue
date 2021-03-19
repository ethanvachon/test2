<template>
  <div>
    <Carousel />
    <LatestNews />
  </div>
</template>

<script>
import Carousel from "../components/carousel.vue";
import LatestNews from "../components/LatestNews";
export default {
  name: "Home",
  components: {
    Carousel,
    LatestNews
  }
};
</script>
<style scoped>
@import "../assets/tailwind.css";
.bg-image {
  background-image: url("https://d12fyb3kmekjk6.cloudfront.net/7fd71319-cd0d-458a-a08f-911323ae4856/img/home/rotators/WPS-Rale.jpg");
  background-size: cover;
}

.dropdown:hover .card {
  height: 32vh;
  width: 14vw;
  display: block;
  position: absolute;
  top: 17vh;
  background-color: white;
  z-index: 100;
}

.nav-text {
  font-size: 15px;
}

.custom-border {
  box-shadow: 0 2px 2px -2px rgb(214, 214, 214);
}

.phone {
  background: hsla(0, 0%, 100%, 0.2);
}

.shadow-t {
  text-shadow: 1px 1px 4px #333;
}

.text-xl {
  cursor: pointer;
}

.nav-items {
  cursor: pointer;
}

.nav-items:hover #underscore {
  display: block;
  position: absolute;
  top: 4.5vh;
}
@keyframes fadeIn {
  0% {
    opacity: 0;
  }
  20% {
    opacity: 1;
  }
}

.fade-in-1 {
  animation: fadeIn-1 ease 3s;
}
@keyframes fadeIn-1 {
  0% {
    opacity: 0;
  }
  40% {
    opacity: 1;
  }
}

.fade-in-2 {
  animation: fadeIn-2 ease 3s;
}
@keyframes fadeIn-2 {
  0% {
    opacity: 0;
  }
  60% {
    opacity: 1;
  }
}

.fade-in-3 {
  animation: fadeIn-3 ease 3s;
}
@keyframes fadeIn-3 {
  0% {
    opacity: 0;
  }
  80% {
    opacity: 1;
  }
}

.fade-in-4 {
  animation: fadeIn-4 ease 3s;
}
@keyframes fadeIn-4 {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

@keyframes fadeInUp {
  from {
    transform: translate3d(0, 40px, 0);
  }

  to {
    transform: translate3d(0, 0, 0);
    opacity: 1;
  }
}

.animated {
  animation-duration: 1s;
  animation-fill-mode: both;
}

.animatedFadeInUp {
  opacity: 0;
}

.fadeInUp {
  opacity: 0;
  animation-name: fadeInUp;
}
</style>
