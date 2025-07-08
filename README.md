# Let me Ask (Frontend)

Este projeto é o frontend da aplicação Let me Ask, desenvolvido durante o evento **NLW Agents #20** da RocketSeat.

## Visão Geral

O frontend do Let me Ask é uma aplicação web moderna construída com React e Vite, utilizando TypeScript para tipagem estática e Tailwind CSS para estilização. Ele interage com o backend para gerenciar salas e perguntas, proporcionando uma experiência de usuário fluida e responsiva.

## Tecnologias Utilizadas

- **React**: Biblioteca JavaScript para construção de interfaces de usuário.
- **Vite**: Ferramenta de build frontend que oferece uma experiência de desenvolvimento rápida.
- **TypeScript**: Superset do JavaScript que adiciona tipagem estática, melhorando a robustez do código.
- **Tailwind CSS**: Framework CSS utility-first para construção rápida de designs personalizados.
- **Radix UI**: Biblioteca de componentes de UI de baixo nível e acessíveis.
- **React Router DOM**: Para roteamento de SPA (Single Page Application).
- **TanStack Query (React Query)**: Para gerenciamento de estado assíncrono e cache de dados.
- **Zod**: (Mencionado no backend, mas relevante para validação de dados em ambos os lados) Biblioteca de validação de esquemas TypeScript-first.

## Padrões de Projeto e Estrutura

O projeto segue uma estrutura de componentes e páginas, comum em aplicações React:

- `src/pages`: Contém os componentes de nível superior que representam as diferentes páginas da aplicação (ex: `create-room.tsx`, `room.tsx`).
- `src/components`: Armazena componentes reutilizáveis, incluindo uma subpasta `ui` para componentes de UI genéricos (ex: `button.tsx`).
- `src/lib`: Inclui utilitários e funções auxiliares (ex: `utils.ts`).
- `src/main.tsx`: Ponto de entrada da aplicação React.

## Setup e Configuração

Para configurar e executar o projeto frontend localmente, siga os passos abaixo:

### Pré-requisitos

Certifique-se de ter o Node.js e o npm (ou yarn) instalados em sua máquina.

### 1. Clonar o Repositório

```bash
git clone https://github.com/MSixels/Web_let_me_ask.git
cd Web_let_me_ask
```

### 2. Instalar Dependências

```bash
npm install
# ou yarn install
```

### 3. Iniciar a Aplicação em Modo de Desenvolvimento

```bash
npm run dev
# ou yarn dev
```

Isso iniciará o servidor de desenvolvimento do Vite. A aplicação estará acessível em `http://localhost:5173` (ou outra porta, se configurado).

### 4. Build para Produção

Para gerar uma build otimizada para produção:

```bash
npm run build
# ou yarn build
```

Os arquivos de build serão gerados na pasta `dist/`.

### 5. Visualizar a Build de Produção (Opcional)

Para testar a build de produção localmente:

```bash
npm run preview
# ou yarn preview
```

## Contribuição

Sinta-se à vontade para contribuir com este projeto. Para isso, faça um fork do repositório, crie uma nova branch para suas alterações e envie um pull request.

## Licença

Este projeto está licenciado sob a licença ISC. Veja o arquivo `LICENSE` para mais detalhes. (Assumindo licença ISC com base no package.json)


