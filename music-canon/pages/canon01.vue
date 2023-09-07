<template>
  <div class="main">
    <h3 class="title">楽器(<span style="color: tomato">12</span>)</h3>
    <div class="unshi">
      <!-- <img src="~/assets/canon01.png" /> -->
    </div>
    <div class="phrase">
      <div class="phrase1">
        <div><p class="si high">ミ</p></div>
        <div><p class="si high">レ</p></div>
        <div><p class="mi high">ド</p></div>
        <div><p class="mi">シ</p></div>
        <div><p class="re">ラ</p></div>
        <div><p class="re">ソ</p></div>
        <div><p class="so">ラ</p></div>
        <div><p class="so">シ</p></div>
      </div>
      <div class="phrase1">
        <div><p class="si high">ド</p></div>
        <div><p class="si">シ</p></div>
        <div><p class="mi">ラ</p></div>
        <div><p class="mi">ソ</p></div>
        <div><p class="fa2">ファ</p></div>
        <div><p class="re">ミ</p></div>
        <div><p class="fa">ファ</p></div>
        <div><p class="so">レ</p></div>
      </div>
      <div class="phrase2">
        <div><p class="p2">ド</p></div>
        <div><p class="p2">ミ</p></div>
        <div><p class="p2">ソ</p></div>
        <div><p class="p2">ファ</p></div>
        <div><p class="p2">ミ</p></div>
        <div><p class="p2 high">ド</p></div>
        <div><p class="p2 high">ミ</p></div>
        <div><p class="p2 high">レ</p></div>
        <div><p class="p2 high">ド</p></div>
        <div><p class="p2">ラ</p></div>
        <div><p class="p2 high">ド</p></div>
        <div><p class="p2">ソ</p></div>
        <div><p class="p2">ファ</p></div>
        <div><p class="p2">ラ</p></div>
        <div><p class="p2">ソァ</p></div>
        <div><p class="p2">ファ</p></div>
      </div>
      <div class="phrase2">
        <div><p class="p2">ミ</p></div>
        <div><p class="p2">ド</p></div>
        <div><p class="p2">レ</p></div>
        <div><p class="p2">シ</p></div>
        <div><p class="p2 high">ド</p></div>
        <div><p class="p2 high">ミ</p></div>
        <div><p class="p2 high">ソ</p></div>
        <div><p class="p2">ソ</p></div>
        <div><p class="p2">ラ</p></div>
        <div><p class="p2">ファ</p></div>
        <div><p class="p2">ソ</p></div>
        <div><p class="p2">ミ</p></div>
        <div><p class="p2">ドァ</p></div>
        <div><p class="p2 high">ド</p></div>
        <div><p class="p2 high">ド</p></div>
        <div><p class="p2">シ</p></div>
      </div>
    </div>
  </div>
</template>

<style scoped>
  h3 {
    margin-bottom: 0;
    font-family: "Zen Maru Gothic";
  }

  .unshi,
  .title,
  .phrase1 {
    justify-content: center;
    text-align: center;
  }
  .title,
  .unshi,
  .phrase1 {
    display: flex;
    font-family: "Zen Maru Gothic";
  }
  .phrase2 {
    display: flex;
    justify-content: center;
    text-align: center;
    font-family: "Zen Maru Gothic";
  }

  p {
    display: inline-block;
    width: 70px;
    height: 70px;
    color: white;
    background-color: green;
    border-radius: 40px;
    margin-left: 1.5rem;
    margin-right: 1.5rem;
    text-align: center;
    line-height: 55px;
    font-family: "Zen Maru Gothic";
    font-size: 3rem;
  }
  .p2 {
    display: inline-block;
    width: 50px;
    height: 50px;
    color: white;
    background-color: black;
    border-radius: 40px;
    margin-left: 0.5rem;
    margin-right: 0.5rem;
    text-align: center;
    line-height: 40px;
    font-family: "Zen Maru Gothic";
    font-size: 2.5rem;
  }

  .si {
    background-color: black;
  }
  .mi {
    background-color: black;
  }

  .re {
    background-color: black;
    color: white;
  }

  .so {
    background-color: black;
  }

  .fa {
    display: inline-block;
    width: 70px;
    height: 70px;
    color: white;
    background-color: black;
    border-radius: 40px;
    margin-left: 1.5rem;
    margin-right: 1.5rem;
    text-align: center;
    line-height: 55px;
    font-family: "Zen Maru Gothic";
    font-size: 2rem;
    margin-top: 2.8rem;
  }
  .fa2 {
    display: inline-block;
    width: 70px;
    height: 70px;
    color: white;
    background-color: black;
    border-radius: 40px;
    margin-left: 1.5rem;
    margin-right: 1.5rem;
    text-align: center;
    line-height: 55px;
    font-family: "Zen Maru Gothic";
    font-size: 2rem;
    margin-top: 2.8rem;
  }
  .high {
    color: tomato;
  }
</style>
