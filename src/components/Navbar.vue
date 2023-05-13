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
</style>