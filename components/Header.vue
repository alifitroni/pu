<template>
  <div class="header">
    <nuxt-link
      to="/#"
      class="button--home"
    >
      <img
        class="img-home"
        src="~/static/home.svg"
      >
    </nuxt-link>

    <input
      id=""
      type="text"
      name=""
      placeholder="Pencarian"
    >

    <label class="button--search" for="search">
      <button>
        <img class="img-search" src="~/static/search.svg">
      </button>
    </label>

    <nuxt-link
      to="/#"
      class="button--notif"
    >
      <img
        class="img-notif"
        src="~/static/notif.svg"
      >
    </nuxt-link>

    <nuxt-link
      to="/#"
      class="button--profil"
    >
      <img
        class="img-profil"
        src="~/static/profil.svg"
      >
    </nuxt-link>
    <div class="clr" />
  </div>
</template>

<script>
export default {

}
</script>

<style>

@media only screen
and (max-device-width: 480px) {

  .header{
    inline-size: 100vw;
    block-size: 15vw;
    background: linear-gradient( to top right, rgb(12, 133, 255),  rgb(2, 115, 228) );
    display: grid;
    grid-template-columns: auto 55vw 10vw auto auto;
  }

  .header input[type=text]{
    inline-size: 117%;
    block-size: 7.5vw;
    position: relative;
    outline: none;
    border: 0;
    border-style: none;
    border-radius: 4px;
    margin-top: 3.9vw;
    margin-bottom: auto;
    z-index: 1;
    padding-left: 3vw;
    padding-right: 9vw;
    font-size: 4vw;
  }

  .header input {
    transition: all .3s;
  }
  .header input:hover {
    background-color: #F5F5F5;
  }
  .header input:focus {
    box-shadow: 0px 0px 4px 0px rgba(65, 65, 65, 0.651);
    background: #F5F5F5;
  }

  .img-home {
    inline-size: 7vw;
    padding: 0.5vw;
  }

  .button--home {
    position: relative;
    margin-top: 3vw;
    margin-bottom: auto;
    margin-right: 3.5vw;
    margin-left: 3.5vw;
    justify-self: center;
  }

  .img-search {
    inline-size: 6vw;
    padding: 1vw;
    justify-self: center;
    opacity: 1;
  }

  .button--search {
    justify-self: center;
    margin-top: 4vw;
    margin-bottom: auto;
  }

  .img-notif {
    inline-size: 6vw;
    padding: 0.5vw;
  }

  .button--notif {
    justify-self: center;
    margin-top: 3.75vw;
    margin-bottom: auto;
    margin-left: 2.5vw;
  }

  .img-profil {
    inline-size: 8vw;
    padding: 0.5vw;
  }

  .button--profil {
    justify-self: right;
    margin-top: 3.5vw;
    margin-bottom: auto;
    margin-right: 2vw;
  }

  button {
    background-color: Transparent;
    /* border-top-right-radius: 1rem;
    border-bottom-right-radius: 1rem; */
    border: none;
    outline: none;
    height: auto;
    width: auto;
    cursor: pointer;
    position: relative;
    z-index: 2;
  }
}

@media only screen
and (min-device-width: 481px)
and (max-device-width: 720px) {

  .header{
    inline-size: 100vw;
    block-size: 10vw;
    background: rgb(12, 133, 255);
    display: grid;
    grid-template-columns: auto 64vw 10vw auto auto;
    justify-content: flex-start;
  }

  .header input[type=text]{
    inline-size: 112%;
    block-size: 5vw;
    position: relative;
    left: 0;
    border: 0;
    border-style: none;
    outline: none;
    padding-left: 2vw;
    padding-right: 5.5vw;
    border-radius: 4px;
    margin-top: 2.5vw;
    margin-bottom: auto;
    font-size: 2.8vw;
    z-index: 1;
  }

  .img-home {
    inline-size: 5vw;
    padding: 0.35vw;
  }

  .button--home {
    margin: 1.9vw;
    margin-right: 3vw;
    margin-left: 2.5vw;
    justify-self: center;
  }

  .img-search {
    inline-size: 3.7vw;
    padding: 0.5vw;
    justify-self: center;
    opacity: 0.8;
  }

  .button--search {
    justify-self: center;
    margin-top: 2.6vw;
    margin-bottom: auto;
  }

  .img-notif {
    inline-size: 4vw;
    padding: 0.3vw;
  }

  .button--notif {
    justify-self: center;
    margin-top: 2.6vw;
    margin-bottom: auto;
    margin-left: 1.5vw;
  }

  .img-profil {
    inline-size: 5.5vw;
    padding: 0.3vw;
  }

  .button--profil {
    justify-self: center;
    margin-top: 2.4vw;
    margin-bottom: auto;
    margin-left: 2vw;
  }

  button {
    background-color: Transparent;
    /* border-top-right-radius: 1rem;
    border-bottom-right-radius: 1rem; */
    border: none;
    outline: none;
    height: auto;
    width: auto;
    cursor: pointer;
    position: relative;
    z-index: 2;
  }
}

@media only screen
and (min-device-width: 721px)
and (max-device-width: 960px) {

  .header{
    inline-size: 100vw;
    block-size: 8vw;
    background: rgb(12, 133, 255);
    display: grid;
    grid-template-columns: auto 65vw 10vw auto auto;
    justify-content: flex-start;
  }

  .header input[type=text]{
    inline-size: 112%;
    block-size: 4vw;
    position: relative;
    left: 0;
    border: 0;
    border-style: none;
    outline: none;
    padding-left: 2vw;
    padding-right: 5.5vw;
    border-radius: 4px;
    margin-top: 2vw;
    margin-bottom: auto;
    z-index: 1;
    font-size: 2vw;
  }

  .img-home {
    inline-size: 4vw;
    padding: 0.28vw;
  }

  .button--home {
    margin: 1.5vw;
    margin-right: 3.5vw;
    margin-left: 3vw;
    justify-self: center;
  }

  .img-search {
    inline-size: 3vw;
    padding: 0.4vw;
    justify-self: center;
    opacity: 0.8;
  }

  .button--search {
    justify-self: center;
    margin-top: 2.1vw;
    margin-bottom: auto;
  }

  .img-notif {
    inline-size: 3.2vw;
    padding: 0.24vw;
  }

  .button--notif {
    justify-self: center;
    margin-top: 2.1vw;
    margin-bottom: auto;
    margin-left: 1.5vw;
  }

  .img-profil {
    inline-size: 4.4vw;
    padding: 0.24vw;
  }

  .button--profil {
    justify-self: center;
    margin-top: 2vw;
    margin-bottom: auto;
    margin-left: 2.2vw;
  }

  button {
    background-color: Transparent;
    border: none;
    height: auto;
    width: auto;
    cursor: pointer;
    position: relative;
    z-index: 2;
  }
}

@media only screen
and (min-device-width: 961px) {

  @media only screen
  and (min-width: 721px) {

    .header{
      inline-size: 100vw;
      block-size: 65px;
      background: rgb(12, 133, 255);
      display: grid;
      grid-template-columns: 25vw 360px 48px 30px auto;
      justify-content: flex-start;
    }

    .header input[type=text]{
      inline-size: 400px;
      block-size: 30px;
      position: relative;
      border: 0;
      border-style: none;
      outline: none;
      padding-left: 10px;
      padding-right: 27px;
      border-radius: 5px;
      margin-top: 17px;
      z-index: 1;
      font-size: 14px;
    }

    .img-home {
      inline-size: 25px;
    }

    .button--home {
      margin-top: 16px;
      margin-right: auto;
      margin-left: 20px;
    }

    .img-search {
      inline-size: 20px;
      padding-top: 4px;
      padding-bottom: 3px;
      padding-left: 3px;
      padding-right: 3px;
      opacity: 0.8;
    }

    .button--search {
      justify-self: center;
      margin-top: 19px;
      margin-bottom: auto;
    }

    .img-notif {
      inline-size: 20px;
    }

    .button--notif {
      justify-self: right;
      margin-top: 20px;
      margin-bottom: auto;
      z-index: 3;
    }

    .img-profil {
      inline-size: 27px;
    }

    .button--profil {
      justify-self: right;
      margin-top: 19px;
      margin-left: 18px;
      z-index: 3;
    }

    button {
      background-color: Transparent;
      border: 0;
      height: auto;
      outline: none;
      width: auto;
      cursor: pointer;
      position: relative;
      z-index: 2;
    }
  }

  @media only screen
  and (max-width: 720px) {

    .header{
      inline-size: 100vw;
      block-size: 65px;
      background: rgb(12, 133, 255);
      display: grid;
      grid-template-columns: 25vw 58vw auto auto;
      justify-content: flex-start;
    }

    .header input[type=text]{
      display: none;
    }

    .img-home {
      inline-size: 25px;
    }

    .button--home {
      margin-top: 16px;
      margin-right: auto;
      margin-left: 20px;
    }

    .img-search {
      inline-size: 20px;
      padding-top: 6px;
      padding-bottom: 2px;
      padding-left: 3px;
      padding-right: 3px;
      opacity: 0.8;
    }

    .button--search {
      justify-self: right;
      margin-top: 17px;
      margin-bottom: auto;
      margin-right: 18px;
      background: #ffffff;
      border-radius: 4px;
    }

    .img-notif {
      inline-size: 20px;
    }

    .button--notif {
      justify-self: center;
      margin-top: 20px;
      margin-bottom: auto;
      z-index: 3;
    }

    .img-profil {
      inline-size: 27px;
    }

    .button--profil {
      justify-self: left;
      margin-top: 19px;
      margin-left: 18px;
      z-index: 3;
    }

    button {
      background-color: Transparent;
      border: 0;
      height: auto;
      outline: none;
      width: auto;
      cursor: pointer;
      position: relative;
      z-index: 2;
    }
  }
}

</style>
