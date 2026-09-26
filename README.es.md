[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Apache 2.0 License][license-shield]][license-url]

<br />
<div align="center">
  <h1 align="center">Ejemplos de Paco</h1>

  <p align="center">
    Programas de ejemplo que demuestran el lenguaje de programación Paco
    <br />
    <a href="https://github.com/pacolang/paco"><strong>Explora el compilador paco »</strong></a>
    <br />
    <br />
    <a href="https://github.com/pacolang/examples/issues">Reportar un problema</a>
    ·
    <a href="https://github.com/pacolang/examples/pulls">Contribuir con un ejemplo</a>
  </p>
</div>

**Leer en:** [English](README.md) · [Português](README.pt-BR.md) · **Español**

## Índice

<ol>
  <li><a href="#sobre-el-proyecto">Sobre el Proyecto</a></li>
  <li><a href="#primeros-pasos">Primeros Pasos</a>
    <ul>
      <li><a href="#requisitos-previos">Requisitos Previos</a></li>
    </ul>
  </li>
  <li><a href="#uso">Uso</a></li>
  <li><a href="#contribuir">Contribuir</a></li>
  <li><a href="#licencia">Licencia</a></li>
  <li><a href="#contacto">Contacto</a></li>
</ol>

## Sobre el Proyecto

Este repositorio reúne programas de ejemplo en Paco. Cada uno es una
demostración pequeña y autocontenida de una funcionalidad específica del
lenguaje o de una capacidad de la biblioteca estándar — concurrencia,
pattern matching, diferenciación automática, y así sucesivamente — en lugar
de una aplicación completa.

Los ejemplos solían vivir dentro de `examples/` en el repositorio del
compilador [`pacolang/paco`][paco-url]. Se movieron aquí para que el
repositorio del compilador se mantenga enfocado en el compilador, el
runtime y la biblioteca estándar, mientras que este puede crecer de forma
independiente a medida que se agregan nuevos ejemplos.

Ejemplos actuales:

- [`http-server/main.paco`](http-server/main.paco) — un servidor HTTP/1.1
  mínimo que crea una tarea por conexión, demostrando el modelo de
  concurrencia de Paco.

## Primeros Pasos

### Requisitos Previos

Necesitas un binario `paco` funcional en tu `PATH`. Consulta
[`pacolang/paco`][paco-url] para saber cómo compilarlo o instalarlo — el
README de allí cubre los requisitos de toolchain y los pasos de build.

## Uso

Clona este repositorio y ejecuta cualquier ejemplo con `paco run`, apuntando
a su punto de entrada `.paco`:

```sh
git clone https://github.com/pacolang/examples.git
cd examples
paco run examples/http-server/main.paco
```

(Ajusta la ruta al punto de entrada según el ejemplo que quieras ejecutar —
los ejemplos de un solo archivo se ejecutan directamente, y los ejemplos con
su propio subdirectorio se ejecutan a través de su `main.paco`.)

## Contribuir

Se aceptan nuevos ejemplos. Si tienes un programa pequeño y enfocado que
muestre bien una funcionalidad del lenguaje Paco o una API de la biblioteca
estándar, abre un pull request:

1. Haz un fork del repositorio.
2. Crea una rama para tu ejemplo (`git checkout -b add-example-name`).
3. Agrega tu ejemplo en su propio archivo o subdirectorio, con un comentario
   breve al inicio explicando qué demuestra.
4. Haz commit de tus cambios y abre un pull request.

## Licencia

Distribuido bajo la Apache License 2.0. Consulta [`LICENSE`](LICENSE) para
más información.

## Contacto

Enlace del proyecto: [https://github.com/pacolang/paco](https://github.com/pacolang/paco)


[paco-url]: https://github.com/pacolang/paco
[contributors-shield]: https://img.shields.io/github/contributors/pacolang/examples.svg?style=for-the-badge
[contributors-url]: https://github.com/pacolang/examples/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/pacolang/examples.svg?style=for-the-badge
[forks-url]: https://github.com/pacolang/examples/network/members
[stars-shield]: https://img.shields.io/github/stars/pacolang/examples.svg?style=for-the-badge
[stars-url]: https://github.com/pacolang/examples/stargazers
[issues-shield]: https://img.shields.io/github/issues/pacolang/examples.svg?style=for-the-badge
[issues-url]: https://github.com/pacolang/examples/issues
[license-shield]: https://img.shields.io/github/license/pacolang/examples.svg?style=for-the-badge
[license-url]: https://github.com/pacolang/examples/blob/main/LICENSE
