<template>
  <div class="projct-section row pt-5 mb-5">
    <div class="col-md-3">
      <div class="card w-100">
        <div class="card-body">
          <h5 class="card-title">Title</h5>
          <h5 class="card-title">Latest <strong class="d-block">News</strong></h5>
          <p class="card-text">
            Our represent a State Of The Art in passive vibration control in
            High End Audio.
          </p>
        </div>
      </div>
    </div>
    <div class="col-md-9">
      <div class="row">
        <div class="col-md-4" v-for="(item, index) in cartLists" :key="index">
          <div class="card w-100">
            <img
              src="https://www.thebalancesmb.com/thmb/iIV7A--elKPnwhB1_-T3gRVfEUM=/1540x1155/smart/filters:no_upscale()/Stocksy_woman-writing-laptop_476082-57ab432d3df78cf459975331.jpg"
              class="card-img-top"
            />
            <div class="card-body">
              <h5 class="card-title">{{ item.title }}</h5>
              <p class="card-text">
                {{ item.description }}
              </p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Projects",
  data() {
    return {
      cartLists: [
        {
          title: "Title",
          description:
            "Our represent a State Of The Art in passive vibration control in High End Audio.",
        },
        {
          title: "Title",
          description:
            "Our represent a State Of The Art in passive vibration control in High End Audio.",
        },
        {
          title: "Title",
          description:
            "Our represent a State Of The Art in passive vibration control in High End Audio.",
        },
      ],
    };
  },
};
</script>

<style scoped>
.card {
  color: #000;
  text-align: left;
  font-size: 13px;
}
</style>