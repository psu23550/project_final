<template>
  <div class="content">
    <q-layout view="hHh lpR fFf">
      <!-- <q-header elevated class="header bg-teal-6 text-black"> -->
      <q-header elevated class="header text-black">
        <q-toolbar>
          <q-btn dense flat round icon="menu" @click="left = !left" />
          <q-toolbar-title class="row header__content">
            <div class="flex-1 q-ma-none title-header">
              <p class="title q-ma-none">
                Smart AI Teaching for Nursing care of Midwifery
              </p>
            </div>
            <router-link to="/"
              ><img class="photo" src="~assets/logo.jpg"
            /></router-link>
          </q-toolbar-title>
        </q-toolbar>
      </q-header>

      <!-- <q-drawer content-class="bg-teal-2 drawer text-white" show-if-above v-model="left" side="left" bordered> -->
      <q-drawer
        content-class="sidebar-layout drawer text-white"
        show-if-above
        v-model="left"
        side="left"
        bordered
      >
        <div class="column">
          <div class="q-pa-lg"></div>
          <q-btn color="" class="btn-router">
            <router-link
              to="/1"
              class="text-right"
              :class="{ 'btn-router-active': $route.path === '/1' }"
              >ความผูกพันธ์กับบุตร</router-link
            >
          </q-btn>
          <!-- <q-btn color="secondary"> -->
          <q-btn color="" class="btn-router">
            <router-link
              to="/2"
              class="text-right"
              :class="{ 'btn-router-active': $route.path === '/2' }"
              >การเลี้ยงลูกด้วยนมคุณเเม่</router-link
            >
          </q-btn>
          <q-btn color="" class="btn-router">
            <router-link
              to="/3"
              class="text-right"
              :class="{ 'btn-router-active': $route.path === '/3' }"
              >การอุ้มบุตร</router-link
            >
          </q-btn>
          <q-btn color="" class="btn-router">
            <router-link
              to="/4"
              class="text-right"
              :class="{ 'btn-router-active': $route.path === '/4' }"
              >การอาบน้ำบุตร</router-link
            >
          </q-btn>
          <q-btn color="" class="btn-router">
            <router-link
              to="/5"
              class="text-right"
              :class="{ 'btn-router-active': $route.path === '/5' }"
              >การดูเเลสะดือเเละการทำความสะอาดสะดื้อ</router-link
            >
          </q-btn>
          <q-btn color="" class="btn-router">
            <router-link
              to="/6"
              class="text-right"
              :class="{ 'btn-router-active': $route.path === '/6' }"
              >การดูเเลการขับถ่าย</router-link
            >
          </q-btn>
          <q-btn color="" class="btn-router">
            <router-link
              to="/7"
              class="text-right"
              :class="{ 'btn-router-active': $route.path === '/7' }"
              >อาการผิดปกติของบุตร</router-link
            >
          </q-btn>

          <q-btn color="" class="btn-router">
            <router-link
              to="/9"
              class="text-right"
              :class="{ 'btn-router-active': $route.path === '/9' }"
              >แบบทดสอบ</router-link
            >
          </q-btn>

          <div class="Barcode">
            <img src="~/assets/barcode.jpg" width="120px" height="120px" />
          </div>
        </div>
      </q-drawer>
      <q-page-container>
        <router-view />
      </q-page-container>
    </q-layout>
  </div>
</template>

<script>
export default {
  methods: {
    onItemClick() {
      // console.log('Clicked on an Item')
    }
  },
  data() {
    return {
      left: false
    };
  }
};
</script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Prompt:wght@500&display=swap");

.header {
  height: 80px;
  background: linear-gradient(to top, #0ba360 0%, #3cba92 100%);
}

.header__content {
  justify-content: center;
  align-items: center;
}

.font-sans {
  font-family: "Prompt", sans-serif;
}

.photo {
  width: 50px;
  height: 50px;
  margin-top: 15px;
}

.title {
  font-family: "Prompt", sans-serif;
  font-size: 1.7rem;
  color: midnightblue;
  // margin-top: 20px;
  // margin-left: 10px;
}

.title-header {
  width: 50%;
  text-align: center;
}

.drawer {
  background-color: aqua;
}

.content {
  width: 100%;
  height: 100%;
  /* background-image: url("~assets/download.jpg"); */
}

.btn1 {
  display: flex;
  justify-content: flex-start;
}

.d {
  text-align: center;
  text-decoration: none;
  color: white;
  margin-top: 10px;
}

.a {
  width: 100%;
  display: flex;
  justify-content: center;
  font-family: "Prompt", sans-serif !important;
}

.text-right {
  text-align: center;
  text-decoration: none;
  color: darkgray;
  padding-bottom: 5px;
  font-family: "Prompt", sans-serif !important;
}

.column {
  margin-left: 10px;
  margin-right: 10px;
  margin-top: -20px;
}

.q-link {
  text-align: center;
}

.cursor-pointer {
  text-align: center;
}

.q-btn {
  margin: 5px;
}

.drawer {
  position: fixed;
}

.Barcode {
  margin-top: 20px;
  margin-left: 80px;
}
.Barcode > img {
  box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px,
    rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px,
    rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
}

.btn-router {
  background: linear-gradient(
    94.5deg,
    rgb(255, 235, 104) -1.2%,
    rgb(61, 247, 255) 119.2%
  );
  border-radius: 15px;

  // &:hover {
  //   color: darkslategray !important;
  // }
}
.btn-router > span > span > a {
  padding: 0 10px;
  border-radius: 15px;

  &:hover {
    color: darkslategray !important;
  }
}
.btn-router-active {
  padding: 0 10px;
  border-radius: 15px;
  background: linear-gradient(
    94.5deg,
    rgb(255, 235, 104) -1.2%,
    rgb(61, 247, 255) 119.2%
  );
  color: darkslategray !important;
}
.flex-1 {
  flex: 1;
}
</style>

<style>
.sidebar-layout {
  /* background: linear-gradient(120deg, #d4fc79 0%, #96e6a1 100%); */
  background: linear-gradient(
    179.1deg,
    rgb(43, 170, 96) 2.3%,
    rgb(129, 204, 104) 98.3%
  ) !important;
}
</style>
