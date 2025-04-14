# API em Go e Framework Chi - Encurtador de URL

## Projeto desenvolvido baseado no módulo Criando uma API REST da Formação em Go da Rocketseat

### Tecnologias

<img src="https://cdn.simpleicons.org/go/00ADD8" height="40" alt="go logo"  />

|Tecnologia | Descrição |
|-----------|-----------|
|Go         |Linguagem de programação estaticamente e fortemente tipada|
|Chi        |Framework para Go que facilita a criação de servidores HTTP|


### Descrição do projeto

O Encurtador de URL é uma API RESTful que recebe uma URL padrão e a encurta gerando um link com pouco caracteres.

O projeto foi desenvolvido em Go junto o framework Chi para aplicar mais recursos na criação da API como os middlewares.

### Funcionalidades

- Encurtar a URL passada
- Redirecionar para a página correspondente da URL encurtada

### Endpoints

- Encurtar URL: `POST/api/shorten`
- Redirecionar: `GET/{code}`

No endpoint para redirecionar para a página corresponde é passado o código (URL encurtada).

### Rodando localmente

Você precisa ter instalado [Go](https://go.dev/) em sua máquina. Versão utilizada: ```go1.22.4```

Clone o repositório

```bash
git clone https://github.com/joaomarcosg/Projeto-Encurtador-de-URL-Golang.git
```

Inicie o servidor

```bash
go run main.go
```