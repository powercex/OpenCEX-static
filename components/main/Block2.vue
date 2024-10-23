<template>
  <div class="content block2">
    <div class="grid grid-cols-5 block2-grid">
      <div class="col-span-3 fleximg">
        <img class="block3-img" src="/img/logo.png" />
      </div>
      <div class="col-span-2 block3-right">
        <h2><span>User-friendly</span> and fast interface</h2>
        <p class="text1">Trading crypto has never been so easy and convenient. Smooth interface giving you the best experience. </p>
        <div class="separator"></div>
        <p class="text2">We took care of your convenience</p>
        <p class="text3">Light interface for quick purchases and professional exchange interface for large-scale trading.</p>
      </div>
    </div>
  </div>
</template>

<style>
.block2 {
  background: #000000;
  padding: 173px 0 130px;
}
body h2 {
  color: #fff;
  padding-bottom: 26px;
  font-size: 60px;
  font-weight: 700;
}
.text1 {
  color: #fff;
  font-size: 24px;
  line-height: 1.4;
  padding-bottom: 19px
}
.text2 {
  color: #fff;
  font-size: 24px;
  padding-bottom: 10px;
}
.text3 {
  color: #fff;
  font-size: 18px;
}
.separator {
  width: 98px;
  height: 4px;
  margin: 20px 0 32px;
  background: #f0af1b;
}
.block3-img {
  position: relative;
  top: -19px;
  left: -51px;
}
.block3-right {
  position: relative;
  left: -27px;
}
.fleximg {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 250px;
  margin-bottom: 62px;
}

@media (max-width: 900px) {
  .block2-grid {
    display: flex !important;
    flex-direction: column;
  }
  .block3-img {
    top: 0;
    left: 0;
    margin-bottom: 20px;
  }
  .block3-right {
    left: 0;
    padding: 0 20px;
  }
  .block2 {
    padding: 43px 0 44px;
  }
  .text1 {
    color: #fff;
    font-size: 16px;
    padding-bottom: 11px;
  }
  .separator {
    margin: 20px 0 20px;
  }
  .text2 {
    color: #fff;
    font-size: 18px;
  }
  .text3 {
    color: #fff;
    font-size: 15px;
  }
}
</style>
