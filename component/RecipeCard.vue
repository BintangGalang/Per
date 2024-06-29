<template>
    <div class="card">
      <img src="https://via.placeholder.com/200x150" alt="Recipe Image" />
      <div class="card-content">
        <h3>Balado Kentang Udang Baso</h3>
        <p>Inspirasi resep mudah cepat dan enak, bahannya selalu sedia didapur tinggal di mix & max aja ala emak2 remp...</p>
        <button>Simpan</button>
      </div>
    </div>
  </template>
  
  <script>
  export default {};
  </script>
  
  <style scoped>
  .card {
    border: 1px solid #ccc;
    border-radius: 5px;
    overflow: hidden;
  }
  
  .card img {
    width: 100%;
    height: auto;
  }
  
  .card-content {
    padding: 1rem;
  }
  
  .card-content h3 {
    margin-bottom: 0.5rem;
  }
  
  .card-content p {
    margin-bottom: 1rem;
  }
  
  .card-content button {
    background-color: #f0ad4e;
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    border-radius: 5px;
    cursor: pointer;
  }
  </style>
  