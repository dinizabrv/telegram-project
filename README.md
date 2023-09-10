# **Pipeline de dados do Telegram**

## **Introdução**

Este projeto trata-se da criação de um pipeline entre um chatbot criado e inserido em um grupo do Telegram, com o objetivo de realizar a automação da ingestão dos dados de mensagens trocadas por lá e consequentemente a análise dos dados gerados e tratados.
Nesse repositório você poderá encontrar os códigos utilizados para criar as funções na AWS Lambda para Ingestão e ETL, assim como as consultas SQL para a parte de análise de dados.

## **Contexto**

### Chatbots

**Chatbot** é um software que simula e processa conversas com usuários de forma automatizada nas plataformas de mensagens disponíveis. Atualmente, esse mercado está em grande crescente, sendo possíveis utilizar Inteligência Artificial para impulsionar a experiência do usuário e a performance desse software na troca de mensagens.

É utilizado em diversos segmentos de mercado, e de forma mais geral, tem como principal forma de atuação o atendimento ao cliente com diversos objetivos. Seja captação de leads, assistência pós venda, automação de tarefas, resolução de problemas e dúvidas, etc.

### Telegram

Para este projeto utilizamos o **Telegram** por ser uma plataforma de mensageria gratuita, e em sua maioria _open source_ (código aberto). Dessa forma, teremos uma maior autonomia para desenvolvermos o projeto, o que justifica sua popularidade entre os desenvolvedores.

## **Arquitetura**

Para a arquitetura do projeto temos como modelo a imagem abaixo. O objetivo é que esse _pipeline_ faça a **ingestão, processamento, armazenamento e tratamento**

![image](https://github.com/dinizabrv/telegram-project/assets/144612240/3ed1dace-645d-403b-bb5b-8ffec9f59e69)

