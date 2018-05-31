<template>
  <div id="app">
    <div class="center-box">
        <div>
            <h1 class="glitch" data-text="CLEM">CLEM</h1>
            <h1 class="glitch" data-text="FREEMAN">FREEMAN</h1>
        </div>
        <br>
        <div>
            <a href="http://github.com/clemf"><h2>github.com/clemf</h2></a>
            <a href="http://www.linkedin.com/in/clemfreeman"><h2>linkedin.com/in/clemfreeman</h2></a>
            <a href="http://twitter.com/clem_free"><h2>twitter.com/clem_free</h2></a>
        </div>
    </div>
  </div>
</template>

<script>
export default {
};
</script>

<style>
    h2 {
        color: lightgrey;
    }
    .center-box {
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 100%;
        max-width: 400px;
        margin: 0 auto;
    }
</style>

<style src="./styles/glitch.scss" lang="scss"></style>