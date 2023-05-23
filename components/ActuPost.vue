<template>
    <div class="NewsPost" style="width: 20vw;">
      <div class="ActuCover">
        <img id="previewImage" :src="coverImage" alt="">
      </div>
      <h4 id="previewTitle" class="ActuTitle">{{ title }}</h4>
      <p id="previewText" class="PostText">{{ text }}</p>
    </div>
  </template>
  
  <script>
  export default {
    name: "ActuPost",
    props: {
      coverImage: {
        type: String,
        default: "assets/imgs/imgs/CouvertureNews40ans.webp",
      },
      title: {
        type: String,
        default: "",
      },
      text: {
        type: String,
        default: "",
      },
    },
  };
  </script>
  
  <style scoped>
  .NewsPost {
    width: 20vw;
  }
  </style>
  