<template>
  <main class="bg-image h-screen">
    <div class="custom-border">
      <nav
        class="container mx-auto text-white flex items-center grid grid-cols-2 h-14"
      >
        <div>
          <a
            href="http://www.facebook.com/pages/Western-Power-Sports/177028072341860"
            target="_blank"
            ><i class="fab fa-facebook nav-text px-1"></i
          ></a>
          <a href="http://twitter.com/WPS_Dist" target="_blank"
            ><i class="fab fa-twitter nav-text  px-1"></i
          ></a>
          <a
            href="http://www.linkedin.com/company/western-power-sports"
            target="_blank"
            ><i class="fab fa-linkedin nav-text px-1"></i
          ></a>
          <a href="http://www.youtube.com/westernpowersports" target="_blank"
            ><i class="fab fa-youtube nav-text px-1"></i
          ></a>
        </div>

        <div class="flex justify-end items-center">
          <div class="flex justify-around mr-3">
            <div class="flex items-center">
              <i class="fas fa-envelope px-1"></i>
              <p>Contact</p>
            </div>
            <p class="px-2">|</p>
            <div class="flex items-center">
              <i class="fas fa-map-pin px-1"></i>
              <p>Find a dealer</p>
            </div>
          </div>
          <div class="phone p-1 rounded flex items-center">
            <i class="fas fa-phone-alt pr-2"></i>
            <p>800-999-3388</p>
          </div>
        </div>
      </nav>
    </div>
    <main>
      <div
        class="container items-end justify-between mx-auto text-white flex pt-5"
      >
        <h1 class="text-5xl font-bold fade-in">WPS</h1>
        <div class="flex">
          <h5 class="px-3 font-bold text-base hover:text-gray-300 fade-in">
            HOME
          </h5>
          <h5 class="px-3 font-bold text-base hover:text-gray-300 fade-in-1">
            CATALOGS
          </h5>
          <h5 class="px-3 font-bold text-base hover:text-gray-300 fade-in-2">
            WEBSITES
          </h5>
          <h5 class="px-3 font-bold text-base hover:text-gray-300 fade-in-3">
            COMPANY
          </h5>
          <h5 class="px-3 font-bold text-base hover:text-gray-300 fade-in-4">
            DEALERS
          </h5>
        </div>
      </div>
      <div
        class="container mx-auto text-white text-center shadow-t font-bold animated animatedFadeInUp fadeInUp"
      >
        <h1 class="text-4xl mt-44 mb-14">WELCOME TO</h1>
        <h1 class="text-8xl mb-20">WESTERN POWER SPORTS</h1>
        <h1 class="text-4xl px-14">
          THE FASTEST GROWING NATION-WIDE DELIVERY SYSTEM OF POWER SPORTS
          INDUSTRY PRODUCTS
        </h1>
      </div>
    </main>
  </main>
</template>

<script>
export default {
  name: "Home"
};
</script>
<style scoped>
@import "../assets/tailwind.css";
.bg-image {
  background-image: url("https://d12fyb3kmekjk6.cloudfront.net/7fd71319-cd0d-458a-a08f-911323ae4856/img/home/rotators/WPS-Rale.jpg");
  background-size: cover;
}

.nav-text {
  font-size: 15px;
}

.custom-border {
  border-bottom: solid rgb(197, 197, 197) 1px;
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

.fade-in {
  animation: fadeIn ease 3s;
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
