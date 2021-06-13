<template>
  <div class="section intro">
    <h2><i aria-hidden="true" class="fa fa-chevron-right"></i>Me</h2>

    <div class="block grid-container grid-parent">
      <div class="split grid-50 mobile-grid-100">
        <div class="self-desc">
          <p>
            也可以叫我冰星
          </p>
          <p>
            一个热爱后端的业余开发者<br/>
            喜欢看一些有意思的项目，也会开发一些实用性的东西
          </p>
          <p>
            目前只掌握了Java和Kotlin<small>前端略懂一二</small><br/>
            <small>前端真的是人学的吗？</small>
          </p>
        </div>
      </div>

      <div class="split grid-50 mobile-grid-100">
        <figure class="identities">
          <figcaption><i class="fas fa-external-link-alt"></i>open-source</figcaption>
          <ul>
            <li>
              <a href="https://github.com/LovesAsuna/">
                <i aria-hidden="true" class="fab fa-github"></i>
                <span class="label">GitHub</span>
                <span class="fake-link">@LovesAsuna</span>
              </a>
            </li>
          </ul>
        </figure>

        <figure class="identities">
          <figcaption><i class="fas fa-external-link-alt"></i>social network</figcaption>
          <ul>
            <li>
              <a href="https://twitter.com/LovesAsuna/">
                <i aria-hidden="true" class="fab fa-twitter"></i>
                <span class="label">Twitter</span>
                <span class="fake-link">@LovesAsuna</span>
              </a>
            </li>
            <li>
              <a href="https://telegram.me/LovesAsuna">
                <i aria-hidden="true" class="fab fa-telegram"></i>
                <span class="label">Telegram</span>
                <span class="fake-link">@LovesAsuna</span>
              </a>
            </li>
            <li>
              <a href="#">
                <i class="fab fa-qq"></i>
                <span class="label">QQ</span>
                <span class="fake-link">625924077</span>
              </a>
            </li>
          </ul>
        </figure>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Me"
}
</script>

<style scoped>
#container .self-desc p {
  border-left: 3px solid #828486;
}

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
<style scoped src="unsemantic/assets/stylesheets/unsemantic-grid-responsive.css"></style>
<style scoped src="@fortawesome/fontawesome-free/css/fontawesome.css"></style>
<style scoped src="@fortawesome/fontawesome-free/css/brands.css"></style>
<style scoped src="@fortawesome/fontawesome-free/css/regular.css"></style>
<style scoped src="@fortawesome/fontawesome-free/css/solid.css"></style>
