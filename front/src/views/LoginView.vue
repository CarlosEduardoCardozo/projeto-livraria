<template>
  <div class="main">
    <div class="tudo">
      <div class="form">
        <label for="input-email">EMAIL</label>
        <input id="input-email" placeholder="Insira seu email..." type="text" />
        <label for="input-senha">SENHA</label>
        <input
          id="input-senha"
          placeholder="Insira sua senha..."
          type="password"
        />
        <button>LOGIN</button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.main {
  height: 800px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #a8a8a863;
}
button {
  margin-left: 1%;
  width: 50%;
  height: 40px;
  border-style: none;
  border-radius: 10px;
  background-color: white;
  color: #3d1a14;
  
  cursor: pointer;
}
label {
  font-size: 25px;
  color: white;
}
.tudo {
  display: flex;
  flex-direction: row;
  padding: 85px;
}

.form {
  height: 500px;
  width: 400px;
  display: flex;
  background-color: #3d1a14;
  border-radius: 30px;
  white-space: nowrap;
  align-items: flex-start;
  justify-content: center;
  padding: 0 40px 0 40px;
  flex-direction: column;
}
button {
  margin: 10% auto;
}
.form input {
  justify-content: center;
  margin-bottom: 12px;
  border-bottom: 2px solid #ffffff;
  border-top: 0;
  border-right: 0;
  outline: none;
  color: white;
  border-left: 0;
  background: transparent;
  height: 33px;
  align-items: center;
  width: 100%;
}
.form button:hover{
  background-color: #200e0b;
  color: #ffffff;
  transition: 0.5s;
}
.form input:hover{
    border-bottom: 3px solid #110806;
    transition: 1.3s;
}
</style>
