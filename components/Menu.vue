<template>
  <div class="menu">
    <h3><strong>MENU</strong></h3>
    <div class="sub-menu">
      <nuxt-link to="/#">
        <img
          src="~/assets/icon/icon-1.png"
        > <span>kesekretariatan</span>
      </nuxt-link>
      <br>
      <nuxt-link to="/#">
        <img
          src="~/assets/icon/icon-2.png"
        > <span>Cipta Karya</span>
      </nuxt-link>
      <br>
      <nuxt-link to="/#">
        <img
          src="~/assets/icon/icon-3.png"
        > <span>Bina Marga</span>
      </nuxt-link>
      <br>
      <nuxt-link to="/#">
        <img
          src="~/assets/icon/icon-4.png"
        > <span>Tata Ruang</span>
      </nuxt-link>
      <br>
      <nuxt-link to="/#">
        <img
          src="~/assets/icon/icon-5.png"
        > <span>Sumber Daya Air</span>
      </nuxt-link>
      <br>
      <nuxt-link to="/#">
        <img
          src="~/assets/icon/icon-6.png"
        > <span>Jasa Konstruksi</span>
      </nuxt-link>
    </div>
  </div>
</template>

<style>

.menu h3{
  margin-left:5px;
  padding:2px;
}
.menu a{
  width: 185px;
  display:inline-block;
  padding-top: 10px;
  padding-bottom: 10px;
  padding-right: 13px;
  padding-left: 10px;
  color:rgb(27, 155, 202);
  border-radius: 2px;
  border: 1px solid #eeffff;
  background-color: #bcf2ff;
  text-decoration: none;
  transition: 0.4s;
}
.menu a:hover{
  color: rgb(0, 202, 27);
  background-color: #f5feff;
  transform: scale(1.03);
}

.sub-menu img {
  max-width: 25px;
  position: absolute;
  vertical-align: center;
}

.sub-menu span {
  margin-left: 35px
}
</style>
