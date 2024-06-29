<template>
  <div class="container">
    <div class="content">
      <h1 class="title">Aplikasi andalan untuk masakan harianmu</h1>
      <RecipeList />
    </div>
    <div class="sidebar">
      <RecipeCard />
    </div>
  </div>
</template>

<script>
import RecipeList from '~/components/RecipeList.vue';
import RecipeCard from '~/components/RecipeCard.vue';

export default {
  components: {
    RecipeList,
    RecipeCard,
  },
};
</script>

<style scoped>
.container {
  display: flex;
  justify-content: space-between;
}

.content {
  width: 60%;
  padding: 2rem;
}

.sidebar {
  width: 30%;
  padding: 2rem;
}

.title {
  font-size: 2.5rem;
  font-weight: bold;
  margin-bottom: 2rem;
}
</style>
