<template>
  <div class="card-inner active" id="about-card">
    <div class="card-wrap">
      <div class="content about">
        <!-- title -->
        <div class="title"><span class="first-word">About</span> Me</div>
        <!-- content -->
        <div class="row">
          <div class="col col-d-6 col-t-6 col-m-12 border-line-v">
            <div class="text-box">
              <p>
                I am Yuanzhe Cui, full-stack developer from {{ city }},
                {{ country }}. I have rich experience in building the web site
                in both of front-end and back-end sides.
              </p>
            </div>
          </div>
          <div class="col col-d-6 col-t-6 col-m-12 border-line-v">
            <div class="info-list">
              <ul>
                <li><strong>Birthday . . . . .</strong> Nov 17 1994</li>
                <li><strong>Residence . . . . .</strong> {{ city }}</li>
                <li><strong>Address . . . . .</strong> {{ country }}</li>
                <li><strong>Remote Work. . . . .</strong> Available</li>
              </ul>
            </div>
          </div>
          <div class="clear"></div>
        </div>
      </div>

      <!--
						Services
					-->
      <div class="content services">
        <!-- title -->
        <div class="title"><span class="first-word">My</span> Services</div>

        <!-- content -->
        <div class="row service-items border-line-v">
          <!-- service item -->
          <div class="col col-d-6 col-t-6 col-m-12 border-line-h">
            <div class="service-item">
              <div class="icon">
                <span class="fa fa-html5"></span>
              </div>
              <div class="name">
                <span> Front-end Development </span>
              </div>
              <div class="desc">
                <div>
                  <p>
                    Beautiful, easy-handling and comfortable frontend that will
                    help you reach all of your marketing.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <!-- service item -->
          <div class="col col-d-6 col-t-6 col-m-12 border-line-h">
            <div class="service-item">
              <div class="icon">
                <span class="fa fa-code"></span>
              </div>
              <div class="name">
                <span> Back-end Development </span>
              </div>
              <div class="desc">
                <div>
                  <p>
                    High performance, creative, adaptable code using design
                    patterns and best practices.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <!-- service item -->
          <div class="col col-d-6 col-t-6 col-m-12 border-line-h">
            <div class="service-item">
              <div class="icon">
                <span class="fa fa-cogs"></span>
              </div>
              <div class="name">
                <span> DevOps </span>
              </div>
              <div class="desc">
                <div>
                  <p>
                    DevOps services include CI/CD, Workflow, Scrum, Testing, and
                    <br />
                    Auto deploying.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <!-- service item -->
          <div class="col col-d-6 col-t-6 col-m-12 border-line-h">
            <div class="service-item">
              <div class="icon">
                <span class="fa fa-bug"></span>
              </div>
              <div class="name">
                <span> Troubleshooting </span>
              </div>
              <div class="desc">
                <div>
                  <p>
                    Critical, Complex, and logical bug fixing in Website
                    building. <br />Any bugs fixed.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="clear"></div>
      </div>

      <!--
						Price Tables
					-->
      <div class="content pricing">
        <!-- title -->
        <div class="title">
          <span class="first-word">Hourly</span> <span>Ratio</span>
        </div>

        <!-- content -->
        <div class="row pricing-items">
          <!-- pricing item -->
          <div class="col col-d-6 col-t-6 col-m-12 border-line-v">
            <div class="pricing-item">
              <div class="icon"><i class="fa fa-html5"></i></div>
              <div class="name">Front-End</div>
              <div class="amount">
                <span class="dollar">$</span>
                <span class="number">35</span>
                <span class="period">hour</span>
              </div>
              <div class="feature-list">
                <ul>
                  <li>React.js, Redux, Material-UI</li>
                  <li>Vue.js, Vuex, Vuetify</li>
                  <li>HTML, CSS, SCSS, JavScript</li>
                  <li>TailWindCSS, AntD, Bootstrap</li>
                  <li>jsPDF, React-PDF, jsDom</li>
                  <li>Fabric.js, Canvas.js, Svg.js</li>
                  <li>Mocha, Cypress, StoryBook</li>
                  <li>Rest API, GraphQL</li>
                </ul>
              </div>
            </div>
          </div>

          <!-- pricing item -->
          <div class="col col-d-6 col-t-6 col-m-12 border-line-v">
            <div class="pricing-item">
              <div class="icon"><i class="fa fa-code"></i></div>
              <div class="name">Back-end</div>
              <div class="amount">
                <span class="dollar">$</span>
                <span class="number">35</span>
                <span class="period">hour</span>
              </div>
              <div class="feature-list">
                <ul>
                  <li>PHP, Laravel, WordPress</li>
                  <li>Node.js, Express.js, Nest.js</li>
                  <li>GraphQL, RestAPI</li>
                  <li>PostgreSQL, MySQL, MongoDB</li>
                  <li>Docker, Kubernete</li>
                  <li>Nginx, Apache, RabbitMQ</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="clear"></div>
        </div>
      </div>

      <!--
						Clients
					-->
      <div class="content clients">
        <!-- title -->
        <div class="title">
          <div class="first-letter">Clients</div>
        </div>

        <!-- content -->
        <div class="row client-items">
          <!-- client item -->
          <div class="col col-d-3 col-t-3 col-m-6 border-line-v">
            <div class="client-item">
              <div class="image">
                <a target="_blank" href="https://skillsquare.io">
                  <img
                    src="@/assets/images/clients/skillsquare.png"
                    alt="skillsqure.io"
                  />
                </a>
              </div>
            </div>
          </div>

          <!-- client item -->
          <div class="col col-d-3 col-t-3 col-m-6 border-line-v">
            <div class="client-item">
              <div class="image">
                <a target="_blank" href="https://comberry.com/">
                  <img
                    src="@/assets/images/clients/comberry.png"
                    alt="comberry"
                  />
                </a>
              </div>
            </div>
          </div>

          <!-- client item -->
          <div class="col col-d-3 col-t-3 col-m-6 border-line-v">
            <div class="client-item">
              <div class="image">
                <a target="_blank" href="https://www.google.com">
                  <img
                    src="@/assets/images/clients/virtualshowroom.png"
                    alt=""
                  />
                </a>
              </div>
            </div>
          </div>

          <div class="clear"></div>
        </div>
      </div>

      <!-- Quote -->
      <div class="content quote">
        <!-- title -->
        <div class="title">
          <div class="first-letter">
            <span>Quote</span>
          </div>
        </div>

        <!-- content -->
        <div class="row">
          <div class="col col-d-12 col-t-12 col-m-12 border-line-v">
            <div class="revs-item">
              <div class="text">
                <div>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Lorem
                  ipsum dolor sit amet, consectetur adipiscing elit.
                </div>
              </div>
              <div class="user">
                <div class="img">
                  <img
                    :src="require('@/assets/images/profile.png')"
                    alt="Yuanzhe Cui"
                  />
                </div>
                <div class="info">
                  <div class="name">Yuanzhe Cui</div>
                  <div class="company">Web Developer</div>
                </div>
                <div class="clear"></div>
              </div>
            </div>
          </div>
          <div class="clear"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'About',
  computed: {
    country() {
      return process.env.VUE_APP_COUNTRY
    },
    city() {
      return process.env.VUE_APP_CITY
    }
  }
}
</script>
