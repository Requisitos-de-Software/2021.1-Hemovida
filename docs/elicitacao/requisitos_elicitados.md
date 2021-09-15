# <center> Requisitos Elicitados

## Histórico de versão
| Data | Versão | Autor | Descrição |
| :-: | :-: | :-: | :-: |
| 14/08/2021 | 0.1 | Lorrayne Cardozo | Criação do documento |
| 02/09/2021 | 0.2 | Jaime Juan | Adição dos links léxicos |
| 14/09/2021 | 0.3 | Lorrayne Cardozo | Correções nas técnicas utilizadas |

<div align="justify">

## 1. Introdução
O presente documento reúne todos os requisitos levantados ao longo do projeto utilizando técnicas de elicitação, totalizando 29 requisitos funcionais e 8 requisitos não-funcionais.

## 2. Metologia
A equipe utilizou diferentes técnicas de elicitação para levantar e concluir, finalmente, a lista de requisitos do projeto. As técnicas utilizadas foram:
* Brainstorm;
* Observação;
* Storytelling;
* Introspecção.

Os requisitos levantados em tais técnicas foram compilados e cada um deles é identificado por um ID, que possui o prefixo RF para requisitos funcionais e RNF para requisitos não-funcionais, juntamente com sua numeração. Para melhor rastreabilidade, as técnicas em que cada requisito se originou serão identificadas com a sigla da técnica juntamente com o número do requisito no devido documento. As técnicas serão referenciadas pelas seguintes siglas:

<center>

| Técnica | Sigla |
|:-:|:-:|
| Brainstorm   | BT |
| Observação   | OBS |
| Storytelling | ST |
| Introspecção | ITP |

</center>

## 3. Resultado
### 3.1. Requisitos Funcionais
| ID | Requisito | Técnica Utilizada |
| :-: | :- | :-: |
| RF01 | Ter a opção de login pelo Meugov.br | [BT01](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm), [OBS02](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao) |
| RF02 | Ter a opção de [logout](./modelagem/lexico?id=logout) | [BT02](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm) |
| RF03 | Ter a opção de se cadastrar pelo Meugov.br | [BT03](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm), [OBS01](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao) |
| RF04 | O [usuário](./modelagem/lexico?id=usuário) deve poder visualizar regras e intruções para a realização da doação | [BT04](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm), [OBS15](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao), [ST03](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/storyboard), [ITP07](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/introspeccao) |
| RF05 | Ter a opção de convidar um amigo | [BT05](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm), [OBS18](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao), [ITP14](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/introspeccao) |
| RF06 | O [usuário](./modelagem/lexico?id=usuário) deve poder visualizar seus dados pessoais (nome, email, telefone, CPF, CNS, tipo de conteúdo) | [BT06](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm), [OBS16](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao) |
| RF07 | Ter a opção de [visualizar histórico de doações](./modelagem/lexico?id=visualizar-histórico-de-doações) | [BT07](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm), [OBS19](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao), [ITP10](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/introspeccao) |
| RF08 | Ter a opção de [visualizar campanhas de doação](./modelagem/lexico?id=visualizar-campanhas-de-doações) | [BT08](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm), [OBS12](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao), [ITP05](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/introspeccao) |
| RF09 | Ter a opção de ver notificações sobre doações agendadas | [BT09](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm) |
| RF10 | Ter a opção de solicitar agendamento de doação | [BT10](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm), [OBS09](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao), [ITP12](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/introspeccao) |
| RF11 | Ter a opção de ver a lista de [hemocentros](./modelagem/lexico?id=hemocentro) próximos a localização | [BT11](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm), [OBS03](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao), [ST02](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/storyboard), [ITP01](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/introspeccao) |
| RF12 | Ter a opção de escolher a localização para procurar [hemocentros](./modelagem/lexico?id=hemocentro) próximos | [BT12](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm), [OBS04](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao) |
| RF13 | Ter a opção de usar a localização do dispositivo para procurar [hemocentros](./modelagem/lexico?id=hemocentro) próximos | [BT13](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm), [OBS05](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao) |
| RF14 | O [usuário](./modelagem/lexico?id=usuário) deve poder visualizar informações (telefone, horário de atendimento, site, endereço ...) sobre o [hemocentro](./modelagem/lexico?id=hemocentro) selecionado | [BT14](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm), [OBS08](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao) |
| RF15 | Ter a opção de ver rotas para locomoção ao [hemocentro](./modelagem/lexico?id=hemocentro) | [BT15](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm), [OBS10](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao), [ST01](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/storyboard), [ITP03](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/introspeccao) |
| RF16 | Ter a opção de visualizar um mapa com a localização dos [hemocentros](./modelagem/lexico?id=hemocentro) próximos | [BT16](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm), [OBS06](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao), [ITP04](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/introspeccao) |
| RF17 | Ter a opção de ver a data da última doação feita | [BT17](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm), [OBS20](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao) |
| RF18 | Ter a opção de ver a data da próxima doação | [BT18](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm), [OBS21](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao) |
| RF19 | Ter a opção de notificar o [usuário](./modelagem/lexico?id=usuário) sobre campanhas de doação | [BT19](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm) |
| RF20 | Ter a opção de notificar o [usuário](./modelagem/lexico?id=usuário) sobre a data de sua próxima doação | [BT20](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm) |
| RF21 | O [usuário](./modelagem/lexico?id=usuário) deve poder selecionar um [hemocentro](./modelagem/lexico?id=hemocentro) da lista | [OBS07](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao) |
| RF22 | O sistema deve dar opções de aplicativos de rotas para o [usuário](./modelagem/lexico?id=usuário) | [OBS11](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao) |
| RF23 | 	O [usuário](./modelagem/lexico?id=usuário) deve poder visualizar as notificações recebidas | [OBS14](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao), [ITP13](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/introspeccao) |
| RF24 | O [usuário](./modelagem/lexico?id=usuário) deve poder visualizar dados sobre o aplicativo (versão, quem desenvolveu ...) | [OBS17](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao) |
| RF25 | O [usuário](./modelagem/lexico?id=usuário) deve poder compartilhar a localização do [hemocentro](./modelagem/lexico?id=hemocentro) mais próximo de sua localização | [OBS22](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao), [ITP09](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/introspeccao) |
| RF26 | O [usuário](./modelagem/lexico?id=usuário) deve ser capaz de avaliar o [hemocentro](./modelagem/lexico?id=hemocentro) | [ST04](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/storyboard), [ITP11](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/introspeccao) |
| RF27 | Detalhar dados do [hemocentro](./modelagem/lexico?id=hemocentro) | [ITP02](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/introspeccao) |
| RF28 | [Compartilhar campanha](./modelagem/lexico?id=compartilhar-campanha-de-doação) via rede social | [OBS13](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/observacao), [ITP06](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/introspeccao) |
| RF29 | Espaço do doador de sangue | [ITP08](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/introspeccao) |


### 3.2. Requisitos Não-Funcionais
| ID | Requisito | Técnica Utilizada |
| :-: | :- | :- |
| RNF01 | O aplicativo deve ter um layout responsivo para variados tamanhos de telas | [BT21](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm) |
| RNF02 | O aplicativo deve ser leve (não ser maior que 100MB) | [BT22](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm) |
| RNF03 | O aplicativo deve ser rapido (não demorar mais que 500ms para abrir e carregar informações) | [BT23](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm) |
| RNF04 | 	O aplicativo deve ter compatibilidade com diversos sistemas operacionais (IOS, Android, versão web) | [BT24](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm) |
| RNF05 | O aplicativo deve ter modo escuro e modo claro | [BT25](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm) |
| RNF06 | O aplicativo deve ter uma interface simples e amigável | [BT26](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm) |
| RNF07 | O aplicativo deve ter fácil uso | [BT27](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm) |
| RNF08 | O aplicativo deve ser intuitivo | [BT28](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./elicitacao/brainstorm) |

## 5. Referências
> SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 07. 1º/2019. Slides apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.