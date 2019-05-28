<template>
<div id="content">

  <ul class="timeline">
    <a name="work"><h1>Work Experience</h1></a>

    <li class="pratt" data-date="Sept - Dec 2018">
      <h2 font-weight="bold" color="#4298c3">Programmer Analyst Intern</h2>
      <h3>Pratt & Whitney Canada</h3>
      <h4>August 2017 - December 2017</h4>
      <ul>
        <li class="desc">Implemented a communications protocol between embedded devices and emulated their request-response sequence  <br />in a test environment.</li>
        <li class="desc">Developed a C++ application to parse files into XML and post them to a SharePoint server resulting in faster file <br />uploads for engineers.</li>
        <li class="desc">Developed, presented, and demoed tools to engineers at Pratt & Whitney to facilitate blackbox testing.</li>
      </ul>
    </li>
    <li class="astuce">
      <h2 font-weight="bold" color="#4298c3">Junior Developer Intern</h2>
      <h3>Astucemedia</h3>
      <h4>May 2018 - January 2019</h4>
      <ul>
        <li class="desc">Developed data ingests for NFL data from SportRadar and weather data from DarkSky. Built APIs to feed broadcast <br />graphics. All projects developed in C# using .NET.</li>
        <li class="desc">Developed a ServiceStack plugin to report the status of an application to a central monitoring hub.</li>
        <li class="desc">Provided support to media broadcast clients to ensure that on-air data is legitimate and serviced any issues.</li>
      </ul>
    </li>
    <li class="broadsign">
      <h2 font-weight="bold" color="#4298c3">Software Developer Intern</h2>
      <h3>Broadsign</h3>
      <h4>May 2019 - Present</h4>
      <ul>
        <li class="desc">In progress!</li>
      </ul>   
    </li>
  </ul>
</div>
</template>

<style>
body {
  background: #252827;
  font-size: 16px;
}
strong {
  font-weight: 600;
}

.timeline h1 {
  font-family: 'Oswald', sans-serif;
  letter-spacing: 1.5px;
  color: #ffffff;
  font-weight: 100;
  font-size: 2.4em;
  padding-bottom: 10vh;
  text-shadow: 2px 4px 4px #0a0a0a;
}

.timeline h2 {
  width: 100%;
  letter-spacing: 1.5px;
  font-weight: 100;
  font-size: 1.6em;
  padding-bottom: 1vh;
}
.timeline h3 {
  font-family: 'Oswald', sans-serif;
  color:#4298c3;
  width: 100%;
  letter-spacing: 1.5px;
  font-weight: 100;
  font-size: 1.2em;
  padding-bottom: 0.5vh;
}
.timeline h4 {
  font-family: 'Oswald', sans-serif;
  color:#4298c3;
  width: 100%;
  letter-spacing: 1.5px;
  font-weight: 100;
  font-size: 1em;
  padding-bottom: 2.5vh;
}
#content {
  text-align: left;
}
/* Timeline */
.timeline {
  border-left: 4px solid #4298c3;
  border-bottom-right-radius: 4px;
  width: 100%;
  border-top-right-radius: 4px;
  background: rgba(255, 255, 255, 0.03);
  color: rgba(255, 255, 255, 0.8);
  font-family: 'Source Sans Pro', sans-serif;
  letter-spacing: 0.5px;
  line-height: 1.4em;
  font-size: 1.03em;
  padding: 50px;
  list-style: none;
  text-align: left;
  font-weight: 100;
}

.timeline .pratt {
  border-bottom: 2px dashed rgba(255, 255, 255, 0.1);
  background: url('../assets/pratt.png') no-repeat bottom right;
  width: 100%;
  padding-bottom: 25px;
  margin-bottom: 50px;
  position: relative;
}

.timeline .pratt:last-of-type {
  padding-bottom: 0;
  margin-bottom: 0;
  border: none;
}
.timeline .pratt:before,
.timeline .pratt:after {
  position: absolute;
  display: block;
}
.timeline .pratt:after {
  box-shadow: 0 0 0 4px #4298c3;
  left: -57.85px;
  background: #313534;
  border-radius: 50%;
  width: 30px;
  content: "";
  top: 10px;
}
.timeline .astuce {
  border-bottom: 2px dashed rgba(255, 255, 255, 0.1);
  background: url('../assets/astucemedia.png') no-repeat bottom right;
  width: 100%;
  padding-bottom: 25px;
  margin-bottom: 50px;
  position: relative;
}

.timeline .astuce:last-of-type {
  padding-bottom: 0;
  margin-bottom: 0;
  border: none;
}
.timeline .astuce:before,
.timeline .astuce:after {
  position: absolute;
  display: block;
}
.timeline .astuce:after {
  box-shadow: 0 0 0 4px #4298c3;
  left: -57.85px;
  background: #313534;
  border-radius: 50%;
  width: 30px;
  content: "";
  top: 10px;
}

.timeline .broadsign {
  border-bottom: 1px dashed rgba(255, 255, 255, 0.1);
  background: url('../assets/broadsign.png') no-repeat right;
  width: 100%;
  padding-bottom: 25px;
  margin-bottom: 50px;
  position: relative;
}

.timeline .broadsign:last-of-type {
  padding-bottom: 0;
  margin-bottom: 0;
  border: none;
}
.timeline .broadsign:before,
.timeline .broadsign:after {
  position: absolute;
  display: block;
}
.timeline .broadsign:after {
  box-shadow: 0 0 0 4px #4298c3;
  left: -57.85px;
  background: #313534;
  border-radius: 50%;
  width: 30px;
  content: "";
  top: 10px;
}
.timeline .desc {
    padding-bottom: 1vh;
    list-style: none;
}

.timeline .desc::before {
  content: "\2022";  /* Add content: \2022 is the CSS Code/unicode for a bullet */
  color: #4298c3; /* Change the color */
  display: inline-block; /* Needed to add space between the bullet and the text */
  width: 1em; /* Also needed for space (tweak if needed) */
  margin-left: -1em; /* Also needed for space (tweak if needed) */
}
</style>
