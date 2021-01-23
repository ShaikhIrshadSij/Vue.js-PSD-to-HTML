<template>
  <div class="row pb-5">
    <div class="col-md-4 mb-2" v-for="(item, index) in cardList" :key="index">
      <div class="card w-100 card-custom">
        <div class="card-body row">
          <div class="col-md-2 flex-center-content">
            <i :class="item.icon"></i>
          </div>
          <div class="col-md-10 text-left">
            <h5 class="card-title">{{ item.title }}</h5>
            <p class="card-text">
              {{ item.description }}
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Cards",
  data() {
    return {
      cardList: [
        {
          icon: "fa fa-map-marker",
          title: "Test Card",
          description: `Our represent a State Of The Art in passive vibration control in High End Audio.`,
        },
        {
          icon: "fa fa-map-marker",
          title: "Test Card",
          description: `Our represent a State Of The Art in passive vibration control in High End Audio.`,
        },
        {
          icon: "fa fa-map-marker",
          title: "Test Card",
          description: `Our represent a State Of The Art in passive vibration control in High End Audio.`,
        },
        {
          icon: "fa fa-map-marker",
          title: "Test Card",
          description: `Our represent a State Of The Art in passive vibration control in High End Audio.`,
        },
        {
          icon: "fa fa-map-marker",
          title: "Test Card",
          description: `Our represent a State Of The Art in passive vibration control in High End Audio.`,
        },
        {
          icon: "fa fa-map-marker",
          title: "Test Card",
          description: `Our represent a State Of The Art in passive vibration control in High End Audio.`,
        },
      ],
    };
  },
};
</script>

<style scoped>
.card-custom {
  color: #000;
  -webkit-box-shadow: -1px 2px 9px 0px rgba(0, 0, 0, 0.75);
  -moz-box-shadow: -1px 2px 9px 0px rgba(0, 0, 0, 0.75);
  box-shadow: -1px 2px 9px 0px rgba(0, 0, 0, 0.75);
}

.card-title {
  font-size: 15px;
}

.card-text {
  font-size: 13px;
}
</style>