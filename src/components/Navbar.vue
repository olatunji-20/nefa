<template>
  <div class="main">
    <div class="logo">
      <img src="../assets/N.png" class="logo-image" />
    </div>
    <div class="options">
      <ul>
        <li>Direction</li>
        <li>Create</li>
        <li>Cart</li>
        <li>Maps</li>
        <li>Support</li>
      </ul>
    </div>
    <div class="noti">
      <span class="material-icons-outlined">notifications</span>
    </div>
  </div>
  <div class="landing">
    <div class="first">
      <h2 class="discover">Discover exclusive NFTs on the jasper network</h2>
      <p class="intro">
        Introducing the newest addition to the NFT Marketplace, welcome to NFTS
        on the casper network
      </p>
      <button>Get started</button>
      <div class="creator">
        <div class="numb">
          <h1>220K</h1>
          <p>NFTs</p>
        </div>
        <div class="numb">
          <h1>10K</h1>
          <p>Users</p>
        </div>
        <div class="numb" style="border-right: 0px">
          <h1>50K</h1>
          <p>Creators</p>
        </div>
      </div>
    </div>
    <div class="second">
        <img src="../assets/pad.png" class="pad" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Name",
  data() {
    return {};
  },
};
</script>

<style scoped>
.main {
  width: 100%;
  height: 8.125rem;
  padding: 2.6875rem 3.125rem;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.logo {
  width: 45px;
  height: 40px;
}
.logo-image {
  width: 100%;
  height: 100%;
  object-fit: contain;
}
.options {
  width: auto;
  height: auto;
}
.options ul li {
  list-style-type: none;
  display: inline-block;
  font-size: 0.9rem;
  margin: 0rem 1.8rem;
  position: relative;
  top: 0px;
  transition: 0.3s;
}
.options ul li:hover {
  color: purple;
  cursor: pointer;
  top: -1px;
}
.noti {
  width: 30px;
  height: auto;
  margin-top: 15px;
}
.landing {
  width: 100%;
  height: auto;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-around;
  padding: 2rem 1.25rem 6.25rem;
}
.landing .first {
  width: 41%;
  height: 37.5rem;
  text-align: left;
}
.discover {
  font-size: 45px;
  text-align: left;
}
.intro {
  font-size: 18px;
  width: 26.25rem;
}
button {
  font-size: 20px;
  width: 200px;
  height: 55px;
  margin-top: 20px;
  background: #2607fd;
  color: white;
  position: relative;
  top: 0px;
  border: 0px;
  clip-path: polygon(
    8% 0,
    92% 0,
    100% 20%,
    100% 80%,
    92% 100%,
    8% 100%,
    0 80%,
    0 20%
  );
  transition: 0.5s;
  font-family: "Orbitron", sans-serif;
}
button:hover {
  top: 3px;
  cursor: pointer;
  background: purple;
}
.creator {
  width: 100%;
  height: 100px;
  margin-top: 50px;
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
}
.numb {
  text-align: center;
  width: 140px;
  height: 100%;
  line-height: 0.5rem;
  padding-top: 13px;
  border-right: 1px solid white;
}
.landing .second {
  width: 50%;
  height: 37.5rem;
  background-image: url(../assets/ellipse.png);
  background-size: cover;
}
.pad {
  width: 100%;
  height: 100%;
  position: relative;
  right: 50px;
  object-fit: cover;
  transform: scale(1.2);
}

@media screen and (max-width: 500px) {
  .main {
    border-bottom: 1px solid purple;
  }
  .options {
    display: none;
  }
  .landing {
    flex-direction: column;
    padding: 1rem 1.25rem 3rem;
  }
  .landing .first {
    width: 100%;
    height: 30rem;
  }
  .discover {
    font-size: 38px;
  }
  .intro {
    font-size: 13px;
    width: auto;
  }
  .landing .second {
    width: 100%;
    height: 30rem;
    margin-top: 30px;
  }
  .second .circle {
    width: 18rem;
    height: 18rem;
  }
  .pad {
    transform: scale(1.1);
  }
}
</style>