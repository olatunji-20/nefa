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
    height: 8.125rem;
    border: 2px solid red;
    /* background: green; */
    padding: 2.6875rem 3.125rem;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}
.logo {
    width: 45px;
    height: 40px;
    border: 1px solid blue;
}
.logo-image {
    width: 100%;
    height: 100%;
    object-fit: contain;
}
.options {
    width: auto;
    height: auto;
    /* border: 1px solid red; */
}
.options ul li {
    list-style-type: none;
    display: inline-block;
    font-size: 0.9rem;
    margin: 0rem 1.8rem;
    position: relative;
    top: 0px;
    transition: .3s;
}
.options ul li:hover {
    color: purple;
    cursor: pointer;
    top: -1px;
}
.noti {
    width: 30px;
    height: 40px;
    border: 1px solid red;
}
.landing {
    width: 100%;
    height: auto;
    border: 2px solid blue;
    /* background: seashell; */
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 2.5rem 1.25rem 6.25rem;
}
.landing .first {
    width: 41%;
    height: 37.5rem;
    border: 1px solid rgb(94, 43, 177);
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
    background: #2607FD;
    color: white;
    position: relative;
    border: 0px;
    clip-path: polygon(8% 0, 92% 0, 100% 20%, 100% 80%, 92% 100%, 8% 100%, 0 80%, 0 20%);
    transition: .5s;
}
button:hover {
    top: 3px;
    cursor: pointer;
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
    line-height: 0.5rem;
    padding-top: 13px;
}
.landing .second {
    width: 50%;
    height: 37.5rem;
    border: 1px solid blue;
}
.second .circle {
    width: 400px;
    height: 400px;
    background: rgb(94, 43, 177, 0.3);
    box-shadow: 3px 3px 3px 9px rgb(94, 43, 177, 0.3);
    border-radius: 50%;
    margin: 80px auto 0px;
    /* border: 2px solid tomato; */
}
.pad {
    width: 100%;
    height: 100%;
    position: relative;
    right: 50px;   
    object-fit: cover;
    transform: scale(1.8)
}
</style>