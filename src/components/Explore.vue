<template>
    <section>
        <div class="first">
            <div class="one">
                <img src="../assets/334.png" class="first-image">
            </div>
            <div class="two">
                <img src="../assets/331.png" class="first-image">
            </div>
            <div class="three">
                <img src="../assets/333.png" class="first-image">
            </div>
            <div class="four">
                <img src="../assets/332.png" class="first-image">
            </div>
            <div class="five">
                <img src="../assets/335.png" class="first-image">
            </div>
            <div class="six">
                <img src="../assets/442.png" class="first-image">
            </div>
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
    padding: 0.625rem;
    display: grid;
}
.first .one {
    width: 13.75rem;
    height: 16.25rem;
    border: 1px solid red;
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
    border: 1px solid blue;
    margin: 0.3125rem;
    grid-row: 1;
    grid-column: 2;
    border-radius: 5px;
}
.first .three {
    width: 5.625rem;
    height: 5.625rem;
    border: 1px solid green;
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
    border: 1px solid green;
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
    border: 1px solid green;
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
    /* border: 1px solid green; */
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
    border: 2px solid palevioletred;
    text-align: left;
    padding-top: 3.125rem;
}
.exp {
    width: 12.5rem;
    height: 3.125rem;
    margin-top: 1.25rem;
    background: #2607FD;
    color: white;
    border: 0px;
    clip-path: polygon(7% 0, 93% 0, 100% 20%, 100% 80%, 93% 100%, 7% 100%, 0 80%, 0 20%);
}
.stay {
    border: 2px solid hotpink;
    width: 100%;
    height: auto;
    padding: 2.5rem 0rem 7.5rem;
    line-height: 7px;
}
.stay .mail {
    border: 1px solid green;
    width: 31.25rem;
    height: 2.5rem;
    margin: 2rem auto 0px;
    padding-top: 0px;
    clip-path: polygon(4% 0, 96% 0, 100% 20%, 100% 80%, 96% 100%, 4% 100%, 0 80%, 0 20%);
}
.stay .mail input {
    width: 70%;
    height: 100%;
    border: 1px solid black;
    margin-top: 0px;
    text-indent: 1.25rem;
}
.stay .mail button {
    width: 29%;
    height: 100%;
    background: #2607FD;
    color: white;
    border: 0px;
}
</style>