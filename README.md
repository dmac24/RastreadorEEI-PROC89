# Rastreador EEI – Aplicación móvil en React Native

## Descripción
Rastreador EEI es una aplicación móvil desarrollada en React Native cuyo objetivo es mostrar información relacionada con la Estación Espacial Internacional (EEI/ISS) utilizando APIs públicas de la NASA.  
La app cuenta con una pantalla principal desde la cual el usuario puede navegar a diferentes secciones: localización de la EEI, información sobre meteoritos y actualizaciones.

Este proyecto fue desarrollado como práctica de desarrollo móvil, consumo de APIs externas y navegación entre pantallas.

## Tecnologías
- React Native
- JavaScript
- React Navigation
- APIs públicas de la NASA (ISS location, meteoritos, actualizaciones)

## Funcionalidades
- Navegación entre pantallas (Stack Navigator)
- Interfaz mobile-first
- Estructura modular por pantallas
- Integración prevista con APIs externas
- Diseño con componentes de React Native

## Estructura del proyecto
- screens/Home.js – Pantalla principal
- screens/IssLocation.js – Pantalla de localización de la EEI
- screens/Meteors.js – Pantalla de meteoritos
- screens/Updates.js – Pantalla de actualizaciones
- App.js – Configuración de navegación

## Cómo ejecutar el proyecto
1. Clonar el repositorio:
```bash
git clone https://github.com/dmac24/RastreadorEEI-PROC89.git
```
2. Instalar dependencias:
```bash
npm install
```

3. Ejecutar en emulador o dispositivo físico:
```bash
npm start

```
