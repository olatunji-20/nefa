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
        <div class="card-image">
          <img src="../assets/113.png" class="image-card" />
        </div>
        <div class="details">
          <h4>Blossom Twinkles</h4>
          <div class="price">
            <div class="p">
              <p>Price</p>
              <p class="cspr">789 CSPR</p>
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
        <div class="card-image">
          <img src="../assets/441.png" class="image-card" />
        </div>
        <div class="details">
          <h4>Blossom Twinkles</h4>
          <div class="price">
            <div class="p">
              <p>Price</p>
              <p class="cspr">789 CSPR</p>
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
        <div class="card-image">
          <img src="../assets/114.png" class="image-card" />
        </div>
        <div class="details">
          <h4>Blossom Twinkles</h4>
          <div class="price">
            <div class="p">
              <p>Price</p>
              <p class="cspr">789 CSPR</p>
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
        <div class="card-image">
          <img src="../assets/115.png" class="image-card" />
        </div>
        <div class="details">
          <h4>Blossom Twinkles</h4>
          <div class="price">
            <div class="p">
              <p>Price</p>
              <p class="cspr">789 CSPR</p>
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
        <div class="card-image">
          <img src="../assets/116.png" class="image-card" />
        </div>
        <div class="details">
          <h4>Blossom Twinkles</h4>
          <div class="price">
            <div class="p">
              <p>Price</p>
              <p class="cspr">789 CSPR</p>
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
          <td class="eee">
            1.
            <div class="draw">
              <img src="../assets/222.png" class="draw-image" />
            </div>
            Collections
          </td>
          <td>4935 CSPR</td>
          <td>11 CSPR</td>
          <td style="text-align: right">675</td>
          <td style="text-align: right">1862</td>
        </tr>
        <tr>
          <td class="eee">
            2.
            <div class="draw">
              <img src="../assets/221.png" class="draw-image" />
            </div>
            Collections
          </td>
          <td>4935 CSPR</td>
          <td>11 CSPR</td>
          <td style="text-align: right">675</td>
          <td style="text-align: right">1862</td>
        </tr>
        <tr>
          <td class="eee">
            3.
            <div class="draw">
              <img src="../assets/223.png" class="draw-image" />
            </div>
            Collections
          </td>
          <td>4935 CSPR</td>
          <td>11 CSPR</td>
          <td style="text-align: right">675</td>
          <td style="text-align: right">1862</td>
        </tr>
        <tr>
          <td class="eee">
            4.
            <div class="draw">
              <img src="../assets/224.png" class="draw-image" />
            </div>
            Collections
          </td>
          <td>4935 CSPR</td>
          <td>11 CSPR</td>
          <td style="text-align: right">675</td>
          <td style="text-align: right">1862</td>
        </tr>
      </table>
    </div>
  </section>
</template>

<script>
export default {
  name: "Collections",
  data() {
    return {};
  },
};
</script>

<style scoped>
section {
  width: 100%;
  height: auto;
  text-align: left;
  padding: 2.5rem 1.875rem;
}
.feat {
  float: left;
  line-height: 5px;
}
.feat h2 {
  font-size: 35px;
}
select {
  width: 11.25rem;
  height: 2.4rem;
  float: right;
  margin-top: 1.25rem;
  border: 2px solid #2607fd;
  clip-path: polygon(
    6% 0,
    94% 0,
    100% 20%,
    100% 80%,
    94% 100%,
    6% 100%,
    0 80%,
    0 20%
  );
  background: #000000;
  color: white;
  text-indent: 10px;
}
.blossom {
  width: 100%;
  height: auto;
  margin: 8.75rem auto;
  padding: 0.3125rem;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  flex-wrap: wrap;
}
.card {
  width: 14.375rem;
  height: 17.25rem;
  position: relative;
  top: 0px;
  transition: 0.4s;
}
.card:hover {
  top: 10px;
  cursor: pointer;
}
.card-image {
  width: 100%;
  height: 11rem;
}
.image-card {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.details {
  width: 100%;
  height: 6.25rem;
  padding-left: 0.3125rem;
  line-height: 4px;
}
.price {
  width: 100%;
  height: 3.125rem;
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  justify-content: space-between;
}
.p {
  width: 80px;
  height: 48px;
  line-height: 0px;
}
.p .cspr {
  font-size: 12px;
}
.com {
  width: 150px;
  height: 48px;
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
}
.comm {
  width: 50%;
  height: 45px;
  padding: 4px 0px;
  text-align: center;
}
.table {
  width: 100%;
  height: 380px;
  margin: 16.875rem auto 1rem;
  overflow: auto;
}
table {
  width: 100%;
  height: auto;
}
th {
  padding: 0.95rem 0px;
}
td {
  padding: 0.4375rem 0px;
}
.eee {
  line-height: 28px;
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
}
table,
th,
td {
  border-collapse: collapse;
}
.draw {
  width: 30px;
  height: 30px;
  border-radius: 50%;
  margin-right: 10px;
}
.draw-image {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

@media screen and (max-width: 500px) {
  section {
    padding: 2rem 1.5rem;
  }
  .feat h2 {
    font-size: 28px;
  }
  select {
    width: 3rem;
    clip-path: polygon(
      13% 0,
      87% 0,
      100% 20%,
      100% 80%,
      87% 100%,
      13% 100%,
      0 80%,
      0 20%
    );
  }
  .blossom {
    width: 100%;
    height: auto;
    flex-wrap: nowrap;
    overflow: auto;
  }
}
</style>