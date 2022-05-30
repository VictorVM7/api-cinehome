# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

## Personas

*João Alberto* - João Alberto Rodrigues tem 31 anos, mora com a esposa Marcela Diniz desde os 25 anos, quando se casaram. Ele é cadeirante desde os 26 anos quando sofreu um acidente de moto na esquina de sua casa. João é muito eclético com relação a filmes, não possuindo um gênero cinemático preferido e ele sempre está por dentro das notícias que envolvem esse meio artístico, sendo isso o principal fator que o fizesse a frequentar os cinemas antes de sofrer o acidente. No entanto, após sua lesão, João não consegue ir aos cinemas facilmente uma vez que, no lugar onde mora, não há calçadas regulares, há pouco movimento de transporte público, não possui muitas condições de ter veículos adaptados e o casal encontra dificuldades físicas de descolamento até o shopping da cidade, onde fica o cinema.

*Ana Beatriz* - Ana Beatriz Silva é uma jovem de 21 anos idade, filha do padeiro José Silva, filha da costureira de uma empresa de camisas Carla Silva e irmã mais velha de Gabriela de 12 anos. Ana, seguindo os passos da mãe, está fazendo um cursinho de moda na sua cidade no interior de Minas Gerais. Ela, como muitos outros brasileiros, nunca foi ao cinema pois o cinema mais próximo fica na cidade vizinha a 42km. Devido as condiçoes da família, eles ainda não tiveram a oportunidade de ver um filme lançado nos cinemas pois as condições são muito difíceis para eles, como o preço da gasolina, deslocamento, preço do ingressos e alimentação.

*Rafael Ambani* - Rafael Ambani é um jovem de 18 anos, filho do grande empresário Carlos Ambani. Rafael é recém formado no ensino médio pela melhor escola do estado onde vive. Ele gosta muito de filmes de super-heróis e um dos seus hobbies favoritos é maratonar filmes e séries. Como Rafael ainda não trabalha e tem poucas obrigações, ele passa bastante tempo na sala de filmes de sua casa com uma televisão de 82 polegadas, assistindo aos seriedados e filmes dos serviços de streaming. Rafael, por ser uma pessoa que poucas vezes sai de sua casa, gostaria que seus filmes favoritos que são lançados no cinema pudessem ser assistidos em sua casa devido ao conforto e a seus gostos pessoais.


## Histórias de Usuários

### Usuário
|  COMO  |	         QUERO	             |  PARA
|:------:| --------------------------- | ------------------------------------------------|
|Usuário	| Cadastrar	                  |  Ter acesso ao site e suas funcionalidades      |
|Usuário	| Ver os horários do filme   	|  Agendar o melhor horário para assistir o filme |
|Usuário	| Ver a sinopse de um filme	  |  Saber o resumo do filme                        |
|Usuário	| Comprar um ingresso	        |  Assisir ao filme escolhido                     |
|Usuário	| Alterar dados do meu perfil | 	Deixá-lo atualizado                            |
|Usuário	| Deslogar	                   |  Sair do site                                   |


### Administrador
|COMO	| QUERO	| PARA |
|:---:|-------|------|
|Administrador	| Disponibilizar os filmes                  |	Usuários poderem assistir             |
|Administrador	| Excluir, manter, alterar e criar usuários | Controle do sistema                   |
|Administrador	| Alterar informações do site               |	Deixá-las atualizadas                 |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Não Funcionais

|   ID	  |              Descrição do Requisito	                 | Prioridade |
|:------:|------------------------------------------------------|:----------:|
|RNF-001	| Ser responsivo (Adaptar as telas)	    | Alta       |
|RNF-002	| Proteger o login e senha do usuário	  | Alta       |
|RNF-003	| A navegação deve ser intuitiva e fácil	              | Média      |
|RNF-004	| A interface precisa conter elementos minimalistas	   | Baixa      |
|RNF-005 |	O sistema deve oferecer um meio de pagamento seguro	 | Alta       |
|RNF-006	| O site deve ser construído em HTML, CSS e JS	        | Média      |


### Requisitos Funcionais

|ID|	Descrição do Requisito |	Prioridade | 
|:-:|-----------------------|:----------:|
|RF-001|	Cadastrar no sistema |	Alta |
|RF-002|	Realizar login	| Alta |
|RF-003|	Opçao para acessar sessão do filme para assistir |	Alta |
|RF-004|	Emitir os ingressos virtuais para o usuário com os horários |	Alta |
|RF-005|	Escolher o filme para assistir |	Média |
|RF-006|	Opção de marcar a sessão do filme |	Média |
|RF-007|	Dar opção de acessibilidade (legendas, alto contraste) |	Média |
|RF-008|	Pesquisar por filmes e filtrá-los por gênero |	Baixa |
|RF-009|	Ver dados dos filmes |	Baixa |
|RF-010|	Dar opção de lembrete para o usuário |	Baixa |
|RF-011|	Avaliar o filme assistido |	Baixa |

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).

## Restrições

| ITEM	| RESTRIÇÃO         |
|:----:|-------------------|
|    1 |	O usuário não poderá gravar ou printar a tela durante o filme |
|    2 |	O usuário não poderá ver o filme sem pagar | 
|    3 |	O administrador não terá acesso aos dados críticos do usuário (Dados bancários) |
|    4 |	Não será possíver dar uma avaliação sem ter assistido o filme |
|    5 |	O usuário não poderá parar o filme e assistir depois |

## LINK DA PLANILHA DE ESPECIFICAÇÃO:
https://drive.google.com/drive/folders/1hpnijMHbGk5BzVUdY7hBcFGXEb4rrCB5
