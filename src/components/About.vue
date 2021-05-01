<template>
  <dev>
    <h1 id = "profile-title"> About me </h1>
    <dev class = "profile-config">
      <img src="../assets/slime.png" alt="logo" class="profile-image">
      <dev class = "profile-data">      
        <div class = "profile-link"><font-awesome-icon :icon="['fab','twitter']" />: <a href="https://twitter.com/_marcy___">@twitter</a></div>
        <div class = "profile-link"><font-awesome-icon icon="envelope" />: <a href="changjungu65@gmaill.com">@gmail</a></div>
        <div class = "profile-link"><font-awesome-icon :icon="['fab','github']" />: <a href="https://github.com/MAAAARCY">@github</a></div>
      </dev>
    </dev>
  </dev>
</template>

<style>
.profile-image {
  width: 100px;
  height: 100px;
  padding-right: 5%;
} 
.profile-config {
  display: flex;
  justify-content: center;
}
.profile-data {
  flex-flow: column;
}
.profile-link {
  font-size: 150%;
  padding-bottom: 10%;
}
#profile-title {
  text-align: center;
}
#profile {
  background-color: #000000;
}
</style>