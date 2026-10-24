# EducAPI Manager Web (EducaManager)

O EducAPI Manager Web, ou Educa Manager (de forma abreviada), é um sistema web front-end, onde é possível gerenciar usuários, contextos/temas e desafios correspondentes a palavras por meio de sua interação com o serviço web EducAPI. O Web Service EducAPI é um sistema que serve de base para diversos aplicativos construídos no projeto de extensão Apps4Society e de pesquisa SisAlfa. Através dele é possível importar novos temas em aplicativos educacionais que auxiliam na alfabetização de crianças, jovens e adultos.


<!--  Use the website https://shields.io/ para fazer os bandge -->
![GitHub](https://img.shields.io/github/license/a4s-ufpb/EducAPI-Manager-Front?label=licence) ![Type Badge](https://img.shields.io/badge/project%3A-Apps4Society-informational) ![enter image description here](https://img.shields.io/badge/project-SisAlfa-yellow)  ![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/a4s-ufpb/EducAPI-Manager-Front?color=blueviolet)

<!--
<img src="https://apps4society.dcx.ufpb.br/wp-content/uploads/2019/06/Inicial.png"  alt="Splash do Literarum"  height="200" width="700"> 
-->

## 🎨 Layout

O layout da aplicação está disponível no Figma: 

<a href="https://www.figma.com/file/wFtRfZdifoyXkr3uGHjyfo/educ-api-manager?node-id=0%3A1">
  <img alt="Link do protótipo das telas no Figma" src="https://img.shields.io/badge/Acessar%20Layout%20-Figma-%2304D361">
</a>

## 🛠 Tecnologias Necessárias

Para rodar este projeto você irá precisar ter instalado o:

* [Docker](https://docs.docker.com/engine/install/) e [Docker Compose](https://docs.docker.com/compose/install/)

Se você não quiser utilizar o Docker para rodar a aplicação, você pode optar por instalar o: 

* [Node](https://nodejs.org/en/download/) 14.16.1+ LTS
* Npm 6.14.12+
* [Angular](https://angular.io/guide/setup-local) CLI 11.2.11+

 > Nota: Este projeto depende do serviço web [EducAPI](https://github.com/a4s-ufpb/EducAPI) para rodar

## :rocket: Como rodar o projeto ? 

Você primeiro vai precisar clonar o repositório do [EducAPI](https://github.com/a4s-ufpb/EducAPI) e seguir os passos para rodá-lo.


Após estar com o EducAPI rodando na sua máquina faça clone deste repositório.

````
$ git clone https://github.com/a4s-ufpb/EducAPI-Manager-Front.git
````

Se você optar por rodar esta aplicação com o Docker, primeiro entre no diretório raiz do proejto e depois suba os containers:

```
$ cd EducAPI-Manager-Front
$ docker-compose up -d
```

Se não, entre no diretório e instale as dependências do Node.

```
$ cd EducAPI-Manager-Front
$ npm install
```

Rode a aplicação com o comando:
```
ng serve
```

Espere para que o projeto seja compilado e vá para o ``localhost:4200``

---
