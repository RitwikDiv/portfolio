<template>
  <div class="container">
    <div class="d-flex flex-wrap align-items-center">
      <div class="col-sm mr-1 mb-1 justify-content-left">
        <img
          :src="profile"
          class="illustration"
          alt="Illustration of me working"
        />
      </div>
      <div class="col-sm mt-3">
        <h4 class="info mt-2 text-primary">
          Hello there! <span class="wave">👋</span>
        </h4>
        <p class="info mr-4">
          I'm Ritwik, a Chicago based design enthusiast 🎨 and technical product
          manager working on AL/ML 🧠 products at Oracle.
        </p>
      </div>
    </div>
    <br />
    <hr />
    <br />
    <h4 class="align-items-center text-primary" id="work">Work 🧑🏻‍💻</h4>
    <ul>
      <li class="d-flex align-items-center flex-wrap mt-4">
        <div class="col col-4">
          <h5>Oracle ⭕</h5>
          <h6 class="text-muted">Technical Product Manager</h6>
          <a
            class="btn btn-warning btn-sm"
            :href="oracle"
            target="_blank"
            rel="noopener noreferrer"
            role="button"
          >
          </a>
        </div>
        <div class="col-8 info">
          <ul>
            <li>
              Working on exciting security and analytics products! Section will
              be updated after spending a year at Oracle
            </li>
          </ul>
        </div>
      </li>
      <li class="d-flex align-items-center flex-wrap mt-4">
        <div class="col col-4">
          <h5>American Express 💳</h5>
          <h6 class="text-muted">Software Engineering Intern</h6>
          <a
            class="btn btn-warning btn-sm"
            :href="amex"
            target="_blank"
            rel="noopener noreferrer"
            role="button"
          >
          </a>
        </div>
        <div class="col-8 info">
          <ul>
            <li>
              Co-designed a SaaS platform that allowed developers to customize
              different technologies and install a micro-service template to
              speed up development by 8 hours.
            </li>
            <li>
              Developed a REST API to monitor the status of the deployed
              applications and to provide a fail-fast functionality in case of
              downtime, dramatically reducing VM provisioning failures by 80%.
            </li>
          </ul>
        </div>
      </li>
      <li class="d-flex align-items-center flex-wrap mt-4">
        <div class="col col-4">
          <h5>Barchart 📈</h5>
          <h6 class="text-muted">Data Engineering Intern</h6>
          <a
            class="btn btn-warning btn-sm"
            target="_blank"
            rel="noopener noreferrer"
            :href="barchart"
            role="button"
          >
          </a>
        </div>
        <div class="col-8 info">
          <ul>
            <li>
              Extracted and normalized agricultural data feed from USDA
              increasing the data coverage for commodity statistics database by
              40%.
            </li>
            <li>
              Designed the database schema and wrote SQL queries to manage
              processing and integration for over a million records of commodity
              data, thereby reducing the integration time by 73.2%.
            </li>
          </ul>
        </div>
      </li>
    </ul>
    <br />
    <hr />
    <br />
    <h4 class="align-items-center text-primary mb-2" id="projects">
      Projects 👾
    </h4>
    <ul>
      <li class="d-flex align-items-center flex-wrap mt-4">
        <div class="col col-4">
          <h5>USustain 🥘</h5>
          <a
            class="btn btn-success btn-sm"
            href="https://devpost.com/software/usustain"
            role="button"
            target="_blank"
            rel="noopener noreferrer"
          >
          </a>
        </div>
        <div class="col-8 info">
          <p class="info">
            37% of college students including several of our classmates don't
            know where their next meal is coming from. When students have to
            worry about their meals, the focus on classes drops and grades
            plummet. USustain is a crowd funding tool to help students pay for
            their meals to support themselves through college.
          </p>
          <span class="badge badge-pill badge-primary mr-2">
            <strong>Project Type: Hackathon</strong></span
          >
          <span class="badge badge-pill badge-secondary">
            <strong>Contribution: PM, Backend, UI/UX</strong></span
          >
        </div>
      </li>
      <li class="d-flex align-items-center flex-wrap mt-4">
        <div class="col col-4">
          <h5>Auxy 🎒</h5>
          <a
            class="btn btn-success btn-sm"
            href="#"
            target="_blank"
            rel="noopener noreferrer"
            role="button"
          >
          </a>
        </div>
        <div class="col-8 info">
          <p class="info">
            Student retention is the biggest problems faced by colleges in USA.
            On average every university loses around 10 million dollars a year
            on grants and tuition from the students who dropped out. Auxy helps
            the universities focus on academically struggling students and boost
            retention by guiding them with to campus resources.
          </p>
          <span class="badge badge-pill badge-primary mr-2">
            <strong>Project Type: Startup</strong></span
          >
          <span class="badge badge-pill badge-secondary">
            <strong>Contribution: PM, User Research</strong></span
          >
        </div>
      </li>
    </ul>
    <br />
    <hr />
    <br />
    <h4 class="align-items-center text-primary" id="skills">Skills 🧑🏻‍💻</h4>
    <ul>
      <li class="d-flex align-items-center flex-wrap mt-3">
        <div class="col-sm">
          <h5>Languages 🐱‍💻</h5>
        </div>
        <div class="col-sm">
          <p class="info text-muted">
            Python, Java, C/C++, HTML5/CSS3, Javascript
          </p>
        </div>
      </li>
      <li class="d-flex align-items-center flex-wrap mt-3">
        <div class="col-sm">
          <h5>Libraries/Frameworks 📚</h5>
        </div>
        <div class="col-sm">
          <p class="info text-muted">
            Web (Vue.js, Node.js, Bootstrap), Data (numpy, pandas, scikit-learn,
            plotly, matplotlib)
          </p>
        </div>
      </li>
      <li class="d-flex align-items-center flex-wrap mt-3">
        <div class="col-sm">
          <h5>Databases 💾</h5>
        </div>
        <div class="col-sm">
          <p class="info text-muted">
            SQL (MySQL, PostgreSQL, Oracle), NoSQL (MongoDB, Redis)
          </p>
        </div>
      </li>
    </ul>
    <br />
  </div>
</template>

<script>
export default {
  name: "Intro",
  data() {
    return {
      profile: require("@/assets/images/intro.png"),
      de: require("@/assets/images/de.png"),
      swe: require("@/assets/images/swe.png"),
      pm: require("@/assets/images/pm.png"),
      oracle: "https://www.oracle.com/index.html",
      amex: "http://www.americanexpress.com/",
      barchart: "https://www.barchart.com/cmdty",
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.info {
  text-align: start;
  font-weight: 500;
}

.h4 {
  font-weight: 600;
}

.wave {
  animation-name: wave-animation; /* Refers to the name of your @keyframes element below */
  animation-duration: 2.5s; /* Change to speed up or slow down */
  animation-iteration-count: infinite; /* Never stop waving :) */
  transform-origin: 70% 70%; /* Pivot around the bottom-left palm */
  display: inline-block;
}

.illustration {
  height: 200px;
  width: 400px;
}

@keyframes wave-animation {
  0% {
    transform: rotate(0deg);
  }
  10% {
    transform: rotate(14deg);
  } /* The following five values can be played with to make the waving more or less extreme */
  20% {
    transform: rotate(-8deg);
  }
  30% {
    transform: rotate(14deg);
  }
  40% {
    transform: rotate(-4deg);
  }
  50% {
    transform: rotate(10deg);
  }
  60% {
    transform: rotate(0deg);
  } /* Reset for the last half to pause */
  100% {
    transform: rotate(0deg);
  }
}
</style>
