<template>
  <div>
    <Navbar/>
    <div class="container">
      <div class="container_row">
        <div class="block_help">
          <p class="help_text">Если у вас есть какие-то вопросы по регистрации или 
            по тому как пользоваться электронным кошельком.Пишите сюда 
            <a href="https://vk.com/marimine26"><img src="/vk.svg" width="30px"></a>
          </p>     
        </div>
          <div class="block_news">
            <h3>Новости</h3>
            <br>
            <p>
              <b>Новая ферма золота</b>
              <br>
              EvgenSv построил одну из самых 
              прибыльных ферм золота от insurgento
            </p>
            <p>
              <b>Дороги в шпиндахляндии</b>
              <br>
              Наконец-то нормальные дороги...
            </p>
          </div>
        </div>
        <a href="" class="server">
            <p class="server_text">Купить проходку</p>
        </a>
      </div>
    </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'

export default {
  components: {
    Navbar,
  },
}
</script>

<style scoped>
.container{
  display: flex;
  justify-content: center;
  flex-direction: column;
  margin-top: 30px;
  max-width: 1200px;
  height: 100%;
  width: 75%;
}
.container_row{
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.block_help{
  min-width: 200px;
  max-width: 400px;
  padding: 10px 20px;
  padding-top: 10px;
  background-color: #638ebd;
  border-radius: 20px;
}
.server_text{
  padding-top: 10px;
  text-decoration: none;
}
.block_news{
  margin-left: 20px;
  position: relative;
  width: 100%;
  padding: 0px 10px;
  padding-top: 10px;
  background-color: #638ebd;
  color: white;
  border-radius: 20px;
  max-width: 800px;
}
.help_text{
  color:white;
  font-size: 10px;
}
.slider{
  position: relative;
  width: 100%;
  height: 100%;
}
.server{
  min-width: 200px;
  max-width: 400px;
  display: flex;
  color:white;
  justify-content: center;
  align-items: center;
  background-color: #638ebd;
  border-radius: 20px;
  min-height: 80px;
  margin-top: -80px;
  text-decoration: none;
  transition: 1s;
}
.server:hover{
  box-shadow: 3px 5px 5px 3px #719ac6;
  margin-top: -83px;
  margin-left: -3px;
  transition: 1s;
}
h3{
  padding: 10px 10px;
  margin-bottom: -20px;
}
@media (min-width: 320px) {
  .help_text{ font-size: calc( 3.125vw + 8px );}
  p{font-size: calc( 3.125vw + 8px );}

}
@media (max-width: 960px) {
  .container_row{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.block_news{
  margin-top: 20px;
   min-width: 200px;
   margin-left: -5px;
}
.server{
  margin-top: 20px;
}
}
@media (min-width: 960px) {
  .help_text{ font-size: 20px; }
  p{ font-size: 20px; }
  .block_help{max-height: 145px;}
}
</style>