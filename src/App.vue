<template>
  <div class="main">
    <cell-phone />
    <login-div />
  </div>
</template>

<script>
import CellPhone from "./components/CellPhone.vue";
import LoginDiv from "./components/LoginDiv.vue";
export default {
  name: "App",
  components: {
    CellPhone,
    LoginDiv,
  },
};
</script>

<style>
* {
  margin: 0;
  box-sizing: border-box;
  padding: 0;
  font-size: 14px;
  font-family: sans-serif;
  text-decoration: none;
}

body {
  min-height: 100vh;
  background-color: rgb(228, 228, 228);
  display: flex;
  justify-content: center;
  align-items: center;
}

.main {
  width: 100%;
  display: flex;
  align-items: center;
  justify-items: center;
  justify-content: center;
}

@media (max-width: 700px) {
 
}
</style>
