<template>
  <dev>
    <h1 id = "portfolio">Portfolio</h1>
    <ul class = "portfolio-list">
      <li class = "portfolio-card">
        <img src ="../assets/typing-adventurer.png" alt="" class="profile-img">
        <p class = "portfolio-title">Typing Adventurer</p>
        <p class = "portfolio-description">自作タイピングゲーム</p>
        <p cladd = "portfolio-technology">Unity, C#</p>
        <p class = "portfolio-description">link: <a href="https://maaaarcy.github.io/Typing-Adventurer/">TypingAdventurer</a></p>
      </li>
    </ul>
  </dev>
</template>

<style>
#portfolio {
  text-align:center;
  margin-top: 80px;
}
.portfolio-list {
  list-style-type: none;
  text-align: center;
}
.portfolio-card {
  display: inline-block;
  margin-top: 30px;
  margin-right: 20px;
  width: 350px;
  background: #fff;
  box-shadow: 0 20px 30px #ccc;
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