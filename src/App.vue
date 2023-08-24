<template>
  <div id="q-app">
    <router-view />
  </div>
</template>
<script>
export default {
  name: "App"
};
</script>

<style lang="scss">
:root {
  --blue_low: #00cfe8;
  --blue: #007bff;
  --indigo: #6610f2;
  --purple: #7367f0;
  --pink: #e83e8c;
  --red: #ea5455;
  --orange: #ff9f43;
  --yellow: #ffc107;
  --green: #28c76f;
  --teal: #20c997;
  --cyan: #17a2b8;
  --white: #fff;
  --gray: #b8c2cc;
  --gray-dark: #1e1e1e;
  --primary: rgb(61, 187, 245);
  --secondary: #82868b;
  --success: #28c76f;
  --info: #00cfe8;
  --warning: #ff9f43;
  --danger: #ea5455;
  --light: #f6f6f6;
  --dark: #4b4b4b;
  --dark_RGB: 75, 75, 75;
  --dark80: rgba(var(--dark_RGB), 0.8);
  --dark60: rgba(var(--dark_RGB), 0.6);
  --mainColor: #eee;
  --black: #000000;

  --font-family-sans-serif: "Montserrat", Helvetica, Arial, serif;
  --font-family-monospace: "Montserrat", Helvetica, Arial, serif;
}

html,
#app,
body {
  // font-family: 'Roboto', sans-serif;
  // font-family: sans-serif;
  font-family: "Montserrat", Helvetica, Arial, serif;
  padding: 0;
  margin: 0;
  // background: #F9F9F9;
  background: var(--mainColor);
}

#app,
html,
body {
  height: 100%;
}

.nice-boxshadow {
  -moz-box-shadow: 0px 1px 5px 0px #676767;
  -webkit-box-shadow: 0px 1px 5px 0px #676767;
  box-shadow: 0px 1px 5px 0px #676767;
}

.apple-boxshadow {
  -webkit-box-shadow: rgba(0, 0, 0, 0.3) 0 1px 3px;
  -moz-box-shadow: rgba(0, 0, 0, 0.3) 0 1px 3px;
  box-shadow: rgba(0, 0, 0, 0.3) 0 1px 8px;
}

.apple-box {
  padding: 20px;
  border-radius: 5px;
  -webkit-box-shadow: rgba(0, 0, 0, 0.3) 0 1px 3px;
  -moz-box-shadow: rgba(0, 0, 0, 0.3) 0 1px 3px;
  box-shadow: rgba(0, 0, 0, 0.3) 0 1px 3px;
}

.border-radius-5 {
  border-radius: 5px;
}

.image-box-shadow {
  box-shadow: rgba(0, 0, 0, 0.07) 0px 1px 2px, rgba(0, 0, 0, 0.07) 0px 2px 4px,
    rgba(0, 0, 0, 0.07) 0px 4px 8px, rgba(0, 0, 0, 0.07) 0px 8px 16px,
    rgba(0, 0, 0, 0.07) 0px 16px 32px, rgba(0, 0, 0, 0.07) 0px 32px 64px;
}
</style>
