<template>
  <div class="home">
    <div class="wrapper">
      <code>Hello! My name is</code>
      <div class="hero">Kelionel Mak</div>
      <div class="headline">I am an Information Systems student at Singapore Management University with a passion for data science and business intelligence to help companies make informed business decisions.</div>
      <div class="json-wrapper">
        <code>
          $ cat profile.json<br><br>
          {
          <ul>
            <li>"github": <a href="https://github.com/kelionelmak" target="_blank">https://github.com/kelionelmak</a>,</li>
            <li>"linkedin": <a href="https://linkedin.com/in/kelionelmak" target="_blank">https://linkedin.com/in/kelionelmak</a></li>
          </ul>
          }
        </code>
      </div>
      <div class="headline">Here's the latest copy of my <a href="https://www.dropbox.com/s/bdmz8ydu0y56hz2/Resume.pdf?dl=0" target="_blank">Résumé</a></div>
      <div class="headline">You can reach me at <a href="mailto:kelionelmak.2019@sis.smu.edu.sg">kelionelmak.2019@sis.smu.edu.sg</a></div>
      <div class="feature">
        Work Experience
      </div>
      <div class="listing">
        <div class="img-wrapper">
          <img src="../assets/img/deloitte.jpg" />
        </div>
        <div class="writeup">
          <div class="title">Deloitte & Touche</div>
          <div class="date"><i>Singapore</i>, May 2017</div>
          <div class="position">Audit Analyst</div>
          <ul>
            <li>Developed Tableau dashboards for IT compliance work for Singapore government agencies.</li>
            <li>Analyzed large company data in internal audit projects for a leading LNG (Liquefied Natural Gas) terminal operator and several Singapore government ministries.</li>
            <li>Developed and presented analytics solutions to several clients.</li>
            <li>Conducted data analytics training and workshops for both Deloitte staff and clients.</li>
          </ul>
          <div class="article">Testimonial: <a href="https://www.dropbox.com/s/3ubly7mn2tk3vw4/Deloitte_Testimonial.pdf?dl=0" target="_blank">Dropbox</a></div>
        </div>
      </div>
      <div class="listing last">
        <div class="img-wrapper">
          <img src="../assets/img/cag.jpg" />
        </div>
        <div class="writeup">
          <div class="title">Changi Airport Group</div>
          <div class="date"><i>Singapore</i>, September 2016</div>
          <div class="position">Data Analyst Intern</div>
          <ul>
            <li>Revamped Air Traffic Statistics Reports for top management of Changi Airport Group and Civil Aviation Authority of Singapore using Tableau to provide more data insights, data accuracy and reduced 80% of process time.</li>
            <li>Analyzed untapped and unstructured Wi-Fi@Changi and geospatial data to provide observations and recommendations for better operational efficiency.</li>
          </ul>
          <div class="article">Testimonial: <a href="https://www.dropbox.com/s/syp8uksppn1j14t/ChangiAirportGroup_Testimonial.pdf?dl=0" target="_blank">Dropbox</a></div>
        </div>
      </div>
      <div class="feature">
        Co-Curricular Activities
      </div>
      <div class="listing last">
        <div class="img-wrapper">
          <img src="../assets/img/smubia.png" />
        </div>
        <div class="writeup">
          <div class="title">SMU Business Intelligence and Analytics Club</div>
          <div class="date">Mar 2020</div>
          <div class="position">Talent & Growth Director</div>
          <ul>
            <li>Attract new data associates and retain senior data associates.</li>
            <li>Build the club’s internal competencies and portfolio.</li>
            <li>Collaborate with industries to work on projects.</li>
          </ul>
          <div class="date">Jan 2020</div>
          <div class="position">Data Associate</div>
          <ul>
            <li>Selected to be a part of the club’s flagship mentoring programme.</li>
            <li>Conducted a Data Science workshop about Web Scraping for 47 other associates.</li>
            <li>Completed a project to predict psychopathy from social media using Python and machine learning models.</li>
          </ul>
        </div>
      </div>
      <div class="feature">
        Education
      </div>
      <div class="listing">
        <div class="img-wrapper">
          <img src="../assets/img/smu.jpg" />
        </div>
        <div class="writeup">
          <div class="title">Singapore Management University</div>
          <div class="date">Aug 2019 - May 2022 <i>(expected)</i></div>
          <div class="position">Bachelor of Science (Information Systems)</div>
        </div>
      </div>
      <div class="listing last">
        <div class="img-wrapper">
          <img src="../assets/img/tp.jpg" />
        </div>
        <div class="writeup">
          <div class="title">Temasek Polytechnic</div>
          <div class="date">Apr 2014 - May 2017</div>
          <div class="position">Diploma in Business Intelligence and Analytics</div>
          <ul></ul>
          <div class="article">Testimonial: <a href="https://www.dropbox.com/s/b7ody2cye55uj8c/TemasekPolytechnic_Testimonial.pdf?dl=0" target="_blank">Dropbox</a></div>
        </div>
      </div>
      <div class="feature">
        Skills
      </div>
      <div class="skills">
        <div class="skill-column">
          <div class="skill-category">
            <div class="title">Programming</div>
            <div class="writeup">SAS, Audit Command Language, Python, JavaScript, PHP, HTML</div>
          </div>
        </div>
        <div class="skill-column">
          <div class="skill-category">
            <div class="title">Office</div>
            <div class="writeup">Word, Excel, Powerpoint, Project, Visio</div>
          </div>
        </div>
        <div class="skill-column">
          <div class="skill-category">
            <div class="title">Data Analytics</div>
            <div class="writeup">SQL Server Management Studio, SAS Enterprise Miner, SAS Enterprise Guide, Qlikview, Tableau, Python</div>
          </div>
        </div>
      </div>
      <div class="feature">
        Certifications
      </div>
      <div class="certification">Tableau Desktop Specialist</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
code {
  font-size: 24px;
  color: #777;
  display: inline-block;
}
div.home {
  display: flex;
  justify-content: center;
  margin-top: 100px;
}
div.json-wrapper {
  background-color: #2c3e50;
  border-radius: 20px;
  padding: 20px;
  margin: 40px 0;
  overflow-x: scroll;
  white-space: nowrap;
}
div.json-wrapper::-webkit-scrollbar {
  width: 0 !important;
  overflow: -moz-scrollbars-none;
  -ms-overflow-style: none;
}
div.json-wrapper code {
  color: #FFF;
  font-size: 1.2rem;
}
div.json-wrapper code a {
  color: #FFF;
  text-decoration: none;
}
div.json-wrapper ul {
  list-style-type: none;
}
div.wrapper {
  width: calc(100% - 40px);
  max-width: 800px;
  text-align: left;
  margin: 20px;
  padding: 0 20px;
}
div.feature {
  text-align: left;
  margin: 40px 0;
  padding-top: 40px;
  font-size: 1.5rem;
  border-top: 1px solid #ddd;
}
div.hero {
  font-size: 4rem;
  color: #2c3e50;
  line-height: 4.8rem;
  margin: 5px 0;
}
div.headline strong {
  color: #444;
}
div.headline {
  font-size: 1.2rem;
  color: #777;
}
div.headline a {
  color: #71a6ea;
  font-weight: bold;
  text-decoration: none;
}
div.listing {
  padding-bottom: 20px;
  border-bottom: 1px solid #eee;
  margin-bottom: 20px;
  display: flex;
  flex-direction: row;
  width: calc(100% - 0px);
}
div.listing.last {
  border-bottom: 0;
}
@media only screen and (max-width: 600px) {
  div.listing .img-wrapper {
    display: none;
  }
}
div.listing .img-wrapper {
  width: 120px;
  min-width: 120px;
  padding-right: 20px;
  position: relative;
  display: inline-block;
}
div.listing .img-wrapper img {
  width: 100px !important;
  margin: 0;
}
div.listing .writeup {
  position: relative;
  display: inline-block;
}
div.listing .writeup ul {
  list-style-type: circle;
}
div.listing .writeup .date {
}
div.listing .writeup .highlight {
  background-color: #71a6ea;
  color: #fff;
  padding: 5px 20px;
  font-size: 0.8rem;
  border-radius: 5px;
  margin: 5px 0;
  display: inline-block;
}
div.listing .writeup .highlight.upcoming {
  background-color: #f4f4f4;
  color: #444;
}
div.listing .writeup .title {
  font-weight: bold;
  font-size: 2rem;
}
div.listing .writeup .article {
  font-size: 0.8rem;
  color: #444;
}
div.listing .writeup .article a {
  color: #71a6ea;
  font-weight: bold;
  text-decoration: none;
}
div.listing .writeup .tag-wrapper {
  margin: 30px 0 10px 0;
  overflow-x: scroll;
}
div.listing .writeup .tag-wrapper::-webkit-scrollbar {
  width: 0 !important;
  overflow: -moz-scrollbars-none;
  -ms-overflow-style: none;
}
div.listing .writeup .tag-wrapper .tag {
  border-radius: 5px;
  border: 1px solid #ddd;
  padding: 10px 20px;
  text-align: center;
  display: inline-block;
  margin: 0px 10px 10px 0;
  width: auto;
}
div.listing .writeup .tag-wrapper .tag:first-of-type {
  margin-left: 0;
}
div.listing .writeup .tag-wrapper .tag:last-of-type {
  margin-right: 0;
}
div.listing .writeup .tag-wrapper .tag code{
  color: #000;
  font-size: 1.2rem;
}
div.alert {
  border-radius: 10px;
  padding: 10px 20px;
  font-size: 0.8rem;
  background-color: #f4f4f4;
  display: inline-block;
  margin: 0 0 10px 0;
}
div.skills {
  display: flex;
}
div.skills .skill-column {
  width: 30%;
  margin-right: 5%;
}
@media only screen and (max-width: 800px) {
  div.skills {
    display: block;
  }
  div.skills .skill-column {
    width: 100% !important;
  }
}

div.skill-category {
  margin-bottom: 2rem;
}
div.skill-category .title {
  font-weight: bold;
  font-size: 1.2rem;
}
div.skill-category .writeup {
  font-size: 1rem;
}
div.skill-category .writeup i {
  font-size: 0.8rem;
  color: #777;
}
</style>
