<h1 align="center">
    ♻️ <a href="#" alt=""> API REST - SpringBoot Base </a>
</h1>

<h3 align="center">
   API Base para uso em projetos.
</h3>

<p align="center">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
</p>

<h4 align="center">
  Concluído
</h4>

Tabela de Conteúdos
=================
<!--ts-->
  * [Sobre o projeto](#-sobre-o-projeto)
  * [Funcionalidades](#-funcionalidades)
  * [Como executar o projeto](#-como-executar-o-projeto)
    * [Pré-requisitos](#pré-requisitos)
  * [Tecnologias](#-tecnologias)
  * [Contribuidores](#-contribuidores)
  * [Como contribuir no projeto](#-como-contribuir-no-projeto)
  * [Autor](#-autor)
  * [Licença](#user-content--licença)
<!--te-->


## Sobre o projeto

Essa API básica foi desenvolvida para agilizar a criação de novos projetos de APIs REST utilizando Java + SpringBoot

## Funcionalidades

- [x] A API BASE possui:
 - [x] Implementação de uma camada de clientes, com mapeamento e registro de dados básicos no banco

---

## Como executar

Este projeto segue a estrutura de uma API REST utilizando SpringBoot

### Pré-requisitos

Antes de começar é necessário ter o Java instalado (version "1.8.0_201") e configurado na máquina.

É necessário possuir uma IDE Java (Recomendado Eclipse) instalada e configurada;

A seguir é recomendada a insatalação do STS (SpringToolSuite) contudo, pode ser utilizada sua IDE de preferência
https://spring.io/tools;

A API BASE está configurada com Lombok para gerar o getters e setters de forma automática, contudo, para a aplicação funcionar o Lombok precisa estar instalado nas IDEs (Eclipse e STS) https://projectlombok.org/download

Em caso de dúvidas ou problemas na instalação do Lombok segue um exemplo no MACOS https://stackoverflow.com/questions/65017414/mac-os-lombok-installation-in-sts

Agora é a hora de clonar ou baixar o projeto e importar na IDE, ápos o carregamento do maven, rode o projeto.

```bash

# O servidor inciará na porta:8080 - acesse http://localhost:8080 Certifique-se que a porta está disponível  

```

---

## Tecnologias

As seguintes ferramentas foram usadas na construção da API:

#### **Website**  ([Java]()  +  [SpringBoot]())

-   **[Java 8]()**
-   **[SpringBoot]()**
-   **[DevTools]()**
-   **[JPA]()**
-   **[H2]()**

> Veja o arquivo  [pom.xml]()

---

## 👨‍💻 Contribuidores

<table>
 <tr>
    <td align="center"><a href=""><img style="" src="" width="100px;" alt=""/><br /><sub><b>Messias Martins</b></sub></a><br /><a title=""></a></td>
   
 </tr>
</table>

## Quer contribuir?

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`
> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](./CONTRIBUTING.md)

---

## Autor

<br />
<sub><b>Messias Martins 🇧🇷</b></sub></a>
<br />

---

## 📝 Licença

Este projeto está sobre a [MIT](./LICENSE).