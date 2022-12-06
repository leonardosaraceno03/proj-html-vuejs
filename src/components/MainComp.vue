<template>
  <div>
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
      <!-- LIGHT BLUE BACKGROUND -->
      <div class="light-blue-bg">
        <div class="container-help">
          <div class="help"><h2>WE HELP TO DELIVER THE BUSINESS CASE</h2></div>
          <div class="lorem-help">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam ratione
            iure rem optio delectus fuga, incidunt, labore adipisci blanditiis
            reiciendis eligendi impedit, quos voluptatibus in sint doloremque
            quia ut iusto?
            <div class="get-started">GET STARTED</div>
          </div>
        </div>
      </div>
      <!-- PROJECT -->
      <div class="project-container">
        <div class="container-line-project">
          <div class="green-line-us"></div>
          <div>PROJECT</div>
        </div>
        <div class="title-arrow">
          <h2 class="project-title">
          OUR EXPERT TRUSTED CONSULTANTS HELP CLIENTS
        </h2>
        <div class="white arrow-container">
          <div><font-awesome-icon icon="fa-solid fa-arrow-left" /></div>
          <div><font-awesome-icon icon="fa-solid fa-arrow-right" /></div>
        </div>
        </div>
        
        <div class="container-img-project">
          <div><img src="../assets/img/DRY-1-790x592.jpg" alt="" /></div>
          <div>
            <img
              src="../assets/img/221bf0b7-8134-43bb-936a-5acbe42db64a-790x592.jpg"
              alt=""
            />
          </div>
          <div><img src="../assets/img/z1el4c4p-790x592.jpg" alt="" /></div>
        </div>
      </div>
      <!-- TESTIMONIAL -->
      <div class="testimonial-container">
        <div class="d-flex">
          <div></div>
          <span class="white">TESTIMONIAL</span>
          <div class="green-line"></div>
        </div>
        <h2 class="white h2-customer">
          WHAT'S THE CUSTOMER SAY <br />
          ABOUT OUR WORK
        </h2>
      </div>
      <!-- WHITE SECTION -->
      <div class="white-bg-container">
        <div class="white-bg">
          <div>
            <p>
              Lorem, ipsum dolor sit amet consectetur adipisicing elit.
              Dignissimos, perferendis ut atque numquam rerum quod temporibus
              aliquid natus molestiae excepturi ea ullam! Optio est aut ipsa
              enim iure, nobis ducimus!
            </p>
            <h3>Vera Duncan</h3>
            <span>Amazon Inc.</span>
          </div>
          <div>
            <p>
              Lorem, ipsum dolor sit amet consectetur adipisicing elit.
              Dignissimos, perferendis ut atque numquam rerum quod temporibus
              aliquid natus molestiae excepturi ea ullam! Optio est aut ipsa
              enim iure, nobis ducimus!
            </p>
            <h3>Vera Duncan</h3>
            <span>Amazon Inc.</span>
          </div>
          <div>
            <p>
              Lorem, ipsum dolor sit amet consectetur adipisicing elit.
              Dignissimos, perferendis ut atque numquam rerum quod temporibus
              aliquid natus molestiae excepturi ea ullam! Optio est aut ipsa
              enim iure, nobis ducimus!
            </p>
            <h3>Vera Duncan</h3>
            <span>Amazon Inc.</span>
          </div>
        </div>
      </div>
      <!-- BLOG -->
      <div class="blog-container">
        <div>
          <div class="container-line-blog">
            <div class="green-line-us"></div>
            <div>BLOG</div>
          </div>
        </div>
        <div class="news-container">
          <h2>THE RECENT NEWS YOU MUST READ IT</h2>
          <div class="read-more">VIEW ALL</div>
        </div>
        <div class="img-blog-container">
          <div class="img-blog-div">
            <img
              class="img-blog"
              src="../assets/img/startup-business-people-and-strategy-board-PAJ3P9K-1390x1042.jpg"
              alt=""
            />
            <div class="lorem-blog">
              <div class="span-container">
                <span>july 4, 2019</span>
                <span>by Paul</span>
              </div>
              <h4>Canadian Consulting Firm acquired by UK Giant</h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Porro
                ut quam, iure id sapiente neque temporibus nemo similique totam
                illo obcaecati ipsum praesentium odit natus optio sequi veniam
                impedit error.
              </p>
            </div>
          </div>
          <div class="img-blog-div">
            <img
              class="img-blog"
              src="../assets/img/business-people-working-together-on-project-and-5FHSKBL-1390.jpg"
              alt=""
            />
            <div class="lorem-blog">
              <div class="span-container">
                <span>july 4, 2019</span>
                <span>by Paul</span>
              </div>
              <h4>Canadian Consulting Firm acquired by UK Giant</h4>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Porro
                ut quam, iure id sapiente neque temporibus nemo similique totam
                illo obcaecati ipsum praesentium odit natus optio sequi veniam
                impedit error.
              </p>
            </div>
          </div>
        </div>
      </div>
      <!-- LET'S TALK ABOUT WORK -->
      <div class="about-work-container">
       <div>
        <h2>LET'S TALK ABOUT WORK</h2>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nesciunt
          architecto saepe quia ipsam? 
        </p>
        <div class="read-more">GET STARTED</div>
       </div>
       
      </div>
    </section>
  </div>
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
          image: "chart-simple-solid.svg",
          title: "STATISTICAL CONSULTING",
          p: "lorem ipsum lorem ipsum lorem ipsumlorem ipsumlorem ipsum lorem ipsumlorem ipsum lorem ipsum",
        },
        {
          image: "volume-high-solid.svg",
          title: "DIGITAL CONSULTING",
          p: "lorem ipsum lorem ipsum lorem ipsumlorem ipsumlorem ipsum lorem ipsumlorem ipsum lorem ipsum",
        },
        {
          image: "wallet-solid.svg",
          title: "BANKING CONSULTING",
          p: "lorem ipsum lorem ipsum lorem ipsumlorem ipsumlorem ipsum lorem ipsumlorem ipsum lorem ipsum",
        },
        {
          image: "bullseye-solid.svg",
          title: "ENTERPRISE CONSULTING",
          p: "lorem ipsum lorem ipsum lorem ipsumlorem ipsumlorem ipsum lorem ipsumlorem ipsum lorem ipsum",
        },
      ],
    };
  },
};
</script>

<style>
.title-arrow{
  display: flex;
  justify-content: space-between;
}
.arrow-container{
  display: flex;
  gap: 10px;
}
.arrow-container>div{
  background: rgba(255, 255, 255, .2) ;
  padding: 30px;
  font-size: 1.5rem;
  height: 90px;
}
.get-started:hover{
  background: white;
  color: red;
  border: 1px solid red;
}
.arrow-container>div:hover{
  color: #35ffbf;
  background: white;
}
.about-work-container > div > div{
  background-color: #1f1e38;
  color: white;
  margin: 0 auto;
}
.about-work-container > div{
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  height: 50%;
  margin: 0 auto;
 
}
.about-work-container >div> p {
  color: white;
  text-align: center;
  margin: 0 auto;
}

.about-work-container >div> h2 {
  color: white;
  
  font-size: 2.5rem;
}
.about-work-container {
  background-image: url("../assets/img/business-people-working-together-on-project-and-B3MZ4TX.jpg");
  height: 450px;
  margin-top: 300px;
  display: flex;
  align-items: center;
  
  
}
.lorem-blog > p {
  color: gray;
  padding: 20px 0px;
}
.span-container {
  color: red;
  display: flex;
  gap: 20px;
  margin: 10px 0px;
}
.lorem-blog > h4 {
  font-size: 1.8rem;
  width: 70%;
}
.lorem-blog {
  color: black;
  background: white;
  position: absolute;
  bottom: -90px;
  right: 0;
  width: 70%;
  padding: 30px 50px;
}
.img-blog-container {
  display: flex;
  justify-content: space-between;
  margin-top: 50px;
}
.img-blog-div {
  width: 48%;
  position: relative;
}
.img-blog {
  width: 100%;
}
.news-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.news-container > h2 {
  color: white;
  font-size: 2.25rem;
}
.blog-container {
  width: 90%;
  margin: 0 auto;
}
.container-line-blog {
  display: flex;
  position: relative;
  gap: 20px;
  color: white;
  margin-top: 250px;
}
.white-bg-container {
  display: flex;
  justify-content: flex-end;
}
.white-bg {
  background: white;
  width: 95%;
  padding: 50px;
  color: gray;
  display: flex;
  justify-content: space-between;
}
.white-bg > div > p {
  padding-bottom: 50px;
}
.white-bg > div > h3 {
  color: black;
}
.h2-customer {
  text-align: end;
  font-size: 3rem;
  margin-top: 100px;
}

.testimonial-container {
  width: 90%;
  margin: 0 auto;
  margin-top: 100px;
}
.testimonial-container :nth-child(1) {
  display: flex;
  justify-content: space-between;
}
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
  position: relative;
}
.help {
  color: #1f1e38;
  width: 320px;
}
.lorem-help {
  color: #1f1e38;
  width: 400px;
}
.container-help {
  display: flex;
  justify-content: space-around;
  gap: 200px;
}
.get-started {
  position: absolute;
  right: 0;
  bottom: 0;
  background: red;
  color: white;
  padding: 20px 50px;
}
.project-title {
  color: white;
  font-size: 3rem;
  width: 55%;
  margin: 30px 0px;
}
.project-container {
  width: 90%;
  margin: 0 auto;
}
.container-line-project {
  display: flex;
  position: relative;
  gap: 20px;
  color: white;
  margin-top: 250px;
}
.container-img-project {
  display: flex;
  justify-content: space-between;
}
.container-img-project > div > img {
  width: 500px;
}
</style>