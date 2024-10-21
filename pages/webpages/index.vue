<template>
    <div class="container">
      <div class="header">
        <div class="logo">
          <img src="toi.jpg" alt="Logo">
        </div>
        <div class="title">
          <h1>Kabeng Toi</h1>
          <p>Jl. Depok, Sukamenak, Purbaratu</p>
          <p>catatan kepala bengkel toi SMKN 4 Tasikmalaya</p>
        </div>
        <div class="right">
          <img src="logo-right.png" alt="Logo Right">
        </div>
      </div>
      <div class="content">
        <div class="back">
          <i class="fa fa-arrow-left"></i>
        </div>
        <div class="menu">
          <div class="menu-item" @click="gotoPinjamAlat">
            <p>PINJAM ALAT</p>
          </div>
          <div class="menu-item" @click="gotoPinjamRuang">
            <p>PINJAM RUANG</p>
          </div>
          <div class="menu-item" @click="gotoSOP">
            <p>SOP</p>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    methods: {
      gotoPinjamAlat() {
        // Implement logic to navigate to Pinjam Alat page
        console.log('Navigating to Pinjam Alat');
      },
      gotoPinjamRuang() {
        // Implement logic to navigate to Pinjam Ruang page
        console.log('Navigating to Pinjam Ruang');
      },
      gotoSOP() {
        // Implement logic to navigate to SOP page
        console.log('Navigating to SOP');
      }
    }
  };
  </script>
  
 
 