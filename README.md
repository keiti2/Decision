# Decision

Repositório para a implementação do algoritmo Simplex e Mochila.

Projeto de Pesquisa Operacional
5º Semestre BSI UNIVEM

O Simplex permite que se encontre valores ideais em situações em que diversos aspectos precisam ser respeitados. Diante de um problema, são estabelecidas inequações que representam restrições para as variáveis. A partir daí, testa-se possibilidades de maneira a otimizar, isto é, maximizar ou minimizar o resultado da forma mais rápida possível.

## Ferramentas

- Javascript
- JQuery
- GitHub para versionamento
- Heroku para hospedagem

## Nota de realease a ser publicado
1.0 - 17/04/2019 - Auxílio no precesso de ensino e aprendizagem, resolução direta para uso profissional, resolução de problema de maximização e gerar PDF 
1.1 - 24/04/2019 Relatorio de sensibilidae, resolução passo a passo, resolução de problema de minimização, imprimir resultado, modelo sem solução.
1.2 -08/05/2019- Solução de problema de programação linear, adicionar restrição dinamicamente, restrições nas quantidades de iterações, resolução passo a passo explicativo, análise de sensibilidade detalhada. 

###Simplex

- Algoritmo Simplex para problemas de maximização.
- Algoritmo Simplex para problemas de minimização.
- É exibido o passo a passo das tabelas geradas pelo método Simplex
- Tabela de Sensibilidade.


###Mochila

- Apreentação da solução, dos itens a serem considerados e a tabela de cálculo.


###Simplex

- Limite máximo de iterações
- Adicionar restriçoes dinamicamente
- Tipo de Simplex (MAX ou MIN)
- Quantidade de variáveis e restrições

##Limitações
•Restrições de quantidade de variáveis e restrições.
•Armazena em banco de dados.
•Propagandas (Marketing)

###Mochila
- Capacidade da mochila
- Peso e valor dos itens
- 
##Limitações
- Não utilizar itens com pesos iguais
- Serão permitidos somente valores inteiros
- 
###Simplex

- Em cada variável da função objetivo e das restrições deve conter apenas o número, sem a adição do 'x', separando os números por ';' e caso tenha alguma variável nula, é necessário inserir o 0.

##Datas Importantes

###Simplex

Datas | Eventos
--------- | ------
30/03/19     | Início do Planejamento
31/03/19    | Criação da Estrutura Principal
01/04/19    | Inserido auxilio no processo de ensino e aprendizagem
02/04/19    | Criação do Cabeçalho da Matriz Principal
03/04/19  | Cálculo
03/04/19  | Geração da Matriz Principal
05/04/19    | Criação das Funções de Parada
06/04/19    | Resolução direta para uso profissional
16/04/19    | Inserindo o maximizar
16/04/19    | Gerar PDF
17/04/19    | Alterações no Readme
18/04/19    | Inserindo a Análise de Sensibilidade
18/04/19    | Estruturação da Função Objetivo
20/04/19    | Arrumando a função maximizar
20/04/19    | Resolução passo a passo
21/04/19    | Imprimir Resultado
21/04/19    | Modelo sem solução
22/04/19    | Correção de layout
24/04/19    | Alterações no Readme
25/04/19    | Correção valores negativos 
26/04/19    | Adicionar restrição dinamicamente
26/04/19    | Restrições na quantidade de iterações
27/04/19    | Correção problema sem solução
29/04/19    | Resolução passo a passo explicativo
29/04/19    | Análise de sensibilidade detalhada
30/04/19    | Alteração no campo de restrições
01/05/19    | Alterações no Readme


###Mochila

Datas | Eventos
--------- | ------
20/05/16     | Início do Planejamento
23/05/16    | Inserindo inputs
25/05/16    | Inserindo o paralax
02/06/16  | Finalização do projeto da mochila
02/06/16  | Atualizando o Read Me
04/06/16  | Refatoração do layout da Mochila e index
05/06/16   | Atualizando README

##Compatibilidade

Requisitos | Ferramentas
--------- | ------
Navegadores     | Mozila Firefox, Chrome, Internet Explorer
Sistema Operacional    | Ubuntu, Windows, Mac, RedHat

##Tecnologias

Tecnologias | Ferramentas
--------- | ------
Front-End     | HTML, Javascript, JQuery
Back-End    | Javascript
Framework WEB    | Bootstrap
Editor de Texto  | Visual Studio Code
Servidor Web    | https://decisionsimplex.herokuapp.com/

##Atividades Realizadas no Período

###Simplex

Código | Título | Tarefa | Situação | Observação
--------- | ------ | -------| -------| -------
1 | Relatório de sensibilidade | Deonstrar ao usuário a tabela de sensibilidade | Concluído|
2 | Solução de problema de Programação linear, adicionar restrições dinamicamente | Botão para adicionar mais restrições |Concluído|
3 | Auxílio no processo de ensino e de aprendizagem | Exemplo na página inicial | Concluído| 
4 | Resolução passo a passo | Demonstrar ao usuário as alterações na tabela causada pelas iterções do método simplex |Concluído| 
5 | Resolução Direta para uso profissional | Resolução direta |
6 | Restrições nas quantidades de iterações | Restringir a quantidade de iteções limite máximo 100 | Concluído |
7 | Resolução maximização | Montar a Tabela Simplex, e possibilitar o usuário a maximizar modelos de simplex com sistemas lineares. | Concluído | Apenas restrições de “<=”
8 | Resolução minimização | Montar a Tabela Simplex, e possibilitar o usuário a minimizar modelos de simplex com sistemas lineares. | Concluído | Apenas restrições de “<=”
9 | Gerar PDF | Gera e salva pdf no dispositivo |Concluído | 
10 | Imprime Resultado | Imprime resultado final | Concluído | 
11 | Resolução passo a passo explicativo | Demonstrativo passo a passo indicando a linha que será substituida |Concluído |
12 | Modelo sem solução | Exibe mensagem caso não tenha solução | Concluído |
13 | Análise de sensibilidade detalhada. |  Demonstrar ao usuário a tabela de sensibilidade. |Concluído|


Código | Título | Tarefa | Situação | Observação
--------- | ------ | -------| -------| -------
1 | Tabela de solução | Demonstrar ao usuário as etapas do algortimo | Concluído |
2 | Solução do problema | Mostrar ao usuário os itens selecionados pelo algoritmo como qualificados | Concluído |
