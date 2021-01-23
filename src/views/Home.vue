<template>
  <div class="flex-wrap">
    <div class="wrap-home-page text-left w-100">
      <h2 class="home-title">
        <span>TRUST AND</span> <br />
        <strong>CLIENT FOCUS</strong>
      </h2>
      <p class="home-des">Here will come the content for site</p>
      <button class="btn app-background p-15 btn-font">
        <i class="fa fa-angle-right"></i> More
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style scoped>
.btn-font {
  font-size: 20px;
  padding: 10px 50px;
}

.home-des {
  font-size: 20px;
}

.flex-wrap {
  height: 95vh;
  display: flex;
  align-items: center;
}

.home-title {
  font-size: 3rem;
}

.home-title span {
  font-size: 2.5rem;
}
</style>
