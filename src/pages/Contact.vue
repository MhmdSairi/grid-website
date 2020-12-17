<template>
  <Layout>
    <Hero title="Contacts" branch="contact"/>
    <section class="section mb-10">
        <div class="container">
            <h3 class="title is-5 has-text-primary">Stay In Touch</h3>
            <p>You can find me around the web:</p>
            <div class="columns is-multiline mt-3">
            <div class="column is-6 is-4-widescreen"><strong class="has-text-primary">My Dear :</strong><a href="#" class="has-text-white"> Nadila Sepianti</a></div>
                <div class="column is-6 is-4-widescreen"><strong class="has-text-primary">Telegram :</strong><a href="//t.me/mhmdsairi" class="has-text-white"> t.me/mhmdsairi</a></div>
                <div class="column is-6 is-4-widescreen"><strong class="has-text-primary">WhatsApp :</strong><a href="https://bit.ly/3caV1XX" class="has-text-white"> +6285349945947</a></div>
                <div class="column is-6 is-4-widescreen"><strong class="has-text-primary">Blog :</strong><a href="https://ironimouse.blogspot.com/" class="has-text-white"> Ironimouse</a></div>
                <div class="column is-6 is-4-widescreen"><strong class="has-text-primary">GitHub :</strong><a href="//github.com/MhmdSairi" class="has-text-white"> github.com/MhmdSairi</a></div>
                <div class="column is-6 is-4-widescreen"><strong class="has-text-primary">GitLab :</strong><a href="//gitlab.com/MhmdSairi" class="has-text-white"> gitlab.com/MhmdSairi</a></div>
                <div class="column is-6 is-4-widescreen"><strong class="has-text-primary">Instagram :</strong><a href="//instagram.com/mhmdsairi_" class="has-text-white"> mhmdsairi_</a></div>
                <div class="column is-6 is-4-widescreen"><strong class="has-text-primary">MagerApps :</strong><a href="//mager.vercel.app/" class="has-text-white"> Mager</a></div>
<div class="column is-6 is-4-widescreen"><strong class="has-text-primary">Sestyc :</strong><a href="https://bit.ly/31UjWLt" class="has-text-white"> MhmdSairi</a></div>
            </div>
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
    title: 'Contact Me',
    description: 'Stay in touch with me, find me around the web',
  },
}
</script>
