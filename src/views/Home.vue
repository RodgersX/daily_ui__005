<template>
  <div class="home">
    <div class="card" style="width: 18rem; height: 500px;">
      <img height="250" width="100%" :src="require('@/assets/image_1.png')">
      <div class="card-body text-center">
        <h3>Plenty of Farmers, Products</h3>
        <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate, aliquam magnam.</p>
        <div class="card-actions">
          <i class="bx bx-dots-horizontal-rounded bx-md"></i>
          <button type="button" class="btn btn-light">skip</button>
        </div>
      </div>
    </div>

    <div class="card" style="width: 18rem; height: 500px;">
      <img height="250" width="100%" :src="require('@/assets/image_2.png')">
      <div class="card-body text-center">
        <h3>Secure Payments</h3>
        <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate, aliquam magnam.</p>
        <div class="card-actions mt-5">
          <i class="bx bx-dots-horizontal-rounded bx-md"></i>
          <button type="button" class="btn btn-success">Get Started</button>
        </div>
      </div>
    </div>

    <div class="card logo-card" style="width: 18rem; height: 500px;">
      <img width="150" :src="require('@/assets/logo.png')">
      <img class="fruits" width="100%" :src="require('@/assets/image.png')">
    </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
}
</script>

<style scoped>
.home {
  height: 100vh;
  background: rgb(231, 199, 205);
  display: flex;
  justify-content: center;
  align-items: center;
}

.card {
  border-radius: 10px;
  padding-top: 1rem;
  overflow: hidden;
  margin: 0 1rem;
}

.card-actions {
  display: flex;
  justify-content: space-between;
}

.logo-card {
  display: flex;
  justify-content: center;
  align-items: center;
}

.fruits {
  position: relative;
  bottom: -6rem;
}

</style>