<template>
  <dev>
    <h1 id = "skill">skill</h1>
    <h1 id = "skill">languages</h1>
    <ul class = "skill-list">
      <li class = "skill-language"><img src="../assets/skills/C++.png" alt="" class="skill-language-img"></li>
      <li class = "skill-language"><img src="../assets/skills/CSharp.png" alt="" class="skill-language-img"></li>
      <li class = "skill-language"><img src="../assets/skills/python.png" alt="" class="skill-python-img"></li>
    </ul>
    <h1 id = "skill">frameworks</h1>
    <ul class = "skill-list">
      <li class = "skill-language"><img src="../assets/skills/vue.png" alt="" class="skill-language-img"></li>
      <li class = "skill-language"><img src="../assets/skills/django.png" alt="" class="skill-python-img"></li>
    </ul>
    <h1 id = "skill">others</h1>
    <ul class = "skill-list">
      <li class = "skill-language"><img src="../assets/skills/unity.png" alt="" class="skill-others-img"></li>
      <li class = "skill-language"><img src="../assets/skills/blender.png" alt="" class="skill-blender-img"></li>
    </ul>
  </dev>
</template>

<script>
export default {
  name: 'Skill'
}
</script>

<style>
#skill {
  text-align: center;
  margin-top: 80px;
}
.skill-list {
  text-align: center;
  padding-left: 15%;
  padding-right: 15%;
  margin-bottom: 10px;
}
.skill-language {
  display: inline-block;
  margin :10px 30px;
  width: 100px;
}
.skill-language-img {
  width: 50px;
  height: 50px;
}
.skill-python-img {
  width: 150px;
  height: 50px;
}
.skill-others-img {
  width: 150px;
  height: 75px;
} 
.skill-blender-img {
  width: 150px;
  height: 50px;
  margin-bottom: 15px;
}

</style>