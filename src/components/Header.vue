<template>
  <div class="section header grid-container grid-parent">
    <div class="split picture-container grid-40">
      <a href="https://cdn.jsdelivr.net/gh/LovesAsuna/blogcdn@stable/gravater.png">
        <picture class="picture">
          <img alt="picture of LovesAsuna"
               src="https://cdn.jsdelivr.net/gh/LovesAsuna/blogcdn@stable/gravater.png"/>
        </picture>
      </a>
    </div>

    <div class="split grid-60">
      <div class="names">
        <h1 class="name">
                        <span class="no-wrap">
                            LovesAsuna
                        </span>
        </h1>
      </div>

      <div class="label-group">
        <span class="header">Home</span>
        <span class="label">
                        <i><font-awesome-icon icon="fa-solid fa-location-dot"/></i>
                        LovesAsunaの小窝 hyosakura.com
                    </span>
      </div>

      <br/>

      <div class="label-group">
        <span class="header">education</span>
        <span class="label">
                        <i><font-awesome-icon icon="fa-solid fa-building-columns"/></i>
                        undergraduate
                    </span>
      </div>

      <div class="label-group">
        <span class="header">editor</span>
        <span class="label">
                        <i><font-awesome-icon icon="fa-solid fa-pen-to-square"/></i>
                        IntelliJ IDEA
                    </span>
      </div>

      <div class="label-group">
        <span class="header">major</span>
        <span class="label">
                       <i><font-awesome-icon icon="fa-solid fa-graduation-cap"/></i>
                        computer science
                    </span>
      </div>


      <div class="label-group">
        <span class="header">platforms</span>
        <span class="label">
                       <i><font-awesome-icon icon="fa-brands fa-windows"/></i>
                        Win11
                    </span>&nbsp;
        <span class="label">
                       <i><font-awesome-icon icon="fa-brands fa-ubuntu"/></i>
                        Debian
                    </span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
#container > .header span.label {
  background-color: #55474a;
  color: white;
}

#container .no-wrap {
  display: inline-block;
}
</style>
<style scoped src="../assets/css/header.css"></style>
<style scoped src="../assets/css/labels.css"></style>
<style scoped src="unsemantic/assets/stylesheets/unsemantic-grid-responsive.css"></style>

