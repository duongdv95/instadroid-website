<template>
  <section class="section" id="changelog">
    <div class="columns">
      <div class="column is-three-quarters container">
        <h1 class="title">Changelog <span class="icon"><i class="fas fa-clipboard-list"></i></span></h1>
        <div class="content">
          <div class="changelog" v-for="(item, index) in changelog" v-bind:key="index">
            <h1 class="title is-4">Version {{item.version}} ({{item.date}})</h1>
            <div class="news" v-if="item.news">
              <h1 class="title is-5">News</h1>
              <p>
                {{item.news}}
              </p>
            </div>
            <div class="features" v-if="item.features">
              <br/>
              <h1 class="title is-5">Features</h1>
              <p>
                <ul>
                  <li v-for="(feature, index) in item.features" v-bind:key="index">
                    {{feature}}
                  </li>
                </ul>
              </p>
            </div>
            <div class="bug-fixes" v-if="item.bugfixes">
              <br/>
              <h1 class="title is-5">Bug Fixes</h1>
              <p>
                <ul>
                  <li v-for="(bugfix, index) in item.bugfixes" v-bind:key="index">
                    {{bugfix}}
                  </li>
                </ul>
              </p>
            </div>
            <div class="improvements" v-if="item.improvements">
              <br/>
              <h1 class="title is-5">Improvements</h1>
              <p>
                <ul>
                  <li v-for="(improvement, index) in item.improvements" v-bind:key="index">
                    {{improvement}}
                  </li>
                </ul>
              </p>
            </div>
            <hr>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Changelog',
  data: () => {
    return {
      changelog: require('@/changelog.json').changelog
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.changelog {
  margin-bottom: 2em;
}
</style>
