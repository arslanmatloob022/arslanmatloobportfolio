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
          <i class="fa fa-book fa-2x" aria-hidden="true"></i>
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
          <i class="fa fa-book fa-2x" aria-hidden="true"></i>
        </div>
        <h1 class="col-12">Skills</h1>
        <div class="graduation col-lg-6 col-md-6 col-sm-6 col-6">
          <h3>Technical Skills</h3>
          <h6><i class="fa fa-dashcube" aria-hidden="true"></i> Vue.Js</h6>
          <h6><i class="fa fa-dashcube" aria-hidden="true"></i> Mongodb</h6>
          <h6><i class="fa fa-dashcube" aria-hidden="true"></i> JavaScript</h6>
          <h6><i class="fa fa-dashcube" aria-hidden="true"></i> Bootstrap</h6>
          <h6><i class="fa fa-dashcube" aria-hidden="true"></i> HTML</h6>
          <h6><i class="fa fa-dashcube" aria-hidden="true"></i> CSS</h6>
        </div>
        <div class="graduation col-lg-6 col-md-6 col-sm-6 col-6">
          <h3>Non-Technical Skills</h3>
          <h6>
            <i class="fa fa-dashcube" aria-hidden="true"></i> Continous Learning
          </h6>
          <h6>
            <i class="fa fa-dashcube" aria-hidden="true"></i> Supportive for
            others
          </h6>
          <h6><i class="fa fa-dashcube" aria-hidden="true"></i> Team Player</h6>
          <h6><i class="fa fa-dashcube" aria-hidden="true"></i> Punctual</h6>
          <h6><i class="fa fa-dashcube" aria-hidden="true"></i> Hardworking</h6>
        </div>
      </div>
      <div class="skills borders divs row">
        <div class="siders">
          <i class="fa fa-bookmark fa-2x" aria-hidden="true"></i>
        </div>
        <h1 class="col-12">Experiance</h1>
        <h3 class="col-12">Work Experiance</h3>
        <h6 class="col-12">
          <i class="fa fa-arrow-circle-o-right" aria-hidden="true"></i>
          Upto 1-Year experiance in fornt-end web development.
        </h6>
        <h6 class="col-12">
          <i class="fa fa-arrow-circle-o-right" aria-hidden="true"></i>
          Currently working on Fiverr with friends with a team of three members.
        </h6>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  namae: "MainPage",
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
  box-shadow: 1px 1px 16px 4px #b09398;
  transition: all 0.3s ease-in-out;
}
.image:hover {
  cursor: pointer;
  transform: scale(1.01);
  box-shadow: 1px 1px 22px 8px #b09398;
}
.image img {
  width: 100%;
  transform: translateY(40px);
  transition: all 0.6s ease-in-out;
}
.image img:hover {
  transform: translateY(0px);
}
*i {
  background-color: #694966;
  color: #fdefef;
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
}
.siders {
  border-radius: 50%;
  top: 50px;
  left: -18px;
  position: absolute;
  z-index: 1;
  color: #fce1e1;
  background-color: #74526c;
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
</style>
