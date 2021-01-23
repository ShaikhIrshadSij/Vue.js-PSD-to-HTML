<template>
  <div class="container-fluid contact-section">
    <div class="container p-15">
      <div class="row">
        <div class="col">
          <input
            type="text"
            class="form-control br-1"
            placeholder="First name"
          />
        </div>
        <div class="col">
          <select class="form-control br-1">
            <option>Select Option</option>
          </select>
        </div>
        <div class="col">
          <label>
            <input type="checkbox" />
            Do you agree?
          </label>
        </div>
        <div class="col">
          <button class="btn btn-font-size">Submit Info</button>
        </div>
        <div class="col">
          <p class="m-0">Display Time: <span>18:36:50</span></p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Contact",
};
</script>

<style scoped>
.contact-section {
  background-color: grey;
}

.br-1 {
  border-radius: 1px;
}

.btn-font-size {
  width: 100%;
  background: #fff;
  color: #000;
  font-size: 14px;
}
</style>