![](https://pataruco.github.io/ga-assets/assets/logos/ga.svg)

# Ejercicio Git

## Instrucciones

- Clona este repo

  ```sh
  git clone git@git.generalassemb.ly:sei-es/perfiles-git-markdown.git
  ```

- Crea una **rama** (`branch`) con tu nombre y apellido (`nombre-apellido`), ejemplo
  ```sh
  git checkout -b pedro-martin
  ```
- Abre este repo en tu editor de texto (VS Code)
  ```sh
  code .
  ```
- Crea un **directorio** con tu (`nombre-apellido`), ejemplo
  ```sh
  mkdir pedro-martin
  ```
- Dentro del nuevo **directorio**, crea un archivo `readme.md`
  ```sh
  cd pedro-martin
  touch readme.md
  ```
- Copia y pega el [contenido](##plantilla) de la plantilla que esta debajo de estas instrucciones
- Haz `commit` de tus cambios.
  ```sh
  git add .
  git commit -m "Tu mensaje"
  ```
- Empuja a remoto, cambia el `nombre-apellido` por el nombre de tu **rama** (`branch`)
  ```sh
  git push --set-upstream origin nombre-apellido
  ```
- En remoto crea una **solicitud de extracción** (`pull request`), [instructiones aquí](https://docs.github.com/es/enterprise/2.21/user/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)

## Plantilla

```markdown
# Nombre completo

## Película(s) favorita(s)

- nombre de película
- nombre de película

## Programa(s) de TV favorito(s)

- nombre de programa de TV
- nombre de programa de TV

## Cancion(es) favorita(s)

- nombre de canción

## ¿Qué esperas de este curso?

Tus expectativas

## ¿Qué esperas de tus instructores?

Tus expectativas

## ¿Qué te motiva a estar aquí?

Tus motivaciones

## ¿Qué preocupaciones tienes sobre este curso?

Tus precupaciones, si tienes alguna

## Tareas

- Haz un enlance de tu ciudad o pueblo natal en Wikipedia, por ejemplo, [Caracas](https://en.wikipedia.org/wiki/Caracas)

- Una imágen de tu caricartura favorita ![Alt text](URL to image)
```
