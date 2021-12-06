<template>
  <div>
    <div class="footer-up">
      <div class="list">
        <ul>
          <li>DC COMICS</li>
          <li><a href="">Characters</a></li>
          <li><a href="">Comics</a></li>
          <li><a href="">Movies</a></li>
          <li><a href="">TV</a></li>
          <li><a href="">Games</a></li>
          <li><a href="">Viedos</a></li>
          <li><a href="">News</a></li>
          <li id="shop">SHOP</li>
          <li><a href="">SHOP DC</a></li>
          <li><a href="">Shop DC Collectibles</a></li>
        </ul>

        <ul>
          <li>DC</li>
          <li><a href="">Terms Of Use</a></li>
          <li><a href="">Privacy policy (New)</a></li>
          <li><a href="">Ad Choise</a></li>
          <li><a href="">Adversting</a></li>
          <li><a href="">Jobs</a></li>
          <li><a href="">Subscriptions</a></li>
          <li><a href="">Talent Workshops</a></li>
          <li><a href="">CPSC Certificates</a></li>
          <li><a href="">Ratings</a></li>
          <li><a href="">Shop Help</a></li>
          <li><a href="">Contact Us</a></li>
        </ul>

        <ul>
          <li>SITES</li>
          <li><a href="">DC</a></li>
          <li><a href="">MAD Magazine</a></li>
          <li><a href="">DC Kids</a></li>
          <li><a href="">DC Universe</a></li>
          <li><a href="">DC Power Visa</a></li>
        </ul>
      </div>
      <div class="icon-footer"></div>
    </div>

    <div class="footer-down">
      <div><a href="">SIGN-UP NOW</a></div>
      <div class="social">
        <div>FOLLOW US</div>
        <a href="">
          <img src="../assets/footer-facebook.png" alt="" />
        </a>

        <a href="">
          <img src="../assets/footer-twitter.png" alt="" />
        </a>

        <a href="">
          <img src="../assets/footer-youtube.png" alt="" />
        </a>

        <a href="">
          <img src="../assets/footer-pinterest.png" alt="" />
        </a>

        <a href="">
          <img src="../assets/footer-periscope.png" alt="" />
        </a>

      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss" scoped>
a {
  text-decoration: none;
  color: rgb(114, 113, 113);
}
.footer-up {
  display: flex;
  justify-content: space-around;
  background-image: url(../assets/footer-bg.jpg);
  color: white;
  flex-wrap: wrap;
  .list {
    display: flex;
    margin: 50px 0;

    ul {
      margin: 0 15px;
      li:first-of-type {
        margin: 10px 0;
      }
      #shop {
        margin: 10px 0;
      }
    }
  }

  .icon-footer {
    width: 50%;
    background-image: url(../assets/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-position: center;
  }
}

.footer-down {
  background-color: rgb(49, 49, 49);
  height: 100px;
  display: flex;
  justify-content: space-around;
  align-items: center;

   div:first-of-type a:first-of-type{
    color: white;
    border: 1px solid dodgerblue;
    padding: 10px
;
    
  }
  .social{
    display: flex;
    align-items: center;
    color: dodgerblue;
      img{
      width: 25px;
      margin: 0 6px;
    }
  }
}
</style>