<template>
  <div class="cell-phone">
    <img src="../assets/cellphone.png" alt="celular" />
  </div>
</template>

<script>
export default {
  name: "CellPhone",
};
</script>

<style>
.cell-phone {
  display: flex;
  align-items: center;
  justify-items: center;
  padding: 3rem;
}
.cell-phone img {
  display: flex;
  height: 60vh;
}

@media (max-width: 700px) {
    .cell-phone{
        display: none;
    }
}
</style>