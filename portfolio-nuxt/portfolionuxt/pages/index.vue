<template>
  <div class="top-wrapper">
    <div class="center-box">
      <h1 class="top-title"><span class="text">N</span>73</h1>
      <p class="sub-title">Web Engineer | Nanami Portfolio</p>
    </div>
  </div>
</template>

<style>
.top-wrapper {
  height: calc(100vh - 90px);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.center-box {
  text-align: center;
  display: flex;
  flex-direction: column; /* 縦並びに */
  align-items: center;
  justify-content: center;
}

.top-title {
  font-size: 60px;
  margin: 0;
  line-height: 1;
}

.sub-title {
  font-size: 20px;
  color: #ccc;
  margin-top: 10px;
}

.text {
  color: #00c8ff;
}
</style>
