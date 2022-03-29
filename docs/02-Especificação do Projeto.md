# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

*João Alberto* - João Alberto Rodrigues tem 31 anos, mora com a esposa Marcela Diniz desde os 25 anos, quanso se casaram. Ele é cadeirante desde os 26 anos quando sofreu um acidente de moto na esquina de sua casa. João é muito eclético com relação a filmes, não possuindo um gênero cinemático preferido e ele sempre está por dentro das notícias que envolvem esse meio artístico, sendo isso o principal fator que o fizesse a frequentar os cinemas antes de sofrer o acidente. No entanto, após sua lesão, João não consegue ir aos cinemas facilmente uma vez que, no lugar onde mora, não há calçadas regulares, há pouco movimento de transporte público, não possui muitas condições de ter veículos adaptados e o casal encontra dificuldades físicas de descolamento até o shopping da cidade, onde fica o cinema.

*Ana Beatriz* - Ana Beatriz Silva é uma jovem de 21 anos idade, filha do padeiro José Silva, filha da costureira de uma empresa de camisas Carla Silva e irmã mais velha de Gabriela de 12 anos. Ana, seguindo os passos da mãe, está fazendo um cursinho de moda na sua cidade no interior de Minas Gerais. Ela, como muitos outros brasileiros, nunca foi ao cinema pois o cinema mais próximo fica na cidade vizinha a 42km. Devido as condiçoes da família, eles ainda não tiveram a oportunidade de ver um filme lançado nos cinemas pois as condições são muito difíceis para eles, como o preço da gasolina, deslocamento, preço do ingressos e alimentação.

*Rafael Ambani* - Rafael Ambani é um jovem de 18 anos, filho do grande empresário Carlos Ambani. Rafael é recém formado no ensino médio pela melhor escola do estado onde vive. Ele gosta muito de filmes de super-heróis e um dos seus hobbies favoritos é maratonar filmes e séries. Como Rafael ainda não trabalha e tem poucas obrigações, ele passa bastante tempo na sala de filmes de sua casa com uma televisão de 82 polegadas, assistindo aos seriedados e filmes dos serviços de streaming. Rafael, por ser uma pessoa que poucas vezes sai de sua casa, gostaria que seus filmes favoritos que são lançados no cinema pudessem ser assistidos em sua casa devido ao conforto e a seus gostos pessoais.


## Histórias de Usuários

### Usuário
|  COMO  |	         QUERO	             |  PARA
|:------:| --------------------------- | ------------------------------------------------|
|Usuário	| Entrar no site             	|  Entender as funcionalidades do site            |  
|Usuário	| Cadastrar	                  |  Ter acesso ao site e suas funcionalidades      |
|Usuário	| Ver os horários do filme   	|  Agendar o melhor horário para assistir o filme |
|Usuário	| Ver a sinopse de um filme	  |  Saber o resumo do filme                        |
|Usuário	| Comprar um ingresso	        |  Assisir ao filme escolhido                     |
|Usuário	| Alterar dados do meu perfil | 	Deixá-lo atualizado                            |
|Usuário	| Deslogar	                   |  Sair do site                                   |


### Administrador
|COMO	| QUERO	| PARA |
|:---:|-------|------|
|Administrador |	Aprovar perfil de usuário	| Verificação de veracidade do cadastro |
|Administrador	| Disponibilizar os filmes |	Usuários poderem assistir |
|Administrador	| Excluir, manter, alterar e criar usuários | Controle do sistema |
|Administrador	| Alterar informações do site |	Deixá-las atualizadas |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
