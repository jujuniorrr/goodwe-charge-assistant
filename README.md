
# GoodWe Charge Assistant

Chatbot desenvolvido para o EV Challenge 2026 da FIAP, com foco no contexto da GoodWe e na gestão inteligente de carregadores para veículos elétricos.

## Integrantes

* Arthur Maziviero Faria — RM 573928
* Tommaso C. Nagliatti — RM 572147
* Jun Uehara
* Felipe de Souza Gallo
* Roberson Reguero Luiz Junior
* Matheus Martins Lacerda

## Problema Abordado

O desafio envolve a ausência de mecanismos integrados para orquestrar potência, registrar ciclos de carregamento, monitorar carregadores, apoiar cobrança e melhorar a gestão energética de eletropostos comerciais ou condominiais.

## Proposta do Chatbot

O GoodWe Charge Assistant atua como uma ferramenta de apoio operacional para responder dúvidas sobre:

* Smart Charging
* OCPP 2.0.1
* Monitoramento remoto
* Monetização de carregadores
* Gestão energética
* Sustentabilidade
* Projeto EMPS

## Tecnologias Utilizadas

* Python
* Google Colab
* Pandas
* Modelo de respostas contextualizadas
* Histórico de conversa
* System Prompt com contexto GoodWe / EV Challenge

## Funcionalidades

* Interface de conversa no Colab
* Histórico de mensagens
* Respostas dentro do contexto GoodWe
* Execução de 5 casos de teste
* Registro dos resultados em CSV

## Como Executar

1. Abrir o notebook `GoodWe_Charge_Assistant.ipynb` no Google Colab.
2. Executar as células em ordem.
3. Utilizar a interface de conversa.
4. Executar os casos de teste.
5. Conferir os arquivos gerados:

   * `resultados_testes_goodwe.csv`
   * `historico_conversas_goodwe.csv`

## Casos de Teste

Foram executados 5 testes com perguntas sobre OCPP, Smart Charging, monitoramento remoto, monetização e sustentabilidade.

Cada teste registra:

* Pergunta enviada
* Resposta esperada
* Resposta obtida
* Avaliação qualitativa

## Vídeo de Demonstração

Link do vídeo: inserir aqui o link do YouTube não listado.

## Observação

Nenhuma API Key foi exposta no repositório. O projeto foi estruturado para demonstrar o funcionamento do chatbot dentro do contexto GoodWe e EV Challenge 2026.

