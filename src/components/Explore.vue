<template>
    <section>
        <div class="first">
            <div class="one"></div>
            <div class="two"></div>
            <div class="three"></div>
            <div class="four"></div>
            <div class="five"></div>
            <div class="six"></div>
        </div>
        <div class="second">
            <h2>Explore New Collections</h2>
            <p>The world of NFTs is constantly evolving, with new and exciting pieces being released everyday. By exploring NFTs, you can discover new atists, support their
                work and be a part of a growing community that values creativity and innovation. <br /><br />
                So why not take the plunge and start exploring the world of NFTs? <br /><br />
                Whether you're an experienced collector or a newcomer to the art world, there's something for everyone in this exciting new frontier. Start browsing NFT 
                marketplaces today and see what catches your eye - who knows, you may just find your next prized possession!
            </p>
            <button class="exp">Explore now</button>
        </div>
        <div class="stay">
            <h4>NEWSLETTER</h4>
            <h2>Stay in the loop</h2>
            <p>Join our mailing list to stay in the loop with our newest feature releases, NFT drops, tips and mailing list</p>
            <div class="mail">
                <input placeholder="Your mail address" />
                <button>join the waitlist</button>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "Explore",
    data() {
        return {

        }
    }
}
</script>

<style scoped>
section {
    width: 100%;
    height: auto;
    border: 2px solid firebrick;
    display: flex;
    flex-direction: row;
    justify-content: center;
    flex-wrap: wrap;
}
section .first {
    width: 45%;
    height: auto;
    border: 3px solid rebeccapurple;
    padding: 10px;
    display: grid;
}
.first .one {
    width: 220px;
    height: 260px;
    border: 1px solid red;
    margin: 5px;
    grid-row: 1;
    grid-column: 1;
    position: relative;
    top: 60px;
    border-radius: 5px;
}
.first .two {
    width: 120px;
    height: 120px;
    border: 1px solid blue;
    margin: 5px;
    grid-row: 1;
    grid-column: 2;
    border-radius: 5px;
}
.first .three {
    width: 90px;
    height: 90px;
    border: 1px solid green;
    margin: 5px;
    grid-row: 1;
    grid-column: 3;
    position: relative;
    top: 30px;
    border-radius: 5px;
}
.first .four {
    width: 90px;
    height: 90px;
    border: 1px solid green;
    margin: 5px;
    grid-row: 2;
    grid-column: 1;
    position: relative;
    top: 60px;
    border-radius: 5px;
}
.first .five {
    width: 120px;
    height: 120px;
    border: 1px solid green;
    margin: 5px;
    grid-row: 2;
    grid-column: 2;
    position: relative;
    top: 60px;
    right: 130px;
    border-radius: 5px;
}
.first .six {
    width: 220px;
    height: 260px;
    border: 1px solid green;
    margin: 5px;
    grid-row: 2;
    grid-column: 3;
    position: relative;
    right: 130px;
    bottom: 140px;
    border-radius: 5px;
}
section .second {
    width: 45%;
    height: auto;
    border: 2px solid palevioletred;
    text-align: left;
    padding-top: 50px;
}
.exp {
    width: 200px;
    height: 50px;
    margin-top: 20px;
    background: tomato;
    border: 0px;
    clip-path: polygon(10% 0, 90% 0, 100% 25%, 100% 75%, 90% 100%, 10% 100%, 0 75%, 0 25%);
}
.stay {
    border: 2px solid hotpink;
    width: 100%;
    height: auto;
    padding: 40px 0px 120px;
    line-height: 7px;
}
.stay .mail {
    border: 1px solid green;
    width: 500px;
    height: 30px;
    margin: 0px auto;
    padding-top: 0px;
    clip-path: polygon(10% 0, 90% 0, 100% 25%, 100% 75%, 90% 100%, 10% 100%, 0 75%, 0 25%);
}
.stay .mail input {
    width: 70%;
    height: 100%;
    border: 1px solid black;
    margin-top: 0px;
    text-indent: 20px;
}
.stay .mail button {
    width: 29%;
    height: 100%;
    background: green;
    border: 0px;
}
</style>