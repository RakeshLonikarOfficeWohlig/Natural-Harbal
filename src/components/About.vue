<template>
  <div>
    <navbar-header></navbar-header>
    <div>
      <div class="jumbotron">
        <div class="container-header">
          <h6 class="con-title">Duis hendrerit dolor</h6>
          <h1 class="con-header">
            Etiam accumsan eget Vestibulum<br />
            ligula nunc vulputate
          </h1>
          <button type="button" class="button-tp1">Contact us</button>
        </div>
      </div>
      <div class="di-img">
        <img class=" " src="../assets/home_herbal_pic3.png" alt="First slide" />
      </div>
    </div>
    <!-- Page 1 Completed -->
    <div>
      <h1 class="con1-header">
        Praesent wisi vel diam. Aliquam nisl. Nulla semper.<br />
        Morbi aliquam eros mauris, rutrum magna vitae<br />
        fermentum nec. Donec vitae velit.
      </h1>

      <div class="maindiv">
        <div class="firstdiv">
          <p class="bottom-para">
            Cras mauris non nunc. Donec tortor justo nec felis sollicitudin a,
            sollicitudin ligula non arcu. Sed congue, lacus et nisl. Morbi
            eleifend pede lacinia neque. Class aptent taciti sociosqu ad litora
            torquent per conubia nostra, per inceptos hymenaeos. Aenean
            scelerisque a, ultricies porta scelerisque, wisi eget elit.
            Phasellus tempor varius, quam et ultrices sit amet dignissim a,
            blandit lectus. Ut sodales tempor. Suspendisse dolor sit amet
            tellus. Integer id mi. Pellentesque mollis aliquam, purus et magnis
            dis parturient montes, nascetur ridiculus mus.
          </p>
        </div>
        <div class="seconddiv">
          <p class="bottom-para">
            Vestibulum fermentum. Aliquam erat ac lacus. Nunc placerat quis,
            odio. Suspendisse eu ligula ut tellus enim, ac hendrerit sagittis.
            Aliquam tellus pharetra porttitor a, faucibus eu, pulvinar augue.
            Nam tempor magna. Fusce nonummy gravida. Suspendisse vitae lacinia
            dictum. Curabitur sit amet dolor. Pellentesque eget enim. Donec
            vitae turpis. Etiam tincidunt in, gravida pulvinar interdum, lacus.
            Integer nonummy faucibus condimentum urna placerat. Duis aliquam,
            nulla massa, feugiat in, odio. Class aptent taciti sociosqu ad
            litora torquent per conubia nostra, per inceptos hymenaeos. Fusce
            porttitor, quam in sollicitudin arcu. Mauris mattis eget, rutrum id,
            vehicula sapien mauris sit amet, tortor.
          </p>
        </div>
        <div class="thirddiv">
          <p class="bottom-para">
            Donec ullamcorper, risus vel diam. Aliquam erat volutpat. Praesent
            rutrum. In hac habitasse platea dictumst. Aenean nonummy sed, neque.
            Sed lobortis mauris viverra semper orci, gravida sit amet, sodales
            nulla mi, eu libero. Cras tempus euismod. Nulla in dolor nonummy
            rutrum. Donec non felis. Mauris imperdiet, risus commodo ligula sit
            amet felis vitae metus eu scelerisque odio consequat sapien sed
            libero. In hac habitasse platea dictumst. Nulla mi facilisis
            dignissim faucibus, nulla ipsum primis in quam. Vestibulum nibh
            lacus, faucibus lorem, malesuada fames ac ante eu eros.
          </p>
        </div>
      </div>
    </div>
    <!-- Page 2 completed -->
    <div>
      <div class="d-img">
        <img
          class=" "
          src="../assets/home_herbal_about1.jpg"
          alt="First slide"
        />
      </div>
    </div>
    <!-- Navigation -->
    <div class="navbar1">
      <ul class="nav justify-content-center">
        <li class="nav-item ">
          <a class="nav-link active" style="color: black" href="#"
            ><b>Etiam blandit</b></a
          >
        </li>
        <li class="nav-item">
          <a class="nav-link" style="color: black" href="#"
            ><b>Phasellus ornare</b></a
          >
        </li>
        <li class="nav-item">
          <a class="nav-link" style="color: black" href="#"
            ><b>Cras egestas</b></a
          >
        </li>
      </ul>
    </div>
    <Footer />
  </div>
</template>

<script>
import NavbarHeader from "../components/NavbarHeader.vue";
import Footer from "../components/Footer.vue";
export default {
  name: "About",
  components: {
    NavbarHeader,
    Footer,
  },
};
</script>

<style>
.container-header {
  height: 400px;
}
.di-img {
  margin-top: -160px;
}
.con-title {
  color: #6b7a6b; /* #6B7A6B */
  margin-top: 70px;
  font-family: Lato, Helvetica, sans-serif;
  letter-spacing: 4px;
  font-size: 17px;
}
.con-header {
  font-size: 53px;
  font-family: Caudex;
  letter-spacing: 2px;
  color: #1c4e2a;
}
.button-tp1 {
  margin-top: 30px;
  height: 45px;
  width: 160px;
  border: none;
  color: #1c4e2a;
}
.con1-header {
  font-size: 35px;
  margin-top: 100px;
  font-family: Caudex;
  letter-spacing: 2px;
  color: #1c4e2a;
}
.navbar1 {
  margin-top: 100px;
}
</style>
