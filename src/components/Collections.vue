<template>
    <section>
        <div class="feat">
            <h2>Featured Collections</h2>
            <p>See what's trending</p>  
        </div>
        <select>
            <option>24h</option>
            <option>48h</option>
        </select>
        <div class="blossom">
            <div class="card">
                <div class="card-image"></div>
                <div class="details">
                    <h4>Blossom Twinkles</h4>
                    <div class="price">
                        <div class="p">
                            <p>Price</p>
                            <h5>789 CSPR</h5>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "Collections",
    data () {
        return {

        }
    }
}
</script>

<style scoped>
section {
    border: 2px solid yellowgreen;
    width: 100%;
    height: 700px;
    text-align: left;
    padding: 40px 50px;
    /* display: flex;
    flex-direction: row;
    flex-wrap: wrap; */
}
.feat {
    float: left;
    line-height: 5px;
}
.feat h2 {
    font-size: 35px;
}
select {
    width: 250px;
    height: 40px;
    border-radius: 10px;
    float: right;
    margin-top: 20px;
}
.blossom {
    width: 99%;
    height: 300px;
    border: 2px solid peru;
    display: block;
    margin: 140px auto;
    padding: 5px;
}
.card {
    border: 1px solid green;
    width: 220px;
    height: 280px;
}
.card-image {
    width: 100%;
    height: 150px;
    border: 1px solid red;
}
.details {
    width: 100%;
    height: 120px;
    border: 1px solid blue;
}
.price {
    width: 100%;
    height: 50px;
    border: 2px solid firebrick;
}
.p {
    width: 100px;
    height: 50px;
    border: 2px solid red;
    line-height: 0px;
}
</style>