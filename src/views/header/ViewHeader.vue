<style lang="css">
@import 'ViewHeader.css';
</style>
<template>
  <div class="header-tabs">
    <div class="main-logo">
      <img alt="Vue logo" class="logo" src="../../assets/logo.svg" />
    </div>

    <div class="content-items">
      <ul>
        <li><a href="#" target="_blank"> FOREX </a></li>
        <li><a href="#" target="_blank"> ACCIONES </a></li>
        <li><a href="#" target="_blank"> FUTUROS </a></li>
        <li><a href="#" target="_blank"> TradeGATEHub </a></li>
      </ul>
    </div>

    <div class="navbar">
      <div class="login-selector">
        <div class="custom-select">
          <div class="selected">
            <div class="selected-container">
              <div class="selected-content">
                <div class="selected-col">
                  <div class="selected-row">
                    <div class="row-label">Login</div>
                  </div>
                </div>
                <div class="row-r-icon"></div>
              </div>
              <div class="selected-icon"></div>
            </div>
          </div>
          <div class="items items-border" style="display: none">
            <div class="triangle-up"></div>
            <div class="placeholder placeholder-div">Seleccione su plataforma</div>
            <div class="row">
              <div id="0" class="row row-label">
                <p class="title">
                  <a href="/" class="nuxt-link-active">Metatrade 4</a>
                </p>
              </div>
            </div>
            <div class="row">
              <div id="1" class="row row-label">
                <p class="title">
                  <a href="/" class="nuxt-link-active">Metatrade 5</a>
                </p>
              </div>
            </div>
            <div class="row">
              <div id="2" class="row row-label">
                <p class="title">
                  <a href="/" class="nuxt-link-active">cTrader</a>
                </p>
              </div>
            </div>
            <div class="row">
              <div id="3" class="row row-label">
                <p class="title">
                  <a href="/" class="nuxt-link-active">CurrenX</a>
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="pipe"></div>
      <a href="#" class="">Contacto</a>
      <div class="language-selector">
        <div class="custom-select">
          <div class="selected">
            <div class="selected-container">
              <div class="selected-content">
                <div class="selected-col">
                  <div class="selected-row">
                    <div class="row-icon">
                      <img src="" alt="" />
                    </div>
                    <div class="row-label">Español</div>
                  </div>
                </div>
                <div class="row-r-icon"></div>
              </div>
              <div class="selected-icon"></div>
            </div>
          </div>
          <div class="items items-border" style="display: none">
            <div class="triangle-up"></div>
            <div class="placeholder placeholder-div">Seleccione su idioma</div>
            <div class="row">
              <div class="row-icon">
                <img src="" alt="" />
              </div>
              <div id="0" class="row row-label">
                <p class="title">
                  <a
                    data-v-bd42e612=""
                    href="/es/"
                    aria-current="page"
                    class="nuxt-link-exact-active nuxt-link-active"
                    >English</a
                  >
                </p>
              </div>
            </div>
            <div class="row">
              <div class="row-icon">
                <img src="" alt="" />
              </div>
              <div id="1" class="row row-label">
                <p class="title">
                  <a
                    data-v-bd42e612=""
                    href="/es/"
                    aria-current="page"
                    class="nuxt-link-exact-active nuxt-link-active"
                    >Español</a
                  >
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div id="top-home" class="header-mobile">
    <div class="main-logo">
      <img src="../../assets/logo.svg" alt="" />
    </div>
    <div class="main-icon">
      <img
        src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA0NiAzMCI+PGRlZnM+PHN0eWxlPi5jbHMtMXtmaWxsOiNmZmY7fTwvc3R5bGU+PC9kZWZzPjx0aXRsZT5pY29uX21lbnU8L3RpdGxlPjxnIGlkPSJMYXllcl8yIiBkYXRhLW5hbWU9IkxheWVyIDIiPjxwYXRoIGNsYXNzPSJjbHMtMSIgZD0iTTQzLjUsNUgyLjVhMi41LDIuNSwwLDAsMSwwLTVoNDFhMi41LDIuNSwwLDAsMSwwLDVaIi8+PHBhdGggY2xhc3M9ImNscy0xIiBkPSJNNDMuNSwxNy41SDIuNWEyLjUsMi41LDAsMCwxLDAtNWg0MWEyLjUsMi41LDAsMCwxLDAsNVoiLz48cGF0aCBjbGFzcz0iY2xzLTEiIGQ9Ik00My41LDMwSDIuNWEyLjUsMi41LDAsMCwxLDAtNWg0MWEyLjUsMi41LDAsMCwxLDAsNVoiLz48L2c+PC9zdmc+"
        alt=""
      />
    </div>
  </div>
</template>
<script setup lang="ts"></script>
