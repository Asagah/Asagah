<template>
  <div class="login-container">
    <navbar-interactive
      rootClassName="navbar-interactive-root-class-name1"
    ></navbar-interactive>
    <div class="login-container1">
      <div class="login-container2">
        <div class="login-container3">
          <app-back></app-back>
          <span class="login-text">
            <span>Lo</span>
            <span class="login-text02">g</span>
            <span>in</span>
          </span>
          <div class="login-container4">
            <span class="login-text04">
              <span>
                -User
                <span v-html="rawxbfx"></span>
              </span>
              <span class="login-text06">Name</span>
            </span>
            <input
              type="text"
              required
              placeholder="Your name"
              class="login-textinput input"
            />
            <span class="login-text07">-Password</span>
            <input
              type="password"
              required
              placeholder="Your password"
              class="login-textinput1 input"
            />
            <button class="login-find button">
              <span>
                <span class="login-text09">Continue</span>
                <br />
              </span>
            </button>
          </div>
        </div>
      </div>
    </div>
    <app-footer rootClassName="footer-root-class-name1"></app-footer>
  </div>
</template>

<script>
import NavbarInteractive from '../components/navbar-interactive.vue'
import AppBack from '../components/back.vue'
import AppFooter from '../components/footer.vue'

export default {
  name: 'Login',
  components: {
    NavbarInteractive,
    AppBack,
    AppFooter,
  },
  data() {
    return {
      rawxbfx: ' ',
    }
  },
  metaInfo: {
    title: 'Login - Dependable Secret Vulture',
    meta: [
      {
        property: 'og:title',
        content: 'Login - Dependable Secret Vulture',
      },
    ],
  },
}
</script>

<style scoped>
.login-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.login-container1 {
  width: 100%;
  height: 567px;
  display: flex;
  align-items: center;
  flex-direction: column;
  background-size: cover;
  justify-content: flex-start;
  background-image: url('https://post.healthline.com/wp-content/uploads/2020/11/834360-Best-Babysitting-websites-and-Apps-1200x628-Facebook-1200x628.jpg');
  background-repeat: no-repeat;
  background-position: center;
}
.login-container2 {
  width: 100%;
  height: 576px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: rgba(0, 0, 0, 0.36);
}
.login-container3 {
  flex: 0 0 auto;
  width: 662px;
  height: 466px;
  display: flex;
  box-shadow: 5px 5px 10px 0px #d4d4d4;
  align-items: center;
  border-radius: var(--dl-radius-radius-radius8);
  flex-direction: column;
  justify-content: flex-start;
  background-color: #ffffff;
}
.login-text {
  font-size: 32px;
  font-style: normal;
  margin-top: 0px;
  font-family: Poppins;
  font-weight: 700;
}
.login-text02 {
  color: #ff4d4f;
}
.login-container4 {
  width: 566px;
  height: 378px;
  display: flex;
  align-self: center;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.login-text04 {
  font-size: 20px;
  margin-top: var(--dl-space-space-twounits);
  font-family: Poppins;
  font-weight: 600;
  margin-left: var(--dl-space-space-halfunit);
}
.login-text06 {
  color: #ff4d4f;
}
.login-textinput {
  width: 554px;
  height: 51px;
  box-shadow: 5px 5px 10px 0px #d4d4d4;
  margin-top: var(--dl-space-space-unit);
  border-width: 0px;
  border-radius: var(--dl-radius-radius-radius8);
}
.login-text07 {
  font-size: 20px;
  margin-top: var(--dl-space-space-oneandhalfunits);
  font-family: Poppins;
  font-weight: 600;
  margin-left: var(--dl-space-space-halfunit);
}
.login-textinput1 {
  width: 555px;
  height: 51px;
  box-shadow: 5px 5px 10px 0px #d4d4d4;
  margin-top: var(--dl-space-space-unit);
  border-width: 0px;
  border-radius: var(--dl-radius-radius-radius8);
}
.login-find {
  color: var(--dl-color-gray-white);
  align-self: center;
  font-style: normal;
  margin-top: var(--dl-space-space-threeunits);
  transition: 0.3s;
  font-weight: 500;
  padding-top: var(--dl-space-space-unit);
  border-width: 0px;
  padding-left: var(--dl-space-space-oneandhalfunits);
  border-radius: 56px;
  padding-right: var(--dl-space-space-oneandhalfunits);
  padding-bottom: var(--dl-space-space-unit);
  background-color: rgb(255, 77, 79);
}
.login-find:hover {
  opacity: 0.5;
}
.login-text09:hover {
  opacity: 0.5;
}
@media(max-width: 991px) {
  .login-text {
    font-size: 32px;
    font-style: normal;
    font-family: Poppins;
    font-weight: 700;
  }
  .login-find {
    width: 139px;
    text-align: center;
    margin-right: 0px;
  }
  .login-text09 {
    width: 139px;
    text-align: center;
    margin-right: 0px;
  }
}
@media(max-width: 767px) {
  .login-text {
    font-size: 32px;
  }
  .login-text02 {
    color: #ff4d4f;
  }
  .login-find {
    width: 137px;
  }
  .login-text09 {
    width: 137px;
  }
}
@media(max-width: 474px) {
  .login-container3 {
    width: 100%;
    height: 490px;
    padding-left: 7%;
    margin-bottom: 0px;
    padding-right: 7%;
  }
  .login-text {
    font-size: 32px;
    font-style: normal;
    font-family: Poppins;
    font-weight: 700;
  }
  .login-text02 {
    color: #ff4d4f;
  }
  .login-container4 {
    width: 100%;
  }
  .login-textinput {
    width: 100%;
  }
  .login-textinput1 {
    width: 100%;
  }
  .login-find {
    margin-top: var(--dl-space-space-oneandhalfunits);
  }
  .login-text09 {
    margin-top: var(--dl-space-space-oneandhalfunits);
  }
}
</style>
