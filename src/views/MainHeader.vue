<template>
 <div class="main-header flex space-between align-items-center">
  <nav class="main-nav flex align-items-center space-between">
    <ul class="flex nav-items">
      <li><a href="#main" class="nav-item">Главная</a></li>
      <li><a href="#about" class="nav-item">О нас</a></li>
      <li><a href="#fields" class="nav-item">Юридические услуги</a></li>
      <li><a href="#contact" class="nav-item">Контакты</a></li>
    </ul>
  
    <div class="contacts">
      <a href="#contact" class="nav-item">
        <span>054-7504999 </span>
        <i class="fas fa-phone"></i>
      </a>
      <div class="name">Адвокат Евгений Колт</div>
    </div>
  </nav>


 </div>
</template>

<script>
export default {
  name: 'MainHeader',
  components: {

  },
  methods: {
   
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/style/basic-style.scss";
.main-header{
  // height: 100px;
  padding: 30px 60px;
  background-color: $color1;
  position: sticky;
  top: 0;
  // background-image: url(../assets/hammer.jpg);
}

.main-nav{
  width: 1100px;
  margin: auto;
  padding: 0 60px;
  color: $color2;
}

ul{
  padding: 0;
}

li{
  padding-right: 30px;
}

.nav-item{
  text-decoration: none;
  // font-size: 22px;
  // letter-spacing: 2px;
  color: $color2;
}

.nav-item:hover{
  border-bottom: 1px solid red;
  padding-bottom: 8px;
}

.contacts{
  // font-size: 22px;
  // letter-spacing: 2px;
}


 
</style>
