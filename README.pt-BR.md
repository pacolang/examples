[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Apache 2.0 License][license-shield]][license-url]

<br />
<div align="center">
  <h1 align="center">Exemplos Paco</h1>

  <p align="center">
    Programas de exemplo demonstrando a linguagem de programação Paco
    <br />
    <a href="https://github.com/pacolang/paco"><strong>Conheça o compilador paco »</strong></a>
    <br />
    <br />
    <a href="https://github.com/pacolang/examples/issues">Relatar um problema</a>
    ·
    <a href="https://github.com/pacolang/examples/pulls">Contribuir com um exemplo</a>
  </p>
</div>

**Leia em:** [English](README.md) · **Português** · [Español](README.es.md)

## Índice

<ol>
  <li><a href="#sobre-o-projeto">Sobre o Projeto</a></li>
  <li><a href="#começando">Começando</a>
    <ul>
      <li><a href="#pré-requisitos">Pré-requisitos</a></li>
    </ul>
  </li>
  <li><a href="#uso">Uso</a></li>
  <li><a href="#contribuindo">Contribuindo</a></li>
  <li><a href="#licença">Licença</a></li>
  <li><a href="#contato">Contato</a></li>
</ol>

## Sobre o Projeto

Este repositório reúne programas de exemplo em Paco. Cada um é uma
demonstração pequena e autocontida de uma funcionalidade específica da
linguagem ou de uma capacidade da biblioteca padrão — concorrência, pattern
matching, diferenciação automática, e assim por diante — em vez de uma
aplicação completa.

Os exemplos costumavam viver dentro de `examples/` no repositório do
compilador [`pacolang/paco`][paco-url]. Foram movidos para cá para que o
repositório do compilador permaneça focado no compilador, no runtime e na
biblioteca padrão, enquanto este pode crescer de forma independente à medida
que novos exemplos forem adicionados.

Exemplos atuais:

- [`http-server/main.paco`](http-server/main.paco) — um servidor HTTP/1.1
  mínimo que cria uma tarefa por conexão, demonstrando o modelo de
  concorrência do Paco.

## Começando

### Pré-requisitos

Você precisa de um binário `paco` funcional no seu `PATH`. Veja
[`pacolang/paco`][paco-url] para saber como compilá-lo ou instalá-lo — o
README de lá cobre os requisitos de toolchain e os passos de build.

## Uso

Clone este repositório e execute qualquer exemplo com `paco run`, apontando
para o seu ponto de entrada `.paco`:

```sh
git clone https://github.com/pacolang/examples.git
cd examples
paco run examples/http-server/main.paco
```

(Ajuste o caminho para o ponto de entrada de acordo com o exemplo que você
quer rodar — exemplos de arquivo único rodam diretamente, e exemplos com seu
próprio subdiretório rodam através do seu `main.paco`.)

## Contribuindo

Novos exemplos são bem-vindos. Se você tem um programa pequeno e focado que
demonstra bem uma funcionalidade da linguagem Paco ou uma API da biblioteca
padrão, abra um pull request:

1. Faça um fork do repositório.
2. Crie uma branch para o seu exemplo (`git checkout -b add-example-name`).
3. Adicione seu exemplo em um arquivo ou subdiretório próprio, com um
   comentário curto no topo explicando o que ele demonstra.
4. Faça commit das suas alterações e abra um pull request.

## Licença

Distribuído sob a Apache License 2.0. Veja [`LICENSE`](LICENSE) para mais
informações.

## Contato

Link do projeto: [https://github.com/pacolang/paco](https://github.com/pacolang/paco)


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
