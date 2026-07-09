# Pokédex — Projeto Final Angular

Projeto final desenvolvido com **Angular** e **TypeScript**, utilizando a **PokéAPI** como base de dados.

O projeto foi desenvolvido a partir dos conhecimentos adquiridos durante o curso e recebeu novas funcionalidades, melhorias visuais e alterações na experiência de navegação.

##Principais alterações feitas

- Criação do componente **PokeExplorerPanel**, com painel de navegação, contador de Pokémon visíveis, contador de capturados, filtro por tipo e botão de sorteio.

- Criação do componente **PokeEmptyState**, exibido quando uma busca ou filtro não encontra resultados.

- Cards da listagem redesenhados com número da Pokédex, cor dinâmica por tipo, animação de entrada, hover com movimento no Pokémon e botão de captura.

- Melhoria no sistema de busca, que agora permite encontrar Pokémon por qualquer parte do nome, e não apenas pelo início.

- Implementação de filtro por tipo utilizando chips dinâmicos gerados a partir dos dados carregados.

- Implementação da funcionalidade de **capturar Pokémon**, com persistência dos dados utilizando `localStorage`.

- Página de detalhes refeita com hero visual, card animado do Pokémon, botão shiny, captura, navegação anterior/próximo, ficha rápida e barras de estatísticas animadas.

- Tela de login implementada com formulário reativo, validação de email/senha, integração com backend fake JWT em Node.js e redirecionamento para a Home após autenticação.

- Modo claro/escuro implementado com variáveis CSS globais, botão de alternância no header e adaptação visual dos cards, filtros, botões e tela de login.

- Remoção da dependência externa do Google Fonts para evitar erros durante o build de produção em ambientes offline.

## Funcionalidades

A aplicação permite pesquisar e filtrar Pokémon, visualizar informações detalhadas, alternar entre as versões normal e shiny, capturar Pokémon, acompanhar a quantidade de capturados, sortear Pokémon aleatórios e alternar entre os temas claro e escuro.

O projeto também conta com uma tela de autenticação integrada a um backend Node.js com JWT, permitindo o acesso à Pokédex após a validação das credenciais.
