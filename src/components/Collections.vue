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
                        <div class="com">
                            <div class="comm">
                                <p>43</p>
                            </div>
                            <div class="comm">
                                <p>43</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="card">
                <div class="card-image"></div>
                <div class="details">
                    <h4>Blossom Twinkles</h4>
                    <div class="price">
                        <div class="p">
                            <p>Price</p>
                            <h5>789 CSPR</h5>
                        </div>
                        <div class="com">
                            <div class="comm">
                                <p>43</p>
                            </div>
                            <div class="comm">
                                <p>43</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="card">
                <div class="card-image"></div>
                <div class="details">
                    <h4>Blossom Twinkles</h4>
                    <div class="price">
                        <div class="p">
                            <p>Price</p>
                            <h5>789 CSPR</h5>
                        </div>
                        <div class="com">
                            <div class="comm">
                                <p>43</p>
                            </div>
                            <div class="comm">
                                <p>43</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="card">
                <div class="card-image"></div>
                <div class="details">
                    <h4>Blossom Twinkles</h4>
                    <div class="price">
                        <div class="p">
                            <p>Price</p>
                            <h5>789 CSPR</h5>
                        </div>
                        <div class="com">
                            <div class="comm">
                                <p>43</p>
                            </div>
                            <div class="comm">
                                <p>43</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="card">
                <div class="card-image"></div>
                <div class="details">
                    <h4>Blossom Twinkles</h4>
                    <div class="price">
                        <div class="p">
                            <p>Price</p>
                            <h5>789 CSPR</h5>
                        </div>
                        <div class="com">
                            <div class="comm">
                                <p>43</p>
                            </div>
                            <div class="comm">
                                <p>43</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            
            
        </div>

        <div class="feat">
            <h2>Leaderboard</h2>
            <p>Latest from casper</p>  
        </div>
        <select>
            <option>24h</option>
            <option>48h</option>
        </select>

        <div class="table">
            <table>
                <tr>
                    <th>Collections</th>
                    <th>Total Volume</th>
                    <th>Floor Price</th>
                    <th style="width: 120px">Unique Owners</th>
                    <th style="text-align: right; width: 180px">Items Listed</th>
                </tr>
                <tr>
                    <td class="eee">1. <div class="draw"></div> Collections</td>
                    <td>4935 CSPR</td>
                    <td>11 CSPR</td>
                    <td style="text-align: right;">675</td>
                    <td style="text-align: right;">1862</td>
                </tr>
                <tr>
                    <td class="eee">2. <div class="draw"></div> Collections</td>
                    <td>4935 CSPR</td>
                    <td>11 CSPR</td>
                    <td style="text-align: right;">675</td>
                    <td style="text-align: right;">1862</td>
                </tr>
                <tr>
                    <td class="eee">3. <div class="draw"></div> Collections</td>
                    <td>4935 CSPR</td>
                    <td>11 CSPR</td>
                    <td style="text-align: right;">675</td>
                    <td style="text-align: right;">1862</td>
                </tr>
                <tr>
                    <td class="eee">4. <div class="draw"></div> Collections</td>
                    <td>4935 CSPR</td>
                    <td>11 CSPR</td>
                    <td style="text-align: right;">675</td>
                    <td style="text-align: right;">1862</td>
                </tr>
            </table>
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
    height: auto;
    text-align: left;
    padding: 40px 30px;
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
    width: 180px;
    height: 40px;
    border-radius: 10px;
    float: right;
    margin-top: 20px;
}
.blossom {
    width: 100%;
    height: auto;
    border: 2px solid peru;
    display: block;
    margin: 140px auto;
    padding: 5px;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    flex-wrap: wrap;
}
.card {
    border: 1px solid green;
    width: 230px;
    height: 300px;
    position: relative;
    top: 0px;
}
.card:hover {
    top: -10px;
    cursor: pointer;
}
.card-image {
    width: 100%;
    height: 200px;
    border: 1px solid red;
}
.details {
    width: 100%;
    height: 100px;
    border: 1px solid blue;
    padding-left: 5px;
    line-height: 4px;
}
.price {
    width: 100%;
    height: 50px;
    border: 2px solid firebrick;
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content: space-between;
}
.p {
    width: 80px;
    height: 48px;
    border: 1px solid red;
    line-height: 0px;
}
.com {
    border: 1px solid green;
    width: 150px;
    height: 48px;
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
}
.comm {
    border: 1px solid teal;
    width: 50%;
    height: 45px;
    padding: 4px 0px;
    text-align: center;
}
.table {
    border: 2px solid fuchsia;
    width: 100%;
    height: auto;
    margin: 270px auto 100px;
}
table {
    width: 100%;
}
th {
    padding: 15px 0px;
}
td {
    padding: 7px 0px;
}
.eee {
    line-height: 28px;
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
}
table, th, td {
    border: 1px solid blue;
    border-collapse: collapse;
}
.draw {
    width: 30px;
    height: 30px;
    margin-right: 10px;
    background: powderblue;
}
</style>