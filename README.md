# Pokedex

Um projeto **Single Page Application (SPA)** que consome a [PokeAPI](https://pokeapi.co) para exibir informações de Pokémon de forma interativa e visualmente agradável.

---

##  Visão Geral

- **O que é:** Uma Pokedex online que exibe cards de Pokémon com dados como nome, tipo, imagem e mais.
- **Tecnologias:** HTML, CSS, JavaScript.
- **Objetivo:** Praticar consumo de APIs REST, manipulação do DOM, layout e responsividade.

---

##  Funcionalidades (Features)

- Buscar e exibir informações dos Pokémon usando a PokeAPI.
- Paginação ou busca por nome/id 
- Visualização de tipo(s), sprite/imagem e stats básicos (vida, ataque, etc.).
- Layout responsivo para desktop e mobile.

---

##  Pré-requisitos

- Navegador moderno com suporte ao Fetch API.
- Ambiente local (não obrigatório, mas recomendado):
  - Node.js + Live Server (VSCode) ou outro servidor estático.
  
---

##  Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/Carloscb124/Pokedex.git
   cd Pokedex
   ```
2. Se estiver usando servidor local, rode:
   ```bash
   live-server
   ```
3. Se não, abra diretamente o `index.html` no navegador.
4. Explore sua Pokedex localmente!

---

##  Estrutura de Pastas

```text
Pokedex/
├── index.html
├── README.md
├── js/
│   └── main.js         # Lógica (fetch, geração de cards, etc.)
├── css/
│   └── styles.css      # Estilos e responsividade
├── images/             # Imagens estáticas (como logo ou favicons)
└── assets/             # Outros recursos (se houver)
```

---

##  Como Funciona (Fluxo Interno)

1. O script faz uma requisição à PokeAPI para obter dados dos Pokémon.
2. É gerado um card com HTML contendo nome, imagem, tipos e stats.
3. Os cards são inseridos no DOM dinamicamente.
4. (Opcional) Adicionar filtros, navegação por página, e mais interações.

---

##  Tecnologias

- **Linguagens:** HTML5, CSS3, JavaScript (ES6+).
- **API:** [PokeAPI](https://pokeapi.co).
- **Ferramentas recomendadas:** VSCode, Live Server, Prettier.

---
