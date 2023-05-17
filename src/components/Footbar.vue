<template>
    <section>
        <div class="one">
            <div class="write">
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Maxime placeat assumenda blanditiis adipisci velit odio ex nisi. Consequuntur ullam consectetur ut deserunt voluptates eius tenetur, voluptatum perspiciatis a molestiae est.</p>
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
                <div class="social-logo"></div>
                <div class="social-logo"></div>
                <div class="social-logo"></div>
                <div class="social-logo"></div>
                <div class="social-logo"></div>
                <div class="social-logo"></div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "Footbar",
    data() {
        return {

        }
    }
}
</script>

<style scoped>
section {
    width: 100%;
    height: 500px;
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
    width: 30%;
    height: 400px;
    border: 1px solid black;
    padding: 1.875rem 1.25rem;
}
.one .write {
    width: 80%;
    height: 200px;
    border: 1px solid purple;
}
.two {
    width: 20%;
    height: 400px;
    padding: 20px 30px;
    border: 1px solid red;
}
.two ul li {
    list-style-type: none;
    text-indent: -40px;
    position: relative;
    left: 0px;
    transition: .4s;
    cursor: pointer;
}
.two ul li:hover {
    left: 10px;
}
.three {
    width: 100%;
    height: 90px;
    border: 1px solid green;
    padding: 1.25rem 2.5rem;
}
.three p {
    float: left;
}
.three .socials {
    border: 1px solid red;
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
    border: 1px solid blue;
    width: 25px;
    height: 25px;
    background: powderblue;
    border-radius: 50%;
}
</style>