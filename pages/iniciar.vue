<template>
  <div class="container">
    <!-- Imagen -->
    <div class="image-container">
      <img src="C:\Users\CRISTIAN\Downloads\descarga (14).png" alt="Iniciando el proyecto Nuxt" />
    </div>

    <!-- Título Principal del Proyecto Nuxt -->
    <h1>Iniciar el Proyecto Nuxt</h1>
    <p>En esta sección, aprenderás cómo iniciar el servidor de desarrollo de Nuxt y cómo comenzar a trabajar en tu aplicación.</p>
    
    <h2>Paso 1: Iniciar el servidor de desarrollo</h2>
    <p>Para ver tu aplicación en acción, primero necesitas iniciar el servidor de desarrollo. Ejecuta el siguiente comando en tu terminal:</p>
    <pre><code>npm run dev</code></pre>
    <p>Esto iniciará el servidor en <a href="http://localhost:3000" target="_blank">http://localhost:3000</a>, donde podrás ver tu aplicación en tiempo real. Asegúrate de que no haya otros servicios utilizando el mismo puerto.</p>

    <h2>Paso 2: Modificar la aplicación</h2>
    <p>Una de las características más poderosas de Nuxt es su capacidad de recarga en caliente. Puedes comenzar a modificar tu aplicación desde el archivo <code>pages/index.vue</code> y ver los cambios reflejados automáticamente en el navegador sin necesidad de recargar la página. Esto hace que el proceso de desarrollo sea mucho más ágil.</p>

    <h2>Paso 3: Ver los registros en la consola</h2>
    <p>Mientras el servidor está en ejecución, puedes ver los registros y mensajes en la terminal. Esto te será útil para detectar errores o para ver información sobre las rutas que se están cargando.</p>

    <h2>Paso 4: Herramientas de desarrollo</h2>
    <p>Aprovecha las herramientas de desarrollo de tu navegador. Abre las herramientas de desarrollo (generalmente con F12 o Ctrl + Shift + I) para inspeccionar elementos, ver la consola y depurar tu aplicación. Nuxt se integra muy bien con las herramientas de Vue.js, lo que te permitirá realizar un seguimiento de los componentes y su estado.</p>

    <h2>Paso 5: Finalizando el servidor</h2>
    <p>Cuando hayas terminado de trabajar, puedes detener el servidor presionando <code>Ctrl + C</code> en la terminal. Esto cerrará el servidor de desarrollo y liberará el puerto.</p>

    <!-- Nuevo Título Principal para Git y GitHub -->
    <h1>Configurar Git y GitHub para tu Proyecto</h1>
    <p>En esta sección, aprenderás a crear un repositorio en GitHub y a inicializar Git en tu proyecto local.</p>

    <h2>Paso 1: Crear un repositorio en GitHub</h2>
    <ol>
      <li>Ve a GitHub e inicia sesión con tu cuenta.</li>
      <li>Haz clic en el botón "New" (Nuevo) en la esquina superior derecha para crear un nuevo repositorio.</li>
      <li>Asigna un nombre a tu repositorio, por ejemplo: <code>grupo-trabajo</code>.</li>
      <li>Puedes agregar una descripción opcional.</li>
      <li>Selecciona si quieres que sea público o privado.</li>
      <li>No añadas un archivo <code>README.md</code>, <code>.gitignore</code>, ni una licencia en esta etapa.</li>
      <li>Haz clic en "Create repository".</li>
    </ol>

    <h2>Paso 2: Inicializar Git en tu proyecto</h2>
    <p>En Visual Studio Code, abre la carpeta de tu proyecto <code>grupo-trabajo</code> y sigue estos pasos:</p>
    <ol>
      <li>Abre la terminal integrada en VS Code (Ctrl + ñ).</li>
      <li>Inicializa Git en la carpeta:</li>
      <pre><code>git init</code></pre>
      <p>Esto crea un repositorio Git local en tu carpeta.</p>
    </ol>

    <h2>Paso 3: Añadir los archivos del proyecto al repositorio local</h2>
    <ol>
      <li>Añade todos los archivos:</li>
      <pre><code>git add .</code></pre>
      <p>Esto agrega todos los archivos de la carpeta al área de preparación (staging area).</p>
      <li>Haz un primer commit:</li>
      <pre><code>git commit -m "Primer commit - Proyecto de Nuxt.js"</code></pre>
    </ol>

    <h2>Paso 4: Vincular el repositorio local con GitHub</h2>
    <ol>
      <li>En la terminal, agrega el repositorio remoto:</li>
      <pre><code>git remote add origin https://github.com/tu-usuario/grupo-trabajo.git</code></pre>
      <p>Asegúrate de reemplazar <code>tu-usuario</code> con tu nombre de usuario de GitHub.</p>
      <li>Empuja tu commit al repositorio remoto:</li>
      <pre><code>git push -u origin master</code></pre>
    </ol>

    <h2>Paso 5: Verifica en GitHub</h2>
    <p>Ahora puedes ir a GitHub y verificar que todos los archivos de tu proyecto se han subido correctamente.</p>

    <NuxtLink to="/">Volver a la página principal</NuxtLink>
  </div>
</template>

<style scoped>
.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  border: 2px solid #e67e22;
  border-radius: 10px;
  background-color: #fef6e4;
}

.image-container {
  text-align: center;
  margin-bottom: 20px;
}

img {
  max-width: 100%;
  height: auto;
  border-radius: 12px;
  border: 2px solid #ddd;
}

h1 {
  color: #e67e22;
  font-size: 2.2em;
  text-align: center;
}

h2 {
  color: #d35400;
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
  color: #e67e22;
  font-weight: bold;
}

a:hover {
  color: #d35400;
}
</style>
