<template>
  <div class="main-menu">
    <Header />
    <h2>Dinas PUPR Kabupaten Banjar</h2>
    <div class="main-image">
      <img class="image1" src="~/static/image1.png" alt="gambar 1">
      <!-- <img class="image2" src="~/static/image2.jpg" alt="gambar 2">
      <img class="image3" src="~/static/image3.jpg" alt="gambar 3"> -->
    </div>
    <Body />
  </div>
</template>

<script>
import Header from '~/components/Header'
import Body from '~/components/Body'

export default {
  components: {
    Header, Body
  }
}
</script>

<style>

@media screen
and (max-device-width: 480px) {

  .main-image{
    position: relative;
    overflow: hidden;
    background: url(../static/background.svg);
    background-size: 120vw;
  }

  .image1 {
    inline-size: 100vw;
    block-size: 45vw;
    margin: 3vw auto auto auto;
    position: unset;
    z-index: 1;
  }

  .main-menu h2 {
    font-size: 5vw;
    color: rgb(23, 143, 255);
    -webkit-text-stroke: 0.05vw white;
    position: absolute;
    margin: 2vw auto auto 4vw;
    z-index: 2;
  }
}

@media screen
and (min-device-width: 481px)
and (max-device-width: 720px) {

  .main-image{
    position: relative;
    overflow: hidden;
    background: url(../static/background.svg);
    background-size: 90vw;
    margin: 1vw 15vw auto 15vw;
  }

  .image1 {
    inline-size: 70vw;
    block-size: 31.5vw;
    margin: 3vw auto auto auto;
    position: unset;
    z-index: 1;
  }

  .main-menu h2 {
    font-size: 3.5vw;
    color: rgb(23, 143, 255);
    -webkit-text-stroke: 0.04vw white;
    position: absolute;
    margin: 1.5vw auto auto 18vw;
    z-index: 2;
  }
}

@media only screen
and (min-device-width: 721px)
and (max-device-width: 960px) {

  .main-image{
    position: relative;
    overflow: hidden;
    background: url(../static/background.svg);
    background-size: 80vw;
    margin: 1vw 20vw auto 20vw;
  }

  .image1 {
    inline-size: 60vw;
    block-size: 27vw;
    margin: 3vw auto auto auto;
    position: unset;
    z-index: 1;
  }

  .main-menu h2 {
    font-size: 3vw;
    color: rgb(23, 143, 255);
    -webkit-text-stroke: 0.03vw white;
    position: absolute;
    margin: 1.5vw auto auto 23vw;
    z-index: 2;
  }
}

@media only screen
and (min-device-width: 961px) {

  .main-image{
    inline-size: 500px;
    block-size: 210px;
    margin-left: calc(25vw - 10px);
    position: relative;
    overflow: hidden;
    background: url(../static/background.svg);
    background-size: auto;
    margin-top: 5px;
  }

  .image1 {
    inline-size: 500px;
    block-size: 185px;
    justify-self: left;
    margin: 24px auto auto auto;
    z-index: 1;
  }

  .main-menu h2 {
    justify-self: center;
    font-size: 24px;
    color: rgb(23, 143, 255);
    -webkit-text-stroke: 0.25px white;
    position: absolute;
    margin-top: 10px;
    margin-left: calc(25vw + 5px);
    z-index: 2;
  }
}

</style>
