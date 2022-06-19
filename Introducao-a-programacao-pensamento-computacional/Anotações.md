# INTRODUÇÃO À PROGRAMAÇÃO E AO PENSAMENTO COMPUTACIONAL

## Pensamento computacional:

- Instruções para resolver problemas

- Habilidade generalista
- Não se restringe ao meio computacional
- A solução encontrada deve ser obtida tanto por um humano quanto por uma máquina
- 4 Pilares
  - Decomposição: Dividir uma tarefa grande em várias menores
  - Reconhecimento de padrões
  - Abstração: Pego do mundo concreto e levo para o mundo das ideias por meio de fórmulas e gráficos por exemplo
  - Design de algoritmos: Definir passo a passo a solução do problema

#### Decomposição:

 "Se você tem um problema que não consegue resolver, existe um problema mais fácil que você consegue: encontre-o". George   Polya

- O que é decompor? 
  - Quebrar um problema complexo em vários menores
- Como decompor?
  1. Identificar ou coletar dados
  2. Agregar os dados
  3. Funcionalidade

#### Padrões:

- Generalizar com o objetivo de obter resolução para problemas diferentes
- Reconhecimento de similaridades e diferenças
- Modelo base
- Estrutura invariante
- Repetição

Como o ser humano reconhece padrões?

- Grau de similaridade
- Grupos conhecidos x grupos desconhecidos

E o computador?

- Comparação

#### Abstração:

Abstrair: Observar um ou mais elementos, avaliando características e propriedades em separado.

Abstração: Processo intelectual de isolamento de um objeto da realidade, é generalizar, tornar mais amplo, geral, extenso.

O método de abstração consiste em tornar a solução geral de modo que possa ser utilizada em outros problemas com características parecidas.

Como fazer?

- Identificar as características do problema
- Identificar os pontos essenciais
- Generalizar

#### Algoritmos:

São instruções executadas passo a passo para cumprir uma tarefa.

O algoritmo descreve o problema por meio de ferramentas narrativas, fluxogramas ou pseudocódigos.

-  O que precisa ser feito?
- Qual a ordem de execução?
- Instruções de resolução

## Habilidades complementares:

- Raciocínio lógico: Pensamento estruturado
  - Indução: Fenômeno observado que extrapola para leis e teorias. Ex.: ciências experimentais
  - Dedução: A partir de leis e teorias se deduz uma resposta para o fenômeno. Ex.: matemática
  - Abdução: A partir de uma conclusão se tira uma premissa (nem sempre a premissa será verdadeira). Ex.: A grama está molhada, logo deve ter chovido. Processo investigativo.
- Aperfeiçoamento
  1. Melhor uso de recursos:
        - Encontrar uma solução eficiente 
        - Otimizar processos 
  2. Melhorar códigos e algoritmos
     - Simplificar linhas de código
     - Funções bem definidas



## Introdução a lógica de programação:

A lógica é utilizada para solucionar um problema. 

- O que é lógica? 
  - Parte da filosofia que trata das formas de pensamento em geral (dedução, indução, hipótese, inferência etc.) e das operações intelectuais que visam a determinação do que é verdadeiro ou não

- Lógica dentro da programação: 
  - É a organização e planejamento das instruções, assertivas em um algoritmo, a fim de viabilizar a implantação de um programa.

#### Técnicas de lógica de programação

- Técnica linear: temos uma sequência de forma ordenada e com dependência entre si

  - Modelo tradicional
  - Não tem vínculo
  - Estrutura hierárquica
  - Programação de computadores

- Técnica estruturada: não linear, existem opções.

  Objetivos:

  - Escrita
  - Entendimento
  - Validação
  - Manutenção - esta técnica facilita essa parte

- Técnica modular: Partes independentes controladas por um conjunto de regras

  Objetivos:

  - Simplificação
  - Decompor problema
  - Verificação de módulo

#### Tipologia e variáveis

- Tipos de dados numéricos:
  - Inteiros: 0, 1, 2, 3, 70, -2, -30...
  - Reais: Positivos e negativos com casas decimais
- Caractere:
  - A, #, @, ?, k, !...
- Lógica boleana:
  - Verdadeiro: 1, V ou S
  - Falso: 0, F, N
- Variável: tipo de estrutura. Analogia - caixa ou gaveta onde irei guardar algo
  - Mutável
  - Possui variações
  - Inconstante
  - Incerto
  - Instável
  - Regras:
    - Atribuição de um ou mais caracteres
    - Primeiro letra - não número
    - Sem espaços em branco
    - Vetada a utilização de palavras reservadas
    - Caracteres e números

#### Instruções primitivas

Vão determinar a ação que irá analisar e processar os dados.

- Cálculos matemáticos (variáveis e constantes) utilizando operadores 
- Entrada, processamento e saída.

#### Instruções condicionais e operadores

Existe uma condição para algo acontecer.

Operadores lógicos: and, or, not.

Operadores: =, <>, <, >, >=, <=

- Condição simples: Se (<condição>) então 

  < Instruções p/ condição verdadeira>

  Fim-se

- Condição composta: Se (<condição>) então 

  < Instruções p/ condição verdadeira>

  senão

  < Instruções p/ condição falsa>

  Fim-se

- Condição encadeada: Se (<condição 1>) então 

  < Instruções p/ condição verdadeira>

  senão

  se (< condição 2>) então

  < Instruções p/ condição 2 verdadeira e condição 1 falsa>

  Senão

  < Instruções p/ condição 1 e condição 2 falsas>

  Fim-se

#### Estruturas de repetição

Laços, loops ou controle de fluxo.

- Números de repetições pré-definidas

- Condição satisfeita

- Existe uma condição para parada

  enquanto ... faça

  repita ... até

  para ... de ... até ... faça

#### Vetores e matrizes

- Vetores: é caracterizada por uma variável dimensionada com tamanho pré-fixado
- Matriz: é uma tabela organizada em linhas e colunas no formato m x n, onde m representa o número de linhas e n o número de colunas. 

#### Funções

- As funções ou sub-rotinas são blocos de instruções que realizam tarefas específicas.
- Podem ser chamadas em pontos específicos das rotinas
- São identificados por nomes e parâmetros

#### Instruções de entrada e saída

- Entrada: Consiste na inserção de dados do mundo real por meio da ação de alguma interface, seja teclado, mouse, arquivos entre outros.
- Saída: Consiste na impressão dos dados do mundo abstrato, digital, por meio da ação de alguma interface.

#### Linguagem de programação

Linguagem de programação é um método padronizado composto por um conjunto de regras sintáticas e semânticas de implementação de um código fonte.

- Toda evolução tecnológica se inicia com o hardware e depois vai para o software.
- 1949 - primeira linguagem de máquina (Assembly)
- 1950 - primeira linguagem de programação
- Hoje o maior desafio é lidar com a grande quantidade de dados (big data)

#### Como um computador entende um programa

Tudo começa por um programa fonte:

- Código fonte:
  - Tradução: execução mais rápida e maior flexibilidade
    - Geração de um programa objeto
    - Execução do programa objeto
  - Interpretado: Programa fonte executado diretamente 
- Compilador: passa a linguagem do programa fonte para linguagem de máquina
  - Programa objeto
  - executa a análise do programa

#### Características de um programa

- Legibilidade: Coerência nas instruções, legível.
- Redigibilidade: Facilidade de escrita do código.
- Confiabilidade: Faz o que foi programado para fazer.
- Baixo custo: Análise de impacto.

#### Análise de códigos 

Compilação:

- Análise léxica
  - Particionar
  - Classificar
  - Eliminar
- Análise sintática
  - Correção do programa - forma
- Análise semântica
  - Lógica do programa











 