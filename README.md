# Creado por: Joel Antonio Jaquez López

# React Hook: useContext (Tema Claro/Oscuro)

## Descripción

Este proyecto demuestra el uso del hook `useContext` en React para compartir un estado global entre componentes: en este caso, el tema claro u oscuro de la aplicación. Implementado completamente con React vía CDN y JSX interpretado con Babel.

## Objetivos del ejercicio

- Crear un contexto de tema (`ThemeContext`).
- Compartir el estado global de tema entre múltiples componentes.
- Cambiar el tema de forma dinámica sin necesidad de pasar props manualmente.

## Estructura del ejercicio

### 1. `ThemeContext`
Espacio común que guarda el estado `theme` y la función `toggleTheme`.

### 2. `ThemeProvider`
Componente que envuelve a toda la aplicación. Proporciona el contexto para que todos sus hijos puedan acceder y modificar el tema.

### 3. `ThemeToggle`
Botón que cambia entre modo claro y oscuro usando `toggleTheme` desde el contexto.

### 4. `ThemeDisplay`
Componente que muestra el tema actual. Cambia dinámicamente el color de fondo y el texto según el tema.

### 5. `App`
Componente principal que agrupa todo dentro del `ThemeProvider`.

## Funcionamiento

- El estado global `theme` se comparte entre los componentes sin necesidad de props intermedios.
- Al hacer clic en el botón, el tema cambia y se actualiza dinámicamente en todos los componentes que lo consumen.
- Se utiliza `useContext()` para leer y actualizar el contexto desde los componentes hijos.

## Tecnologías utilizadas

- React 18 (vía CDN)
- ReactDOM 18 (vía CDN)
- Babel (para interpretar JSX directamente en el navegador)

## Como correr el ejercicio

- Clonar el repositorio y ejecutar LiveServer
- Acceder mediante la siguiente ruta del servidor de la clase: http://awita.site/usuarios/jaq23369/React%20Hock%20%28useContext%29%20CDN/

