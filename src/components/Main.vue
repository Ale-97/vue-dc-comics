<template>
  <div class="main-container">
    <div class="container-black"> 
      <div> --&gt;Content goes here &lt;-- </div>
      </div>
    <div class="container-icon">
      <div>
        <img src="../assets/buy-comics-digital-comics.png" alt="" />
        <div>DIGITAL COMICS</div>
      </div>
      <div>
        <img src="../assets/buy-comics-merchandise.png" alt="" />
        <div>DC MERCHANDISE</div>
      </div>
      <div>
        <img src="../assets/buy-comics-subscriptions.png" alt="" />
        <div>SUBSCRIPTION</div>
      </div>
      <div>
        <img src="../assets/buy-comics-shop-locator.png" alt="" />
        <div>COMIC SHOP LOCATOR</div>
      </div>
      <div>
        <img src="../assets/buy-dc-power-visa.svg" alt="" />
        <div>DC POWER VISA</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Main",
};
</script>

<style lang="scss" scoped>
.main-container {
  color: white;


  .container-black {
    height: 100px;
    background: black;
    display: flex;
    align-items: center;
  };


  .container-icon {
    background-color: dodgerblue;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 12px;
    padding: 40px 0;

    div {
      display: flex;
      align-items: center;
      margin: 0 15px;

      img {
        width: 50px;
      };

      &:nth-of-type(4) > img,&:nth-of-type(1) > img {
        width: 35px;
      };

    };
  };
};
</style>