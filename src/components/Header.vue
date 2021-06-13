<template>
  <div class="section header grid-container grid-parent">
    <div class="split picture-container grid-40">
      <a href="https://cdn.jsdelivr.net/gh/LovesAsuna/blogcdn@stable/gravater.png">
        <picture class="picture">
          <img src="https://cdn.jsdelivr.net/gh/LovesAsuna/blogcdn@stable/gravater.png"
               alt="picture of LovesAsuna"/>
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
                        <i aria-hidden="true" class="fas fa-map-marker-alt"></i>
                        LovesAsunaの小窝 hyosakura.com
                    </span>
      </div>

      <br/>

      <div class="label-group">
        <span class="header">education</span>
        <span class="label">
                        <i aria-hidden="true" class="fas fa-university"></i>
                        undergraduate
                    </span>
      </div>

      <div class="label-group">
        <span class="header">editor</span>
        <span class="label">
                        <i aria-hidden="true" class="fas fa-edit"></i>
                        IntelliJ IDEA
                    </span>
      </div>

      <div class="label-group">
        <span class="header">major</span>
        <span class="label">
                       <i class="fas fa-graduation-cap"></i>
                        computer science
                    </span>
      </div>


      <div class="label-group">
        <span class="header">platforms</span>
        <span class="label">
                        <i aria-hidden="true" class="fab fa-windows"></i>
                        Win10
                    </span>&nbsp;
        <span class="label">
                        <i aria-hidden="true" class="fab fa-centos"></i>
                        Centos7
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
<style scoped src="@fortawesome/fontawesome-free/css/fontawesome.css"></style>
<style scoped src="@fortawesome/fontawesome-free/css/brands.css"></style>
<style scoped src="@fortawesome/fontawesome-free/css/regular.css"></style>
<style scoped src="@fortawesome/fontawesome-free/css/solid.css"></style>
<style scoped src="../assets/css/header.css"></style>
<style scoped src="../assets/css/labels.css"></style>
<style scoped src="unsemantic/assets/stylesheets/unsemantic-grid-responsive.css"></style>

