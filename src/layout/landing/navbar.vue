<template>
  <div class="container">
    <div class="row">
      <div class="col-md-12">
        <div class="nav-container">
          <!-- <img src="@/assets/icons/logo.png" alt="" /> -->
          <header>
            <a href="/" class="logo">
              <h4>
                <span class="secondary">Perse</span
                ><span class="primary">Move</span>
              </h4>
            </a>
            <nav>
              <ul class="nav-links">
                <li><a href="#">Track</a></li>
                <li><a href="about">About</a></li>
                <li><a href="#">Contact</a></li>
              </ul>
              <div class="burger" @click="burgerClick">
                <div class="line1"></div>
                <div class="line2"></div>
                <div class="line3"></div>
              </div>
            </nav>
          </header>
          <div class="social-header">
            <ul class="social-links">
              <li>
                <a href="#"><img src="@/assets/icons/fb.svg" alt="" /></a>
              </li>
              <li>
                <a href="#"><img src="@/assets/icons/ig.svg" alt="" /></a>
              </li>
              <li>
                <a href="#"><img src="@/assets/icons/offer.svg" alt="" /></a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    burgerClick() {
      let burger = document.querySelector(".burger");
      console.log(burger.classList);
      burger.classList.toggle("toggle");
    },
  },
};
</script>

<style>
</style>