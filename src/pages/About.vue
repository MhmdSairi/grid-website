<template>
  <Layout>
    <Hero title="Something About Me" branch="about"/>
    <section class="section mb-10">
      <div class="container">
        <h3 class="title is-5 has-text-primary">About Information</h3>
        <div class="columns">
          <div class="column is-2">
            <g-image src="~/images/pp.gif"></g-image>
          </div>
          <div class="column is-10">
            <p>Hello! I’m MhmdSairi. Software Engineer from Indonesia, Kalimantan Selatan, Banjarmasin. I have rich experience in web development and also UI / UX Development.</p>
            <div class="columns is-multiline mt-3">
              <div class="column is-6 is-4-widescreen"><strong class="has-text-primary">Age :</strong> {{calculateAge}}</div>
              <div class="column is-6 is-4-widescreen"><strong class="has-text-primary">Residence :</strong> Indonesia</div>
              <div class="column is-6 is-4-widescreen"><strong class="has-text-primary">Freelance :</strong> Available</div>
              <div class="column is-6 is-4-widescreen"><strong class="has-text-primary">Address :</strong> Banjarmasin, ID</div>
              <div class="column is-6 is-4-widescreen"><strong class="has-text-primary">Chat :</strong><a href="//t.me/mhmdsairi" class="has-text-white"> t.me/mhmdsairi</a></div>
              <div class="column is-6 is-4-widescreen"><strong class="has-text-primary">WhatsApp :</strong><a href="https://bit.ly/3caV1XX" class="has-text-white"> 085349945947</a></div>
            </div>
          </div>
        </div>
        <hr>
        <h3 class="title is-5 has-text-primary">Coding Skills</h3>
        <div class="columns is-multiline">
          <div class="column is-6-widescreen">
            <small>PHP / Laravel</small>
            <b-progress :value="95" show-value format="percent" type="is-primary"></b-progress>
          </div>
          <div class="column is-6-widescreen">
            <small>HTMl,CSS,SASS</small>
            <b-progress :value="85" show-value format="percent" type="is-primary"></b-progress>
          </div>
          <div class="column is-6-widescreen">
            <small>Javascript / VueJS</small>
            <b-progress :value="75" show-value format="percent" type="is-primary"></b-progress>
          </div>
          <div class="column is-6-widescreen">
            <small>SQL / MySQL</small>
            <b-progress :value="85" show-value format="percent" type="is-primary"></b-progress>
          </div>
        </div>
        <hr>
        <h3 class="title is-5 has-text-primary">Knowledge & Technology</h3>
        <g-image src="~/images/tc-laravel.png" class="mr-3" width="40px"></g-image>
        <g-image src="~/images/tc-rest.png" class="mr-3" width="40px"></g-image>
        <g-image src="~/images/tc-sql.png" class="mr-3" width="40px"></g-image>
        <g-image src="~/images/tc-sass.png" class="mr-3" width="40px"></g-image>
        <g-image src="~/images/tc-git.png" class="mr-3" width="40px"></g-image>
      </div>
    </section>
  </Layout>
</template>

<script>
import Hero from '~/components/Hero.vue'
export default {
  components: {
    Hero,
  },
  metaInfo: {
    title: 'Me',
    description: "I'm currently working as Backend Developer using Laravel as the framework."
  },
  computed:{
    calculateAge() {
      let currentDate = new Date();
      let birthDate = new Date("2000/07/10");
      let difference = currentDate - birthDate;
      let age = Math.floor(difference/31557600000);
      return age
    }
  }
}
</script>
