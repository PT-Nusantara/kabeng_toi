<template>
    <div class="container">
      <h1>Buat akun</h1>
      <div class="input-group">
        <label for="username">USERNAME</label>
        <input type="text" id="username" placeholder="Masukkan username">
      </div>
      <div class="input-group">
        <label for="password">PASSWORD</label>
        <input type="password" id="password" placeholder="Masukkan password">
      </div>
      <div class="button-group">
        <button class="button" @click="keluar">Keluar</button>
        <button class="button" @click="buatAkun">Buat</button>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    methods: {
      keluar() {
        // Implementasikan logika keluar dari halaman
      },
      buatAkun() {
        // Implementasikan logika pembuatan akun
      }
    }
  }
  </script>
  