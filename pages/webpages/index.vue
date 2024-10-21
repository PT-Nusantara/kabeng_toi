<template>
    <div class="container">
      <div class="header">
        <div class="logo">
          <img src="@/assets/img/toi.jpg" alt="Logo">
        </div>
        <div class="title">
          <h1>Kabeng Toi</h1>
          <p>Jl. Depok, Sukamenak, Purbaratu</p>
          <p>catatan kepala bengkel toi SMKN 4 Tasikmalaya</p>
        </div>
        <div class="right">
          <img src="@/assets/img/smkn4.jpg" alt="Logo Right">
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
  <style scoped>
  body {
  background-color: #f5f5f5;
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

h1 {
  text-align: center;
  margin-bottom: 20px;
}

.button-container {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

button {
  background-color: #333;
  color: #fff;
  border: none;
  padding: 15px 30px;
  cursor: pointer;
  border-radius: 5px;
}

button:hover {
  background-color: #555;
}

.logo-container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 20px;
}

.logo {
  width: 100px;
  height: 100px;
  border-radius: 50%;
}

.logo-text {
  margin-left: 10px;
  font-size: 1.5em;
  font-weight: bold;
}
  </style>