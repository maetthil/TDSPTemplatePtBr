# Definição de Dados e Variáveis

Esse documento fornece um hub central para as fontes de dados brutos, processados/transformados e conjuntos de variáveis. Mais detalhes de cada conjunto de dados será providenciado no relatório de resumo de dados.

Para cada dado, um relatório individual descrevendo o schema, o significado de cada campo, e outras informações que são úteis para o entendimento do dado é fornecido. Se o conjunto de dados é a saida de processamentos/transformações/engenharia de variáveis de conjunto(s) de dados existentes, os nomes dos conjuntos de dados de entrada, e os links para os scripts que são usados para conduzir a operação serão providenciados.

Quando for o caso, a ferramenta Interactive Data Exploration, Analysis, and Reporting (IDEAR) desenvolvida pela Microsoft pode ser usada para explorar e visualizar os dados, e gerar os relatórios. 

Para cada conjunto de dados, os links para os cojuntos de amostra no diretório _**Data**_ também é fornecido.

[comment]: <> (Para facilitar a modificação desse relatório, os caminhos dos arquivos são colocados nessa página, por exemplo um caminho para o dataset 1, mas eles são apenas placeholders apontando para uma página não existente. Eles devem ser modificados para apontar para a localização real)

## Fontes de Dados Brutos 

|                               Nome |                          Local Original |                          Local de Destino |       Ferramentas/Scripts para Ingestão de Dados |                            Link para o Relatório |
|-----------------------------------:|----------------------------------------:|------------------------------------------:|-------------------------------------------------:|-------------------------------------------------:|
|                Conjunto de dados 1 | Descrição breve da localização original | Descrição breve da localização de destino | [script1.py](link/to/python/script/file/in/Code) | [Relatório Conjunto de dados 1](link/to/report1) |
|                Conjunto de dados 2 | Descrição breve da localização original | Descrição breve da localização de destino |       [script2.R](link/to/R/script/file/in/Code) | [Relatório Conjunto de dados 2](link/to/report2) |


[comment]: <> (Fornecer um breve resumo dos dados, ex: como ter acesso ao dado. Mais informações detalhadas devem estar no Relatório Conjunto de dados x.)

* Resumo Conjunto de dados 1.
* Resumo Conjunto de dados 2.

## Dados Processados
|                                 Nome |                                                                Conjunto(s) de dados de entrada |                  Ferramentas/Scripts para Processamento |                                       Link para o Relatório |
|-------------------------------------:|-----------------------------------------------------------------------------------------------:|--------------------------------------------------------:|------------------------------------------------------------:| 
|       Conjunto de Dados 1 Processado | [Conjunto de dados 1](link/to/dataset1/report), [Conjunto de dados 2](link/to/dataset2/report) | [Python_Script1.py](link/to/python/script/file/in/Code) | [Relatório Conjunto de Dados 1 Processado](link/to/report1) |
|       Conjunto de Dados 2 Processado |                                                 [Conjunto de dados 2](link/to/dataset2/report) |              [script2.R](link/to/R/script/file/in/Code) | [Relatório Conjunto de Dados 2 Processado](link/to/report2) |

[comment]: <> (Fornecer um breve resumo dos dados processados, ex: qual o motivo do processamento dessa forma. Mais informações detalhadas devem estar no Relatório Conjunto de Dados x Processado.)

* Resumo Conjunto de dados 1 processado.
* Resumo Conjunto de dados 2 processado.

## Conjunto de Variáveis

|                    Nome |                                                                           Conjunto(s) de dados de entrada |         Ferramentas/Scripts de Engenharia de Dados |                                Link para o Relatório |
|------------------------:|----------------------------------------------------------------------------------------------------------:|---------------------------------------------------:|-----------------------------------------------------:| 
| Conjunto de Variáveis 1 | [Conjunto de dados 1](link/to/dataset1/report), [Conjunto de Dados 2 Processado](link/to/dataset2/report) |       [R_Script2.R](link/to/R/script/file/in/Code) | [Relatório Conjunto de Variáveis 1](link/to/report1) |
| Conjunto de Variáveis 2 |                                                 [Conjunto de Dados 2 Processado](link/to/dataset2/report) | [SQL_Script2.sql](link/to/sql/script/file/in/Code) | [Relatório Conjunto de Variáveis 2](link/to/report2) |

[comment]: <> (Fornecer uma descrição detalhada do conjunto de variáveis, como o significado de cada variável. Mais informações sobre o conjunto de variáveis devem estar no Relatório Conjunto de Variáveis x)

* Resumo do Conjunto de Variáveis 1. 
* Resumo do Conjunto de Variáveis 2.