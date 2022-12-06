<template>
  <div>
    <!-- NAV -->
    <nav>
      <div>
        <!-- LEFT SIDE NAV -->
        <div><img id="logotype" src="../assets/img/logotype.png" alt="" /></div>
      <!-- RIGHT SIDE NAV -->
        <ul class="list">
          <SectionComp
            v-for="(elem, index) in sectionArray"
            :key="index"
            :sezione="elem"
            class="hover-list"
          />
        </ul>
      </div>
      <!-- TITLE SECTION -->
      <section class="jumbotron">
        <div>
        <div class="container-line-header">
          <div class="green-line"></div>
          <div>ALWAYS THE BEST WAY YOU NEED IT</div>
        </div>
        <h1>THE BEST <br> BUSINESS <br> CONSULTING</h1>
        <div>
          <div class="read-more">
            READ MORE
          </div>
        </div>
      </div>
      </section>
      
      
    </nav>
  </div>
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
.read-more:hover{
  background: white;
 color: #1f1e38;
}
.hover-list{
  height: 10px;
}
.hover-list :hover{
  border-top: 2px solid white;
  padding-top: 15px;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.container-line-header{
  display: flex;
  position: relative;
  gap: 20px;
  margin-top: 150px;
}
.container-line :nth-child(2){
  letter-spacing: .5rem;
}
nav {
  background-image: url("../assets/img/header phlox.jpg");
  background-size: cover;
  padding-top: 30px;
  height: 100vh;
}
nav > :nth-child(1){
  display: flex;
  justify-content: space-between;
  width: 90%;
  margin: 0 auto;
}
.list {
  display: flex;
  list-style: none;
  gap: 10px;
  color: white;
}

#logotype {
  width: 150px;
}
div > h1{
  
  font-size: 6rem;
  padding-top: 50px;
  padding-bottom: 50px;
}
.jumbotron{
  width: 90%;
  margin: 0 auto;
  color: white;
  
}

.read-more{
  background-color: #39ffbf;
  width: 200px;
  height: 70px;
  justify-content: space-around;
  display: flex;
  align-items: center;
  color: black;
}
.green-line{
  color: #39ffbf;
  background: #39ffbf;
  width: 50px;
  border: 2px solid;
  align-self: flex-end;
  
}
</style>
