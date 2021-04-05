<template>
  <section class="section" id="video">
    <div class="columns is-centered">
      <div class="column is-half">
        <div class="video-wrapper">
          <iframe
            src="https://www.youtube.com/embed/OA79QZBVLCA"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "DemoVideo",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.video-wrapper {
  position: relative;
  padding-bottom: 56.25%; /* 16:9 */
  height: 0;
}

.video-wrapper iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
</style>
