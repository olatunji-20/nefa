<template>
    <div class="main">
        <div class="logo"></div>
        <div class="options">
            <ul>
                <li>Direction</li>
                <li>Create</li>
                <li>Cart</li>
                <li>Maps</li>
                <li>Support</li>
            </ul>
        </div>
        <div class="noti"></div>
    </div>
    <div class="landing">
        <div class="first">
            <h2 class="discover">Discover exclusive NFTs on the jasper network</h2>
            <p class="intro">Introducing the newest addition to the NFT Marketplace, welcome to NFTS on the casper network</p>
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
                <div class="numb" style="border-right: 0px;">
                    <h1>50K</h1>
                    <p>Creators</p>
                </div>
            </div>
        </div>
        <div class="second">
            <div class="circle">
                <img src="../assets/pad.png" class="pad" />
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Name",
    data() {
        return {

        }
    }
}
</script>

<style scoped>
.main {
    width: 100%;
    height: 130px;
    border: 2px solid red;
    background: green;
    padding: 43px 50px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}
.logo {
    width: 45px;
    height: 40px;
    border: 1px solid blue;
}
.options {
    width: auto;
    height: auto;
    border: 1px solid red;
}
.options ul li {
    list-style-type: none;
    display: inline-block;
    font-size: 14px;
    margin: 0px 30px;
}
.noti {
    width: 30px;
    height: 40px;
    border: 1px solid red;
}
.landing {
    width: 100%;
    height: 900px;
    border: 2px solid blue;
    background: seashell;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 40px 20px;
}
.landing .first {
    width: 40%;
    height: 700px;
    border: 1px solid green;
    text-align: left;
}
.discover {
    font-size: 45px;
    text-align: left;
}
.intro {
    font-size: 18px;
    width: 420px;
}
button {
    font-size: 20px;
    width: 200px;
    height: 60px;
    margin-top: 20px;
    background: tomato;
    border: 0px;
    clip-path: polygon(10% 0, 90% 0, 100% 25%, 100% 75%, 90% 100%, 10% 100%, 0 75%, 0 25%);
}
.creator {
    border: 1px solid red;
    width: 100%;
    height: 100px;
    margin-top: 50px;
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
}
.numb {
    border-right: 2px solid blue;
    text-align: center;
    width: 140px;
    height: 100%;
    line-height: 8px;
    padding-top: 13px;
}
.landing .second {
    width: 50%;
    height: 700px;
    border: 1px solid blue;
}
.second .circle {
    width: 500px;
    height: 500px;
    border-radius: 50%;
    margin: 50px auto;
    border: 2px solid tomato;
}
.pad {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transform: scale(0.2)
}
</style>