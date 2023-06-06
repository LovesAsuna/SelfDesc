<template>
  <div class="section intro">
    <h2>
      <font-awesome-icon icon="fa-solid fa-chevron-right"/>
      Game
    </h2>

    <div class="block grid-container grid-parent">
      <div class="split grid-50 mobile-grid-100">
        <p>
          热衷于第一人称射击、手游和Galgame<br/>
          游戏是人生不可或缺的一部分！<br/>
          没有游戏的人生可太无趣了 <small>No Game No Life</small>
        </p>
      </div>

      <div class="split grid-50 mobile-grid-100">
        <figure class="identities">
          <figcaption><i>
            <font-awesome-icon icon="fa-solid fa-up-right-from-square"/>
          </i>profiles
          </figcaption>
          <ul>
            <li>
              <a href="https://steamcommunity.com/id/lovesasuna/">
                <i>
                  <font-awesome-icon icon="fa-brands fa-steam"/>
                </i>
                <span class="label">Steam</span>
                <span class="fake-link">LovesAsuna</span>
              </a>
            </li>
          </ul>
        </figure>

        <div class="label-group">
          <span class="header alt"><i><font-awesome-icon icon="fa-solid fa-tag"/></i>fps</span>

          <span class="label">Apex Legends</span>
          <span class="label">Rainbow Six Siege</span>
        </div>

        <div class="label-group">
          <span class="header alt"><i><font-awesome-icon icon="fa-solid fa-tag"/></i>手游</span>

          <span class="label">
            <i><font-awesome-icon icon="fa-solid fa-tag"/></i>
            <span class="status">原神</span>
            <span class="link">101272031</span>
          </span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Intro"
}
</script>

<style scoped>
#container .section.intro {
  opacity: 0.9;
  background: rgba(255, 255, 255, 1);
}


@media (max-width: 768px) {
  #container {
    padding: 0;
  }

  #container,
  #container > *:first-child {
    border-top-left-radius: 0;
  }

  #container,
  #container > *:last-child,
  #container > *:last-child > *:last-child {
    border-bottom-right-radius: 0;
  }

  #container .section.header {
    background: rgba(0, 0, 0, 0.75);
  }

  #container .intro .block .split {
    padding: 0 0.5em;
  }

  #container .intro p {
    border-left: none;
    padding: 0.2em;
  }
}

</style>
<style scoped src="../assets/css/intro.css"></style>
<style scoped src="../assets/css/identities.css"></style>
<style scoped src="../assets/css/labels.css"></style>
<style scoped src="../assets/css/links.css"></style>
<style scoped src="unsemantic/assets/stylesheets/unsemantic-grid-responsive.css"></style>
