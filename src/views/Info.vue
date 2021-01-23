<template>
  <div class="container-fluid info-section">
    <div class="container">
      <div class="row">
        <div class="col-md-6 card-pad">
          <div class="row">
            <div class="col-md-2 flex-center-content">
              <i class="fa fa-search"></i>
            </div>
            <div class="col-md-10 text-left">
              <h5 class="card-title">Content Title</h5>
              <p class="card-text">Test Description for the site</p>
              <div class="row">
                <div class="col-md-6">
                  <button class="btn btn-font-size">Button 1</button>
                </div>
                <div class="col-md-6">
                  <button class="btn btn-font-size app-background">
                    Button 2
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-6 card-pad">
          <div class="row">
            <div class="col-md-2 flex-center-content">
              <i class="fa fa-search"></i>
            </div>
            <div class="col-md-10 text-left">
              <h5 class="card-title">Content Title</h5>
              <p class="card-text">Test Description for the site</p>
              <div class="row">
                <div class="col-md-6">
                  <button class="btn btn-font-size">Button 1</button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Info",
};
</script>

<style scoped>
.info-section {
  background-color: skyblue;
}

.card-pad {
  padding: 50px 15px;
}

.btn-font-size {
  width: 100%;
  background: #fff;
  color: #000;
  font-size: 14px;
}
</style>