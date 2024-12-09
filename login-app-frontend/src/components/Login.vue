<template>
  <main class="login-container">
    <section class="login-box">
      <header>
        <h1>Iniciar Sesión</h1>
      </header>
      <form>
        <article class="form-group">
          <label for="username">Usuario</label>
          <input type="text" id="username" name="username" placeholder="Ingresa tu usuario" required />
        </article>
        <article class="form-group">
          <label for="password">Contraseña</label>
          <input type="password" id="password" name="password" placeholder="Ingresa tu contraseña" required />
        </article>
        <footer>
          <button type="submit">Ingresar</button>
        </footer>
      </form>
    </section>
  </main>
</template>

<style scoped>
/* Contenedor principal */
.login-container {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  background-color: #f4f4f9;
  margin: 0;
}

/* Caja de login */
.login-box {
  background: #ffffff;
  padding: 2rem;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  width: 100%;
  max-width: 400px;
}

/* Estilo del encabezado */
header h1 {
  margin: 0 0 1.5rem 0;
  font-size: 1.5rem;
  text-align: center;
  color: #333333;
}

/* Estilo de grupos del formulario */
.form-group {
  margin-bottom: 1.5rem;
}

label {
  display: block;
  margin-bottom: 0.5rem;
  font-weight: bold;
  color: #333333;
}

input {
  width: 100%;
  padding: 0.75rem;
  border: 1px solid #cccccc;
  border-radius: 4px;
  font-size: 1rem;
  box-sizing: border-box;
}

/* Botón de enviar */
button {
  width: 100%;
  padding: 0.75rem;
  background: teal;
  color: white;
  border: none;
  border-radius: 4px;
  font-size: 1rem;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

button:hover {
  background: darkcyan;
}
</style>
