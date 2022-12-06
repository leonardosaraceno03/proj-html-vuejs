<template>
  <footer class="bg-blue">
    <div class="footer-container">
      <div><img src="../assets/img/logotype-2-150x25.png" alt="" /></div>
      <div>
        <ul class="list">
          <SectionComp
            v-for="(elem, index) in sectionArray"
            :key="index"
            :sezione="elem"
          />
        </ul>
      </div>
      <div class="icon-container">
        <font-awesome-icon class="fa-brands" icon="fa-brands fa-instagram" />
        <font-awesome-icon class="fa-brands" icon="fa-brands fa-linkedin-in" />
        <font-awesome-icon class="fa-brands" icon="fa-brands fa-facebook-f" />
        <font-awesome-icon class="fa-brands" icon="fa-brands fa-twitter" />
      </div>
    </div>
    <div class="white terms">
      <div >
        <div>Terms of use</div>
        <div>Privacy Enviromental Policy</div>
      </div>
      <div>
        Copyright 2020 Phlox Consulting.All Rights Reserved.
      </div>
    </div>
  </footer>
</template>

<script>
import SectionComp from "../components/SectionComp.vue";
export default {
  components: {
    SectionComp,
  },
  data() {
    return {
      sectionArray: [
        { title: "HOME" },
        { title: "ABOUT" },
        { title: "PROJECTS" },
        { title: "SERVICES" },
        { title: "BLOG" },
        { title: "CONTACT" },
      ],
    };
  },
};
</script>

<style>
.terms{
  display: flex;
  justify-content: space-between;
  width: 90%;
  margin: 0 auto;
  padding-top: 50px;
  border-top: 1px solid white;
}
.fa-brands {
  color: white;
}
.icon-container {
  display: flex;
  gap: 20px;
}
.footer-container {
  display: flex;
  justify-content: space-between;
  width: 90%;
  margin: 0 auto;
  padding-top: 100px;
  padding-bottom: 50px;
}
</style>