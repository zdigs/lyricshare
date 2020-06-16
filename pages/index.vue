<template>
  <div class="container">
    <h1 class="title">LyricShare</h1>
    <h4 class="subtitle">.live</h4>

  </div>
</template>

<script>
export default {
  components: {
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 55px;
  color: #35495e;
  letter-spacing: 2px;
  text-transform: capitalize;
  margin: 25px 0px
}

.subtitle {
  font-weight: 300;
  font-size: 1.1rem;
  color: #526488;
  word-spacing: 2px;
  letter-spacing: 4px;
  padding-top:45px;
  padding-left: 4px;
  max-width: 600px;
}

.subtitle a {
  font-weight: 500;
  color: inherit
}

.links {
  padding-top: 15px;
  margin-bottom: 20px
}

.content-logos {
  display: flex;
  align-items: center;
  justify-content: center;
  min-width: 500px;
}
.plus {
  font-size: 2.5rem;
  margin: 15px;
  color: #35495e
}
.h3 {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-weight: 400;
  margin: 10px;
}
</style>
