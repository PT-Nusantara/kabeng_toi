<template>
  <div class="container">
    <h1 class="text-center">login</h1>
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
  background-color: #f5f5f5;
  font-family: Arial, sans-serif;
}

.container {
  width: 400px;
  margin: 100px auto;
  background-color: #fff;
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  padding: 30px;
}

h2 {
  text-align: center;
  margin-bottom: 30px;
}

input[type="text"],
input[type="password"] {
  width: 100%;
  padding: 10px;
  margin: 10px 0;
  border: 1px solid #ddd;
  border-radius: 4px;
  box-sizing: border-box;
}

button {
  background-color: #4CAF50;
  color: white;
  padding: 10px 20px;
  margin: 20px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  width: 100%;
}

button:hover {
  background-color: #45a049;
}

a {
  color: #4CAF50;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
</style>