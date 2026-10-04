Pokédex — Trabalho Final de Frameworks Web I

Aplicação web interativa desenvolvida em React para consulta, busca, filtragem por tipo e visualização de detalhes de Pokémon consumindo a [PokéAPI](https://pokeapi.co/).

---

 Integrantes do Grupo

- Vinícius de Morais Furriel — Fundação, Listagem Principal e Paginação
- Otávio Sidnei dos Santos Andrade — Componentes de Interação, Cards, Busca e Filtros
- Natasha Pedroso Dias Alves — Rota Dinâmica de Detalhes, Loading e Tratamento de Erros
- João Lucas Rodrigues e Silva — Estilização Avançada com `styled-components`, Responsividade, Integração Final e Documentação

---

 Funcionalidades da Aplicação

- **Listagem Paginada:** Exibição contínua de Pokémon com cálculo dinâmico de `offset` e `limit`.
- **Busca em Tempo Real:** Input de pesquisa por nome do Pokémon.
- **Filtro por Tipo:** Seleção combinável por tipos (Fire, Water, Grass, Electric, etc.).
- **Otimização de Desempenho:** Aplicação do Hook `useMemo` na lógica de filtragem.
- **Página de Detalhes:** Navegação dinâmica (`/pokemon/:id`) exibindo estatísticas oficiais, peso, altura, tipos e habilidades.
- **Feedback Visual:** Componentes reutilizáveis de `Loading` (Spinner) e `ErrorMessage`.
- **Design Responsivo & CSS-in-JS:** Interface estilizada via `styled-components` com paleta de cores dinâmica para cada tipo de Pokémon e layout adaptável.

---

 Tecnologias Utilizadas

- **React 19**
- **Vite**
- **React Router Dom (v7)**
- **Axios**
- **Styled Components** (`styled-components`)

---

 Como Executar o Projeto Localmente

1. Clonar o repositório:
   `git clone [https://github.com/joaolucasrs7/trabalho-final-Frameworks_Web_I](https://github.com/joaolucasrs7/trabalho-final-Frameworks_Web_I)`