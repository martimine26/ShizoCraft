<template>
    <section>
    <div class="container">
        <div class="block">
            <img src="/newIcon.svg" class="logo">
            <div class="phantom"></div>
            <div class="phantom"></div>
            <a href="/login" class="login">Войти</a>
        </div>
    </div>
    </section>
</template>

<style scoped>
.block{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
    background-color: #638ebd;
    width: 90%;
    padding: 5% 10px;
    max-height: 100px;
    margin-top: 20px;
    border-radius: 20px;
}
.container{
    display: flex;
    justify-content: center;
}
.login{
    color: #ffffff;
    text-decoration: none;
    font-size: 8px;
}
.phantom{
    width: 200px;
}
.logo{
    color:white;
    text-decoration: none;
    max-width: 200px;
    min-width: 100px;
}
@media (min-width: 320px) {
  .login{ font-size: calc( 3.125vw + 8px ); }
}

@media (min-width: 960px) {
  .login{ font-size: 27px; }
}
</style>