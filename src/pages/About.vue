<template>
  <div id="wrapper" class="about">
    <div class="about-app jumbotron">
          <img src="../static/logo.png" class="website-logo">

          <p>{{$store.state.webappName}} is a web-based application that enables the searching, sorting, filtering, viewing, and downloading of Administrative Orders issued by the Philippine Department of Health.</p>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-md-7">
          <h1>Who are we?</h1>
          <p>EpiMetrics, Inc. is a health research institution geared towards the achievement of health equity through rigorous and creative conception, execution, translation, and communication of health systems and  research</p>
          <img src="../static/epimetrics_logo.png" alt="EpiMetrics logo" class="epimetrics-logo">
          <br>
          <br>
        </div>
        <div class="col-md-4 col-md-offset-1">
          <h1> In cooperation with: </h1>
          <img class="doh-logo" src="../static/doh_logo.png" alt="DOH logo">
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.about {
  margin-bottom:20px;
}

.about .about-app {
  padding-left:10px;
  padding-right:10px;
}

.about .epimetrics-logo {
  width: 60%;
}

.about .doh-logo{
  width:30%
}

.about .website-logo {
  height: 150px;
}
</style>