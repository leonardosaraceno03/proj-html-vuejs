<template>
  <div class="d-flex">
    <div class="red-circle">
      <img
        class="filter-white"
        :src="require(`../assets/img/${card.image}`)"
        alt=""
      />
    </div>
    <div class="card-consulting">
      <div></div>
      <h2>{{ card.title }}</h2>
      <p>{{ card.p }}</p>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    card: Object,
  },
};
</script>

<style>
.white {
  color: white;
}
.filter-white {
  filter: invert(100%);
  width: 40px;
}
.card-consulting {
  padding-top: 100px;
  width: 40%;
}
p {
  display: flex;
  flex-wrap: wrap;
  width: 300px;
}
.red-circle {
  width: 60px;
  height: 60px;
  background: red;
  border-radius: 50%;
  margin-top: 120px;
  margin-right: 30px;

  display: flex;
  justify-content: space-around;
}
.d-flex {
  display: flex;
}
</style>