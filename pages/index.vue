<template>
  <div class="container">
    <!-- Imagen -->
    <div class="image-container">
      <img src="C:/Users/CRISTIAN/Downloads/descarga (13).png" alt="Descripción de la imagen" />
    </div>

    <!-- Título Principal -->
    <h1 class="main-title">Guía para Crear un Proyecto en Nuxt</h1>
    
    <!-- Introducción -->
    <p class="intro-text">
      Nuxt.js es un framework basado en Vue.js que te permite crear aplicaciones web de forma sencilla y eficiente.
    </p>
    <p class="intro-text">
      A continuación, encontrarás los pasos para configurar e iniciar un proyecto de Nuxt:
    </p>

    <!-- Sección: ¿Qué es Nuxt.js? -->
    <div class="section">
      <h2 class="section-title">¿Qué es Nuxt.js?</h2>
      <p class="section-text">
        Nuxt.js es un marco de código abierto basado en Vue.js, utilizado para construir aplicaciones Vue.js renderizadas por el servidor. Proporciona una amplia gama de características, como renderización del lado del servidor (SSR), generación de sitios estáticos (SSG), división automática de código, un potente sistema de enrutamiento, entre otros, lo que permite a los desarrolladores construir aplicaciones web modernas de manera más eficiente.
      </p>
    </div>

    <!-- Sección: Características de Nuxt -->
    <div class="section">
      <h2 class="section-title">Principales Características de Nuxt:</h2>
      <ul class="features-list">
        <li><strong>Renderización del lado del servidor (SSR):</strong> Mejora la velocidad de carga de la página y el rendimiento de SEO.</li>
        <li><strong>Generación de sitios estáticos (SSG):</strong> Pre-renderiza páginas estáticas, mejorando el rendimiento y la experiencia del usuario.</li>
        <li><strong>División automática de código:</strong> Carga solo el código JavaScript necesario para la página actual, optimizando el rendimiento.</li>
        <li><strong>Enrutamiento incorporado:</strong> Enrutamiento basado en el sistema de archivos, sin necesidad de configuración adicional.</li>
        <li><strong>Modularidad:</strong> Fácil integración de bibliotecas y servicios de terceros a través de módulos.</li>
        <li><strong>Ecosistema robusto:</strong> Nuxt.js cuenta con un amplio soporte de plugins y módulos, facilitando el desarrollo.</li>
      </ul>
    </div>

    <!-- Enlaces de navegación -->
    <div class="navigation">
      <ul>
        <li><NuxtLink to="/configuracion">Configuración del Proyecto</NuxtLink></li>
        <li><NuxtLink to="/iniciar">Iniciar el Proyecto</NuxtLink></li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
/* Estilos generales del contenedor */
.container {
  max-width: 900px;
  margin: 50px auto;
  padding: 20px;
  text-align: center;
  background-color: #f9f9fb;
  border-radius: 15px;
  border: 3px solid #3498db;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
}

/* Estilos del título principal */
.main-title {
  color: #2c3e50;
  font-size: 2.8em;
  font-weight: bold;
  margin-bottom: 20px;
}

/* Texto introductorio */
.intro-text {
  color: #34495e;
  font-size: 1.3em;
  margin: 10px 0;
  line-height: 1.6;
}

/* Sección y títulos de las secciones */
.section {
  margin: 40px 0;
}

.section-title {
  font-size: 2.2em;
  color: #3498db;
  margin-bottom: 15px;
}

/* Texto dentro de las secciones */
.section-text {
  font-size: 1.2em;
  color: #7f8c8d;
  line-height: 1.7;
}

/* Lista de características */
.features-list {
  text-align: left;
  margin: 0 auto;
  padding: 0;
  list-style-type: none;
  max-width: 700px;
}

.features-list li {
  margin-bottom: 15px;
  font-size: 1.2em;
  color: #34495e;
}

.features-list strong {
  color: #2980b9;
}

/* Imagen */
.image-container {
  margin: 20px 0;
}

img {
  max-width: 100%;
  height: auto;
  border-radius: 12px;
  border: 2px solid #ddd;
}

/* Estilos de los enlaces de navegación */
.navigation ul {
  list-style-type: none;
  padding: 0;
  margin: 20px 0;
}

.navigation li {
  margin: 10px 0;
}

a {
  color: #3498db;
  text-decoration: none;
  font-size: 1.2em;
  font-weight: bold;
}

a:hover {
  color: #2980b9;
  text-decoration: underline;
}
</style>
