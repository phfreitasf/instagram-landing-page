<template>
  <div class="login-instagram">
    <img src="../assets/instagram.png" class="logo" />
    <img src="../assets/pedro.jpg" class="profile-pic" />
    <a href="#" class="btn-continue">Continuar como phfreitasf</a>
    <div class="change-acc">
      <p>Não é phfreitasf?</p>
      <p class="blue-text">Trocar de conta</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "LoginDiv",
};
</script>

<style>
.login-instagram {
  background-color: white;
  border: 2px solid rgba(0, 0, 0, 0.15);
  display: flex;
  flex-direction: column;
  align-content: space-around;
  align-items: center;
  padding: 2rem 2rem;
}

.login-instagram * {
    margin: 10px;
}
.profile-pic {
  border-radius: 50%;
  overflow: none;
  width: 50%;
  height: 50%;
}

.btn-continue {
  font-weight: bolder;
  color: white;
  text-align: center;
  background-color: #0095f6;
  border-radius: 4px;
  padding: 0.5rem;
  width: 18rem;
}

.change-acc {
  display: flex;
  flex-direction: row;
}
.blue-text {
  color: #699bf6;
  font-weight: bold;
  margin-left: 0px;
  cursor: pointer;
}

@media (max-width: 700px) {
    .login-instagram{
        border: none;
        background-color: rgb(228, 228, 228);
        margin: auto;
    }
}

</style>