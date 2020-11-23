<template>
  <div class="hero instadroid is-primary is-fullheight">
    <div class="hero-head">
      <nav class="navbar">
        <div class="container">
          <div class="navbar-brand">
            <!-- <a class="navbar-item">
              <img src="https://bulma.io/images/bulma-type-white.png" alt="Logo">
            </a> -->
            <span v-on:click="toggle" class="navbar-burger burger" data-target="navbarMenuHeroA">
              <span></span>
              <span></span>
              <span></span>
            </span>
          </div>
          <div id="navbarMenuHeroA" class="navbar-menu">
            <div class="navbar-end">
              <!-- <a class="navbar-item is-active">
                Home
              </a> -->
              <a href="#documentation" class="navbar-item">
                Documentation
              </a>
              <a href="#changelog" class="navbar-item">
                Changelog
              </a>
              <span class="navbar-item">
                <a class="button is-primary is-inverted"  href='https://play.google.com/store/apps/details?id=com.danielduong.instadroid&pcampaignid=pcampaignidMKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1' target="none">
                  <span>Download</span>
                </a>
              </span>
            </div>
          </div>
        </div>
      </nav>
    </div>
    <div class="hero-body is-justify-content-center">
      <div class="columns is-justify-content-center">
        <div class="column is-two-thirds">
          <div class="columns is-vcentered">
            <div class="column is-one-third">
              <figure class="image is-9by16">
                <img src="../assets/hero-app-image-sample.png">
              </figure>
            </div>
            <div class="column">
              <h1 class="title">
                Instadroid
              </h1>
              <h1 class="subtitle">
                Automate <strong>liking</strong>, <strong>following</strong>, and <strong>unfollowing</strong> on instagram using this app.
                Expand your reach and grow your brand or business now!
              </h1>
              <div class="columns is-centered">
                <div class="column is-half">
                  <a href='https://play.google.com/store/apps/details?id=com.danielduong.instadroid&pcampaignid=pcampaignidMKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1'>
                    <img alt='Get it on Google Play' src='../assets/google-play-badge.png'/>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Instadroid",
  props: {
    msg: String,
  },
  methods: {
    toggle: function(event) {
      event.target.classList.toggle("is-active")
      const target = document.getElementById(event.target.dataset.target)
      target.classList.toggle("is-active")
    }
  }
};
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
</style>
