<h1 align="center">🚗 Sistema de Parqueadero</h1>

<p align="center">
  Sistema web desarrollado en Laravel para el registro y control de vehículos en un parqueadero.
</p>

<hr>

<h2>📌 Descripción</h2>
<p>
Este sistema permite registrar el ingreso de vehículos reemplazando el registro manual en papel.
Se almacena la placa, tipo de vehículo, propietario (opcional), observaciones y la fecha/hora
de ingreso se registra automáticamente.
</p>

<h2>⚙️ Funcionalidades</h2>
<ul>
  <li>Registro de vehículos</li>
  <li>Listado de vehículos activos</li>
  <li>Edición de información</li>
  <li>Marcado de salida del vehículo</li>
  <li>Interfaz usable en dispositivos móviles</li>
</ul>

<h2>🛠️ Tecnologías</h2>
<ul>
  <li>Laravel</li>
  <li>PHP</li>
  <li>MySQL</li>
  <li>HTML5</li>
  <li>CSS</li>
  <li>Blade</li>
</ul>

<h2>🖥️ Interfaz del Sistema</h2>

<h3>Formulario de Registro</h3>
<img src="images/formulario.png" width="600">

<h3>Listado de Vehículos</h3>
<img src="images/listado.png" width="600">

<h3>Vista en Móvil</h3>
<img src="images/movil.png" width="300">

<h2>🗄️ Base de Datos</h2>
<p>
La aplicación utiliza MySQL. La tabla principal es <strong>vehiculos</strong>, creada mediante
migraciones de Laravel.
</p>

<h2>▶️ Ejecución</h2>
<pre>
git clone https://github.com/cepedakevin1-a11y/parqueadero-laravel.git
composer install
php artisan migrate
php artisan serve
</pre>

<h2>👤 Autor</h2>
<p>Kevin Cepeda</p>

<h2>📎 Repositorio</h2>
<p>
<a href="https://github.com/cepedakevin1-a11y/parqueadero-laravel">
Repositorio en GitHub
</a>
</p>
