<template>
  <div class="card-started" id="home-card">
    <div class="profile no-photo">
      <div
        class="slide"
        :style="{
          backgroundImage:
            'url(' + require('@/assets/images/yuanzhecui.png') + ')'
        }"
      ></div>

      <div class="title">Yuanzhe Cui</div>
      <div class="subtitle subtitle-typed">
        <div class="typing-title" style="display: none;">
          <p>Front-end Developer</p>
          <p>Fullstack Developer</p>
          <p>Back-end Developer</p>
          <p>Freelancer</p>
        </div>
      </div>
      <span class="typed-cursor">|</span>

      <!-- profile socials -->
      <div class="social">
        <a target="_blank" :href="linkedInUrl">
          <span class="fa fa-linkedin"></span>
        </a>
        <a target="_blank" :href="githubUrl">
          <span class="fa fa-github"></span>
        </a>
        <a target="_blank" :href="stackoverflowUrl">
          <span class="fa fa-stack-overflow"></span>
        </a>
        <a target="_blank" :href="hackerrankUrl">
          <span class="fab fa-hackerrank"></span>
        </a>
      </div>

      <!-- profile buttons -->
      <div class="lnks">
        <a href="/docs/cuiyuanzhe.pdf" class="lnk" target="_blank">
          <span class="text">Download CV</span>
          <span class="ion ion-android-download"></span>
        </a>
      </div>
    </div>
  </div>
</template>
<script>
import { defineComponent } from '@vue/composition-api'
// import Resume from '@/assets/docs/resume.pdf'
export default defineComponent({
  setup() {},
  computed: {
    getResume() {
      // return Resume
    },

    linkedInUrl() {
      return process.env.VUE_APP_LINKEDIN
    },
    githubUrl() {
      return process.env.VUE_APP_GITHUB
    },
    stackoverflowUrl() {
      return process.env.VUE_APP_STACKOVERFLOW
    },
    hackerrankUrl() {
      return process.env.VUE_APP_HACKER_RANK
    }
  }
})
</script>
