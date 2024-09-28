<template>
  <div class="container">
    <h1>Iniciar un Proyecto en Nuxt.js 3.0</h1>
    <p>Para empezar un proyecto en <em>Nuxt.js 3.0</em>, sigue estos pasos:</p>

    <h2>1. Instalar Node.js y NPM</h2>
    <p>Primero, necesitas tener instalado <em>Node.js</em> en tu computadora. Para verificar si está instalado, abre una terminal y escribe:</p>
    <pre><code>node -v</code></pre>
    <pre><code>npm -v</code></pre>
    <p>Si no está instalado, descárgalo desde <a href="https://nodejs.org/" target="_blank">nodejs.org</a> y sigue las instrucciones de instalación.</p>

    <h2>2. Crear un Proyecto Nuxt.js</h2>
    <p>Con <em>NPM</em> instalado, puedes usar el comando oficial de Nuxt para crear un proyecto. En la terminal, ve a la carpeta donde quieras crear tu proyecto y ejecuta:</p>
    <pre><code>npx nuxi init nombre-del-proyecto</code></pre>
    <p>Este comando genera una estructura básica para el proyecto. Luego, entra en la carpeta del proyecto:</p>
    <pre><code>cd nombre-del-proyecto</code></pre>

    <h2>3. Instalar Dependencias</h2>
    <p>Para que el proyecto funcione, necesitas instalar las dependencias. Ejecuta el siguiente comando:</p>
    <pre><code>npm install</code></pre>
    <p>Esto descargará e instalará todas las dependencias necesarias que están especificadas en el archivo <code>package.json</code>.</p>

    <h2>4. Ejecutar el Proyecto en Desarrollo</h2>
    <p>Una vez que todo está instalado, puedes iniciar el servidor de desarrollo con:</p>
    <pre><code>npm run dev</code></pre>
    <p>El proyecto estará disponible en <strong>http://localhost:3000</strong>, donde podrás ver los cambios en tiempo real.</p>

    <h2>5. Configuración de GitHub</h2>
    <p>Si quieres integrar tu proyecto con <em>GitHub</em>, sigue estos pasos:</p>
    <ol>
      <li>Inicializa un repositorio en la carpeta del proyecto:</li>
      <pre><code>git init</code></pre>
      <li>Crea un archivo <code>.gitignore</code> y agrega la siguiente línea para ignorar la carpeta <code>node_modules</code>:</li>
      <pre><code>node_modules/</code></pre>
      <li>Añade todos los archivos del proyecto:</li>
      <pre><code>git add .</code></pre>
      <pre><code>git commit -m "Inicializar proyecto Nuxt.js"</code></pre>
      <li>Sube el proyecto a un repositorio en GitHub:</li>
      <pre><code>git remote add origin https://github.com/tu-usuario/nombre-del-repositorio.git</code></pre>
      <pre><code>git push -u origin main</code></pre>
    </ol>

  
    <p>Con estos pasos tendrás un proyecto de <em>Nuxt.js</em> configurado y listo para desarrollar aplicaciones educativas.</p>

    <NuxtLink to="/">Volver a la página principal</NuxtLink>
  </div>
</template>

<style scoped>
.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  border: 2px solid #27ae60;
  border-radius: 10px;
  background-color: #eafaf1;
}

h1 {
  color: #2c3e50;
  font-size: 2.2em;
  text-align: center;
}

h2 {
  color: #27ae60;
  font-size: 1.5em;
}

p {
  color: #34495e;
  font-size: 1.1em;
}

pre {
  background-color: #ecf0f1;
  padding: 10px;
  border-radius: 5px;
  color: #e74c3c;
}

a {
  text-decoration: none;
  color: #27ae60;
  font-weight: bold;
}

a:hover {
  color: #16a085;
}
</style>
