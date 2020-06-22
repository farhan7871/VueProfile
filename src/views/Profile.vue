<template>
  <div class="profile">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-6">
          <div class="media text-left">
            <img src="../assets/1.jpg" class="user-pic mr-3" />
            <div class="media-body">
              <h5 class="mt-0">{{firstName}} {{ lastName}}</h5>
              {{bio}}
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";

export default {
  name: "profile",
  data: function() {
    return {
      firstName: "Muhammad",
      lastName: "Farhan",
      bio:
        "Saya adalah mahasiswa Informatika di Universitas Islam Indonesia tertarik dan menyukai dunia teknologi dan entrepreneurship"
    };
  },
  components: {}
};
</script>

<style scoped>
.user-pic {
  border-radius: 200%;
  height: 80px;
  width: 80px;
}
</style>