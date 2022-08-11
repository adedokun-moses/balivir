<template>
  <nav>
    <div class="top_nav">
      <div>
        <select>
          <option>Sell On Divir</option>
        </select>
        |
      </div>
      <div>
        <select>
          <option>Nigerian</option>
        </select>
        |
      </div>

      <div>
        <i class="fa fa-user" style="margin-left: 3px"></i>
        <select>
          <option>Account</option>
        </select>
      </div>
    </div>
    <div class="bottom_nav">
      <div style="flex-basis: 10%">
        <h5><i class="fa fa-bars"></i> Divavir</h5>
      </div>

      <div class="nav_search" style="flex-basis: 70%">
        <i class="fa fa-search" style="margin-right: 7px"></i>
        <input type="text" placeholder="Find products you love" />
      </div>
       <div style="flex-basis: 10%">
        <h3><i class="fa fa-shopping-cart fa-2x" style="margin-right: 5px; "></i> Add to Wishlist</h3>
      </div>

      <div style="flex-basis: 10%">
        <h3><i class="fa fa-bars fa-2x" style="margin-right: 5px; "></i> Add to Wishlist</h3>
      </div>
    </div>
  </nav>
</template>


<style scoped>
nav {
  display: flex;
  flex-direction: column;
}

.top_nav {
  display: flex;
  justify-content: right;
  padding: 10px;
}
.top_nav select {
  padding: 10px 5px;
  border: none;
  background: white;

  font-size: 15px;
}

.top_nav option {
  padding: 10px;
  border: none;
  background: white;
  color: red;
}
.bottom_nav {
  display: flex;
  margin: 0px;
  padding: 10px;
  border-bottom: 2px solid #898585;
}
.bottom_nav > div {
  margin: 0px;
  padding: 0px;
  width: 100%;
}

.bottom_nav h5 {
  margin: 0px;
  font-size: 30px;
}
.nav_search input {

  padding: 20px 40px;
  margin-top: -10px;
  border: 1px solid rgba(13, 19, 23, 0.2);
  border-radius: 20px;
  outline: none;
  width: 85%;
}

.nav_search i{
     padding: 10px 0px;
     position: relative;
     left: 40px;
  
}
     
.bottom_nav h3 {
  margin: 7px 0px;
  font-size: 13px;
  padding: 0px 0px;
}


/* .nav_search input {
  width: 80%;
  border: 1px solid rgba(13, 19, 23, 0.2);
  border-radius: 20px;
  outline: none;
  padding: 10px;
} */

</style>