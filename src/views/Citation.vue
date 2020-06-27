<template>
  <div class="citation-container">
    <div class="citation">
      <p>« Когда справедливость исчезает, то не остается ничего, что могло бы придать ценность жизни людей »</p>
      <p>Иммануил Кант</p>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Citation',
  components: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/style/basic-style.scss";

.citation{
  border: 1px solid $color3;
  border-radius: 10px;
  width: fit-content;
  float: right;
  padding: 30px;
  margin: 80px 0 150px 0;
}
p{
  direction: rtl;  
  // font-size: 18px;
  font-style: italic;
}
</style>
