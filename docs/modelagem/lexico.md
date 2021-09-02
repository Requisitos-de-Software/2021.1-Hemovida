# <center> Léxicos

## Histórico de Revisões

| Data | Versão | Autor | Descrição |
| --- | --- | --- | --- |
| 23/08/2021 | 1.0 | Guilherme Braz, Victor Hugo  | Criação do documento |


<div align="justify">

## Introdução 
Nessa parte da modelagem foi usado a técnica de léxicos para demonstrar e explicar o contexto/escopo do projeto em símbolos para ajudar na compreensão e organização da modelagem de requisitos.

## Metodologia
É uma técnica de modelagem para descrever símbolos do software. Esses símbolos servem para descrever o ambiente e a dinâmica que o software está inserido. Cada símbolo é descrito em:
- nome: nome do símbolo;
- sinônimo: possíveis sinônimos do símbolo;
- noção: significado do símbolo (denotação);
- impacto: efeito que o símbolo gera no software e efeitos sofridos pelo símbolo no contexto do mesmo (conotação);
- tipos: verbo, objeto, estado.

## Léxicos

### [agendar doações](./modelagem/lexico?id=agendar-doações) 
| | |
| :- | :- |
| Nome: | [agendar doação](./modelagem/lexico?id=agendar-doações) |
| Sinônimos: | marcar doação |
| Noção: | O [usuário](./modelagem/lexico?id=usuário) conferir uma agenda para poder marcar uma [doação de sangue](./modelagem/lexico?id=doação-de-sangue) futura e receber os dados do hemocentro para receber uma confirmação do agendamento, local e data |
| Impacto: | O [usuário](./modelagem/lexico?id=usuário) possui agendada uma [doação de sangue](./modelagem/lexico?id=doação-de-sangue) confirmada pelo hemocentro e que será notificada pelo Hemovida |
| tipo: | verbo  |

### [cadastrar](./modelagem/lexico?id=cadastrar)
| | |
| :- | :- |
| Nome: | [cadastrar](./modelagem/lexico?id=cadastrar) |
| Sinônimos: | Registrar  |
| Noção: | Cadastro de senha e obtenção de acesso aos dados referentes ao Hemovida |
| Impacto: | O [usuário](./modelagem/lexico?id=usuário) criar uma senha para acessar seus dados pessoais referentes ao Hemovida |
| tipo: | verbo  |

### [campanha de doação](./modelagem/lexico?id=campanha-de-doação) 
| | |
| :- | :- |
| Nome: | [campanha de doação](./modelagem/lexico?id=campanha-de-doação) |
| Sinônimos: | _ |
| Noção: | evento para [doação de sangue](./modelagem/lexico?id=doação-de-sangue)|
| Impacto: | proporciona um evento mais estruturado para [doação de sangue](./modelagem/lexico?id=doação-de-sangue) |
| tipo: | objeto  |

### Compartilhar [campanha de doação](./modelagem/lexico?id=campanha-de-doação) 
| | |
| :- | :- |
| Nome: | Compartilhar [campanha de doação](./modelagem/lexico?id=campanha-de-doação) |
| Sinônimos: | |
| Noção: | O [usuário](./modelagem/lexico?id=usuário) ser notificado de uma campanha [doação de sangue](./modelagem/lexico?id=doação-de-sangue) e caso seja do seu interesse convidar ou informar outras pessoas em suas redes sociais, será dada a opção para compartilhar a informação onde e com quem ele/ela quiser  |
| Impacto: | O aplicativo permite conscientizar outras pessoas sobre campanhas do governo e/ou beneficentes em relação a [doação de sangue](./modelagem/lexico?id=doação-de-sangue) permite que ele alcance novos [usuário](./modelagem/lexico?id=usuário)s a utilizarem o aplicativo e seus recursos |
| tipo: | verbo  |

### [convidar amigo](./modelagem/lexico?id=convidar-amigo)
| | |
| :- | :- |
| Nome: | [convidar amigo](./modelagem/lexico?id=convidar-amigo) |
| Sinônimos: | Invitar amigo, chamar amigo |
| Noção: | [convidar amigo](./modelagem/lexico?id=convidar-amigo)s para participar de doações de sangue  |
| Impacto: |  o [usuário](./modelagem/lexico?id=usuário) pode convidar um amigo para realizar doações de sangue |
| tipo: | verbo  |

### [data doação](./modelagem/lexico?id=data-doação) 
| | |
| :- | :- |
| Nome: | [data doação](./modelagem/lexico?id=data-doação) |
| Sinônimos: | Período da doação |
| Noção: | Data na qual a [doação de sangue](./modelagem/lexico?id=doação-de-sangue) do [usuário](./modelagem/lexico?id=usuário) foi realizada |
| Impacto: | data fica armazenada para solicitações de detalhes e histórico de doação |
| tipo: | estado  |

### [doação de sangue](./modelagem/lexico?id=doação-de-sangue) 
| | |
| :- | :- |
| Nome: | [doação de sangue](./modelagem/lexico?id=doação-de-sangue) |
| Sinônimos: | _ |
| Noção: | ato de doar sangue |
| Impacto: | doação é realizada para o hemocentro|
| tipo: | verbo  |

### Hemocentro 
| | |
| :- | :- |
| Nome: | Hemocentro |
| Sinônimos: | _ |
| Noção: | local onde se realiza a [doação de sangue](./modelagem/lexico?id=doação-de-sangue) e a [campanha de doação](./modelagem/lexico?id=campanha-de-doação) |
| Impacto: | Proporciona espaço para realização das atividades de [doação de sangue](./modelagem/lexico?id=doação-de-sangue): campanhas e a doação em si |
| tipo: | objeto  |

### [localização atual](./modelagem/lexico?id=localização-atual) 
| | |
| :- | :- |
| Nome: | [localização atual](./modelagem/lexico?id=localização-atual) |
| Sinônimos: | posição atual, lugar atual |
| Noção: | local onde o [usuário](./modelagem/lexico?id=usuário) está no momento atual |
| Impacto: | Proporciona a funcionalidade de rotas e mapas de hemocentro  |
| tipo: | estado  |

### [Logar](./modelagem/lexico?id=logar)
| | |
| :- | :- |
| Nome: | [Logar](./modelagem/lexico?id=logar) |
| Sinônimos: | acessar, entrar, conectar |
| Noção: | A partir da senha gerada no cadastro e os dados pessoais, o [usuário](./modelagem/lexico?id=usuário) consegue acessar com sua conta o aplicativo para utilizar os recursos do aplicativo sincronizado com suas informações |
| Impacto: | O [usuário](./modelagem/lexico?id=usuário) pode utilizar o aplicativo em vários dispositivos com seus dados pessoais sincronizados através de uma conta pessoal|
| tipo: | verbo  |


### [logout](./modelagem/lexico?id=logout)
| | |
| :- | :- |
| Nome: | [logout](./modelagem/lexico?id=logout) |
| Sinônimos: | desconectar, sair |
| Noção: | Ato de desconectar da aplicação |
| Impacto: | Encerra a sessão do [usuário](./modelagem/lexico?id=usuário) |
| tipo: | verbo |

### [Mapa de hemocentros](./modelagem/lexico?id=mapa-de-hemocentros) 
| | |
| :- | :- |
| Nome: | [Mapa de hemocentros](./modelagem/lexico?id=mapa-de-hemocentros) |
| Sinônimos: | _ |
| Noção: | [Mapa de hemocentros](./modelagem/lexico?id=mapa-de-hemocentros) perto do [usuário](./modelagem/lexico?id=usuário) |
| Impacto: | [usuário](./modelagem/lexico?id=usuário) pode visualizar um mapa contendo os hemocentros ao seu redor a partir de sua [localização atual](./modelagem/lexico?id=localização-atual) |
| tipo: | objeto  |

### [Rotas de locomoção](./modelagem/lexico?id=rotas-de-locomoção)
| | |
| :- | :- |
| Nome: | [Rotas de locomoção](./modelagem/lexico?id=rotas-de-locomoção) |
| Sinônimos: | Caminhos para locomoção |
| Noção: | Rotas para o hemocentro |
| Impacto: | Disponibiliza caminhos para o hemocentro, o qual o [usuário](./modelagem/lexico?id=usuário) poderá visualizar caso solicite |
| tipo: | objeto |

### [Visualizar campanhas de doações](./modelagem/lexico?id=visualizar-campanhas-de-doações) 
| | |
| :- | :- |
| Nome: | [Visualizar campanhas de doações](./modelagem/lexico?id=visualizar-campanhas-de-doações) |
| Sinônimos: | _ |
| Noção: | Acessar o aplicativo para visualizar as informações que levam a campanhas de doações de sangue linkadas no Hemovida |
| Impacto: | O [usuário](./modelagem/lexico?id=usuário) possui uma fonte direta à informações referentes a campanhas de [doação de sangue](./modelagem/lexico?id=doação-de-sangue) para poder participar e divulgar elas |
| tipo: | verbo  |

### [visualizar histórico de doações](./modelagem/lexico?id=visualizar-histórico-de-doações) 
| | |
| :- | :- |
| Nome: | [visualizar histórico de doações](./modelagem/lexico?id=visualizar-histórico-de-doações) |
| Sinônimos: | Solicitar histórico de doações |
| Noção: | O [usuário](./modelagem/lexico?id=usuário) pode verificar uma agenda pessoal com doações de sangue registradas anteriormente ao uso do aplicativo ou agendadas após |
| Impacto: | O [usuário](./modelagem/lexico?id=usuário) tem mais facilidade para poder verificar em um único local todo o histórico de doações registradas e agendas |
| tipo: | verbo |

### [visualizar lista de hemocentros](./modelagem/lexico?id=visualizar-lista-de-hemocentros) 
| | |
| :- | :- |
| Nome: | [visualizar lista de hemocentros](./modelagem/lexico?id=visualizar-lista-de-hemocentros) |
| Sinônimos: | Solicitar lista de hemocentros |
| Noção: | Acessar o aplicativo para visualizar uma lista de hemocentros linkadas no Hemovida e seus respectivos dados e informações relevantes |
| Impacto: | O [usuário](./modelagem/lexico?id=usuário) possui um meio direto à uma lista de hemocentros para poder verificar suas informações e possivelmente [agendar doações](./modelagem/lexico?id=agendar-doações) com mais facilidade |
| tipo: | verbo  |

### [visualizar notificações](./modelagem/lexico?id=visualizar-notificações) 
| | |
| :- | :- |
| Nome: | [visualizar notificações](./modelagem/lexico?id=visualizar-notificações) |
| Sinônimos: | _ |
| Noção: | O [usuário](./modelagem/lexico?id=usuário) verificar as notificações enviadas para ele através do aplicativo |
| Impacto: | O [usuário](./modelagem/lexico?id=usuário) não perde informações e alertas importante que ele espera receber ou pressupõe que já tenha visto |
| tipo: | verbo  |

### [visualizar regras e instruções para realizar doações](./modelagem/lexico?id=visualizar-regras-e-instruções-para-realizar-doações) 
| | |
| :- | :- |
| Nome: | [visualizar regras e instruções para realizar doações](./modelagem/lexico?id=visualizar-regras-e-instruções-para-realizar-doações) |
| Sinônimos: | _ |
| Noção: | O [usuário](./modelagem/lexico?id=usuário) pode ver as regras e instruções necessárias para poder realizar a [doação de sangue](./modelagem/lexico?id=doação-de-sangue) corretamente |
| Impacto: | [usuário](./modelagem/lexico?id=usuário) pode identificar as regras e instruções de [doação de sangue](./modelagem/lexico?id=doação-de-sangue), podendo [agendar doações](./modelagem/lexico?id=agendar-doações) e comparecer a campanhas de [doação de sangue](./modelagem/lexico?id=doação-de-sangue) sem dúvidas|
| tipo: | verbo  |

### [visualizar rotas para o hemocentro](./modelagem/lexico?id=visualizar-rotas-para-o-hemocentro) 
| | |
| :- | :- |
| Nome: | [visualizar rotas para o hemocentro](./modelagem/lexico?id=visualizar-rotas-para-o-hemocentro) |
| Sinônimos: | Solicitar rotas para o hemocentro |
| Noção: | [Rotas de locomoção](./modelagem/lexico?id=rotas-de-locomoção) para facilitar a ida ao hemocentro |
| Impacto: | [usuário](./modelagem/lexico?id=usuário) a partir de sua [localização atual](./modelagem/lexico?id=localização-atual), pode [visualizar rotas para o hemocentro](./modelagem/lexico?id=visualizar-rotas-para-o-hemocentro) de sua escolha |
| tipo: | verbo  |

### [usuário](./modelagem/lexico?id=usuário)
| | |
| :- | :- |
| Nome: | [usuário](./modelagem/lexico?id=usuário) |
| Sinônimos: | Cliente, Ator |
| Noção: | São os utilizadores do produto final de acordo com escopo pré-estabelecido |
| Impacto: | [usuário](./modelagem/lexico?id=usuário) pode [cadastrar](./modelagem/lexico?id=cadastrar), [Logar](./modelagem/lexico?id=logar), fazer [logout](./modelagem/lexico?id=logout), [visualizar regras e instruções para realizar doações](./modelagem/lexico?id=visualizar-regras-e-instruções-para-realizar-doações), [visualizar rotas para o hemocentro](./modelagem/lexico?id=visualizar-rotas-para-o-hemocentro), [visualizar notificações](./modelagem/lexico?id=visualizar-notificações), [visualizar lista de hemocentros](./modelagem/lexico?id=visualizar-lista-de-hemocentros), [convidar amigo](./modelagem/lexico?id=convidar-amigo), compartilhar [campanha de doação](./modelagem/lexico?id=campanha-de-doação) e [agendar doações](./modelagem/lexico?id=agendar-doações)   |
| tipo: | objeto  |

## Referências

> SAMPAIO, Julio; FRANCO, Ana. "A strategy for Conceptual Model Acquisition". Departamento de informática, Pontíficia Universidade Católica, Rio de Janeiro.

</div>