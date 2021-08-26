<template>
  <div>
    <navbar-header></navbar-header>
    <div class="jumbotron">
      <div class="container">
        <h1 class="display-4">Contact us</h1>
      </div>
    </div>
    <div class="dissimg">
      <img class=" " src="../assets/home_herbal_pic5.png" alt="First slide" />
    </div>
    <!--Header End-->
    <div class="main-1">
      <div>
        <img
          src="../assets/home_herbal_logo_small.png"
          class="card-img-main"
          alt="..."
        />
        <h1 class="main1-header">Herbal</h1>
        <h5 class="main1-title">Original natural herbs</h5>
        <p class="main1-para">
          Suspendisse justo euismod venenatis convallis<br />
          aliquam blandit tempus vitage pede.<br /><br />
          <b
            >Level 13,2 Elizabeth St,<br />
            Melbourne, Victoria 3000<br />
            Australia.
          </b>
        </p>
      </div>
      <!-- first div end -->
      <div>
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3151.797748414627!2d144.96211051531895!3d-37.818206079751405!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6ad642b384a66f05%3A0x184e7067954ebf3b!2s13%2F2%20Elizabeth%20St%2C%20Melbourne%20VIC%203000%2C%20Australia!5e0!3m2!1sen!2sin!4v1629974748391!5m2!1sen!2sin"
          class="map"
          allowfullscreen=""
          loading="lazy"
        ></iframe>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
import NavbarHeader from "../components/NavbarHeader.vue";
import Footer from "../components/Footer.vue";
export default {
  name: "Faq",
  components: {
    NavbarHeader,
    Footer,
  },
};
</script>

<style>
.main-1 {
  margin-top: 60px;
  display: flex;
}
.card-img-main {
  width: 12%;
  margin: 60px 350px 20px;
}
.main1-header {
  font-family: Caudex;
  font-size: 50px;
  letter-spacing: 2px;
  margin-top: -10px;
  margin-left: 4px;
  color: #1c4e2a;
}
.main1-title {
  color: #6b7a6b; /* #6B7A6B */
  font-family: Lato, Helvetica, sans-serif;
  letter-spacing: 4px;
  font-size: 18px;
  margin-top: 20px;
  margin-left: 4px;
}
.main1-para {
  color: #6b7a6b; /* #6B7A6B */
  font-family: Lato, Helvetica, sans-serif;
  /* letter-spacing:4px; */
  font-size: 14px;
  margin-top: 40px;
  margin-bottom: 100px;
  margin-left: 4px;
}
.map {
  /* width="600"
          height="350" */
  width: 700px;
  margin-left: -200px;
  margin-bottom: 150px;
  height: 400px;
  border: 0;
}
</style>
