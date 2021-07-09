<template id="navBar">
    <div>
  <b-navbar toggleable="lg" type="dark" variant="success">
    <b-navbar-brand class="navbar-header" href="#">7 Wonders Of Oregon</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="#">Compare</b-nav-item>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-item-dropdown text="Locations" right>
          <b-dropdown-item href="#">Columbia River Gorge</b-dropdown-item>
          <b-dropdown-item href="#">Crater Lake</b-dropdown-item>
          <b-dropdown-item href="#">Painted Hills</b-dropdown-item>
          <b-dropdown-item href="#">Oregon Coast</b-dropdown-item>
          <b-dropdown-item href="#">Smith Rock</b-dropdown-item>
          <b-dropdown-item href="#">The Wallowas</b-dropdown-item>
          <b-dropdown-item href="#">Mt. Hood</b-dropdown-item>
      </b-nav-item-dropdown>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>
<script>
export default {
  name: 'Navbar',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
  outline: none;
}

.navbar-header {
  margin-left: 2%;
}

</style>
