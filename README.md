# React Movies

![movie](https://github.com/user-attachments/assets/b9bb0db4-07e0-4e2c-b193-7f3279dd50b5)

## Sobre o projeto

**React Movies** é um projeto prático de landing page do canal JavaScript Mastery. O site exibe os filmes mais populares de acordo com a API TMDB (The Movie Database) e um top 5 de filmes com base nos mais buscados.

Site totalmente responsivo.  

Status: ✔️Finalizado

##  Recursos e Tecnologias Utilizadas
- **React.js**
- **useDebounce**
- **Tailwind CSS**
- **TMBD API**
- **AppWrite**

## Como Rodar na sua máquina

**Pré-requisitos**

Certifique-se de ter o seguinte instalado em sua máquina:

- Git
- Node.js
- npm 

Em seguida, clone o repositório com o comando:

```bash
git clone https://github.com/stephanybrazeir0/react-movies.git
```

Abra a pasta do projeto no seu VSCode e instale as dependências com:

```bash
npm install
```

Para configurar as variáveis de ambiente você precsara criar na raiz do projeto um arquivo .env.local com os seguintes conteúdos:

```bash
VITE_TMDB_API_KEY=
VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_COLLECTION_ID=
```

Substitua os valores pelas suas credenciais da API do The Movie Database e do AppWrite. Para isso, você deve criar uma conta no TMDB e criar um projeto no AppWrite com um banco de dados e uma coleção.

Por fim, você pode executar o projeto com `npm run dev` em seu terminal e abrir a URL http://localhost:5173 no seu navegador. 


