
# Guía del proyecto: Trabajo colaborativo con Git y GitHub

Esta guía explica cómo trabajar con repositorios remotos, reportar errores y proponer correcciones usando Git y GitHub. El proyecto se basa en lo aprendido en el Laboratorio 3 de Diseño de Interfaces de Programación Avanzado.

## Objetivo del proyecto

Aprender a colaborar en proyectos de software mediante repositorios remotos, ramas, Issues y Pull Requests.

### Herramientas utilizadas

- Git para controlar las versiones del proyecto.
- GitHub para alojar repositorios y colaborar.
- Visual Studio Code para revisar y editar archivos.
- Un navegador web para comprobar los resultados.

## Pasos de trabajo

1. Crear un fork del repositorio original en GitHub.
2. Clonar el repositorio propio con `git clone`.
3. Revisar los archivos del proyecto y localizar el error.
4. Crear un Issue para describir el problema.
5. Crear una rama para realizar la corrección.
6. Probar los cambios y registrarlos con un commit.
7. Subir la rama y crear un Pull Request.

## Lista de tareas

- [x] Crear un repositorio y clonarlo.
- [x] Identificar un error en el código.
- [x] Practicar el uso de ramas y commits.
- [ ] Revisar los cambios antes de enviar un Pull Request.

## Archivos y comandos principales

| Elemento | Descripción |
|----------|-------------|
| `index.html` | Contiene la estructura de la página web. |
| `estilos.css` | Define los colores y la tipografía. |
| `script.js` | Contiene la lógica para calcular el total del carrito. |
| `git status` | Muestra el estado de los archivos. |

## Ejemplo de comandos

Para comprobar los cambios del proyecto, se utiliza `git status`.

```bash
git status
git add .
git commit -m "Corrige un error del proyecto"
git push origin main
```

## Recursos de consulta

Puedes consultar la [documentación oficial de Git](https://git-scm.com/doc) para aprender más sobre el control de versiones.

## Imagen del proyecto

![Imagen de referencia del proyecto](../img/image.png)
