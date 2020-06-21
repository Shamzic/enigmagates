<template>
  <div class="container">
    <div class="row mt-3">
      <div class="col">
        <img :src="require('../../assets/key.png')">
        <span class="title"> ENIGMAGATES </span>
      </div>

    <div class="row">
      <div class="col">
        <div class="dropdown">
          <button
            class="btn btn-secondary dropdown-toggle"
            type="button"
            id="dropdownMenu1"
            data-toggle="dropdown"
            aria-haspopup="true"
            aria-expanded="false"
          >
            ENIGMES
          </button>
          <div class="dropdown-menu" aria-labelledby="dropdownMenu2">
            <button class="dropdown-item" type="button">Découvrir</button>
            <button class="dropdown-item" type="button">Lancer une énigme en groupe</button>
            <button class="dropdown-item" type="button">Classement</button>
          </div>
        </div>
      </div>
        <div class="col">
          <button
            class="btn btn-outline-secondary"
            type="button"
            id="dropdownMenu2"
          >
            PARAMETRES
          </button>
      </div>
      </div>
    </div>
    <hr/>
  </div>
</template>

<script>

export default {
  name: 'Header',
  props: {

  },
  components: {

  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

img {
  width: 40px;
}

.title {
  font-size: 25px;
}
</style>
