# <center> MoSCoW

## Histórico de versão
| Data | Versão | Autor | Descrição |
| :-: | :-: | :-: | :-: |
| 20/08/2021 | 0.1 | Guilherme Braz | Criação do documento |
| 20/08/2021 | 0.2 | João Victor | Revisão do documento |
<div align="justify">

## 1. Introdução
Esse documento contém uma análise dos requisitos levantados. Essa análise é feita através do método MoSCoW que auxilia na determinação de uma sistema de prioridades, classificando os requisitos conforme alguns critérios.

## 2. Metologia
Como falado brevemente na introdução, o método MoScoW é utilizado para definir prioridades e graus de importâncias para os requisitos do projeto. Ele utiliza de 4 critérios:

- **Must**:  requisitos indispensáveis para o projeto, o mesmo não pode ser entregue sem esses requisitos completos, pois são essenciais para completude do escopo do projeto.

- **Should**: são requisitos importantes e que agregam muito ao projeto, mas não são considerados indispensáveis para a completude do projeto.

- **Could**: requisitos que são desejáveis, porém não necessários para entrega ou satisfação do cliente. Portanto são tarefas que podem ser feitas caso haja tempo e recursos sobrando para finalizá-las.

- **Won’t**: são requisitos de menor prioridade, não são necessários para o momento, podendo até atrapalhar o andamento do projeto. 


## 3. Resultado
| ID | Requisito | MoSCoW |
| :-: | :- | :- |
| RF01 | Ter a opção de login pelo Meugov.br | Must |
| RF02 | Ter a opção de [logout](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=logout) | Must |
| RF03 | Ter a opção de criar conta pelo Meugov.br | Must |
| RF04 | O [usuário](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=usuário) deve poder visualizar regras e intruções para a realização da doação | Should |
| RF05 | Ter a opção de convidar um amigo | Should |
| RF06 | O [usuário](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=usuário) deve poder visualizar seus dados pessoais (nome, email, telefone, CPF, CNS, tipo de conteúdo) | Must |
| RF07 | Ter a opção de [visualizar histórico de doações](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=visualizar-histórico-de-doações) | Must |
| RF08 | Ter a opção de [visualizar campanhas de doação](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=visualizar-campanhas-de-doações) | Must |
| RF09 | Ter a opção de ver notificações sobre doações agendadas | Could |
| RF10 | Ter a opção de solicitar agendamento de doação | Should |
| RF11 | Ter a opção de ver a lista de [hemocentro](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=hemocentro)s próximos a localização | Could |
| RF12 | Ter a opção de escolher a localização para procurar [hemocentro](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=hemocentro)s próximos | Could |
| RF13 | Ter a opção de usar a localização do dispositivo para procurar [hemocentro](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=hemocentro)s próximos | Could |
| RF14 | O [usuário](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=usuário) deve poder visualizar informações (telefone, horário de atendimento, site, endereço ...) sobre o [hemocentro](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=hemocentro) selecionado | Must |
| RF15 | Ter a opção de ver rotas para locomoção ao [hemocentro](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=hemocentro) | Could |
| RF16 | Ter a opção de visualizar um mapa com a localização dos [hemocentro](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=hemocentro)s próximos | Won't |
| RF17 | Ter a opção de ver a data da ultima doação feita | Must |
| RF18 | Ter a opção de ver a data da próxima doação | Must |
| RF19 | Ter a opção de notificar o [usuário](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=usuário) sobre campanhas de doação | Could |
| RF20 | Ter a opção de notificar o [usuário](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=usuário) sobre a data de sua próxima doação | Should |
| RF21 | O [usuário](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=usuário) deve poder selecionar um [hemocentro](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=hemocentro) da lista | Should |
| RF22 | O sistema deve dar opções de aplicativos de rotas para o [usuário](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=usuário) | Won't |
| RF23 | O [usuário](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=usuário) deve poder visualizar as notificações recebidas | Must |
| RF24 | O [usuário](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=usuário) deve poder visualizar dados sobre o aplicativo (versão, quem desenvolveu ...) | Must |
| RF25 | O [usuário](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=usuário) deve poder compartilhar a localização do [hemocentro](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=hemocentro) mais próximo de sua localização | Could |
| RF26 | O [usuário](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=usuário) deve ser capaz de avaliar o [hemocentro](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=hemocentro) | Could |
| RF27 | Detalhar dados do [hemocentro](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=hemocentro) | Should |
| RF28 | [compartilhar campanha](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=compartilhar-campanha-de-doação) via rede social | Should |
| RN29 | O aplicativo deve ter um layout responsivo para variados tamanhos de telas | Must |
| RN30 | O aplicativo deve ser leve (não ser maior que 100MB) | Should |
| RN31 | O aplicativo deve ser rapido (não demorar mais que 500ms para abrir e carregar informações) | Should |
| RN32 | O aplicativo deve ter compatibilidade com diversos sistemas operacionais (IOS, Android, versão web) | Must |
| RN33 | O aplicativo deve ter modo escuro e modo claro | Could |
| RN34 | O aplicativo deve ter uma interface simples e amigavel | Must |
| RN35 | O aplicativo deve ter fácil uso | Must |
| RN36 | O aplicativo deve ser intuitivo | Must |

## 4. Referências
SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 07. 1º/2019. Slides apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.