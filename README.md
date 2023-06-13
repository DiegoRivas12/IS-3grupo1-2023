![Logo_change_your_mind](https://github.com/eluqm/IS-3grupo1-2023/assets/78099176/3c332c47-94b7-4ed5-86cb-5952d1962ba8)

<h1 align="center">Change your mind</h1>
<h1 align="center">Aplicación para la mejora de la salud mental </h1>

## Problematica:


## :label: Aplicaciones Similares:

## :label: Propósito del Proyecto

El presente proyecto tiene por objetivo brindar una **herramienta de soporte y seguimiento** de los estados emocionales para los usuarios que interactuen con la aplicación. Estos datos se recopilan mediante sencillas preguntas, escalas y comentarios que el usuario va aportando con el objetivo de formar un **perfil personalizado** único para cada usuario.

Asimismo, otro propósito del proyecto es **brindar una rutina, acorde a su perfil creado en la aplicación,** que le recomendará realizar ciertas actividades, le **proporcionará ejercicios** de meditación, le dará acceso directo a playlist musicales de relajación y brindará acceso rápido a consultas con psicólogos especialistas, nutricionistas y terapeutas para aquellos casos que requieran atención profesional.

Finalmente, el presente proyecto tiene por objetivo **brindar un chat-bot motivador** que escribirá frases relacionadas con el estado de animo del usuario motivándolo a seguir con la rutina personalizada propuesta por la aplicación o **hacer comentarios agradables sobre el usuario** en base a su estado de animo. Este utiliza palabras coincidentes dentro de su repositorio de respuestas para seleccionar y brindar una respuesta lógica frente a las preguntas/respuestas del usuario.

## :label: Tecnologias Usadas <br>
**1**. Flutter, como SDK de código abierto para desarrollar la implementación de las vistas diseñadas para el proyecto.
<p align="center">
	<img src="https://docs.flutter.dev/assets/images/flutter-logo-sharing.png" width=800>
</p>

**2**. CMake como herramienta de construcción automática para compilar, debugar y testear la aplicación a nivel de componentes e integración.
<p align="center">
	<img src="https://blog.desdelinux.net/wp-content/uploads/2019/07/cmake.jpg" width=800/>
</p>

**3.** Dart Y C++ como lenguajes de programación para desarollar el código fuente y la lógica detras de las vistas en Android y Windows.
<p align="center">
	<img src="https://miro.medium.com/v2/resize:fit:800/1*W0kCy2dvS3mTAQkTpW4PuQ.jpeg" width=800/>
</p>

**4.** Swift como lenguaje de programación para desarrollar el código fuente y la lógica para dispositivos iOS.
<p align="center">
	<img src="https://www.vectorlogo.zone/logos/swift/swift-ar21.png" width=800/>
</p>
 
## :label: Interfaz del Proyecto <br>
	


## :red_circle: Desarrollo

### Funcionalidades

### Casos de Uso

#### 1. Caso de uso: Inicio de sesión

| Nombre | Código | Pre-condición | Acciones | Post-condición |
| ------ | ------ | ------------- | -------- | -------------- |
| Login | UC-001 | El usuario no ha iniciado sesión | 1. Ingresar nombre de usuario y contraseña <br> 2. Autenticar credenciales | El usuario inicia sesión correctamente y se redirige a la pantalla principal |

#### 2. Caso de uso: Calificación diaria del estado de ánimo

| Nombre | Código | Pre-condición | Acciones | Post-condición |
| ------ | ------ | ------------- | -------- | -------------- |
| Calificación diaria del estado de ánimo | UC-002 | El usuario ha iniciado sesión | 1. Seleccionar una opción para calificar el estado de ánimo <br> 2. Guardar la calificación en la base de datos | La calificación del estado de ánimo se registra correctamente y se muestra una confirmación |

#### 3. Caso de uso: Diálogo con chatbot amigable

| Nombre | Código | Pre-condición | Acciones | Post-condición |
| ------ | ------ | ------------- | -------- | -------------- |
| Diálogo con chatbot amigable | UC-003 | El usuario ha iniciado sesión | 1. Mostrar mensaje de bienvenida del chatbot <br> 2. Permitir al usuario ingresar mensajes <br> 3. Responder a las consultas del usuario de manera inteligente <br> 4. Ofrecer opciones o sugerencias relevantes durante la conversación | El chatbot interactúa con el usuario de manera amigable y proporciona respuestas relevantes |

#### 4. Caso de uso: Acceder a acceso directo de profesionales en salud mental

| Nombre | Código | Pre-condición | Acciones | Post-condición |
| ------ | ------ | ------------- | -------- | -------------- |
| Acceder a acceso directo de profesionales en salud mental | UC-004 | El usuario ha iniciado sesión | 1. Mostrar una lista de profesionales disponibles <br> 2. Permitir al usuario seleccionar un profesional <br> 3. Proporcionar información detallada sobre el profesional seleccionado <br> 4. Facilitar la comunicación entre el usuario y el profesional seleccionado | El usuario puede acceder directamente a profesionales en salud mental y comunicarse con ellos |

#### 5. Caso de uso: Generación de rutina en la aplicación en base a datos recolectados de usuario

| Nombre | Código | Pre-condición | Acciones | Post-condición |
| ------ | ------ | ------------- | -------- | -------------- |
| Generación de rutina en la aplicación en base a datos recolectados de usuario | UC-005 | El usuario ha iniciado sesión y ha proporcionado datos relevantes | 1. Recolectar y analizar datos relevantes del usuario <br> 2. Utilizar algoritmos para generar una rutina personalizada <br> 3. Mostrar la rutina generada al usuario <br> 4. Permitir al usuario realizar ajustes o personalizaciones en la rutina | Se genera una rutina personalizada basada en los datos del usuario y se muestra al usuario |

#### 6. Caso de uso: Ver estadísticas de progreso personal incremental

| Nombre | Código | Pre-condición | Acciones | Post-condición |
| ------ | ------ | ------------- | -------- | -------------- |
| Ver estadísticas de progreso personal incremental | UC-006 | El usuario ha iniciado sesión y ha registrado progresos | 1. Recopilar datos sobre el progreso del usuario <br> 2. Calcular estadísticas relevantes <br> 3. Mostrar gráficos o tablas con las estadísticas <br> 4. Actualizar las estadísticas de forma automática o mediante una acción del usuario | Las estadísticas de progreso personal se muestran al usuario de manera incremental |

### Diagrama de Casos de Uso


### Diseño de Modelo de Datos 


### Diseño de Arquitectura


# **Estilos de Programación**

## 1. Declared-Intentions.

### *Restricciones*

## 2. Plugins.

### *Restricciones* 

## 3. Dataspaces.

### *Restricciones*

 ## 4. Resful.
### *Restricciones*

## 5. Pipeline.


# **Concepto CRUD aplicado**
CRUD hace referencia a un acrónimo en el que se reúnen las primeras letras de las cuatro operaciones fundamentales de aplicaciones persistentes en sistemas de bases de datos:
### Create (Crear registros)
### Read bzw. Retrieve (Leer registros)
### Update (Actualizar registros)
### Delete bzw. Destroy (Borrar registros)
En pocas palabras, CRUD resume las funciones requeridas por un usuario para crear y gestionar datos. Varios procesos de gestión de datos están basados en CRUD, en los que dichas operaciones están específicamente adaptadas a los requisitos del sistema y de usuario, ya sea para la gestión de bases de datos o para el uso de aplicaciones.
# **Prácticas de Código Legible**

## *1. Agrupación de código.*
   
## *2. Se Utilizo el mismo vocabulario para el mismo tipo de variable*

## *3. Identacion correspondiente* <br>

## *4. Poner en mayúscula las palabras especiales de SQL*
    
## *5. Cada función realiza solo realiza una tarea*
   
## *6. Los nombres de las funciones realizan lo mencionado*
   
## *7. Organización de Archivos y Carpetas.*

## *8. Evitar codigo redundante.* <br>

### 🔩Planificación de tareas de implementación en la herramienta TRELLO 🔩

# Modelo logico de la base de datos
![modelo logico](images/modelo_logico.PNG)


### 🔩COLABORADORES🔩
<br>
<a href="https://github.com/Miguel-Deza">
    <img src="https://avatars.githubusercontent.com/u/78099176?v=4" width="50px">
</a>
Miguel Angel Deza Cuela
<br>
<a href="https://github.com/AngelAnconeyra">
    <img src="https://avatars.githubusercontent.com/u/84652181?s=400&u=164b8541b0a891ca18a127c351a750611a3647a9&v=4" width="50px">
</a>
Roy Angel Choquehuanca Anconeyra

<br>
<a href="https://github.com/MC-io">
    <img src="https://avatars.githubusercontent.com/u/87913065?v=4" width="50px">
</a>
Moises Alejandro Casaverde Aleman

### Licencia de Flutter
<a href="https://flutter.dev/">
  <h1 align="center">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://storage.googleapis.com/cms-storage-bucket/6e19fee6b47b36ca613f.png">
      <img alt="Flutter" src="https://storage.googleapis.com/cms-storage-bucket/c823e53b3a1a7b0d36a9.png">
    </picture>
  </h1>
</a>

[![codecov](https://codecov.io/gh/flutter/flutter/branch/master/graph/badge.svg?token=11yDrJU2M2)](https://codecov.io/gh/flutter/flutter)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/5631/badge)](https://bestpractices.coreinfrastructure.org/projects/5631)
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/flutter/flutter/badge)](https://deps.dev/project/github/flutter%2Fflutter)
[![SLSA 1](https://slsa.dev/images/gh-badge-level1.svg)](https://slsa.dev)

Flutter es el SDK de Google para crear experiencias de usuario atractivas y rápidas para móvil, web y escritorio desde una única base de código. Flutter es utilizado por desarrolladores y organizaciones de todo el mundo, es gratuito y fuente abierta.
