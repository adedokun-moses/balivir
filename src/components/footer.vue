<template>
  <footer>
    <div class="shopping">
      <div>
        <i class="fa fa-dollar"></i>
        <h5>Affordable Prices</h5>
      </div>
      <div>
        <i class="fa fa-dollar"></i>
        <h5>Worldwide Shopping</h5>
      </div>
      <div>
        <i class="fa fa-dollar"></i>
        <h5>Safe Payment</h5>
      </div>
      <div>
        <i class="fa fa-dollar"></i>
        <h5>Shop With Confidence</h5>
      </div>
      <div>
        <i class="fa fa-dollar"></i>
        <h5>Help Center</h5>
      </div>
    </div>

    <div class="contact">
      <div>
        <h5>Stay Connected With Us</h5>
        <i class="fa fa-facebook fa-2x"></i>
        <i class="fa fa-twitter fa-2x"></i>
        <i class="fa fa-messanger fa-2x"></i>
        <i class="fa fa-instagram fa-2x"></i>
        <i class="fa fa-whataspp fa-2x"></i>
      </div>

      <div>
        <h5>Shopping With Us</h5>
        <ul>
          <li>Making Payment</li>
          <li>Delivery Option</li>
          <li>Buyer Protection</li>
        </ul>
      </div>
      <div>
        <h5>Customer Care</h5>
        <ul>

          <li>Customer service</li>
          <li>Transaction Services Agreement</li>
          <li>Take our feedback survey</li>
        </ul>
      </div>

      <div>
        <h5>Collaborate With Us</h5>
        <ul>

          <li>Partnerships</li>
          <li>Affiliate program</li>
        
        </ul>
      </div>
    </div>
  </footer>
</template>




<style scoped>
footer {
  margin-top: 30px;
}

.shopping {
  display: flex;
}
.shopping > div {
  width: 100%;
  text-align: center;
  font-size: 25px;
}

.contact {
  display: flex;
  background: #0036c2;
}
.contact > div {
  width: 100%;
 margin: 20px 20px ;
  color: white;
}
.contact h5 {
  margin: 10px 0px;
  font-size: 25px;
}
.contact i{
  margin: 10px 10px;
}
.contact ul{
    list-style: none;
    margin: 0px;
    padding: 0px;
 
}
.contact li{
    padding: 10px 0px;
}
</style>