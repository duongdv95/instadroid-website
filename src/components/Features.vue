<template>
  <section class="section" id="features">
    <div class="columns is-centered">
      <div class="column is-three-quarters">
        <div class="columns">
          <div class="column">
            <div class="card">
              <div class="card-content feature">
                <figure>
                  <img class="feature-icon" src="@/assets/community.svg" />
                </figure>
                <p class="title is-5">
                  Community
                </p>
                <p>
                  Join our <a href="https://www.facebook.com/groups/298146074618530" target="blank">FB group</a> to stay up-to-date with app news
                </p>
              </div>
            </div>
          </div>
          <div class="column">
            <div class="card">
              <div class="card-content feature">
                <figure>
                  <img class="feature-icon" src="@/assets/grow.svg" />
                </figure>
                <p class="title is-5">
                  Growth
                </p>
                <p>
                  Organically increase traffic to your Instagram profile 
                </p>
              </div>
            </div>
          </div>
          <div class="column">
            <div class="card">
              <div class="card-content feature">
                <figure>
                  <img class="feature-icon" src="@/assets/time.svg" />
                </figure>
                <p class="title is-5">
                  Automation
                </p>
                <p>
                  Schedule daily interactions to target hashtags in your niche
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Features'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.feature-icon {
  max-height: 100px;
}
.feature {
  display: flex;
  flex-direction: column;
  align-items: center;
  }
  .card-content {
    padding: 3rem;
  }
</style>
