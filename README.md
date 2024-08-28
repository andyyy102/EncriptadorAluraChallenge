# Encriptador de Texto Challenge #1 Alura Oracle

Este proyecto es una herramienta simple para encriptar y desencriptar texto utilizando un método de sustitución de caracteres. El encriptador reemplaza ciertas letras con secuencias de texto específicas y puede revertir el proceso para desencriptar el texto. La interfaz está construida con HTML, CSS y JavaScript.

## Estructura del Proyecto

El proyecto está compuesto por tres archivos principales:

1. **`index.html`**: El archivo HTML que define la estructura de la interfaz de usuario.
2. **`index.js`**: El archivo JavaScript que contiene la lógica para encriptar, desencriptar y copiar el texto.
3. **`styles.css`**: El archivo CSS que define el estilo visual de la interfaz de usuario (no incluido aquí, pero necesario para la apariencia).

## Cómo Funciona

1. **Encriptar Texto**: Convierte el texto ingresado en una forma encriptada donde:
   - `e` se convierte en `enter`
   - `i` se convierte en `imes`
   - `a` se convierte en `ai`
   - `o` se convierte en `ober`
   - `u` se convierte en `ufat`

2. **Desencriptar Texto**: Revierte el texto encriptado a su forma original reemplazando:
   - `enter` con `e`
   - `imes` con `i`
   - `ai` con `a`
   - `ober` con `o`
   - `ufat` con `u`

3. **Copiar Texto**: Permite copiar el texto encriptado o desencriptado al portapapeles.

## Archivos

### `index.html`

Define la estructura del encriptador, incluyendo un área de texto para ingresar el texto y botones para encriptar, desencriptar y copiar el texto.

### `index.js`

Contiene las funciones:

- `encriptar()`: Encripta el texto ingresado.
- `desencriptar()`: Desencripta el texto encriptado.
- `copiarTexto()`: Copia el texto al portapapeles.


## Contribuciones

Las contribuciones son bienvenidas. Si tienes sugerencias o mejoras, por favor abre un *issue* o envía una *pull request*.


