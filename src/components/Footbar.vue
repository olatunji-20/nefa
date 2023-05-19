<template>
  <section>
    <div class="one">
      <div class="write">
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Maxime
          placeat assumenda blanditiis adipisci velit odio ex nisi. Consequuntur
          ullam consectetur ut deserunt voluptates eius tenetur, voluptatum
          perspiciatis a molestiae est.
        </p>
      </div>
    </div>
    <div class="two">
      <p>Market Place</p>
      <ul>
        <li>All NFTs</li>
        <li>Art</li>
        <li>Collectibles</li>
        <li>Domain Names</li>
        <li>Music</li>
        <li>Photography</li>
        <li>Sport</li>
        <li>Trading Cards</li>
        <li>Utility</li>
        <li>Visual Words</li>
      </ul>
    </div>
    <div class="two">
      <p>Account</p>
      <ul>
        <li>Profile</li>
        <li>Favourite</li>
        <li>Collectibles</li>
        <li>Watchlist</li>
        <li>My Collectibles</li>
        <li>Photography</li>
        <li>Create</li>
        <li>Settings</li>
      </ul>
    </div>
    <div class="two">
      <p>Company</p>
      <ul>
        <li>About</li>
        <li>Careers</li>
        <li>Get in touch</li>
      </ul>
    </div>
    <div class="three">
      <p>© NEFA, All rights reserved.</p>
      <div class="socials">
        <div class="social-logo"><a href="#" class="fa fa-linkedin"></a></div>
        <div class="social-logo"><a href="#" class="fa fa-facebook"></a></div>
        <div class="social-logo"><a href="#" class="fa fa-twitter"></a></div>
        <div class="social-logo"><a href="#" class="fa fa-snapchat"></a></div>
        <div class="social-logo"><a href="#" class="fa fa-instagram"></a></div>
        <div class="social-logo"><a href="#" class="fa fa-telegram"></a></div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Footbar",
  data() {
    return {};
  },
};
</script>

<style scoped>
section {
  width: 100%;
  height: auto;
  background: #000000;
  color: white;
  display: flex;
  font-size: 14px;
  flex-direction: row;
  justify-content: center;
  flex-wrap: wrap;
  text-align: left;
  line-height: 25px;
}
.one {
  width: 400px;
  height: 400px;
  padding: 1.875rem 1.25rem;
}
.one .write {
  width: 80%;
  height: 200px;
}
.two {
  width: 250px;
  height: 400px;
  padding: 20px 30px;
}
.two ul li {
  list-style-type: none;
  text-indent: -40px;
  position: relative;
  left: 0px;
  transition: 0.4s;
  cursor: pointer;
}
.two ul li:hover {
  left: 10px;
}
.three {
  width: 100%;
  height: 90px;
  padding: 1.25rem 2.5rem;
}
.three p {
  float: left;
}
.three .socials {
  height: 30px;
  width: 250px;
  margin-top: 10px;
  float: right;
  padding: 2px;
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  justify-content: space-around;
}
.three .socials .social-logo {
  width: 25px;
  height: 25px;
  background: #000;
  border-radius: 50%;
}
.fa {
  padding: 0px 5px;
  font-size: 18px;
  color: white;
}

@media screen and (max-width: 500px) {
  section {
    flex-direction: column;
  }
  .one,
  .two {
    width: 100%;
    height: auto;
  }
  .three {
    height: auto;
  }
  .three .socials {
    float: left;
  }
}
</style>