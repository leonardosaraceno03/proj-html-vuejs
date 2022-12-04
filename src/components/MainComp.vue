<template>
  <main>
    <section>
      <div class="container">
        <div><h2>OUR CONSULTANT CAN HELP YOU</h2></div>
        <div class="green-line-main"></div>
      </div>
    </section>
    <section>
      <div class="card-container">
        <CardCompMain
          v-for="(elem, index) in consultantArray"
          :key="index"
          :card="elem"
        />
      </div>
    </section>
    <!-- BLUE BACKGROUND -->
    <section class="bg-blue">
      <!-- ABOUT US -->
      <div class="container-about-us">
        <div>
          <img
            src="../assets/img/business-people-working-together-on-project-and-5FHSKBL.jpg"
            alt=""
          />
        </div>
        <div>
          <div class="container-line">
            <div class="green-line-us"></div>
            <div>ABOUT US</div>
          </div>
          <div>
            <h1 class="strategy">WE MAKE YOUR STRATEGY WORK</h1>
            <p class="lorem-white">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Asperiores porro sunt deleniti corporis suscipit tempore dolore
              soluta molestiae maiores maxime. Dolor perferendis eligendi rerum
              quisquam possimus dolorem cum laborum iure!
            </p>
          </div>
        </div>
      </div>
      <div class="light-blue-bg">
        <div class="container-help">
          <div class="help"><h2>WE HELP TO DELIVER THE BUSINESS CASE</h2></div>
          <div class="lorem-help">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam ratione
            iure rem optio delectus fuga, incidunt, labore adipisci blanditiis
            reiciendis eligendi impedit, quos voluptatibus in sint doloremque
            quia ut iusto?
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
import CardCompMain from "../components/CardCompMain.vue";
export default {
  components: {
    CardCompMain,
  },
  data() {
    return {
      consultantArray: [
        {
          image: "../assets/img/chart-simple-solid.svg",
          title: "STATISTICAL CONSULTING",
          p: "lorem ipsum lorem ipsum lorem ipsumlorem ipsumlorem ipsum lorem ipsumlorem ipsum lorem ipsum",
        },
        {
          image: "../assets/img/volume-high-solid.svg",
          title: "DIGITAL CONSULTING",
          p: "lorem ipsum lorem ipsum lorem ipsumlorem ipsumlorem ipsum lorem ipsumlorem ipsum lorem ipsum",
        },
        {
          image: "../assets/img/wallet-solid.svg",
          title: "BANKING CONSULTING",
          p: "lorem ipsum lorem ipsum lorem ipsumlorem ipsumlorem ipsum lorem ipsumlorem ipsum lorem ipsum",
        },
        {
          image: "../assets/img/bullseye-solid.svg",
          title: "ENTERPRISE CONSULTING",
          p: "lorem ipsum lorem ipsum lorem ipsumlorem ipsumlorem ipsum lorem ipsumlorem ipsum lorem ipsum",
        },
      ],
    };
  },
};
</script>

<style>
.bg-blue {
  background: #1f1e38;
}
main {
  height: 100vh;
}
h2 {
  font-size: 1.8rem;
}
.container {
  display: flex;
  justify-content: end;
  padding-top: 120px;
  position: relative;
}
.green-line-main {
  width: 55%;
  height: 1px;
  align-self: flex-end;
  border: 2px solid #39ffbf;
  margin-left: 50px;
  align-self: center;
}
.card-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  width: 60%;
  margin: 0 auto;
  height: 100vh;
}
.container-about-us {
  display: flex;
}

.green-line-us {
  color: #39ffbf;
  width: 50px;
  border: 2px solid;
  height: 2px;
  margin-top: 10px;
}
.container-line {
  display: flex;
  position: relative;
  gap: 20px;
  color: white;
  margin-top: 250px;
  margin-left: 80px;
}
.strategy {
  color: white;
  width: 710px;
  font-size: 3.5rem;
  margin-left: 80px;
}
.lorem-white {
  color: white;
  margin-left: 80px;
}
.light-blue-bg {
  background-color: #35ffbf;
  width: 90%;
  height: 250px;
  display: flex;
  align-items: center;
  justify-content: space-around;
  
}
.help {
  color: #1f1e38;
  width: 320px;
}
.lorem-help{
  color: #1f1e38;
  width: 400px;
}
.container-help{
  display: flex;
  justify-content: space-around;
  gap: 200px;
}
</style>