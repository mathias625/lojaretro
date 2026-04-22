# Loja Retrô Games

Projeto fullstack de uma loja de videogames retrô com CRUD completo de produtos.

---

## Sobre o projeto

Este projeto foi desenvolvido com o objetivo de praticar conceitos de desenvolvimento web fullstack, incluindo:

* Backend com Node.js e Express
* Banco de dados MySQL
* Frontend com HTML, CSS e JavaScript
* Integração via API REST

A aplicação permite gerenciar produtos de uma loja retrô, como consoles, jogos e acessórios.

---

## Funcionalidades

* Listar produtos
* Cadastrar novos produtos
* Editar produtos existentes
* Excluir produtos
* Visualizar detalhes

---

## Tecnologias utilizadas

### Backend

* Node.js
* Express
* MySQL (mysql2)
* dotenv
* cors

### Frontend

* HTML5
* CSS3
* JavaScript 

---

## Como rodar o projeto

### 1. Banco de dados

Execute o script SQL:
```
---

### 2. Backend

Entre na pasta:

```bash
cd Back
```

Instale as dependências:

```bash
npm init -y
npm install express cors mysql2 dotenv
```

Configure o arquivo `.env`:

```
DATABASE_URL=localhost
DATABASE_USER=root
DATABASE_PASSWORD=
DATABASE=lojaretro
```

Execute o servidor:

```bash
node server.js
```

Servidor disponível em:

```
http://localhost:3000
```

---

### 3. Frontend

Abra a pasta `Front` e:

* Clique com o botão direito no arquivo `index.html`
* Abra com Live Server

---

## Rotas da API

| Método | Rota          | Descrição         |
| ------ | ------------- | ----------------- |
| GET    | /produtos     | Listar produtos   |
| POST   | /produtos     | Criar produto     |
| GET    | /produtos/:id | Buscar produto    |
| PUT    | /produtos/:id | Atualizar produto |
| DELETE | /produtos/:id | Deletar produto   |

---

## Exemplo de produto

```json
{
  "nome": "Super Nintendo",
  "imagem": "url_da_imagem",
  "preco": 899.90,
  "categoria": "Console",
  "marca": "Nintendo"
}
```

---

## Problemas comuns

* API não conecta: verifique se o backend está rodando
* Erro de banco: confira o arquivo `.env`
* Imagens não aparecem: verifique os links

---

## Melhorias futuras

* Sistema de login
* Carrinho de compras
* Deploy online
* Filtro por categoria
* Busca de produtos

---

## Autor

Desenvolvido por Mathias Pereira
