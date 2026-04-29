# Guía básica de Git y GitHub

## Introducción

**Git** es un sistema de control de versiones que permite guardar el historial de cambios de un proyecto. Sirve para trabajar de forma ordenada, recuperar versiones anteriores y colaborar con otros desarrolladores.

**GitHub** es una plataforma online donde podemos subir repositorios Git, compartir proyectos, colaborar con otras personas y guardar nuestro código en la nube.

## Comandos básicos de Git

| Comando | Explicación |
|---|---|
| `git init` | Inicializa un repositorio Git |
| `git status` | Muestra el estado de los archivos |
| `git add .` | Añade todos los archivos al área de preparación |
| `git commit -m "mensaje"` | Guarda los cambios con un mensaje |
| `git remote add origin URL` | Conecta el repositorio local con GitHub |
| `git push -u origin main` | Sube el proyecto a GitHub |
| `git clone URL` | Descarga un repositorio existente |
| `git pull` | Descarga cambios recientes del repositorio remoto |

## Flujo de trabajo básico

1. **Crear un repositorio**
   - Se crea una carpeta para el proyecto.
   - Se inicializa Git con `git init`.

2. **Añadir archivos**
   - Se crea o modifica el archivo `README.md`.
   - Se añaden los archivos con `git add .`.

3. **Hacer commit**
   - Se guardan los cambios con un mensaje descriptivo.

4. **Subir a GitHub**
   - Se crea un repositorio en GitHub.
   - Se conecta el repositorio local con GitHub.
   - Se suben los cambios con `git push`.

## Ejemplo práctico

```bash
mkdir evaluacion-git
cd evaluacion-git
git init
echo "# Guía básica de Git y GitHub" > README.md
git add .
git commit -m "README inicial"
git branch -M main
git remote add origin https://github.com/usuario/UF1467_EC02_nombre_apellido.git
git push -u origin main# UF1467_EC02
