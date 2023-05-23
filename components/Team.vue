<template>
    <div class="NewsPost" style="width: 25vw;">
      <h3>📌 : L'équipe</h3>
      <div class="Grid">
        <div class="Select">
          <img :src="image1" alt="Image de couverture MAES sud">
          <button class="CitySelect"><a href="Lille.php">LILLE</a></button>
        </div>
        <div class="Select">
          <img :src="image2" alt="Image de couverture MAES sud">
          <button class="CitySelect"><a href="Paris.php">PARIS</a></button>
        </div>
        <div class="Select">
          <img :src="image3" alt="Image de couverture MAES sud">
          <button class="CitySelect"><a href="Cannes.php">SUD</a></button>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "TeamPost",
    props: {
      image1: {
        type: String,
        default: "assets/imgs/imgs/CoverParis.jpg",
      },
      image2: {
        type: String,
        default: "assets/imgs/imgs/Conception.jpg",
      },
      image3: {
        type: String,
        default: "assets/imgs/imgs/CoverParis.jpg",
      },
    },
  };
  </script>
  
  <style scoped>
  .NewsPost {
    width: 25vw;
  }
  </style>
  