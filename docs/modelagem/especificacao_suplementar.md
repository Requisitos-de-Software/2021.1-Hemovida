# <center> Especificação Suplementar

## Histórico de versão
| Data | Versão | Autor | Descrição |
| :-: | :-: | :-: | :-: |
| 19/08/2021 | 0.1 | Lorrayne Cardozo | Criação do documento |
<div align="justify">

## 1. Introdução
A especificação suplementar visa descrever os requisitos não-funcionais do projeto que não foram suficientemente atingidos por meio das técnicas anteriormente utilizadas, se aliando a outras técnicas, como a modelagem. 

## 2.  Escopo
O Hemovida é um aplicativo móvel multiplataforma, gratuito, que possibilita realizar a captação de doadores de sangue, apoiando os [hemocentro](./modelagem/lexico?id=hemocentro)s da rede pública de saúde do Brasil a divulgar informações pertinentes ao público e campanhas de [doação de sangue](./modelagem/lexico?id=doação-de-sangue).

## 3. Metodologia
A metodologia utilizada será o FURPS+, que é um método para a classificação dos requisitos não-funcionais do software. Seu nome é um acrônimo das categorias que podem ser usadas na definição destes requisitos: 
* Functionality (Funcionalidade): refere-se as características e capacidades, funções e segurança da aplicação;
* Usability (Usabilidade): é o atributo que avalia a interface com o [usuário](./modelagem/lexico?id=usuário), incluindo documentação, ajudas, design, etc;
* Reliability (Confiabilidade): remete-se à integridade, conformidade e interoperabilidade do aplicativo, avaliando frequência e gravidade de falhas, o tempo médio entre elas, a possibilidade de recuperação, e a possibilidade de previsão;
* Performance (Desempenho): avalia atributos de desempenho do software, como: velocidade de processamento, tempo de resposta, consumo de memória e eficiência;
* Supportability (Facilidade de suporte): os requisitos de suportabilidade envolvem a manutenibilidade, compatibilidade, configurabilidade, testabilidade, entre outras características que envolvem o suporte do software;
* '+': engloba os outros requisitos não-funcionais que devem ser lembrados, como requisitos de design e interface.

## 4. FURPS+

### 4.1. Funcionalidade
* Os requisitos funcionais do aplicativo Hemovida que foram obtidos por meio de técnicas de elicitação podem ser encontrados no documento de [Requisitos Elicitados](./elicitacao/requisitos_elicitados).

### 4.2. Usabilidade
* Facilidade no uso: O aplicativo deve ser intuitivo, para que o [usuário](./modelagem/lexico?id=usuário) encontre com facilidade o que procura.

### 4.3. Confiabilidade
* Privacidade de dados: Os dados dos [usuário](./modelagem/lexico?id=usuário)s devem ser mantidos em segurança.
* Transparência: O aplicativo deve deixar claro todas as informações sobre como os dados coletados dos [usuário](./modelagem/lexico?id=usuário)s serão usadas.
* Disponibiilidade: Os servidores devem estar sempre disponíveis, para que o [usuário](./modelagem/lexico?id=usuário)s consiga usar o aplicativo com satisfação independente de dia ou horário.

### 4.4. Desempenho
* Armazenamento: O Hemovida ocupa 9,2 MB no sistema [Android](https://play.google.com/store/apps/details?id=br.gov.datasus.hemovida&hl=pt_BR&gl=US) e 16,5 MB em [IOS](https://apps.apple.com/br/app/hemovida/id1316529541).
* Localização: O aplicativo utiliza a localização do dispositivo para rastrear os [hemocentro](./modelagem/lexico?id=hemocentro)s mais próximos.

### 4.5. Suportabilidade
* Compatibilidade: O aplicativo deve estar disponível para Android e IOS.
* Internet: O aplicativo necessita de acesso contínuo a internet.

### 4.6. Acessibilidade
* Design intuitivo: O design deve ser intuitivo e acessível para melhor compreensão de analfabetos tecnológicos e deficientes visuais.

## 5. Referências
SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 13. 1º/2019. Slides apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.