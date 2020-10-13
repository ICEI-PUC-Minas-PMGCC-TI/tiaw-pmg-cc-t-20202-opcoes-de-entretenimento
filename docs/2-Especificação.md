# Especificações Do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Contexto.md"> Documentação de Contexto</a></span>
* As personas foram montadas com base em intrevistas feitas pelos participantes do grupo


## Personas

Enzo da Silva tem 11 anos, é estudante do Ensino Fundamental. Pensa em se tornar
jodador profissional de Futebol quando crescer, sua preocupação atual é passar na escola e 
desenvolver uma relação mais saudavel com seu irmão durante a Pandemia.

Karen Pereira tem 22 anos, é estudante de Desing Grafico e está em um estagio.
Pensa em se formar, se tornar financeiramente independente, se mudar para a Europa
e futuramente se casar lá, atualmente ela enfrenta a frustração de não poder sair com as amigas
por isso precisa encontrar formas de se relacionar melhor com sua familia.

Joel Batista tem 56 anos, aposentado e atualmente dá consultoria de engenharia civil.
Pensa em juntar a familia o maximo possivel e que seus netos tenham uma educação de qualidade
sua preocupação atual é descobrir os gostos dos seus netos e se aproximar deles.


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Enzo da Silva       | Descobrir filmes novos rapidamente | Para ter sugestões do que assistir com os pais|
|Enzo da Silva       | Conhecer jogos de celular novos    | Para poder jogar com os irmãos         |
|Karen Pereira       | Séries de acordo com meus gostos   | Para ver com as amigas                 |
|Karen Pereira       | Ver os filmes mais relevantes do momento | para comentar sobre eles com a mãe |
|Karen Pereira       | Recomendações de filmes românticos | para assistir com a mãe que também gosta do gênero|
|Joel Batista        | Conhecer jogos de criança          | ocupar o tempo quando estiver com o neto |
|Karen Pereira       | poder visualizar as opções de entretenimento tanto no desktop quanto no celular |para poder procurar opções de entretenimento em qualquer lugar|
|Joel Batista        | Interface com possibilidade de zoom| para facilitar a leitura e procura     |
|Joel Batista        | buscar por palavra-chave           | ajudar a encontrar conteúdo que nao sei o nome certo|
|Joel Batista        | Interface simples                  | para ficar mais fácil navegar no aplicativo |
|Karen Pereira       | Ficar atualizada nos últimos lançamentos de filmes e séries| para assistir com seu irmão|
|Joel Batista        | Manter um registro de filmes de ação que me interesse| visualizar depois e manter um histórico deles para me lembrar depois |
|Enzo da Silva       | Avaliar o conteúdo                 | ter uma referência sobre o conteúdo    |
|Enzo da Silva       | compartilhar conteúdo por fora do site| enviar aos amigos  |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001|O site deve apresentar uma database de filmes e séries(API ou server local) | ALTA | 
|RF-002| O site deve oferecer uma funcionalidade de filtro/pesquisa para permitir ao usuário localizar um conteúdo baseado no seu título, gênero, atores ou sinopse informado na caixa de pesquisa | MÉDIA |
|RF-003| O site deve permitir salvar conteúdos preferidos | BAIXA | 
|RF-004| O site deve separar os conteúdos por gênero, ano de publicação e autor| MÉDIA |
|RF-005| O site deve ter bom nível de contraste e visibilidade entre os elementos da tela em conformidade | BAIXA | 
|RF-006| O site deve possuir opção de criação de grupos para match de opções de entretenimento dentro da mesma família | ALTA |
|RF-007| O site deve apresentar um  sistema de avaliação | MÉDIA | 
|RF-008| O site deve possuir espaço para comentários | MÉDIA |
|RF-009| O site deve possuir um sistema de recomendações baseado nas avaliações dos usuários | MÉDIA | 
|RF-010| O site deve permitir que os usuários compartilhem recomendações do site | BAIXA |
|RF-011| O site deve possuir opção de cadastro de contas para usuários | ALTA | 

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O site deverá ser responsivo permitindo a visualização em desktop e em celular de forma adequada | ALTA | 
|RNF-002| O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge) | ALTA | 



## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o dia 14/12/2020    |

