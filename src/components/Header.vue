<template>
  <div class="header-container">
    <div class="container-logo">
      <img src="../assets/dc-logo.png" alt="" />
    </div>

    <div>
      <ul>
        <li>CHARACTERS</li>
        <li>COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped>
.header-container {
  display: flex;
  justify-content: space-around;
  align-items:center;

  .container-logo {
    margin: 15px 0;
  }

  ul {
    display: flex;
    li {
      margin: 0 10px;
    }
  }
}
</style>