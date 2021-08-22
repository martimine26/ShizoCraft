<template>
  <section>
    <form>
      <p>Login </p>
      <div class="form-group">
        <input type="text" class="form-control">

      </div>
      <p>Password </p>
       <div class="form-group">
        <input type="text" class="form-control">
      </div>
      <p>
        <nuxt-link to="/" style="font-size:20px;color:black;">To home page</nuxt-link>
      </p>

      <button type="button" class="btn btn-primary">Invite!</button>
    </form>
  </section>
</template>

<script>

</script>


<style scoped>
form {
  padding-top: 100px;
  width: 500px;
  margin: 0 auto;
}
p{
    color:#1D72D4;
    font-size: 30px;
}
.btn{
    width: 100px;
}
</style>