# Análise de Tarefas

## Histórico de Versão 

| Data | Descrição | Versão | Autores |
| -------- | -------- | -------- | -------- |
| 29/10/2020 | Criando documento | 0.1 |Lucas Kishima |
| 29/10/2020 | Adicionando Objetivo | 0.2 |Lucas Kishima |
| 29/10/2020 | Adicionando novo fluxo de tarefas para o objetivo 3.1 | 0.3 |Lucas Kishima |
| 29/10/2020 | Adicionando áreas de destaque para o objetivo 3.1 | 0.4 |Lucas Kishima |
|29/10/2020|Atualizando documento, melhora dos objetivos 3.2 e 3.3 e adicionando novo fluxo de tarefas para objetivo 3.4|0.5|Paulo Gontijo, Daniel Oda|

## 1. Introdução

A Análise de Tarefas é utilizada para se ter um entendimento sobre qual é o trabalho dos usuários, como eles o realizam e por quê. Nesse tipo de análise, o trabalho é definido em termos dos objetivos que os usuários querem ou precisam atingir. 

## 2. Análise Hierárquica de Tarefas ( HTA – Hierarchical Task Analysis)

Nesse projeto será utilizado o método de Análise Hierárquica de Tarefas.  Essa análise examina primeiramente os objetivos de alto nível (por exemplo, marcar uma reunião), decompondo-os em subobjetivos (por exemplo, decidir a data, decidir o local, convidar os participantes etc.), buscando identificar quais subobjetivos são mais difíceis de atingir (ou que geram mais erros) e que, portanto, limitam ou mesmo impedem o atingimento do objetivo maior. A análise será feita levando o perfil de cada uma das personas, para estabelecer assim melhores cenários de interação.

## Objetivo

Anteriormente foi realizada uma análise de tarefas utilizando personas de interesse, essa versão do documento pode ser encontrada [aqui](https://interacao-humano-computador.github.io/2020.1-Corpo-De-Bombeiros-Militar-Do-Distrito-Federal/ponto_de_controle_2/analise_tarefas/) . O objetivo dessa nova versão do documento é realizar novamente essa análise de tarefas utilizando desta vez usuários reais, melhorar a apresentação dos dados, refinar os resultados e validar a análise de tarefas anterior.


## 3. Objetivos:

### 3.1 Solicitar uma análise de projeto para áreas acima de 3000m² afim de obter um alvará de construção
 
#### Fluxo de tarefas:

![](https://i.imgur.com/rRZsBPB.png)

#### Áreas de destaque:

- As tarefas destacadas em amarelo:
    -  Poderiam ser unificadas em apenas uma, deixando o processo mais rápido.Isso Também acarretaria na eliminação do menu carta de serviços, suas opções ficariam agora dentro de serviços, dessa forma eliminando um menu desnecessário e a exclusão de um termo "carta de serviços", não tão intuitivo para o usuário comum. 

- As tarefas destacadas em vermelho:
    - Essas tarefas são executadas fora do sistema, mas que poderiam ser ralizadas pelo mesmo, poupando o usuário de baixar algum programa pra descompactar o arquivo .rar, imprimir o formulário e de levar o formulário até um posto do na hora. Desta forma, as tarefas 8,9,10 e 11 poderiam ser reduzidas a apenas duas, preenchimento do formulário e envio da solicitação.
    


| Tarefas | problemas e recomendações | 
| -------- | -------- |
| 1- Abrir o site do corpo de bombeiros DF.    |  -  |
| 2- selecionar a opção serviços no menu superior.    |  -  |
| 3- escolher a opção carta de serviços.    | - |
| 4- ir para a aba serviços preventivos no menu lateral   |O site possui menu superior, mas ao clicar na opção carta de serviços aparece um menu lateral, seria interessante unificar em apenas um menu. |
| 5- selecionar a opção análise de projeto para áreas acima de 3000m²   |  -  |
| 6- Clicar no link para visualizar lista de profissionais  |erro 404.|
| 7- Clicar no link para realizar download do formulário   |erro 404.|



### 3.2 Acessar o DINAP (Diretoria de Inativos e Pensionistas)

#### Fluxo de tarefas:

![](https://i.imgur.com/acL03iN.png)

#### Áreas de destaque:

- Asterisco vermelho na Tarefa 4.1:
    - O site disponibiliza um formulário online para preenchimento de Dados, mostrando que há no sistema essa funcionalidade. Isso seria extremamente útil em praticamente todas as tarefas que envolvem download e preenchimento de um documento, já que estas tarefas são executadas manualmente fora do sistema.

- As tarefas destacadas em amarelo:
    -  Todos os documentos são exibidos de uma só vez no menu superior abaixo da opção "Requerimentos", que se clicada não se obtem reposta do sistema. Poderia ser criada uma página "Requerimentos" onde o usuário poderia escolher o documento desejado de forma mais intuitiva. Essa exibição no menu superior é confusa.

- As tarefas destacadas em vermelho:
    - Essas tarefas são executadas fora do sistema, mas que poderiam ser ralizadas pelo mesmo, poupando o usuário de baixar o formulário, imprimir o formulário e de levar o formulário até um posto do na hora. Desta forma, as tarefas 5.2,5.3 e 5.4 poderiam ser reduzidas a apenas duas, preenchimento do formulário e envio da solicitação.

| Tarefas | Problemas e Recomendações | 
| -------- | -------- | 
| 1 - Abrir o site do corpo de bombeiros DF |-    |
| 2 - Clicar na opção DINAP no menu superior|-    |
| 3 - Informações                           |-    |
| 3.1 - Dúvidas Frequentes                  |-    |
| 4 - Fale Conosco                          |-    |
| 4.1 - Preenchimento de dados para contato |Único formulário online do site, ferramenta que seria útil em praticamente todas as tarefas|
| 5 - Requerimentos                         |Essa opção no menu superior não faz nada, os documentos são todos exibidos abaixo dela|
| 5.1 - Escolher documento desejado         |-    |
| 5.2 - Download do documento desejado      |-    |
| 5.3 - Imprimir e preencher documento      | Tarefa realizada fora do site, poderia ser feita no mesmo |
| 5.4 - Apresentar documento preenchido no balcão do Na Hora      | Tarefa realizada fora do site, poderia ser feita no mesmo |

- #### Observação:
    - Em todas as páginas existe um botão para imprimir a página, funcionalidade sem utilidade que poderia ser excluída.


### 3.3 Consultar a existência de novos boletins

![](https://i.imgur.com/rMsbY9v.png)

| Tarefas | Problemas e Recomendações | 
| -------- | -------- | 
| 1 - Clicar em entrar no canto superior direito.     |-    |
| 2 - Realizar login com suas credenciais.|-     |
| 3 - Clicar no boletim desejado.|-     |
| 3 - Fazer download do arquivo pdf.|-     | 

### 3.4 Solicitar perícia de incêndio

![](https://i.imgur.com/KuGrQc9.png)

|Tarefas|Problemas e Recomendações|
|-------|-------------------------|
|1 - Entrar no site: CBM-DF| |
|2 - Acessar os serviços||
|3 - Solicitar o serviço de "Perícia de incêndio"| O site disponibiliza informações para que a solicitação seja feita, porém, nenhum dos requisitos para a realização dessa tarefa é feita de forma online. Tal forma é ultrajada e não condiz com o cenário mundial. Se o serviço fosse solicitado de forma online, o contingente administrativo poderia se empenhar em tarefas mais importantes, custos seriam poupados de ambos lados, solicitante-servidor, além de uma maior eficiência na realização da tarefa.|



