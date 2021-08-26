<template>
  <div>
    <navbar-header></navbar-header>
    <div class="jumbotron">
      <div class="container">
        <h1 class="display-4">Shop</h1>
      </div>
    </div>
    <div>
      <div class="header2">
        <div class="h6">
          <p>Showing all 9 results</p>
        </div>
        <div class="drop">
          <div class="dropdown show">
            <a
              class="btn btn-default dropdown-toggle"
              href="#"
              role="button"
              id="dropdownMenuLink"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              Dropdown link
            </a>

            <div class="dropdown-menu" aria-labelledby="dropdownMenuLink">
              <a class="dropdown-item " href="#">Action</a>
              <a class="dropdown-item" href="#">Another action</a>
              <a class="dropdown-item" href="#">Something else here</a>
            </div>
          </div>
        </div>
      </div>

      <div class="cardbox1">
        <div
          class="cardsize1 row row-cols-1 row-cols-sm-2 row-cols-md-3 row-cols-lg-4 row-cols-lg-5"
        >
          <div class="col mb-4">
            <div class="card border-default hover- mb-3" style="">
              <div class="card-img">
                <img
                  src="../assets/home_herbal_product1-600x600.jpg"
                  class="card-img-top"
                  alt="..."
                />
              </div>

              <div class="card-body">
                <h5 class="card-title1">Sed frignill tempus</h5>
                <h6 class="card-amount">$ 9.00</h6>
              </div>
            </div>
          </div>
          <div class="col mb-4">
            <div class="card border-default hover- mb-3" style="">
              <div class="card-img">
                <img
                  src="../assets/home_herbal_product2-600x600.jpg"
                  class="card-img-top"
                  alt="..."
                />
              </div>

              <div class="card-body">
                <h5 class="card-title1">Aliquam tempus</h5>
                <h6 class="card-amount">$ 9.00</h6>
              </div>
            </div>
          </div>
          <div class="col mb-4">
            <div class="card border-default hover- mb-3" style="">
              <div class="card-img">
                <img
                  src="../assets/home_herbal_product3.jpg"
                  class="card-img-top"
                  alt="..."
                />
              </div>

              <div class="card-body">
                <h5 class="card-title1">Nullam imperdiet</h5>
                <h6 class="card-amount">$ 9.00</h6>
              </div>
            </div>
          </div>
        </div>
      </div>
      <Footer />
    </div>
  </div>
</template>

<script>
import NavbarHeader from "../components/NavbarHeader.vue";
import Footer from "../components/Footer.vue";
export default {
  name: "Shop",
  components: {
    NavbarHeader,
    Footer,
  },
};
</script>

<style>
.jumbotron {
  background-color: #d2d8d2;
}
.display-4 {
  font-family: Caudex;
  font-size: 60px;
  margin-top: 28px;
  margin-bottom: 28px;
  letter-spacing: 2px;
  color: #1c4e2a;
}

.card-title1 {
  color: #1c4e2a;
  font-family: Caudex;
  font-size: 25px;
  margin-left: -80px;
  margin-top: -20px;
}
.card-amount {
  color: #ff8c00;
  font-family: Caudex;
  font-size: 22px;
  margin-left: -200px;
}

/* ---------Cards---------- */
.cardbox1 {
  margin: 20px 0px 0px 200px;
  border: none;
  /* border-color: #c7b78f;
	border-radius: 0;
	border: red; */
}
.cardsize1 {
  width: 1100px;
}
.card-img {
  padding: 20px 20px 25px 20px;
}
.header2 {
  display: flex;
  justify-content: space-between;
}
.h6 {
  margin-top: 30px;
  margin-left: 200px;
  font-size: 15px;
  color: #6b7a6b;
}
.drop {
  margin-right: 200px;
}
</style>
