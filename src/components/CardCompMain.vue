<template>
  <div class="card-consulting">
        <div><img :src="`${card.image}`" alt=""></div>
        <h2>{{card.title}}</h2>
        <p>{{card.p}}</p>
        
  </div>
</template>

<script>
export default {
    props:{
    card: Object
  }
}
</script>

<style>
.card-consulting{
    padding-top: 100px;
    width: 40%;
}
p{
  display: flex;
  flex-wrap: wrap;
  width: 400px;
}
</style>