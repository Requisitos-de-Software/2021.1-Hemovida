# <center> Brainstorm


## Histórico de versão
| Data | Versão | Autor | Descrição |
| :-:|:-:|:-:|:-: |
| 11/08/2021 | 0.1 | João Victor | Criação do documento |

<div align="justify">

## 1. Introdução
A técnica de brainstorm busca encontrar a solução para um problema por meio do compartilhamento espontâneo de ideias. Para que seja um sucesso, esse processo deve se focar em quantidade e não em qualidade.

Com isso o brainstorm deve ser feito de uma maneira livre de críticas, mesmo as ideias que paracem ineficientes devem ser analisadas, pois a partir delas podem surgir pensamentos mais elaborados.

Os passos para a realização de um brainstorm são:

- Aquecimento
- Geração de ideias
- Agrupamento de ideias
- Encerramento

## 2. Metodologia
A equipe realizou uma reunião no dia 10/08/2021 para a realização da técnica de brainstorm. Para a organização das ideias utilizamos o [Microsoft Whiteboard](https://www.microsoft.com/pt-br/microsoft-365/microsoft-whiteboard/digital-whiteboard-app) uma ferramenta de quadro branco digital e colaborativo em que cada participante escrevia suas ideias em anotações, e para ter um direcionameto dessas ideias foram levantadas as seguintes perguntas:

- Quais as caracteristicas o app deve ter?
- Quais informações o app deve fornecer?
- Quais as tarefas que o [usuário](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=usuário) pode realizar no app?

Os membros do grupo que participaram do braistorm foram:

- Guilherme Braz
- Jaime Juan
- João Victor
- Lorrayne Cardozo
- Victor Hugo

## 3. Objetivo
O objetivo desse documento é registrar as ideias e requisitos levantados por meio da técnica de brainstorm.

## 4. Brainstorm
### 4.1 Resultados

<p align='center'>
    <img src='images/brainstorm_1.png' width=40% height=auto>
    <figcaption align='center'>
        <b>Figura 1: Ideias levantadas sobre as características que o app deve ter</b>
        <br>
        <small>Fonte: Autor</small>
    </figcaption>
</p>

<p align='center'>
    <img src='images/brainstorm_2.png' width=50% height=auto>
    <figcaption align='center'>
        <b>Figura 2: Ideias levantadas sobre as informações o app deve fornecer</b>
        <br>
        <small>Fonte: Autor</small>
    </figcaption>
</p>

<p align='center'>
    <img src='images/brainstorm_3.png' width=50% height=auto>
    <figcaption align='center'>
        <b>Figura 3: Ideias levantadas sobre as tarefas que o [usuário](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=usuário) pode realizar no app</b>
        <br>
        <small>Fonte: Autor</small>
    </figcaption>
</p>

### 4.2 Requisitos elicitados

| Id | Descrição | Tipo de requisito |
| -- | --------- | ----------------- |
| 001 | Ter a opção de login pelo Meugov.br | Requisito Funcional |
| 002 | Ter a opção de [logout](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=logout) | Requisito Funcional |
| 003 | Ter a opção de criar conta pelo Meugov.br | Requisito Funcional |
| 004 | Ter a opção de ver regras de doação | Requisito Funcional |
| 005 | Ter a opção de convidar um amigo | Requisito Funcional |
| 006 | Ter a opção de visualizar dados pessoais | Requisito Funcional |
| 007 | Ter a opção de [visualizar histórico de doações](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=visualizar-histórico-de-doações) | Requisito Funcional |
| 008 | Ter a opção de [visualizar campanhas de doação](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=visualizar-campanhas-de-doações) | Requisito Funcional |
| 009 | Ter a opção de ver notificações sobre doações agendadas | Requisito Funcional |
| 010 | Ter a opção de solicitar agendamento de doação | Requisito Funcional |
| 011 | Ter a opção de ver a lista de [hemocentro](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=hemocentro)s próximos a localização | Requisito Funcional |
| 012 | Ter a opção de escolher a localização para procurar [hemocentro](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=hemocentro)s próximos | Requisito Funcional |
| 013 | Ter a opção de usar a localização do dispositivo para procurar [hemocentro](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=hemocentro)s próximos | Requisito Funcional |
| 014 | Ter a opção de ver informações sobre os [hemocentro](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=hemocentro)s (telefones, horário de atendimento, site... ) | Requisito Funcional |
| 015 | Ter a opção de ver rotas para locomoção ao [hemocentro](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=hemocentro) | Requisito Funcional |
| 016 | Ter a opção de visualizar um mapa com a localização dos [hemocentro](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=hemocentro)s próximos | Requisito Funcional |
| 017 | Ter a opção de ver a data da ultima doação feita | Requisito Funcional |
| 018 | Ter a opção de ver a data da próxima doação | Requisito Funcional |
| 019 | Ter a opção de notificar o [usuário](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=usuário) sobre campanhas de doação | Requisito Funcional |
| 020 | Ter a opção de notificar o [usuário](https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico?id=usuário) sobre a data de sua próxima doação | Requisito Funcional |
| 021 | O aplicativo deve ter um layout responsivo para variados tamanhos de telas | Requisito Não Funcional |
| 022 | O aplicativo deve ser leve (não ser maior que 100MB) | Requisito Não Funcional |
| 023 | O aplicativo deve ser rapido (não demorar mais que 500ms para abrir e carregar informações) | Requisito Não Funcional |
| 024 | O aplicativo deve ter compatibilidade com diversos sistemas operacionais (IOS, Android, versão web) | Requisito Não Funcional |
| 025 | O aplicativo deve ter modo escuro e modo claro | Requisito Não Funcional |
| 026 | O aplicativo deve ter uma interface simples e amigavel | Requisito Não Funcional |
| 027 | O aplicativo deve ter facil uso | Requisito Não Funcional |
| 028 | o aplicativo deve ser intuitivo | Requisito Não Funcional |

## 5. Conclusão

Ao total foram identificados 28 requisitos utilizando a técnica de brainstorm, sendo 20 requistos funcionais e 8 requisitos não funcionais.


## 6. Referências

Woebcken, Cayo. O que é brainstorming e as 7 melhores técnicas para a tomada de decisões inteligentes. Disponível em: https://rockcontent.com/br/blog/brainstorming/ 

</div> 