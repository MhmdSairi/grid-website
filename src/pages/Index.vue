<template>
  <Layout>
    <section class="hero is-fullheight has-text-centered">
      <div class="hero-body">
        <div class="container">
          <h1 class="title is-1 has-text-primary">Hi I'm MhmdSairi</h1>
          <vue-typed-js :strings="subtitle" class="has-text-centered is-block" :loop="true">
            <h2 class="subtitle has-text-white"><span class="has-text-primary is-italic">return </span>"<span class="typing"></span>";</h2>
          </vue-typed-js>
        </div>
      </div>
    </section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Here I am',
    description: 'I’m from Banjarmasin, Indonesia and I have been working as a junior front-end programmer for more than 2 years and still love to do it every day.',
  },
  data() {
    return {
      subtitle: [
        'Backend Developer',
        'PHP Programmer',
        'UI / UX Lover',
        'Boy ?',
        'Fullstack?'
      ]
    }
  },
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
