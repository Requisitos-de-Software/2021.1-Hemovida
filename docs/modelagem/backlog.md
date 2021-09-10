# <center> Backlog do Produto


## Histórico de versão
| Data | Versão | Autor | Descrição |
| :-:|:-:|:-:|:-: |
| 31/08/2021 | 0.1 | João Victor e Victor Hugo | Criação do documento |
| 02/09/2021 | 0.3 | Jaime Juan | Adição dos links léxicos |

<div align="justify">

## 1. Introdução

O Product Backlog é uma lista com as funcionalidades de um produto, representando o que um cliente deseja receber ao final do projeto, e é descrito com uma linguagem própria. Esta lista sofre mudanças ao decorrer do projeto, a medida que se entende mais sobre o produto e seus [usuários](./modelagem/lexico?id=usuário).

As user stories ou Historias de Usuário são uma descrição de uma necessidade do [usuário](./modelagem/lexico?id=usuário) do produtor sobre o ponto de vista desse [usuário](./modelagem/lexico?id=usuário). Ela busca descrever requisitos de uma forma simples e leve.

## 2. Metodologia

Para a criação das histórias de [usuário](./modelagem/lexico?id=usuário), foi feita uma adptação dos requisitos elicitados para o formato de histórias de [usuário](./modelagem/lexico?id=usuário) e depois listadas no backlog.

As histórias de [usuário](./modelagem/lexico?id=usuário) seguem o seguinte padrão: "Eu como [usuário](./modelagem/lexico?id=usuário)[persona], [desejo]...[para que assim]..." .

## 4. Resultados

| Épico | Feature | ID | História de Usuário | Requisito |
| ----- | ------- | -- | ------------------- | --------- |
| EP01- Autenticação | Login<hr>Cadastro | US01<br>US02<hr>US03 | Eu como [usuário](./modelagem/lexico?id=usuário) do sistema desejo realizar o login utilizando o gov.br para que possa ter acesso ao aplicativo<br>Eu como [usuário](./modelagem/lexico?id=usuário) do sistema desejo realizar o [logout](./modelagem/lexico?id=logout)  para que possa me desconectar do aplicativo<hr>Eu como [usuário](./modelagem/lexico?id=usuário) do sistema desejo realizar o cadastro no gov.br para poder realizar o login no aplicativo | RF01<br>RF02<hr>RF03 |
| EP02 - Regras de doação | Regras | US04 | Eu como [usuário](./modelagem/lexico?id=usuário) do sistema desejo [visualizar regras e instruções para realizar doações](./modelagem/lexico?id=visualizar-regras-e-instruções-para-realizar-doações) para que possa me preparar | RF04 |
| EP03 - Doador | Informações pessoais<hr>Informações sobre o app<hr>[Convidar amigo](./modelagem/lexico?id=convidar-amigo)<hr>Informações sobre doação | US05<hr>US06<hr>US07<hr>US08<br>US09<br>US10 | Eu como [usuário](./modelagem/lexico?id=usuário) do sistema desejo visualizar meus dados pessoais para poder verificar se estão corretos<hr>Eu como [usuário](./modelagem/lexico?id=usuário) do sistema desejo visualizar dados sobre o aplicativo para poder verificar sua versão e quem o desenvolveu<hr> Eu como [usuário](./modelagem/lexico?id=usuário) do sistema desejo poder [convidar amigos](./modelagem/lexico?id=convidar-amigo) para que eles possam realizar a [doação de sangue](./modelagem/lexico?id=doação-de-sangue)<hr>Eu como [usuário](./modelagem/lexico?id=usuário) desejo visualizar o histórico de doações para que possa ver informações sobre doações já realizadas<br>Eu como [usuário](./modelagem/lexico?id=usuário) desejo visualizar a data da ultima doação realizada para poder planejar a data da próxima<br>Eu como [usuário](./modelagem/lexico?id=usuário) desejo visualizar a data da próxima doação para poder planejar com antecedencia | RF06<hr>RF24<hr>RF05<hr>RF07<br>RF17<br>RF18 |
| EP04 - [Hemocentro](./modelagem/lexico?id=hemocentro) | Solicitar agendamento de doação<hr>Ver a lista de [hemocentros](./modelagem/lexico?id=hemocentro) próximos a localização<hr>Procurar [hemocentros](./modelagem/lexico?id=hemocentro) próximos<hr>Usar a localização do dispositivo para procurar [hemocentros](./modelagem/lexico?id=hemocentro) próximos<hr>Visualizar informações sobre o [hemocentro](./modelagem/lexico?id=hemocentro)<hr>Ver rotas para locomoção ao [hemocentro](./modelagem/lexico?id=hemocentro)<hr>Visualizar um mapa com a localização dos [hemocentros](./modelagem/lexico?id=hemocentro) próximos<hr>Selecionar um [hemocentro](./modelagem/lexico?id=hemocentro) da lista<hr> Dar opções de aplicativos de rotas para o [usuário](./modelagem/lexico?id=usuário)<hr>Avaliar o [hemocentro](./modelagem/lexico?id=hemocentro)<hr>Detalhar dados do [hemocentro](./modelagem/lexico?id=hemocentro) | US011<hr>US012<hr>US013<hr>US014<hr>US015<hr>US016<hr>US017<hr>US018<hr>US019<hr>US020<hr>US021 | Eu como [usuário](./modelagem/lexico?id=usuário) preciso preciso solicitar um agendamento para minha doação<hr>Eu como [usuário](./modelagem/lexico?id=usuário) desejo ver uma lista dos [hemocentros](./modelagem/lexico?id=hemocentro) próximos a minha localização<hr>Eu como [usuário](./modelagem/lexico?id=usuário) gostaria de procurar [hemocentros](./modelagem/lexico?id=hemocentro) próximos apartir de uma localização escolhida<hr>Eu como [usuário](./modelagem/lexico?id=usuário) desejo usar a localização do meu dispositivo para procurar [hemocentros](./modelagem/lexico?id=hemocentro) próximos<hr>Eu como [usuário](./modelagem/lexico?id=usuário) preciso ver as informações sobre o [hemocentro](./modelagem/lexico?id=hemocentro) selecionado<hr>Eu como [usuário](./modelagem/lexico?id=usuário) preciso saber das melgores rotas possíveis para locomoção até o [hemocentro](./modelagem/lexico?id=hemocentro) selecionado<hr>Eu como [usuário](./modelagem/lexico?id=usuário) gostaria de ver um mapa com a localização dos [hemocentros](./modelagem/lexico?id=hemocentro) próximos<hr>Eu como [usuário](./modelagem/lexico?id=usuário) preciso poder selecionar um [hemocentro](./modelagem/lexico?id=hemocentro) da lista para ver sua informações e agendar doamento<hr>Eu como [usuário](./modelagem/lexico?id=usuário) gostaria de receber recomendações sobre aplicativos que possam traçar uma rota até o [hemocentro](./modelagem/lexico?id=hemocentro) selecionado<hr>Eu como [usuário](./modelagem/lexico?id=usuário) gostaria de poder avaliar [hemocentros](./modelagem/lexico?id=hemocentro)<hr>Eu como [usuário](./modelagem/lexico?id=usuário) preciso receber dados detalhados do [hemocentro](./modelagem/lexico?id=hemocentro) | RF10<hr>RF11<hr>RF12<hr>RF13<hr>RF14<hr>RF15<hr>RF16<hr>RF21<hr>RF22<hr>RF26<hr>RF27 |
| EP05 - Avisos | Notificar doações agendadas confirmadas<hr>Notifcar novas campanhas de doação<hr>Notificar próxima doação<hr>[Visualizar notificações](./modelagem/lexico?id=visualizar-notificações) recebidas<hr>[Visualizar campanhas de doação](./modelagem/lexico?id=visualizar-campanhas-de-doações)<hr>[Compartilhar campanha](./modelagem/lexico?id=compartilhar-campanha-de-doação) via rede social | US022<hr>US023<hr>US024<hr>US025<hr>US026<hr>US027 | Eu como [usuário](./modelagem/lexico?id=usuário) desejo receber notificações confirmando minhas doações agendadas<hr>Eu como [usuário](./modelagem/lexico?id=usuário) gostaria de receber notificações me informando sobre novas campanhas de doação<hr>Eu como [usuário](./modelagem/lexico?id=usuário) preciso receber notificações me lembrando a data da próxima doação quando estiver próxima<hr>Eu como [usuário](./modelagem/lexico?id=usuário) gostaria de poder visualizar as notificações recebidas mesmo que já as tenha visto<hr>Eu como [usuário](./modelagem/lexico?id=usuário) preciso poder visualziar campanhas de doação para me informar melhor<hr>Eu como [usuário](./modelagem/lexico?id=usuário) gostaria de poder [compartilhar campanhas](./modelagem/lexico?id=compartilhar-campanha-de-doação) de interesse, via rede social | RF09<hr>RF19<hr>RF20<hr>RF23<hr>RF08<hr>RF28 |




## 6. Referências

- SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 15. 1º/2019. 46 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

</div> 