<template>
  <b-navbar toggleable="md" type="dark" id="nav-color">
    <b-navbar-brand left to="/" aria-label="Homepage">
      <img id="logo" src="./../../assets/images/logo.png" alt="Website Logo" />
    </b-navbar-brand>
    <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>
    <b-collapse is-nav id="nav_collapse">
      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-navbar-nav right>
          <b-nav-item href="/#AboutMe">About Me</b-nav-item>
          <b-nav-item href="/#Education">Education & Experience</b-nav-item>
          <b-nav-item href="/#Skills">Skills</b-nav-item>
          <b-nav-item href="/#Projects">Projects</b-nav-item>
          <b-nav-item href="/#Contact">Contact</b-nav-item>
          <b-nav-item
            href="https://drive.google.com/open?id=1OG18DXxBKq6timYqfFff27zbGUIf8z1y"
          >Resume</b-nav-item>
        </b-navbar-nav>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>
<script>
export default {
  name: "NavBar"
};
</script>
<style>
#nav-color {
  position: absolute;
  z-index: 100;
  /*background-color: #2b3033;*/
}
#logo {
  height: 2em;
}
</style>
