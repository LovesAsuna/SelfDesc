<template>
  <div class="section intro">
    <h2><i>
      <font-awesome-icon icon="fa-solid fa-chevron-right"/>
    </i> Me
    </h2>

    <div class="block grid-container grid-parent">
      <div class="split grid-50 mobile-grid-100">
        <div class="self-desc">
          <slot></slot>
        </div>
      </div>

      <div class="split grid-50 mobile-grid-100">
        <figure class="identities">
          <figcaption><i>
            <font-awesome-icon icon="fa-solid fa-up-right-from-square"/>
          </i> open-source
          </figcaption>
          <ul>
            <li>
              <a href="https://github.com/LovesAsuna/">
                <i>
                  <font-awesome-icon icon="fa-brands fa-github"/>
                </i>
                <span class="label">GitHub</span>
                <span class="fake-link">@LovesAsuna</span>
              </a>
            </li>
          </ul>
        </figure>

        <figure class="identities">
          <figcaption><i>
            <font-awesome-icon icon="fa-solid fa-up-right-from-square"/>
          </i> social network
          </figcaption>
          <ul>
            <li>
              <a href="https://twitter.com/LovesAsuna/">
                <i>
                  <font-awesome-icon icon="fa-brands fa-twitter"/>
                </i>
                <span class="label">Twitter</span>
                <span class="fake-link">@LovesAsuna</span>
              </a>
            </li>
            <li>
              <a href="https://telegram.me/LovesAsuna">
                <i>
                  <font-awesome-icon icon="fa-brands fa-telegram"/>
                </i>
                <span class="label">Telegram</span>
                <span class="fake-link">@LovesAsuna</span>
              </a>
            </li>
            <li>
              <a href="#">
                <i>
                  <font-awesome-icon icon="fa-brands fa-qq"/>
                </i>
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
#container .self-desc :deep(p) {
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

  #container .intro :deep(p) {
    border-left: none;
    padding: 0.2em;
  }
}
</style>
<style scoped src="../assets/css/intro.css"></style>
<style scoped src="../assets/css/identities.css"></style>
<style scoped src="unsemantic/assets/stylesheets/unsemantic-grid-responsive.css"></style>
