<template>
  <dev>
    <h1 id = "portfolio">Portfolio</h1>
    <ul class = "portfolio-list">
      <li class = "portfolio-card">
        <img src ="../assets/typing-adventurer.png" alt="" class="profile-img">
        <p class = "portfolio-title">Typing Adventurer</p>
        <p class = "portfolio-description">自作タイピングゲーム</p>
        <p cladd = "portfolio-technology">使用技術:Unity, C#</p>
        <p class = "portfolio-description">link: <a href="https://maaaarcy.github.io/Typing-Adventurer/">TypingAdventurer</a></p>
      </li>
      <li class = "portfolio-card">
        <img src ="../assets/Liverary.png" alt="" class="profile-img">
        <p class = "portfolio-title">Liverary</p>
        <p class = "portfolio-description">Open Hack U 2020 Online Vol.5出場作品</p>
        <p cladd = "portfolio-technology">使用技術:Vue.js,Flask,Raspberrypi</p>
        <p class = "portfolio-description">link: <a href="https://www.slideshare.net/ShomaKobayashi/liverary">Liverary</a></p>
      </li>
    </ul>
  </dev>
</template>

<script>
export default {
  name: 'Portfolio'
}
</script>

<style>
#portfolio {
  text-align:center;
  margin-top: 80px;
}
.portfolio-list {
  text-align: center;
  overflow-x: auto;
  white-space: nowrap;
  -webkit-overflow-scrolling: touch;
}
.portfolio-card {
  display: inline-block;
  margin-left: -15px;
  margin-right: 30px;
  margin-bottom: 20px;
  width: 350px;
  background: #fff;
}
.profile-img {
  width: 100%;
  height: 100%;
}
.portfolio-title {
  font-size: 150%;
}
.portfolio-description {
  font-size: 100%;
}
.portfolio-technology {
  font-size: 100%;
}
</style>