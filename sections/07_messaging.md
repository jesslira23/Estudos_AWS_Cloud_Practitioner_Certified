# Messaging

# Índice

* [SQS (Simples Queue Service)](#sqs)
* [SNS (Simple Notification Service)](#sns)
* [SES (Simple Email Service)](#amazon-quicksight)
* [Amazon EventBridge](#amazon-eventbridge)
* [Resumo sobre os serviços](#resumo-sobre-os-serviços)

## SQS

* Serviço de filas simples de mensagens gerenciado pela AWS.
* Serviço totalmente gerenciado (~sem servidor), usado para desacoplar aplicativos.
* Não há limite de mensagend na fila.
* queue model

## SNS

* Serviço de mensageria da AWS (notificação). Pode enviar mensagens para SMS, Msg Push e e-mail.
* Combinação de publisers and subscribers (editores e assinantes)
* Pub/sub model
* Assinantes: Email, Lambda, SQS, HTTP, Mobile…
* Sem retenção de mensagens
* É um serviço web que facilita a configuração, operação e envio de notificações da nuvem.
* É usado para criar e integrar aplicativos distribuídos e pouco acoplados.

## SES

* Serviço de envio de email escalasse e econômico.

## Amazon EventBridge

* Serviço de barramento de eventos serverless da AWS que permite conectar aplicações usando eventos, facilitando a construção de arquiteturas orientadas a eventos.


## Resumo sobre os serviços

![Resumo Messaging](../images/07_fig_messaging.png)

[<img align="center" src="../images/botao-home.png" height="25" width="25"/> Home](../README.md)