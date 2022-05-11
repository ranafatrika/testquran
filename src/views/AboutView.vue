<script setup>
import Navbar from "../components/Navbar.vue";

</script>

<template>
  <navbar />
  <div class="pesan text-center">Tinggalkan Pesan</div>
  <form action="forms/contact.php" method="post" role="form" class="php-email-form mt-4">
    <div class="row">
      <div class="col-md-6 form-group">
        <input type="text" name="name" class="form-control" id="name" placeholder="Your Name" required>
      </div>
      <div class="col-md-6 form-group mt-3 mt-md-0">
        <input type="email" class="form-control" name="email" id="email" placeholder="Your Email" required>
      </div>
    </div>
    <div class="form-group mt-3">
      <input type="text" class="form-control" name="subject" id="subject" placeholder="Subject" required>
    </div>
    <div class="form-group mt-3">
      <textarea class="form-control" name="message" rows="5" placeholder="Message" required></textarea>
    </div>
    <div class="my-3">
      <div class="loading text-center">Loading</div>
      <div class="error-message"></div>

        <button type="submit" class="btn btn-primary text-center">Kirim</button>

      <div class="sent-message text-center">Your message has been sent. Thank you!</div>
    </div>
  </form>
  <section class="semua" style="background-color:#87cefa;">
    <section class="page-section" id="team">
        <div class="row">
          <div class="col-lg-4">
            <div class="team-member">
              <h4 class="media"><a target="_blank" href="https://wa.me/6283800945787">
                Whatsapp
              </a></h4>
            </div>
          </div>
          <div class="col-lg-4">
            <div class="team-member">
              <h4 class="media"><a target="_blank" href="https://www.instagram.com/ranaaa_ftka">
                Instagram
              </a></h4>
            </div>
          </div>
          <div class="col-lg-4">
            <div class="team-member">
              <h4 class="media"><a target="_blank" href="https://www.facebook.com/profile.php?id=100075545091932">
                Facebook
              </a></h4>
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
.pesan{
  font-family: poppins;
  font-size: 25px;
}
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
