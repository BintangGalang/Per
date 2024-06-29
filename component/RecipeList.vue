<template>
    <div>
      <h2 class="list-title">Rekomendasi Resep</h2>
      <ul class="recipe-list">
        <li v-for="recipe in recipes" :key="recipe.id">
          <a :href="recipe.link">
            <img :src="recipe.image" alt="Resep: {{ recipe.title }}" />
            <h3>{{ recipe.title }}</h3>
          </a>
        </li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        recipes: [
          {
            id: 1,
            title: 'Balado Kentang Udang Baso',
            image: 'https://via.placeholder.com/300x200',
            link: '/recipe/1',
          },
          // Tambahkan resep lainnya di sini
        ],
      };
    },
  };
  </script>
  
  <style scoped>
  .list-title {
    font-size: 1.5rem;
    margin-bottom: 1rem;
  }
  
  .recipe-list {
    list-style: none;
    padding: 0;
  }
  
  .recipe-list li {
    margin-bottom: 1rem;
  }
  
  .recipe-list img {
    width: 100%;
    height: auto;
    border-radius: 5px;
  }
  </style>
  