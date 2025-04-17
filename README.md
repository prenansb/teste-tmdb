# 🧪 Teste Técnico – Lista de Filmes com Filtros

## 🎯 Objetivo

Criar uma aplicação frontend que consome a API pública do [TMDB (The Movie Database)](https://developer.themoviedb.org/docs), listando filmes populares e permitindo filtrá-los por diferentes critérios.

---

## 📋 Requisitos

### Funcionalidades obrigatórias:

1. **Listar filmes populares**
   - Utilizar a [API de filmes populares](https://developer.themoviedb.org/reference/movie-popular-list) da TMDB.
   - Exibir:
     - Poster
     - Título
     - Data de lançamento
     - Nota média

2. **Filtros**
   - Adicione filtros para os seguintes campos:
     - **Gênero** (action, comedy, etc.) – [API de gêneros](https://developer.themoviedb.org/reference/genre-movie-list)
     - **Nota mínima**
     - **Ano de lançamento**
   - Os filtros devem ser feitos com **componentes do [shadcn/ui](https://ui.shadcn.com/)**, como:
     - `Select`
     - `Input`
     - `Slider`
     - `Button`

3. **UX**
   - Indicador de carregamento durante requisições.
   - Mensagem de erro caso algo falhe na requisição.
   - Interface responsiva.

---

## 💻 Requisitos técnicos

- **React** (pode usar Next.js ou Vite)
- **shadcn/ui** para UI
- **fetch** ou **axios** para chamadas HTTP
- Pode usar **Tailwind CSS**
- Código organizado e com boas práticas

---

## 🎯 Diferenciais (não obrigatórios)

- Paginação
- Deploy no Vercel ou Netlify

---

## 📦 Entrega

1. Suba o código no GitHub.
2. Crie um `README.md` com:
   - Como rodar o projeto
   - Quais decisões tomou no desenvolvimento
3. Envie o link do repositório para avaliação.

---

## 📅 Prazo sugerido

Você pode fazer no seu tempo, mas recomendamos finalizar em até **3 dias**.
