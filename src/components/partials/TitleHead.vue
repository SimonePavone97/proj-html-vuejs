<template>

  <div class="padd text-white">
    <h3>Hungry?</h3>
    <div>
      <p>
        <font color="#fcdc31">great food</font> <br> delivered <br>
        <button type="button" class="btn btn-danger text-uppercase">view our menu <i class="fa-solid fa-arrow-right"></i></button>
      </p>
    </div>

  </div>

</template>



<script>
  export default {
    name: 'TitleHead',
  }
</script>



<style scoped lang="scss">
  .padd {
    padding-top: 310px;
    padding-bottom: 310px;
  }

  p{
    font-size: 5em;
  }

</style>