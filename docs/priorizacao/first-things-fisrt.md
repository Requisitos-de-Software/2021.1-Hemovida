# <center> First Things First

## Histórico de versão
| Data | Versão | Autor | Descrição |
| :-: | :-: | :-: | :-: |
| 17/08/2021 | 0.1 | Jaime Juan e Victor Hugo | Criação do documento |
| 18/08/2021 | 0.2 | Jaime Juan e Victor Hugo | Finalização da Tabela de Priorização |
| 02/09/2021 | 0.3 | Jaime Juan | Adição dos links léxicos |

<div align="justify">

## 1. Introdução
Técnica de priorização de requisitos "First Things First" tem como objetivo estabelecer uma ordem relativa de prioridade em relação à implementação de certas funcionalidades, considerando fatores que impactam na disponibilização delas aos [usuários](./modelagem/lexico?id=usuário) da aplicação.

## 2. Metologia
Nessa prática de priorização, é construída uma tabela de forma que equilibre os posionamentos do cliente e do desenvolvedor. Para isso, devem ser seguidos 8 (oito) passos:

- Passo 1: Listar todos os requisitos em uma tabela, retirando aqueles dependentes de outro requisito.

- Passo 2: Estimar o _Benefício Relativo_ que cada recurso fornece ao cliente ou ao negócio, de 1 a 9, em que 1 é o menos significativo e 9 o mais significativo.

- Passo 3: Estimar a _Penalidade Relativa_ que o negócio sofreria, se o recurso não fosse incluído, de 1 a 9, em que 1 é o com menor penalidade e 9 maior penalidade.

- Passo 4: A coluna _Valor Total_ é a soma do (_Benefício Relativo_ * _Peso Relativo_ + _Penalidade Relativa_ * _Peso Relativo_).

- Passo 5: Estimar o _Custo Relativo_ de implementação de cada requisito, de 1 a 9.

- Passo 6: Estimar o _Risco Relativo_ ao risco a cada requisito de uma escala de 1 a 9.

- Passo 7: Calcular a _Prioridade_ para cada requisito pela fórmula: _Valor %_ / (_Custo %_ * _Peso Custo_ + _Risco %_ * _Peso Risco_). 

- Passo 8: Ordenar a lista em ordem decrescente de prioridade.


## 3. Tabela de Referência - Requisitos Funcionais e Não Funcionais
| ID | Requisito | Técnica Utilizada |
| :-: | :- | :- |
| RF01 | Ter a opção de login pelo Meugov.br | Brainstorm |
| RF02 | Ter a opção de [logout](./modelagem/lexico?id=logout) | Brainstorm |
| RF03 | Ter a opção de criar conta pelo Meugov.br | Brainstorm |
| RF04 | O [usuário](./modelagem/lexico?id=usuário) deve poder visualizar regras e intruções para a realização da doação | Observação |
| RF05 | Ter a opção de convidar um amigo | Brainstorm |
| RF06 | O [usuário](./modelagem/lexico?id=usuário) deve poder visualizar seus dados pessoais (nome, email, telefone, CPF, CNS, tipo de conteúdo) | Observação |
| RF07 | Ter a opção de [visualizar histórico de doações](./modelagem/lexico?id=visualizar-histórico-de-doações) | Brainstorm |
| RF08 | Ter a opção de [visualizar campanhas de doação](./modelagem/lexico?id=visualizar-campanhas-de-doações) | Brainstorm |
| RF09 | Ter a opção de ver notificações sobre doações agendadas | Brainstorm |
| RF10 | Ter a opção de solicitar agendamento de doação | Brainstorm |
| RF11 | Ter a opção de ver a lista de [hemocentros](./modelagem/lexico?id=hemocentro) próximos a localização | Brainstorm |
| RF12 | Ter a opção de escolher a localização para procurar [hemocentros](./modelagem/lexico?id=hemocentro) próximos | Brainstorm |
| RF13 | Ter a opção de usar a localização do dispositivo para procurar [hemocentros](./modelagem/lexico?id=hemocentro) próximos | Brainstorm |
| RF14 | O [usuário](./modelagem/lexico?id=usuário) deve poder visualizar informações (telefone, horário de atendimento, site, endereço ...) sobre o [hemocentro](./modelagem/lexico?id=hemocentro) selecionado | Observação |
| RF15 | Ter a opção de ver rotas para locomoção ao [hemocentro](./modelagem/lexico?id=hemocentro) | Brainstorm |
| RF16 | Ter a opção de visualizar um mapa com a localização dos [hemocentros](./modelagem/lexico?id=hemocentro) próximos | Brainstorm |
| RF17 | Ter a opção de ver a data da ultima doação feita | Brainstorm |
| RF18 | Ter a opção de ver a data da próxima doação | Brainstorm |
| RF19 | Ter a opção de notificar o [usuário](./modelagem/lexico?id=usuário) sobre campanhas de doação | Brainstorm |
| RF20 | Ter a opção de notificar o [usuário](./modelagem/lexico?id=usuário) sobre a data de sua próxima doação | Brainstorm |
| RF21 | O [usuário](./modelagem/lexico?id=usuário) deve poder selecionar um [hemocentro](./modelagem/lexico?id=hemocentro) da lista | Observação |
| RF22 | O sistema deve dar opções de aplicativos de rotas para o [usuário](./modelagem/lexico?id=usuário) | Observação |
| RF23 | O [usuário](./modelagem/lexico?id=usuário) deve poder visualizar as notificações recebidas | Observação |
| RF24 | O [usuário](./modelagem/lexico?id=usuário) deve poder visualizar dados sobre o aplicativo (versão, quem desenvolveu ...) | Observação |
| RF25 | O [usuário](./modelagem/lexico?id=usuário) deve poder compartilhar a localização do [hemocentro](./modelagem/lexico?id=hemocentro) mais próximo de sua localização | Observação |
| RF26 | O [usuário](./modelagem/lexico?id=usuário) deve ser capaz de avaliar o [hemocentro](./modelagem/lexico?id=hemocentro) | StoryBoard |
| RF27 | Detalhar dados do [hemocentro](./modelagem/lexico?id=hemocentro) | Introspecção |
| RF28 | [Compartilhar campanha](./modelagem/lexico?id=compartilhar-campanha-de-doação) via rede social | Introspecção |
| RN01 | O aplicativo deve ter um layout responsivo para variados tamanhos de telas | Brainstorm |
| RN02 | O aplicativo deve ser leve (não ser maior que 100MB) | Brainstorm |
| RN03 | O aplicativo deve ser rapido (não demorar mais que 500ms para abrir e carregar informações) | Brainstorm |
| RN04 | O aplicativo deve ter compatibilidade com diversos sistemas operacionais (IOS, Android, versão web) | Brainstorm |
| RN05 | O aplicativo deve ter modo escuro e modo claro | Brainstorm |
| RN06 | O aplicativo deve ter uma interface simples e amigavel | Brainstorm |
| RN07 | O aplicativo deve ter fácil uso | Brainstorm |
| RN08 | O aplicativo deve ser intuitivo | Brainstorm |

## 4. Priorização First Things First
| Funcionalidade | Benefício relativo | Penalidade | Valor Total | Valor % | Custo Relativo | Custo % | Risco relativo | Risco % | Prioridade |
| -------------- | ------------------ | ---------- | ----------- | ------- | -------------- | ------- | -------------- | ------- | ---------- |
| RF20 |9|9|18|4,9451|7|3,8462|5|2,9412|0,7286|
| RF09 |8|8|16|4,3956|6|3,2967|5|2,9412|0,7047|
| RF18 |8|8|16|4,3956|6|3,2967|5|2,9412|0,7047|
| RF19 |8|9|17|4,6703|7|3,8462|5|2,9412|0,6881|
| RF06 |8|7|15|4,1209|7|3,8462|6|3,5294|0,5587|
| RF11 |8|8|16|4,3956|7|3,8462|7|4,1176|0,5519|
| RF04 |5|5|10|2,7473|5|2,7473|4|2,3529|0,5387|
| RF23 |7|5|12|3,2967|6|3,2967|5|2,9412|0,5285|
| RF25 |7|6|13|3,5714|6|3,2967|6|3,5294|0,5232|
| RF08 |7|8|15|4,1209|7|3,8462|7|4,1176|0,5175|
| RF28 |7|5|12|3,2967|7|3,8462|5|2,9412|0,4857|
| RF24 |4|3|7|1,9231|4|2,1978|3|1,7647|0,4853|
| RF05 |6|6|12|3,2967|6|3,2967|6|3,5294|0,4830|
| RF12 |7|7|14|3,8462|7|3,8462|7|4,1176|0,4830|
| RF14 |7|7|14|3,8462|7|3,8462|7|4,1176|0,4830|
| RF16 |7|7|14|3,8462|7|3,8462|7|4,1176|0,4830|
| RF07 |6|7|13|3,5714|6|3,2967|7|4,1176|0,4817|
| RF10 |8|8|16|4,3956|8|4,3956|9|5,2941|0,4536|
| RF13 |8|7|15|4,1209|8|4,3956|8|4,7059|0,4528|
| RF01 |7|6|13|3,5714|7|3,8462|7|4,1176|0,4485|
| RF02 |6|5|11|3,0220|6|3,2967|5|2,9412|0,4485|
| RF21 |7|6|13|3,5714|7|3,8462|7|4,1176|0,4485|
| RF27 |6|6|12|3,2967|7|3,8462|6|3,5294|0,4470|
| RF26 |7|4|11|3,0220|6|3,2967|6|3,5294|0,4427|
| RF17 |4|5|9|2,4725|6|3,2967|5|2,9412|0,3964|
| RF03 |6|5|11|3,0220|7|3,8462|7|4,1176|0,3795|
| RF15 |7|4|11|3,0220|7|3,8462|7|4,1176|0,3795|
| RF22 |4|4|8|2,1978|5|2,7473|6|3,5294|0,3502|
| Total |189|175|364|100|182|100|170|100|13,1792|

### **Pesos adotados:**
- Peso Relativo: 1.
- Peso Custo: 1.
- Peso Risco: 1.

## 5. Referências
First Things First: Prioritizing Requirements. E.Wiegers, Karl. Disponível em: https://www.processimpact.com/articles/prioritizing.pdf. Acesso em 17 de agosto de 2021.