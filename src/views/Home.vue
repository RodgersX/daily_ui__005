<template>
  <div class="home">
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <div class="card">
            <img height="250" width="100%" :src="require('@/assets/image_1.png')">
            <div class="card-body text-center">
              <h3>Plenty of Farmers, Products</h3>
              <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate, aliquam magnam.</p>
              <div class="card-actions card-actions__first">
                <div class="mr-4">
                  <ol class="carousel-indicator mt-2">
                    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active bg-warning"></li>
                    <li data-target="#carouselExampleIndicators" data-slide-to="1" class="bg-secondary"></li>
                    <li data-target="#carouselExampleIndicators" data-slide-to="2" class="bg-secondary"></li>
                  </ol>
                </div>
                <button type="button" class="btn btn-light" data-target="#carouselExampleIndicators" data-slide-to="2">skip</button>
              </div>
            </div>
          </div>
        </div>
        <div class="carousel-item">
          <div class="card">
            <img height="250" width="100%" :src="require('@/assets/image_2.png')">
            <div class="card-body text-center">
              <h3>Secure Payments</h3>
              <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate, aliquam magnam.</p>
              <div class="card-actions" style="margin-top: 4rem;">
                <ol class="carousel-indicator mt-2">
                  <li data-target="#carouselExampleIndicators" data-slide-to="0" class="bg-secondary"></li>
                  <li data-target="#carouselExampleIndicators" data-slide-to="1" class="active bg-warning"></li>
                  <li data-target="#carouselExampleIndicators" data-slide-to="2" class="bg-secondary"></li>
                </ol>
                <button type="button" class="btn btn-success" data-target="#carouselExampleIndicators" data-slide-to="2">Get Started</button>
              </div>
            </div>
          </div>
        </div>
        <div class="carousel-item">
          <div class="card logo-card">
            <img width="150" :src="require('@/assets/logo.png')">
            <img class="fruits" width="100%" :src="require('@/assets/image.png')">
          </div>
        </div>
      </div>
      <a 
      class="carousel-control-next" 
      href="#carouselExampleIndicators" 
      role="button" 
      data-slide="next"></a>
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
  display: flex;
  justify-content: center;
  align-items: center;
}

.card {
  height: 100vh;
  width: 100vw;
  border-radius: 10px;
  padding-top: 1rem;
  overflow: hidden;
  margin: 0 1rem;
}

.card-actions {
  display: flex;
  justify-content: space-between;
}

.card-actions__first {
  margin-top: 4rem;
}

.carousel-indicator li {
  list-style: none;
  display: inline-block;
  margin: 4px 2px 0 2px;
  width: 10px;
  height: 10px;
  border-radius: 100%;
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