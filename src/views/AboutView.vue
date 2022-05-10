<script setup>
import Navbar from "../components/Navbar.vue";

</script>

<template>
  <navbar />
  <div class="accordion accordion-flush bg-light mt-5" id="accordionFlushExample">
    <div class="accordion-item bg-light">
      <h2 class="accordion-header" id="flush-headingOne">
        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
          Contact
        </button>
      </h2>
      <div id="flush-collapseOne" class="accordion-collapse collapse" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
        <div class="accordion-body">ig: ranaaa_ftka | fb: Rana Fatrika | twitter: Rana Fatrika | Call me: 081268223669</div>
      </div>
    </div>
  </div>

  <section class="semua" style="background-color: #E1BA9D;">
    <section class="page-section" id="team">
      <div class="container">
        <div class="text-center">
          <h2 class="section-heading text-uppercase">CONTACT</h2>
          <h3 class="section-subheading">If you want to contact me, just let me know.</h3>
        </div>
        <div class="row">
          <div class="col-lg-4">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="/src/assets/1.jpg" alt="..." />
              <h4 class="media"><a target="_blank" href="https://wa.me/6283800945787">
                Whatsapp
              </a></h4>
              <p class="tl">083800945787</p>
              <a class="btn btn-social mx-2"><p class="p1"><a target="_blank" href="https://wa.me/6283800945787">
                Whatsapp
              </a></p></a>
            </div>
          </div>
          <div class="col-lg-4">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="/src/assets/alq2.png" alt="..." />
              <h4 class="media">Email</h4>
              <p class="tl">dwityamaudy@gmail.com</p>
              <a class="btn btn-social mx-2" style="background-image: url('src/assets/alq4.jpg');" href="mailto:dwityamaudy@gmail.com"></a>
            </div>
          </div>
          <div class="col-lg-4">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="/src/assets/3.png" alt="..." />
              <h4 class="media">Instagram</h4>
              <p class="tl">@bentocake.athere</p>
              <a class="btn btn-social mx-2" style="background-image: url('src/assets/alq2.png');" href="https://www.instagram.com/bentocake.athere/?igshid=YmMyMTA2M2Y="></a>
            </div>
          </div>
        </div>
      </div>
    </section>
  </section>
</template>

<script>
import { onMounted } from "vue";

onMounted(() => {
  document.getElementsByTagName("body")[0].style.backgroundColor = "#E1BA9D";
  document.getElementsByTagName("body")[0].style.backgroundSize ="cover";
});

</script>

<style scoped>
.team-member {
  margin-bottom: 3rem;
  text-align: center;
}
.team-member img {
  width: 14rem;
  height: 14rem;
  border: 0.5rem solid rgba(0, 0, 0, 0.1);
}
.team-member h4, .team-member .h4 {
  margin-top: 1.5rem;
  margin-bottom: 0;
}

.page-section {
  background-size: cover;
  background-repeat: no-repeat;
}

.section-heading {
  padding-top: 50px;
  font-family: "Segoe UI";
  font-weight: bold;
  font-size: 40px;
  color: white;
}
.section-subheading {
  font-family: "Segoe UI";
  font-size: 25px;
  color: #DB825B;
  padding-bottom: 40px;
}
.tl {
  font-family: "Segoe UI";
  font-size: 18px;
  color: #DB825B;
}
.media{
  font-family: "Segoe UI";
  font-size: 25px;
  color: white;
}
.btn-social {
  height: 2.5rem;
  width: 2.5rem;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0;
  background-size: contain;
  background-repeat: no-repeat;
}
</style>


<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
.tentang{
  background: #87cefa;
}
.accordion-button{
  text-align: center;
}
.accordion-body{
  margin-top: 20px;
  text-align: center;
  color: blue;
}
</style>
