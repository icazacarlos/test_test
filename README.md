# Prueba de Java & Gradle

## Objetivo principal

- Crear una librería que contiene el modelo para una aplicación Java Spring Boot

## Aspecto a evaluar

- Programación Orientada a Objetos en Java
- Generación de Javadoc
- Manejo de git, ramificación en git
- Creación de *pull request* en Bitbucket

## Prerrequisitos

- JDK 11
- Cualquier editor de texto

## Configuración inicial

- Importar este repositorio en su cuenta personal de Bitbucket
- El nombre del repositorio debe ser `bg-training-gradle`
- El nivel de acceso al repositorio debe estar privado
- Otorgar acceso de administrador a la siguiente cuenta de correo electrónico `cicaza@consultec-ti.com`

## Actividades

1. Crear las ramas `develop` y `documents` a partir de la rama `master`
2. Crear la rama `feature/add_classes` a partir de la rama `develop`
3. Crear la clase `Loan` y *otras clases relacionadas*, a partir de la información del proyecto `bg-training-angular` (ver los archivos JSON del mock server)
5. Agregar documentación Javadoc a la clase y sus atributos
6. Configurar el proyecto con las siguientes coordenadas Maven:
   - Grupo = com.consultec.training.products.model
   - Artefacto = loans-model
   - Versión = 1.0.0-SNAPSHOT
7. Debe trabajar los cambios del proyecto en la rama `feature/add_classes`
8. Generar el Javadoc del proyecto y publicarlo en la rama `documents`
9. Crear los *pull request* hacia la rama `develop`
10. Publicar la librería en el repositorio local de Maven

## Tiempo estimado
- 60 minutos
