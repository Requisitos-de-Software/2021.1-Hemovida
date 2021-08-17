# <center> Requisitos Elicitados </center>

## Histórico de versão
| Data | Versão | Autor | Descrição |
| :-: | :-: | :-: | :-: |
| 17/08/2021 | 0.1 | Jaime Juan e Victor Hugo | Criação do documento |
<div align="justify">

## 1. Introdução
Técnica de priorização de requisitos "First Things First" tem como objetivo estabelecer uma ordem relativa de prioridade em relação à implementação de certas funcionalidades, considerando fatores que impactam na disponibilização delas aos usuários da aplicação.

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
| RF02 | Ter a opção de logout | Brainstorm |
| RF03 | Ter a opção de criar conta pelo Meugov.br | Brainstorm |
| RF04 | O usuário deve poder visualizar regras e intruções para a realização da doação | Observação |
| RF05 | Ter a opção de convidar um amigo | Brainstorm |
| RF06 | O usuário deve poder visualizar seus dados pessoais (nome, email, telefone, CPF, CNS, tipo de conteúdo) | Observação |
| RF07 | Ter a opção de visualizar histórico de doações | Brainstorm |
| RF08 | Ter a opção de visualizar campanhas de doação | Brainstorm |
| RF09 | Ter a opção de ver notificações sobre doações agendadas | Brainstorm |
| RF10 | Ter a opção de solicitar agendamento de doação | Brainstorm |
| RF11 | Ter a opção de ver a lista de hemocentros próximos a localização | Brainstorm |
| RF12 | Ter a opção de escolher a localização para procurar hemocentros próximos | Brainstorm |
| RF13 | Ter a opção de usar a localização do dispositivo para procurar hemocentros próximos | Brainstorm |
| RF14 | O usuário deve poder visualizar informações (telefone, horário de atendimento, site, endereço ...) sobre o hemocentro selecionado | Observação |
| RF15 | Ter a opção de ver rotas para locomoção ao hemocentro | Brainstorm |
| RF16 | Ter a opção de visualizar um mapa com a localização dos hemocentros próximos | Brainstorm |
| RF17 | Ter a opção de ver a data da ultima doação feita | Brainstorm |
| RF18 | Ter a opção de ver a data da próxima doação | Brainstorm |
| RF19 | Ter a opção de notificar o usuário sobre campanhas de doação | Brainstorm |
| RF20 | Ter a opção de notificar o usuário sobre a data de sua próxima doação | Brainstorm |
| RF21 | O usuário deve poder selecionar um hemocentro da lista | Observação |
| RF22 | O sistema deve dar opções de aplicativos de rotas para o usuário | Observação |
| RF23 | 	O usuário deve poder visualizar as notificações recebidas | Observação |
| RF24 | O usuário deve poder visualizar dados sobre o aplicativo (versão, quem desenvolveu ...) | Observação |
| RF25 | O usuário deve poder compartilhar a localização do hemocentro mais próximo de sua localização | Observação |
| RF26 | O usuário deve ser capaz de avaliar o hemocentro | StoryBoard |
| RF27 | Detalhar dados do hemocentro | Introspecção |
| RF28 | Compartilhar campanha via rede social | Introspecção |
| RN01 | O aplicativo deve ter um layout responsivo para variados tamanhos de telas | Brainstorm |
| RN02 | O aplicativo deve ser leve (não ser maior que 100MB) | Brainstorm |
| RN03 | O aplicativo deve ser rapido (não demorar mais que 500ms para abrir e carregar informações) | Brainstorm |
| RN04 | 	O aplicativo deve ter compatibilidade com diversos sistemas operacionais (IOS, Android, versão web) | Brainstorm |
| RN05 | O aplicativo deve ter modo escuro e modo claro | Brainstorm |
| RN06 | O aplicativo deve ter uma interface simples e amigavel | Brainstorm |
| RN07 | O aplicativo deve ter fácil uso | Brainstorm |
| RN08 | O aplicativo deve ser intuitivo | Brainstorm |

## 4. Priorização First Things First
<!-- Victor Hugo - Completar a Tabela e solicitar o PR -->
| Funcionalidade | Benefício relativo | Penalidade | Valor Total | Valor % | Custo Relativo | Custo % | Risco relativo | Risco % | Prioridade |
| -------------- | ------------------ | ---------- | ----------- | ------- | -------------- | ------- | -------------- | ------- | ---------- |
| RFxx |xx|xx|xx|xx,xxxx|xx|xx,xxxx|x|xx,xxxx|xx,xxxx|
| RFxx |xx|xx|xx|xx,xxxx|xx|xx,xxxx|x|xx,xxxx|xx,xxxx|
| Total |xx|xx|xx|100|xx|100|xx|100|-|

### **Pesos adotados:**
- Peso Relativo: 1.
- Peso Custo: 1.
- Peso Risco: 1.

## 5. Referências
First Things First: Prioritizing Requirements. E.Wiegers, Karl. Disponível em: https://www.processimpact.com/articles/prioritizing.pdf. Acesso em 17 de agosto de 2021.