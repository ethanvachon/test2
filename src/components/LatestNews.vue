<template>
  <div class="bg-gray-100 h-100">
    <div class="mx-auto">
      <h1 class="text-2xl text-center pt-8 font-bold">Latest News</h1>
      <h1 class="text-6xl text-center text-blue-500 pb-5">_</h1>
      <div class="flex justify-around">
        <div class="card bg-white mb-10 flex justify-center">
          <div>
            <img
              class="p-2 py-28"
              src="//cdn.wpsstatic.com/images/500_max/1584-5f5bf1d7ed094.jpg"
            />
            <a
              href="https://www.wps-inc.com/news/article/fly-racing-launches-2021-mx-line/885"
              target="_blank"
            >
              <h1 class="px-6 text-xl font-semibold text-blue-400">
                FLY RACING LAUNCHES 2...
              </h1>
            </a>
            <p class="py-3 px-6">Posted on Sep 11th 2020</p>
          </div>
        </div>
        <div class="card bg-white mb-10 flex justify-center">
          <div>
            <img
              class="p-2 py-28"
              src="//cdn.wpsstatic.com/images/500_max/7b44-5f5beca9b9cd8.jpg"
            />
            <a
              href="https://www.wps-inc.com/news/article/fire-power-announces-all-new-oem-spec-oil-filters/884"
              target="_blank"
            >
              <h1 class="px-6 text-xl font-semibold text-blue-400">
                FIRE POWER ANNOUNCES...
              </h1>
            </a>
            <p class="py-3 px-6">Posted on Sep 11th 2020</p>
          </div>
        </div>
        <div class="card bg-white mb-10 flex justify-center">
          <div>
            <img
              class="p-2 py-28"
              src="//cdn.wpsstatic.com/images/500_max/7f3f-5f5bc982ce792.png"
            />
            <a
              href="https://www.wps-inc.com/news/article/wps-named-exclusive-aftermarket-distributor-for-kolpin-brand/883"
              target="_blank"
            >
              <h1 class="px-6 text-xl font-semibold text-blue-400">
                WPS NAMED EXCLUSIVE...
              </h1>
            </a>
            <p class="py-3 px-6 border-b-2 mb-3">Posted on Sep 11th 2020</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "LatestNews"
};
</script>

<style scoped>
img {
  opacity: 0.8;
}
.card {
  width: 30vw;
}
</style>
