Pokedex - Explore o Mundo dos Pokémon

Visão Geral:
O projeto "Pokedex" oferece uma incrível experiência de imersão no universo dos Pokémon. Com recursos de captura, os usuários podem ampliar sua coleção de Pokémon. Além disso, informações detalhadas sobre cada Pokémon, incluindo estatísticas e habilidades, estão ao alcance dos treinadores. A flexibilidade de remover Pokémon da sua coleção também está à disposição. Esta aplicação proporciona uma jornada envolvente para os fãs, permitindo que eles interajam com os Pokémon de maneiras diversas e significativas.

Fonte de Dados:
Para criar essa experiência, nosso projeto utiliza a Poke API, uma API pública amplamente utilizada em aplicações de aprendizado de programação e em casos de processos seletivos. Ela é a nossa fonte confiável de informações sobre Pokémon.

Recursos Principais:
Integração de APIs: Utilizamos a Poke API para buscar dados essenciais sobre os Pokémon.
React Router: Navegação suave entre as diferentes páginas da aplicação.
Design Systems: Um design coeso e atraente em todo o aplicativo.
Estado Global: Mantemos um estado global para manter o controle dos Pokémon na coleção do usuário.
Páginas Principais
PokemonListPage
Nesta página, os usuários podem visualizar todos os Pokémon disponíveis.
Eles têm a opção de capturar novos Pokémon e visualizar detalhes.
Também é possível verificar a sua Pokedex pessoal para ver os Pokémon capturados.
PokedexPage
Aqui, os usuários podem ver todos os Pokémon capturados.
Eles têm a flexibilidade de excluir Pokémon de sua Pokedex.
Os dados são salvos automaticamente ao atualizar a página.
PokemonDetailPage
Nesta página, os usuários podem explorar detalhes abrangentes de cada Pokémon.
Eles têm a opção de capturar um Pokémon, caso ele não esteja na Pokedex, ou excluí-lo se já estiver.
Componentes Chave
PokemonCard: Exibe informações e botões para interagir com um Pokémon, como adicionar à Pokedex ou capturar.
Header: Cada página possui um header com uma interface específica.
Como Começar
Certifique-se de ter o Node.js e npm instalados.Clone o repositório.

No diretório do projeto, execute npm install para instalar as dependências.
Inicie o aplicativo com npm run start.
Tecnologias e Ferramentas Utilizadas
React
React Hooks
React Router Dom
React Context API
Axios para fazer chamadas à Poke API
Styled-Components para estilização
React Icons para ícones
Estrutura do Projeto
src: Contém todas as pastas e arquivos do projeto.
assets: Armazena imagens dos tipos de Pokémon e outras imagens utilizadas no projeto.
components: Contém componentes reutilizáveis, como PokemonCard e Header.
constants: Armazena a URL padrão da API utilizada.
contexts: Contém arquivos de contexto utilizados no projeto.
pages: Possui as páginas principais da aplicação, incluindo PokemonListPage, PokemonDetailPage e PokedexPage.
routes: Gerencia a navegação entre as páginas.

Contribuição:
Fique à vontade para contribuir com melhorias ou correções neste projeto. Sua participação é valiosa para tornar a experiência Pokémon ainda mais incrível!

Aventure-se e explore o emocionante mundo dos Pokémon com a Pokedex. Vamos começar a jornada!
