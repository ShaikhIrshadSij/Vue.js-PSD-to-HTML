<template>
  <header>
    <div class="container pt-3">
      <div class="row">
        <div class="col-md-5 wrap-img-header">
          <img
            src="https://www.visioninfotech.net/wp-content/uploads/2019/02/main_logo_white.png"
            style="height: 40px"
          />
        </div>
        <div class="col-md-7">
          <div class="row">
            <div class="col-md-4 text-left relative">
              <i class="fa fa-map-marker circle-icon animated"></i>
              <div class="wrap-header-address">
                <p class="m-0">Office Address:</p>
                <p class="m-0">Address 1, 2, 3</p>
              </div>
            </div>
            <div class="col-md-4 text-left relative">
              <i class="fa fa-microphone circle-icon animated"></i>
              <div class="wrap-header-address">
                <p class="m-0">Office Telephone:</p>
                <p class="m-0">+91 7600678749</p>
              </div>
            </div>
            <div class="col-md-4 text-left relative">
              <i class="fa fa-address-book circle-icon animated"></i>
              <div class="wrap-header-address">
                <p class="m-0">Office Timing:</p>
                <p class="m-0">Mon-Fri 9.00 to 6.30</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <nav
        class="navbar navbar-expand-lg navbar-light app-background mt-4 p-15 border-radius: 4px;"
      >
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
              <a class="nav-link" href="#">Link 1</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Link 2</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Link 3</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Link 4</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Link 5</a>
            </li>
          </ul>
          <i class="fa fa-search header-search-icon"></i>
        </div>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>

.wrap-img-header {
  text-align: left;
}

.circle-icon {
  padding: 10px 13px;
  background: #fff;
  color: #000;
  border-radius: 50%;
  font-size: 14px;
  position: absolute;
  left: 0;
  top: 50%;
  transform: translateY(-50%);
}

.circle-icon:hover {
  background: #154854;
  color: #fff;
}

.wrap-header-address {
  padding-left: 35px;
  color: #fff;
}

.navbar-light .navbar-brand {
  color: #fff;
}

.navbar-light .navbar-nav .nav-link {
  color: #fff !important;
}

.header-search-icon {
  position: absolute;
  right: 30px;
  color: #fff;
}
</style>