<template>
  <dev>
    <h1 id="works">Works</h1>
    <dev id="works-list">
      <ul>
        <li id="works-content"> 高専ロボコン2019出場 </li>
        <li id="works-content"> Open Hack U 2020 Online Vol.5出場 </li>
      </ul>
    </dev>
  </dev>
</template>

<script>
export default {
  name: 'Works'
}
</script>

<style>
#works{
    text-align: center;
}
#works-list{
    display: flex;
    justify-content: center;
}
#work-content{
    text-align: center;
    list-style-type: none;
}
</style>