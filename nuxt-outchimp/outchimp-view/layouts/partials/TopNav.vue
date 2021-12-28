<template>
  <div>
    <b-navbar type="dark" variant="dark">
      <div class="container">
        <b-navbar-nav>
          <!--        <b-nav-item href="#">Home</b-nav-item>-->
          <nuxt-link class="navbar-brand" to="/">Home</nuxt-link>
          <nuxt-link class="navbar-brand" to="/dashboard">Dashboard</nuxt-link>
        </b-navbar-nav>
        <b-navbar-nav class="ml-auto">
         <li class="nav-item">
           <nuxt-link class="navbar-brand" to="/">Login</nuxt-link>
         </li>
          <li class="nav-item">
            <nuxt-link class="navbar-brand" to="/auth/register">Register</nuxt-link>
         </li>
        </b-navbar-nav>
      </div>
    </b-navbar>
  </div>
</template>
