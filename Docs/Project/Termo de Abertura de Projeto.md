# Termo de Abertura de Projeto

## Panorama do Negócio
* Quem é o cliente, qual o seu domínio de negócio?.
* Que problema do negócio estamos tentando solucionar?

## Escopo
* Que soluções de ciência de dados estamos tentando construir?
* O que iremos fazer?
* Como será consumido pelo cliente?


## Equipe
* Quem está nesse projeto:
	* Empresa:
		* Project lead
		* PM
		* Data scientist(s)
		* Account manager
	* Cliente:
		* Data administrator
		* Business contact
	
## Métricas
* Quais são os **objetivos** qualitativos? (ex: reduzir usuários churn)
* Qual é a **métrica** quantificável (ex: reduzir a fração de usuários com 4 semanas de inatividade)
* Quantificar que melhoria nos valores da métrica é útil para o cenário do cliente (ex: reduzir a fração de usuários com 4 semanas de inatividade em 20%)
* Qual é o valor baseline (atual) da métrica? (fração de usuários com 4 semanas de inatividade atualmente = 60%)
* Como iremos medir a métrica? (ex: Teste A/B em um subconjunto específico por um período determinado; ou comparação de performance com a baseline após a implementação)

## Plano
* Marcos, linha do tempo, descrição curta do que será feito em cada marco.

## Arquitetura
* Dados
  * Que dados estamos esperando? Dados brutos nas fontes do cliente (ex: arquivos on-prem, SQL, on-prem Hadoop etc.)
* Ingestão de dados de on-prem para Azure utilizando ADF ou outra ferramenta de ingestão (Azcopy, EventHub etc.) para mover:
  * Todos os dados, 
  * Dados após algumas pré-agregações on-prem,
  * Amostra de dados para modelagem 
  
* Que ferramentas e recursos de armazenamento de dados/análises serão utilizados na solução ex:
  * ASA para agregação em fluxo 
  * HDI/Hive/R/Python para construção das variáveis, agregação e amostragem
  * AzureML para modelagem e operacionalização por meio de web service
* Como o modelo ou webservice(s) operacionalizado será consumido no fluxo de trabalho do cliente? Se necessário, escrever pseudo-código para as chamadas das APIs do web service.
  * Como o cliente usará os resultados do modelo para tomar decisão?
  * Pipeline de movimentação de dados em produção
  * Criar um diagrama mostrando o fluxo de dados de ponta a ponta e a arquitetura de decisão
    * Se existir uma mudança substancial no fluxo de trabalho do cliente, criar um diagrama antes/depois mostrando o fluxo de dados.
  
## Comunicação
* Como iremos manter contato? Reuniões semanais?
* Quem serão as pessoas contactadas em ambos os lados?
