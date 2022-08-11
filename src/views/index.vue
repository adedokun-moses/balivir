<template>
  <Nav />
  <div class="container">
    <img src="../assets/img.png" alt="image" />
  </div>
  <div class="topcategories">
    <h5>Top Categories</h5>

    <div class="produc" v-for="prod in product" :key="prod.name">
      <div class="single">
        <img :src="prod.image" />
        <h4>{{ prod.name }}</h4>
      </div>
    </div>
  </div>
  <div class="gadgegt">
    <h5>All about gadgets</h5>
    <div class="gadget_prd">
      <div class="main_prod">
        <img src="../assets/new.png" style="width: 100%" />
        <button>View More Product</button>
      </div>
      <div class="single_prod">
        <div>
          <img src="../assets/leg7.png" />
        </div>
        <div>
          <img src="../assets/leg7.png" />
        </div>
        <div>
          <img src="../assets/leg7.png" />
        </div>
        <div>
          <img src="../assets/leg7.png" />
        </div>
      </div>
    </div>
  </div>

  <div class="phone">
    <h5>Our Special Deals Right Now</h5>

    <div class="produc" v-for="prod in product" :key="prod.name">
      <div class="single_deals">
        <img :src="prod.image" />
      </div>
    </div>
  </div>

  <div class="suoerdeals">
    <img src="../assets/super.png" alt="" />
    <button>Check It Out Now</button>
    <!-- 
      <img src="../assets/super1.png" />
            <img src="../assets/super2.png"  class="img_deals"/>
    <div class="deals" style="flex-basis: 60%">
      <h5>SuperDeals Avaolable</h5>
      <button>Check It Now</button>
    </div> -->
  </div>

  <div class="discount_deals">
    <h5>Discount Deals</h5>
    <div class="produc" v-for="prod in product" :key="prod.name">
      <div class="single_">
        <img :src="prod.image" />
        <div class="single_det">
          <div>
            <h4>{{ prod.name }}</h4>
            <h3>{{ prod.amount }}</h3>
          </div>
          <div style="float: right">
            <h3>{{ prod.mainamount }}</h3>
            <h3 style="color: red">{{ prod.discount }}</h3>
          </div>
        </div>
      </div>
    </div>

    <h5>Amazing Offers</h5>

    <div class="produc" v-for="prod in product" :key="prod.name">
      <div class="single_">
        <img :src="prod.image" />
        <div class="single_det">
          <div>
            <h4>{{ prod.name }}</h4>
            <h3>{{ prod.amount }}</h3>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="makeup">
      <h5>All about Make-Up</h5>
    <div class="produc" v-for="prod in product" :key="prod.name">
      <div class="single_makeup">
        <img :src="prod.image" />
     <!--    <h4>{{ prod.name }}</h4> -->
      </div>
    </div>
  </div>

  <div class="seemore">
    <h5>More To See</h5>

    <div class="produc" v-for="prod in product" :key="prod.name">
      <div class="single_">
        <img :src="prod.image" />
        <div class="single_det">
          <div>
            <h4>{{ prod.name }}</h4>
            <h3>{{ prod.amount }}</h3>
          </div>
        </div>
      </div>
    </div>
    <div class="loadmore">
      <button>View More</button>
    </div>
  </div>

   <Footer/>
</template>


<script> 
import Nav from "../components/nav.vue";
import Footer from "../components/footer.vue";
import products from "/product.json";
export default {
  components: { Nav, Footer},

  data() {
    return {
      product: products,
    };
  },
};
</script>

<style scoped>
@import "../../public/cssfolder/home.css"
</style>