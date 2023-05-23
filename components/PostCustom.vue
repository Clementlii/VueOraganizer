<template>
    <div class="PostCustom" style="width: 20vw;">
      <div class="tabs">
        <div role="tablist" aria-label="tabs component" class="tabs-btn-container">
          <button role="tab" aria-controls="panel-1" id="tab-1" type="button" aria-selected="true" tabindex="0" class="tab active-tab">Architectes</button>
          <button role="tab" aria-controls="panel-2" id="tab-2" type="button" aria-selected="false" tabindex="-1" class="tab">Administration</button>
        </div>
        <div id="panel-1" role="tabpanel" tabindex="0" aria-labelledby="tab-1" class="tab-content active-tab-content">
          <div class="dropdown">
            <button class="dropbtn">Textures <i class="fa-solid fa-chevron-down"></i></button>
            <div class="dropdown-content">
              <a href="https://architextures.org/" target="_blank">architextures.org</a>
              <a href="https://www.textures.com/" target="_blank">textures.com</a>
            </div>
          </div>
          <div class="dropdown">
            <button class="dropbtn">Block3D <i class="fa-solid fa-chevron-down"></i></button>
            <div class="dropdown-content">
              <a href="https://3dwarehouse.sketchup.com/?hl=fr" target="_blank">3dwarehouse.com</a>
              <a href="https://www.polantis.com/fr/" target="_blank">polantis.com</a>
              <a href="https://www.bimobject.com/fr" target="_blank">bimproject</a>
            </div>
          </div>
        </div>
        <div id="panel-2" role="tabpanel" tabindex="0" aria-labelledby="tab-2" class="tab-content">
          <div class="dropdown">
            <button class="dropbtn">Cadastres / PLU <i class="fa-solid fa-chevron-down"></i></button>
            <div class="dropdown-content">
              <a href="https://cadastre.data.gouv.fr/datasets/plan-cadastral-informatise" target="_blank">Plan-cadastral-informatise</a>
              <a href="https://documents-plu2.lillemetropole.fr/PLU2.php" target="_blank">PLU 2</a>
              <a href="https://diffuweb.lillemetropole.fr/PLU3/docsplu3-V1/Accueil.php" target="_blank">PLU 3</a>
              <a href="https://geomel.lillemetropole.fr/adws/app/ea6babec-176a2-11ea-8a28-b7da9ed8745f/index.php" target="_blank">geomel</a>
            </div>
          </div>
          <div class="dropdown">
            <button class="dropbtn">CERFA PC<i class="fa-solid fa-chevron-right"></i></button>
            <div class="dropdown-content">
              <a href="https://www.service-public.fr/particuliers/vosdroits/R20835" target="_blank">CERFA PC</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "PostCustom",
  };
  </script>
  
  <style scoped>
  .PostCustom {
    width: 20vw;
  }
  </style>
  