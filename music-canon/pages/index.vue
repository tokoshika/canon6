<template>
  <div class="main-container">
    <div class="title">
      <h1>鹿追小学校6年生</h1>
      <h2>鍵盤&リコーダー練習用</h2>
      <h2>パッヘルベル　カノン</h2>
    </div>
    <img class="canon" src="~/assets/canon01.png" />
  </div>
  <div class="youtube">
    <iframe
      width="900px"
      height="300px"
      src="https://www.youtube.com/embed/lZEe9dMwXnc?si=Opna4SSQMTya0VXo"
      title="YouTube video player"
      frameborder="0"
      allow="accelerometer;
        autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture;
        web-share"
      allowfullscreen
    >
    </iframe>
  </div>
</template>

<style scoped>
  .main-container,
  .youtube {
    display: flex;
    justify-content: center;
    font-family: "Zen Maru Gothic";
    margin-bottom: 2rem;
  }
  .title {
    margin-right: 2rem;
  }
  .canon {
    width: 50%;
    display: flex;
    justify-content: center;
  }
</style>
