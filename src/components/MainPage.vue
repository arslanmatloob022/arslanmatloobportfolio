<template>
  <section>
    <div class="profile">
      <div class="text">
        <h1>Arslan Matloob</h1>
        <h3>Web Front-end Developer</h3>
        <p>
          I am a passionate and skilled frontend web developer with expertise in
          Vue.js, a powerful JavaScript framework that empowers seamless and
          responsive user interfaces. With a strong foundation in JavaScript,
          HTML, CSS, SCSS, and Bootstrap, I create visually appealing,
          intuitive, and highly functional web applications. My proficiency
          extends to MongoDB, enabling me to develop dynamic, data-driven
          websites and applications.
        </p>
      </div>
      <div class="media">
        <div class="image">
          <img src="@/assets/profilepic.png" alt="" srcset="" />
        </div>
      </div>
    </div>
    <div class="main">
      <div class="education borders divs row">
        <div class="siders">
          <i class="fa fa-book"></i>
        </div>
        <h1 class="col-lg-12 col-md-12 col-sm-12 col-12">Education</h1>
        <div class="graduation col-lg-4 col-md-4 col-sm-4 col-4">
          <h3>Graduation</h3>

          <h5>COMSATS University Islamabad</h5>
          <h6>From 2018 To 2022</h6>
          <h6>GPA: 2.98</h6>
        </div>
        <div class="graduation col-lg-4 col-md-4 col-sm-4 col-4">
          <h3>Intermadiate</h3>
          <h5>Imperial College Of Technology Lahore</h5>
          <h6>From 2015 To 2018</h6>
          <h6>Grade: A</h6>
        </div>
        <div class="graduation col-lg-4 col-md-4 col-sm-4 col-4">
          <h3>Matriculation</h3>
          <h5>Army Public School And College</h5>
          <h6>From 2008 To 2015</h6>
          <h6>Grade: A-</h6>
        </div>
      </div>

      <div class="skills borders divs row">
        <div class="siders">
          <i class="fa fa-cogs" aria-hidden="true"></i>
        </div>
        <h1 class="col-12">Skills</h1>
        <div class="graduation col-lg-6 col-md-6 col-sm-6 col-6">
          <h3>Technical Skills</h3>
          <h6><i class="fa fa-cube" aria-hidden="true"></i> Vue.Js</h6>
          <h6><i class="fa fa-cube" aria-hidden="true"></i> Mongodb</h6>
          <h6><i class="fa fa-cube" aria-hidden="true"></i> JavaScript</h6>
          <h6><i class="fa fa-cube" aria-hidden="true"></i> Bootstrap</h6>
          <h6><i class="fa fa-cube" aria-hidden="true"></i> HTML</h6>
          <h6><i class="fa fa-cube" aria-hidden="true"></i> CSS</h6>
        </div>
        <div class="graduation col-lg-6 col-md-6 col-sm-6 col-6">
          <h3>Non-Technical Skills</h3>
          <h6>
            <i class="fa fa-cube" aria-hidden="true"></i> Continous Learning
          </h6>
          <h6>
            <i class="fa fa-cube" aria-hidden="true"></i> Supportive for others
          </h6>
          <h6><i class="fa fa-cube" aria-hidden="true"></i> Team Player</h6>
          <h6><i class="fa fa-cube" aria-hidden="true"></i> Punctual</h6>
          <h6><i class="fa fa-cube" aria-hidden="true"></i> Hardworking</h6>
        </div>
      </div>

      <div class="skills borders divs row">
        <div class="siders">
          <i class="fa fa-id-badge" aria-hidden="true"></i>
        </div>
        <h1 class="col-12">Experiance</h1>
        <h3 class="col-12">Work Experiance</h3>
        <h6 class="col-12">
          <i class="fa fa-cube" aria-hidden="true"></i>
          Upto 1-Year experiance in fornt-end web development.
        </h6>
        <h6 class="col-12">
          <i class="fa fa-cube" aria-hidden="true"></i>
          Currently working on Fiverr with friends with a team of three members.
        </h6>
      </div>

      <div class="skills borders divs row">
        <div class="siders">
          <i class="fas fa-folder-open"></i>
        </div>
        <h1 class="col-lg-12 col-md-12 col-sm-12 col-12">Projects</h1>
        <div class="projects col-lg-12 col-md-12 col-sm-12 col-12">
          <div class="pro-main row">
            <div
              v-for="project in projects"
              :key="project.id"
              class="proj-card col-lg-3 col-md-3 col-sm-4 col-4"
            >
              <div class="images">
                <img :src="project.image" alt="" />
              </div>
              <div class="info">
                <h4>{{ project.name }}</h4>
                <p>{{ project.description }}</p>
              </div>
              <a :href="project.link" target="_blank" rel="noopener noreferrer">
                <button class="view-btn">View</button></a
              >
            </div>
          </div>
        </div>
      </div>

      <div class="education borders divs row">
        <div class="siders">
          <i class="fas fa-user-circle" aria-hidden="true"></i>
        </div>
        <h1 class="col-lg-12 col-md-12 col-sm-12 col-12">Social Accounts</h1>
        <div class="graduation col-lg-4 col-md-4 col-sm-4 col-4">
          <a
            href="https://github.com/arslanmatloob022"
            target="_blank"
            rel="noopener noreferrer"
            ><h5><i class="fab fa-github" aria-hidden="true"></i> Github</h5></a
          >
          <a
            href="https://linkedin.com/in/raoarslanmatloob"
            target="_blank"
            rel="noopener noreferrer"
            ><h5>
              <i class="fab fa-linkedin" aria-hidden="true"></i> LinkedIn
            </h5></a
          >
        </div>
        <div class="graduation col-lg-4 col-md-4 col-sm-4 col-4">
          <a
            href="https://www.facebook.com/arslan.raajput.1/"
            target="_blank"
            rel="noopener noreferrer"
            ><h5>
              <i class="fab fa-facebook" aria-hidden="true"></i> Facebook
            </h5></a
          >
          <a
            href="https://www.instagram.com/i_arslan_rao/"
            target="_blank"
            rel="noopener noreferrer"
            ><h5>
              <i class="fab fa-instagram" aria-hidden="true"></i> Instagram
            </h5></a
          >
          <a
            ><h5>
              <i class="fab fa-whatsapp" aria-hidden="true"></i> 03007626555
            </h5></a
          >
        </div>
        <div class="graduation col-lg-4 col-md-4 col-sm-4 col-4">
          <a
            href="mailto:raoarslanmatloob@gmail.com"
            target="_blank"
            rel="noopener noreferrer"
            ><h5><i class="fab fa-dropbox" aria-hidden="true"></i> Email</h5></a
          >
          <a href="callto:+923007626555"
            ><h5>
              <i class="fa fa-phone" aria-hidden="true"></i> 0300-7626-555
            </h5></a
          >
        </div>
      </div>

      <div class="education borders divs row">
        <div class="siders">
          <i class="fab fa-buysellads" aria-hidden="true"></i>
        </div>
        <fiverr-Badge-Vue></fiverr-Badge-Vue>
      </div>
    </div>
  </section>
</template>
<script>
import fiverrBadgeVue from "./fiverrBadge.vue";
export default {
  namae: "MainPage",
  components: {
    fiverrBadgeVue,
  },
  data() {
    return {
      projects: [
        {
          id: 1,
          image: require("@/assets/projectimgs/e1.png"),
          name: "E-Commerce",
          description:
            "This is frontend of an e-commerce website. This work done by me from scratch. A work of my project",
          link: "https://ecomwebbyarslanmatloob.netlify.app/",
        },
        {
          id: 2,
          image: require("@/assets/projectimgs/slack1.png"),
          name: "Slack (Clone)",
          description:
            "This is frontend of a well-known website named Slack. For best practice of front-end development.",
          link: "https://slackbyarslanmatloob.netlify.app/",
        },
        {
          id: 3,
          image: require("@/assets/projectimgs/t1.png"),
          name: "Tic Tac Toe Pro",
          description:
            "This is a small website complete game with new features and functions. A practice of Javascript.",
          link: "https://tictactoegamebyarslanmatloob.netlify.app/",
        },
        {
          id: 4,
          image: require("@/assets/projectimgs/w1.png"),
          name: "Web dazzels",
          description:
            "This is my own project and to be lounched officially soon. This is the master piece of my work.",
          link: "https://webdazzels.netlify.app/",
        },
        {
          id: 5,
          image: require("@/assets/projectimgs/a1.png"),
          name: "Bored App",
          description:
            "A small and intersting Application. To practice the API fetching process using fetch method(Js)",
          link: "https://boredandactive.netlify.app/#/",
        },
      ],
    };
  },
};
</script>
<style scoped>
* {
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}
.profile {
  background-color: #694966;
  margin: 0;
  padding: 3dvw 2dvw;
  display: flex;
  margin-bottom: 3dvh;
}

.profile .text {
  width: 60dvw;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.text h1 {
  font-size: 4.5dvw;
  color: #fce1e1;
}
.text h3 {
  font-size: 2.5dvw;
  color: #f8dada;
}
.text p {
  font-size: 1.2dvw;
  padding: 2dvw 4dvw;
  color: #ffeaea;
}
.profile .media {
  width: 40dvw;
}
.image {
  overflow: hidden;
  background-color: #74526c;
  border-radius: 220px 220px 0px 220px;
  box-shadow: 0 0 16px 4px #b09398;
  transition: all 0.3s ease-in-out;
}
.image:hover {
  cursor: pointer;
  transform: scale(1.01);
  box-shadow: 0 0 32px 8px #b09398;
}
.image img {
  width: 100%;
  transform: translateY(40px);
  transition: all 0.6s ease-in-out;
}
.image img:hover {
  transform: translateY(0px);
}
.main {
  background-color: #fdefef;
  padding-left: 30px;
}
.divs {
  width: 100%;
  background-color: #fdefef;
  margin: 0;
  padding: 3dvw 2dvw;
}
.margin {
  margin-bottom: 30px;
}
.borders {
  position: relative;
  border-left: 3px solid #74526c;
  border-bottom: 2px solid #74526c;
}
.siders {
  border-radius: 50%;
  top: 44px;
  left: -1.4dvw;
  height: 2.6dvw;
  width: 2.6dvw;
  padding: 2px 6px;
  position: absolute;
  z-index: 1;
  background-color: #74526c;
  display: flex;
  justify-content: center;
  align-items: center;
}
.fa-cogs,
.fa-folder-open,
.fa-id-badge,
.fa-user-circle,
.fa-buysellads,
.fa-book {
  font-size: 1.4dvw;
  color: #fce2f9;
}
.divs h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  color: #74526c;
}
.divs h1 {
  font-size: 2.6dvw;
}

.divs h3 {
  font-size: 1.6dvw;
}

.divs h3 {
  font-weight: 500;
  font-size: 2dvw;
}
.divs h5 {
  font-size: 1.4vw;
}
.divs h6 {
  font-size: 1.2vw;
}
.projects {
  padding: 0;
  margin: 0;
}
.main-pro {
  padding: 0;
  margin: 0;
}

.proj-card {
  display: flex;
  align-items: center;
  flex-direction: column;
  height: fit-content;
  border-radius: 8px;
  padding: 10px;
  box-shadow: 1px 1px 10px 1px #74526c;
  border: 1px solid #74526c;
  transition: all 0.3s ease-in-out;
  cursor: pointer;
  margin: 20px 50px;
}
.proj-card:hover {
  transform: scale(1.008);
}
.images {
  width: 100%;
  height: 50%;
}
.images img {
  width: 100%;
  height: 120px;
  border-radius: 6px;
  transition: all 0.4s ease-in-out;
}
.images img:hover {
  transform: scale(1.08);
}

.info {
  text-align: center;
}
.info p {
  font-size: 1dvw;
}
.info h4 {
  font-size: 1.8dvw;
}
.view-btn {
  border: 1px solid #74526c;
  border-radius: 6px;
  font-size: 1dvw;
  padding: 4px 16px;
  color: #694966;
  transition: all 0.3s ease-in-out;
}
.view-btn:hover {
  transform: scale(1.01);
  box-shadow: 1px 1px 8px 1px #74526c;
}
@media screen and (max-width: 678px) {
  .proj-card {
    padding: 10px;
    margin: 8px 14px;
  }
}
</style>
