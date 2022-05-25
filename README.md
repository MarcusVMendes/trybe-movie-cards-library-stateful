# Boas vindas ao repositório do projeto movie cards library stateful!


Este projeto foi desenvolvido por [MarcusVMendes](http://www.linkedin.com/in/marcusvmendes-dev) enquanto estudante de Desenvolvimento Web Full Stack na [Trybe](https://www.linkedin.com/school/betrybe/) no periodo 2021/2022, como requisito parcial para aprovação de módulo.  #vqv 🚀

A proposta do projeto é desenvolver uma single-page application utilizando componentes React com estado e ciclo.


# Habilidades

  - Ler o estado de um componente e usá-lo para alterar o que exibimos no browser
  - Inicializar um componente, dando a ele um estado pré-definido
  - Atualizar o estado de um componente
  - Capturar eventos utilizando a sintaxe do React
  - Criar formulários utilizando sintaxe JSX com as tags : `input`, `textarea`, `select`, `form`
  - Transmitir informações de componentes filhos para componentes pais via callbacks.<br><br>


# Instalação do projeto localmente

Após cada um dos passos, haverá um exemplo do comando a ser digitado para fazer o que está sendo pedido, caso tenha dificuldades e o exemplo não seja suficiente, não hesite em me contatar em _marcus.mendes89@gmail.com_.
<br>
<br>

<div style="text-align: left">1. Abra o terminal e crie um diretório no local de sua preferência com o comando <b>mkdir</b>:</div><br>

```javascript
mkdir projetos
```
<br>
<div style="text-align: left">2. Entre no diretório que acabou de criar e depois clone o projeto:<div><br>


```javascript
cd projetos
git clone git@github.com:MarcusVMendes/trybe-movie-cards-library-stateful.git
```
<br>
<div style="text-align: left">3. Acesse o diretório do projeto e depois utilize o comando <b>npm install</b> para instalar todas as dependências necessárias:<div><br>

```javascript
cd trybe-movie-cards-library-stateful
npm install
```

<br>
<div style="text-align: left">4. Na raiz do repositório, executar o comando <b>npm start</b> para inicializar a execução do projeto:<div><br>

```javascript
npm start
```
<br>

# Sumário


- [Requisitos do Projeto](#requisitos-do-projeto)

    `Requisitos do projeto:`
    - [1 - Crie um componente chamado `<SearchBar />`](#1---crie-um-componente-chamado-searchbar-)
    - [2 - Renderize um formulário dentro de `<SearchBar />`](#2---renderize-um-formulário-dentro-de-searchbar-)
    - [3 - Renderize um input do tipo texto dentro do formulário em `<SearchBar />`](#3---renderize-um-input-do-tipo-texto-dentro-do-formulário-em-searchbar-)
    - [4 - Renderize um input do tipo checkbox dentro do formulário em `<SearchBar />`](#4---renderize-um-input-do-tipo-checkbox-dentro-do-formulário-em-searchbar-)
    - [5 - Renderize um select dentro do formulário em `<SearchBar />`](#5---renderize-um-select-dentro-do-formulário-em-searchbar-)
    - [6 - Crie um componente chamado `<AddMovie />`](#6---crie-um-componente-chamado-addmovie-)
    - [7 - Renderize um formulário dentro de `<AddMovie />`](#7---renderize-um-formulário-dentro-de-addmovie-)
    - [8 - Renderize um input do tipo texto dentro do formulário em `<AddMovie />` para obter o título do novo filme](#8---renderize-um-input-do-tipo-texto-dentro-do-formulário-em-addmovie--para-obter-o-título-do-novo-filme)
    - [9 - Renderize um input do tipo texto dentro do formulário em `<AddMovie />` para obter o subtítulo do novo filme](#9---renderize-um-input-do-tipo-texto-dentro-do-formulário-em-addmovie--para-obter-o-subtítulo-do-novo-filme)
    - [10 - Renderize um input do tipo texto dentro do formulário em `<AddMovie />` para obter o caminho da imagem do novo filme](#10---renderize-um-input-do-tipo-texto-dentro-do-formulário-em-addmovie--para-obter-o-caminho-da-imagem-do-novo-filme)
    - [11 - Renderize uma `textarea` dentro do formulário em `<AddMovie />` para obter a sinopse do novo filme](#11---renderize-uma-textarea-dentro-do-formulário-em-addmovie--para-obter-a-sinopse-do-novo-filme)
    - [12 - Renderize um `input` do tipo `number` dentro do formulário em `<AddMovie />` para obter a avaliação do novo filme](#12---renderize-um-input-do-tipo-number-dentro-do-formulário-em-addmovie--para-obter-a-avaliação-do-novo-filme)
    - [13 - Renderize um `select` do formulário em `<AddMovie />` para selecionar o gênero do novo filme](#13---renderize-um-select-do-formulário-em-addmovie--para-selecionar-o-gênero-do-novo-filme)
    - [14 - Renderize um botão do formulário em `<AddMovie />` para fazer uso dos dados do novo filme, contidos no estado de `<AddMovie />`](#14---renderize-um-botão-do-formulário-em-addmovie--para-fazer-uso-dos-dados-do-novo-filme-contidos-no-estado-de-addmovie)
    - [15 - Crie um componente chamado `<MovieLibrary />`](#15---crie-um-componente-chamado-movielibrary-)
    - [16 - Configure o estado inicial do componente `<MovieLibrary />`](#16---configure-o-estado-inicial-do-componente-movielibray-)
    - [17 - Renderize `<SearchBar />` dentro de `<MovieLibrary />`](#17---renderize-searchbar-dentro-de-movielibrary-)
    - [18 - Renderize `<MovieList />` dentro de `<MovieLibrary />`](#18---renderize-movielist--dentro-de-movielibrary-)
    - [19 - Renderize `<AddMovie />` dentro de `<MovieLibrary />`](#19---renderize-addmovie-dentro-de-movielibrary-)
    - [20 - Adicione proptypes a todos os componentes](#20---adicione-proptypes-a-todos-os-componentes)