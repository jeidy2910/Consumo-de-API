# Pokémon API - Angular

## Descripción

Este proyecto fue desarrollado en Angular y consume la API pública de Pokémon (PokeAPI) para mostrar información de los Pokémon.

## Tecnologías utilizadas

- Angular 19
- TypeScript
- HTML
- SCSS
- Node.js
- npm

## Requisitos

Antes de ejecutar el proyecto es necesario tener instalado:

- Node.js (versión 20 o superior)
- npm
- Angular CLI

Instalar Angular CLI:

```bash
npm install -g @angular/cli
```

Verificar las versiones:

```bash
node -v
npm -v
ng version
```

## Instalación

1. Clonar el repositorio:

```bash
git clone URL_DEL_REPOSITORIO
```

2. Entrar a la carpeta del proyecto:

```bash
cd NOMBRE_DEL_PROYECTO
```

3. Instalar las dependencias:

```bash
npm install
```

## Ejecutar el proyecto

Iniciar el servidor de desarrollo:

```bash
ng serve
```

o

```bash
npm start
```

Abrir el navegador en:

```
http://localhost:4200
```

## Compilar el proyecto

Para generar la versión de producción ejecutar:

```bash
ng build
```

Los archivos compilados se encontrarán en la carpeta:

```
dist/
```

## Solución de problemas

Si ocurre algún error relacionado con dependencias, ejecutar:

```bash
npm install
```

Si el problema continúa:

```bash
rm -rf node_modules
rm package-lock.json
npm install
```

En Windows (PowerShell):

```powershell
Remove-Item node_modules -Recurse -Force
Remove-Item package-lock.json
npm install
```

## API utilizada

El proyecto consume la API pública:

https://pokeapi.co/

## Autor

Alexa
Tecnólogo en Análisis y Desarrollo de Software - SENA