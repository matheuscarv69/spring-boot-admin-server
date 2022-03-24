# 🌍 Spring Boot Admin Server 👀

Este projeto trata-se de uma implementação do Spring Boot Admin, que nada mais é que um aplicativo Web utilizado para
gerenciar e monitorar aplicações Spring Boot.

[![GitHub stars](https://img.shields.io/github/stars/matheuscarv69/spring-boot-admin-server?color=7159)](https://github.com/matheuscarv69/spring-boot-admin-server/stargazers)
![Maven Central with version prefix filter](https://img.shields.io/maven-central/v/org.apache.maven/apache-maven/3.6.3?color=7159)

## 🤔 O que é este projeto?

Uma implementação do Spring Boot Admin para monitorar aplicações desenvolvidas com Spring Boot.

### 🐳 Docker

Este projeto conta com um **Dockerfile**, com as instruções para realizar o build da aplicação.

Os requisitos para isso são:

- [Docker](https://www.docker.com/products/docker-desktop) - Baixe de acordo com o seu SO

A imagem da aplicação também está disponível no Docker Hub:

- [matheuscarv69/spring-boot-admin-server](https://hub.docker.com/r/matheuscarv69/spring-boot-admin-server)

Caso queria executa-lá através dessa imagem, abaixo tem alguns comandos que podem lhe ajudar:

## ⬇ 1. Pull

```shell
docker pull matheuscarv69/spring-boot-admin-server
```

## 🏃‍♂️ 2. Running

O comando abaixo executa a imagem baixada em um container, essa aplicação possui uma env var.

```shell
docker run -d -p 8081:8081 -e SERVER_PORT=8081 matheuscarv69/spring-boot-admin-server
```

## 🔧 Variáveis de Ambiente da Aplicação

| ENV_VARS                      | Descrição                                                        |
| ----------------------------- |------------------------------------------------------------------|
| SERVER_PORT                   | Porta que a aplicação utilizará em sua execução. (Default: 8081) |

## 📝 Acessando o painel da Aplicação

Essa aplicação disponibiliza um painel web para monitorar as aplicações, para visualizá-lo acesse a seguinte URL. 
(Atenção para a porta que você passou na variável de ambiente)

```bash
http://localhost:8081/wallboard
```

Você acessará essa tela que mostrará as aplicações clientes que estão em execução:

<img src="https://i.imgur.com/m7sg4pV.png" min-width="400px" max-width="600px"  alt="swagger">

Por meio desse painel é possível ter acesso à várias informações das aplicações:

<img src="https://i.imgur.com/dhZ43oe.png" min-width="400px" max-width="600px"  alt="swagger">


## 🚀 Tecnologias 👩‍🚀

As seguintes tecnologias foram utilizadas no desenvolvimento do projeto.

- Java 11
- Spring Boot 2.6.4
    - Web
    - Profiles (local)
- [Spring Boot Admin 2.5.1](https://codecentric.github.io/spring-boot-admin/current/)
## 👨🏻‍💻 Autor

<br>
<a href="https://github.com/matheuscarv69">
 <img style="border-radius: 35%;" src="https://avatars1.githubusercontent.com/u/55814214?s=460&u=ffb1e928527a55f53df6e0d323c2fd7ba92fe0c3&v=4" width="100px;" alt=""/>
 <br />
 <sub><b>Matheus Carvalho</b></sub></a> <a href="https://github.com/matheuscarv69" title="Matheus Carvalho">🚀</a>

Feito por Matheus Carvalho, entre em contato!✌🏻

 <p align="left">
    <a href="mailto:matheus9126@gmail.com" alt="Gmail" target="_blank">
      <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white&link=mailto:matheus9126@gmail.com"/></a>
    <a href="https://www.linkedin.com/in/matheus-carvalho69/" alt="Linkedin" target="_blank">
        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&link=https://www.linkedin.com/in/matheus-carvalho69/"/></a>  
    <a href="https://www.instagram.com/_mmcarvalho/" alt="Instagram" target="_blank">
      <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white&link=https://www.instagram.com/_mmcarvalho/"/></a>  
  </p>