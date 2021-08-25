# <center> Cenários


## Histórico de versão
| Data | Versão | Autor | Descrição |
| :-:|:-:|:-:|:-: |
| 24/08/2021 | 0.1 | João Victor | Criação do documento |

<div align="justify">

## 1. Introdução
Os cenários são exemplos da vida real em que o sistema é ou será utilizado. É uma estrategia para compreender as interações entre ambientes e sistemas, assim como elicitar a parte comportamental do software, sua dinâmica e/ou seu fluxo.

## 2. Metodologia
Para a elaboração dos cenários, utilizaremos a tabela a seguir como modelo para os cenários.

| | |
| - | - |
| Título | Título do cenário |
| Objetivo | Objetivo/meta do cenário |
| Contexto | pré-condição:</br>pós-condição: |
| Atores | Atores envolvidos |
| Recursos | Recursos envolvidos |
| Episódios | Detalhes do cenário |
| Restrições | Descrição da restrição |
| Exceção | Descrição da exceção |

## 3. Objetivo

O objetivo desse documento é apresentar os cenários criados.

## 4. Cenários

### C01 - Login utilizando o gov.br
| | |
| - | - |
| Título | Login utilizando o gov.br |
| Objetivo | Logar no Hemovida para ter acesso a histórico de doações, agendamento, convite à amigos e etc. |
| Contexto | pré-condição: Possuir cadastro no Meugov.br</br>pós-condição: Usuário logado com acesso liberado às funcionalidades de agendamento, histórico etc. |
| Atores | Usuário |
| Recursos | Acesso à internet</br>App instalado |
| Episódios | 1.O usuário com cadastro no gov.br acessa o hemovida</br>2.O usuário não logado acessa a aba Doador</br>3.O usuário não logado seleciona o botão entrar</br>4.O usuário não logado seleciona o campo CPF e digita seu CPF</br>5.O usuário não logado seleciona o botão avançar</br>6. O usuário não logado seleciona o campo senha e digita sua senha</br>7.O usuário não logado seleciona o botão avançar</br> |
| Restrições | - |
| Exceção | CPF/senha inválidos</br>Usuário fechar aplicativo antes de terminar a ação</br>Internet parar de funcionar durante a ação |

### C02 - Visualizar histórico de doações
| | |
| - | - |
| Título | Visualizar histórico de doações |
| Objetivo | O usuário pode visualizar informações sobre doações ja feitas |
| Contexto | pré-condição:Usuário logado </br>pós-condição:O usuário verá as informações sobre suas doações já feitas |
| Atores | Usuário |
| Recursos | Acesso à internet |
| Episódios | 1.O usuário acessa o Hemovida</br>2.O usuário acessa a aba Doador</br>3.O usuário seleciona a opção Minhas doações</br> |
| Restrições | - |
| Exceção | O usuário não ter feito nenhuma doação</br>Usuário fechar aplicativo antes de terminar a ação</br>Internet parar de funcionar durante a ação |

### C03 - Visualizar campanhas de doação
| | |
| - | - |
| Título | Visualizar campanhas de doação |
| Objetivo | O usuário poder visualizar quais são as campanhas de doação que estão ocorrendo ou já foram finalizadas |
| Contexto | pré-condição: - </br>pós-condição:Usuário visualiza as campanhas de doação ativas |
| Atores | Usuário |
| Recursos | Acesso à internet |
| Episódios | 1.O usuário acessa o Hemovida</br>2.O usuário acessa a aba Campanhas</br>3.O usuário seleciona o link da campanha desejada |
| Restrições | - |
| Exceção | Não possuir campanhas para serem divulgadas</br>Usuário fechar aplicativo antes de terminar a ação</br>Internet parar de funcionar durante a ação |

### C04 - Agendamento de doação
| | |
| - | - |
| Título | Agendamento de doação |
| Objetivo | O usuário agendar uma doação de sangue no hemocentro desejado |
| Contexto | pré-condição:Usuário logado </br>pós-condição:Agendamento concluido |
| Atores | Usuário |
| Recursos | Acesso à internet |
| Episódios | 1.O usuário acessa o Hemovida</br>2.O usuário seleciona o hemocentro desejado</br>3.O usuário seleciona a aba Solicitar agendamento</br>4.O usuário seleciona a data desejada</br>5.O usuário seleciona um dos horários disponiveis daquele dia</br>6.O usuário confirma o agendamento   |
| Restrições | - |
| Exceção | O serviço de agendamento estar indisponível</br>Não possuir horários disponiveis no dia selecionado</br>Usuário fechar aplicativo antes de terminar a ação</br>Internet parar de funcionar durante a ação |

### C05 - Visualizar regras para doação
| | |
| - | - |
| Título | Visualizar regras para doação |
| Objetivo | o usuário visualizar quais são as regras e condições basicas para poder realizar a doação de sangue |
| Contexto | pré-condição: - </br>pós-condição:O usuário visualiza as regras de doação |
| Atores | Usuário |
| Recursos | - |
| Episódios | 1.O usuário acessa o Hemovida</br>2.O usuário seleciona a aba Regras |
| Restrições | - |
| Exceção | - |

## 5. Referências

Durante a elaboração desse documento, os seguintes documentos de Cenarios serviu como referência:

- [Documento de cenario do grupo iFut](https://requisitos-de-software.github.io/2020.1-iFut/modelagem/cenarios/cenariosTotais/)
- [Documento de cenario do grupo Plant Jammer](https://requisitos-de-software.github.io/2020.2-PlantJammer/#/pages/ponto_de_controle_3/cenarios)
- SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 10;
- BARBOSA, Simone; SILVA, Bruno. "Interação Humano-Computador". Elsevier Editora Ltda, 2010.


</div> 