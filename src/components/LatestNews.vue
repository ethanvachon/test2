<template>
  <div class="bg-gray-100 h-100">
    <div class="mx-auto">
      <h1 class="text-2xl text-center pt-8 font-bold">Latest News</h1>
      <h1 class="text-6xl text-center text-blue-500 pb-5">_</h1>
      <div class="flex justify-around">
        <div class="card bg-white mb-10 flex justify-center">
          <div class="image-fit">
            <img
              class="p-2 py-20"
              src="//cdn.wpsstatic.com/images/500_max/1584-5f5bf1d7ed094.jpg"
            />
          </div>
        </div>
        <div class="card bg-white mb-10 flex justify-center">
          <div class="image-fit">
            <img
              class="p-2 py-20"
              src="//cdn.wpsstatic.com/images/500_max/7b44-5f5beca9b9cd8.jpg"
            />
          </div>
        </div>
        <div class="card bg-white mb-10 flex justify-center">
          <div class="image-fit">
            <img
              class="p-2 py-20"
              src="//cdn.wpsstatic.com/images/500_max/7f3f-5f5bc982ce792.png"
            />
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
  /* position: absolute;
  top: 3rem; */
}
.card {
  height: 40vh;
  width: 30vw;
}
.image-fit {
  padding-bottom: 100%;
}
</style>
