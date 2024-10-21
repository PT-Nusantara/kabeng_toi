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
<style scoped>
body {
  font-family: sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  background-color: #f5f5f5;
}

.container {
  background-color: #fff;
  padding: 30px;
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  width: 350px;
}

h2 {
  text-align: center;
  margin-bottom: 20px;
}

input[type="text"],
input[type="password"] {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  box-sizing: border-box;
  border-radius: 4px;
}

button {
  background-color: #4CAF50;
  color: white;
  padding: 12px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  border-radius: 4px;
}

button:hover {
  background-color: #45a049;
}

.forgot-password {
  text-align: center;
  margin-top: 10px;
}

a {
  color: #4CAF50;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
</style>
