<template>
  <section>
    <div class="first" data-aos="flip-left">
      <div class="one">
        <img src="../assets/334.png" class="first-image" />
      </div>
      <div class="two">
        <img src="../assets/331.png" class="first-image" />
      </div>
      <div class="three">
        <img src="../assets/333.png" class="first-image" />
      </div>
      <div class="four">
        <img src="../assets/332.png" class="first-image" />
      </div>
      <div class="five">
        <img src="../assets/335.png" class="first-image" />
      </div>
      <div class="six">
        <img src="../assets/442.png" class="first-image" />
      </div>
    </div>
    <div class="second" data-aos="flip-right">
      <h2>Explore New Collections</h2>
      <p>
        The world of NFTs is constantly evolving, with new and exciting pieces
        being released everyday. By exploring NFTs, you can discover new atists,
        support their work and be a part of a growing community that values
        creativity and innovation. <br /><br />
        So why not take the plunge and start exploring the world of NFTs?
        <br /><br />
        Whether you're an experienced collector or a newcomer to the art world,
        there's something for everyone in this exciting new frontier. Start
        browsing NFT marketplaces today and see what catches your eye - who
        knows, you may just find your next prized possession!
      </p>
      <button class="exp">Explore now</button>
    </div>
    <div class="stay">
      <h4>NEWSLETTER</h4>
      <h2>Stay in the loop</h2>
      <p>
        Join our mailing list to stay in the loop with our newest feature
        releases, NFT drops, tips and mailing list
      </p>
      <div class="mail">
        <input placeholder="Your mail address" />
        <button>join the waitlist</button>
      </div>
    </div>
  </section>
</template>

<script>
import AOS from 'aos';
import 'aos/dist/aos.css';

AOS.init({
  duration: 1000
});

export default {
  name: "Explore",
  data() {
    return {};
  },
};
</script>

<style scoped>
section {
  width: 100%;
  height: auto;
  display: flex;
  flex-direction: row;
  justify-content: center;
  flex-wrap: wrap;
}
section .first {
  width: 45%;
  height: auto;
  padding: 0.625rem;
  display: grid;
}
.first .one {
  width: 13.75rem;
  height: 16.25rem;
  margin: 0.3125rem;
  grid-row: 1;
  grid-column: 1;
  position: relative;
  top: 3.75rem;
  border-radius: 5px;
}
.first .two {
  width: 7.5rem;
  height: 7.5rem;
  margin: 0.3125rem;
  grid-row: 1;
  grid-column: 2;
  border-radius: 5px;
}
.first .three {
  width: 5.625rem;
  height: 5.625rem;
  margin: 0.3125rem;
  grid-row: 1;
  grid-column: 3;
  position: relative;
  top: 1.875rem;
  border-radius: 5px;
}
.first .four {
  width: 5.625rem;
  height: 5.625rem;
  margin: 0.3125rem;
  grid-row: 2;
  grid-column: 1;
  position: relative;
  top: 3.75rem;
  border-radius: 5px;
}
.first .five {
  width: 7.5rem;
  height: 7.5rem;
  margin: 0.3125rem;
  grid-row: 2;
  grid-column: 2;
  position: relative;
  top: 3.75rem;
  right: 8.125rem;
  border-radius: 5px;
}
.first .six {
  width: 13.75rem;
  height: 16.25rem;
  margin: 0.3125rem;
  grid-row: 2;
  grid-column: 3;
  position: relative;
  right: 8.125rem;
  bottom: 8.75rem;
  border-radius: 5px;
}
.first-image {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 5px;
}
section .second {
  width: 45%;
  height: auto;
  text-align: left;
  padding: 3.125rem 1rem;
}
.exp {
  width: 12.5rem;
  height: 3.125rem;
  margin-top: 1.25rem;
  background: #2607fd;
  color: white;
  border: 0px;
  clip-path: polygon(
    7% 0,
    93% 0,
    100% 20%,
    100% 80%,
    93% 100%,
    7% 100%,
    0 80%,
    0 20%
  );
  font-family: "Orbitron", sans-serif;
  position: relative;
  top: 0px;
  transition: 0.4s;
}
.exp:hover {
  top: 3px;
  background: purple;
  cursor: pointer;
}
.stay {
  width: 100%;
  height: auto;
  padding: 2.5rem 0rem 7.5rem;
}
.stay .mail {
  width: 40%;
  height: 2.5rem;
  margin: 2rem auto 0px;
  padding-top: 0px;
  clip-path: polygon(
    4% 0,
    96% 0,
    100% 20%,
    100% 80%,
    96% 100%,
    4% 100%,
    0 80%,
    0 20%
  );
}
.stay .mail input {
  width: 70%;
  height: 100%;
  margin-top: 0px;
  text-indent: 1.25rem;
  border: 0px;
  font-family: "Orbitron", sans-serif;
}
.stay .mail button {
  width: 29%;
  height: 100%;
  background: #2607fd;
  color: white;
  border: 0px;
  font-family: "Orbitron", sans-serif;
}

@media screen and (max-width: 500px) {
  section {
    flex-direction: column;
  }
  section .first {
    width: 100%;
    display: none;
  }
  section .second {
    width: 100%;
    height: auto;
  }
  .stay {
    line-height: auto;
  }
  .stay .mail {
    width: 80%;
  }
  .stay .mail input {
    width: 50%;
  }
  .stay .mail button {
    width: 50%;
  }
}
</style>