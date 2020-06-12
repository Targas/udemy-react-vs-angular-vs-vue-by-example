<template>
  <div id="app">
    <nav class="navbar" role="navigation">
      <div class="container">
        <div class="navbar-brand">
          <router-link to="/">
            <img src="http://pr8.com.br/targas/images/profile.jpg" class="logo">
          </router-link>

          <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false">
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
          </a>
        </div>

        <div id="navbarBasicExample" class="navbar-menu">
          <div class="navbar-end">
            <div class="navbar-start">
              <router-link to="/about" class="navbar-item r-item">About</router-link>
              <router-link to="/faq" class="navbar-item r-item">Faq</router-link>
              <router-link to="/features" class="navbar-item r-item">Features</router-link>
            </div>
            
              <div class="navbar-item">
              <div class="buttons">
                <a class="button is-primary">
                  <strong>
                    <i class="fa fa-sign-in"></i>
                    Join now
                  </strong>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </nav>

    <router-view/>
  </div>
</template>

<style lang="scss">
@import '../node_modules/bulma/bulma.sass';
@import 'mq';

.logo {
  width: 50px;
  height: 50px;
}
.navbar {
  background-color: #383838;
}
.navbar-item {
  color: #FFFFFF;
  padding: 0 10px;
}
</style>
