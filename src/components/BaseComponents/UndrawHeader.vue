<template>
  <section id="undraw">
    <div class="container">
      <div class="row">
        <div class="col-6">
          <img
            src="../../utils/undraw_Reading_re_29f8.svg  "
            class="img-fluid"
            alt="girl reading"
          />
        </div>
        <div class="col-6">
          <img
            src="../../utils/undraw_road_to_knowledge_m8s0.svg"
            class="img-fluid road"
            alt="road to knowledge"
          />
          <base-button
            to="/home"
            class="btn-sm btn-outline-primary right big"
            style="margin-bottom: 30px"
            >Home</base-button
          >
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.road {
  margin-left: -40px;
}
.right {
  float: right;
  margin-top: -15px;
}
#undraw {
  margin-bottom: 40px;
}
@media only screen and (min-width: 768px) {
  .right {
    margin-top: 100px;
  }
  .big {
    font-size: x-large;
  }
}
</style>
