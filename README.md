Runeterra Explorador de Campeões
1. Carregamento da Página

Ao abrir o arquivo index.html, uma tela de carregamento (#loading-screen) é exibida com uma citação do jogo. Durante esse processo:

O arquivo Personagem.json é carregado e processado pelo script.js.

Para cada campeão encontrado, o JavaScript cria um card e o insere na seção principal (<section class="card-container">).

Após o término do carregamento, a tela de loading é ocultada e a galeria de campeões é exibida ao usuário.

2. Galeria de Campeões

A área principal (<main>) apresenta uma grade composta por cards individuais. Cada card representa um campeão e exibe:

Imagem

Nome

Título

Ao clicar em um card, o script.js abre a janela de detalhes (#champion-details-modal), onde informações mais completas do campeão são apresentadas.

3. Busca e Autocomplete

O campo de busca (#input-busca) permite localizar campeões pelo nome. Conforme o usuário digita:

A lista de autocomplete (#autocomplete-list) sugere campeões correspondentes ao termo digitado.

Ao confirmar a busca, a galeria exibe apenas os campeões compatíveis com o termo inserido.

4. Filtros e Ordenação
Filtros por Função

O sistema permite filtrar campeões de acordo com suas funções, como Top, Jungle, Mid, ADC e Support. O botão Todos restaura a visualização completa.

Ordenação

A–Z: Reorganiza os campeões em ordem alfabética.

Ano de lançamento: Ordena os campeões pelo ano em que foram adicionados ao jogo.

Limpar: Remove todos os filtros e ordenações, retornando ao estado padrão.

5. Janela de Detalhes (Modal)

Ao selecionar um campeão, é aberto um modal com fundo dinâmico (#modal-background) baseado na imagem do próprio campeão. O conteúdo interno (#modal-content) exibe informações detalhadas oriundas do Personagem.json, incluindo:

Nome e título

História completa

Citação

Gráficos de dificuldade, força e dano

Habilidades com ícones e descrições

Galeria de skins

O modal pode ser fechado clicando no botão (#modal-close-btn) ou clicando fora da área principal.

Resumo

O projeto integra HTML, JSON e JavaScript para criar uma interface dinâmica e intuitiva que permite explorar campeões do universo de League of Legends, oferecendo recursos de busca, filtros, ordenação e uma janela de detalhes avançada.
