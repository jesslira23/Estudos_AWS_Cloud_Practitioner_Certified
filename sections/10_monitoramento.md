# Monitoramento

# Índice

* [Amazon Cloudwatch](#amazon-cloudwatch)
* [Amazon CloudTrail](#amazon-cloudtrail)
* [Amazon Trusted Advisor](#amazon-trusted-advisor)
* [Amazon Config](#amazon-config)
* [AWS Raio-X](#amazon-raiox)
* [Resumo sobre os serviços](#resumo-sobre-os-serviços)

## Amazon Cloudwatch

* Monitoramento principal da AWS.
* CloudWatch fornece métricas para todos os serviços na AWS.
* Coleta dados de monitoramento e operações na forma de logs, métricas e eventos.
* Métrica é uma variável a ser monitorada (CPUUtilization, NetworkIn, etc.)
* 4 recursos do CloudWatch:
    1. CloudWatch Logs
        - Coletar logs
    2. CloudWatch Dashboards
        - Monitore o desempenho dos serviços AWS e métricas de faturamento por meio de gráficos
    3. CloudWatch Events
        - Scripts agendados a partir de regras em uma programação
    4. Alarmes CloudWatch
        - Os alarmes são usados ​​para acionar notificações para qualquer métrica

## Amazon CloudTrail

* Serviço que possibilita governança, conformidade e auditoria.
* Habilitado por padrão!
* Obtenha um histórico de eventos/chamadas de API feitas em sua conta AWS (Console, SDK, CLI, Serviços AWS)
* CloudTrail Insights: análise automatizada de seus eventos CloudTrail
* Se um recurso for excluído na AWS, investigue primeiro o CloudTrail!
* É um serviço web que registra atividades realizadas em sua conta e entrega arquivos de log a um bucket do Amazon S3. CloudTrail é para auditoria, enquanto CloudWatch é para monitoramento de desempenho.
* Serviço que registra a atividade da API na sua conta e entrega arquivos de log a um bucket do Amazon S3
* princípio de design da AWS Cloud uma empresa segue ao usar o AWS CloudTrail = **Garantir a rastreabilidade.**


## Amazon Trusted Advisor

* Serviço de monitoramento que fornece insights e recomendações pra otimizar recursos, seguindo as melhores práticas da AWS.
* Atingir o objetivo de identificar qualquer grupo de segurança que permita tráfego SSH de entrada irrestrito.
* Recomendações nas categorias de otimização de custos e cotas de serviço.

* 5 pilares:
    1. Otimização de custo
    2. Performance
    3. Segurança
    4. Tolerância a falhas
    5. Serviços limitados
* Disponibilidade:
    1. Para todos os clientes: Checagem padrão com recomendações em que você pode receber emails semanalmente e notificações do console.
    2. Para clientes dos **Planos de Suporte Business & Enterprise**

## Amazon Config

* Serviço que fornece monitoramento e gerenciamento contínuo dos recursos e configurações na conta AWS.
* serviço que permite avaliar, auditar e avaliar as configurações dos recursos AWS.
* Ele monitora e registra continuamente as configurações dos recursos AWS e permite automatizar a avaliação das configurações registradas em relação às configurações desejadas.
* Pode ajudar a determinar quando um volume EBS foi removido de uma instância EC2 fornecendo uma linha do tempo das mudanças de configuração.


## AWS Raio-X

* Sistema de rastreamento distribuído.
    - Teste localmente
    - Adicione instruções de log em qualquer lugar
    - Reimplantar na produção
* Analise e depure aplicações de produção e distribuídas.
* Link documentação: [AWS xray](https://aws.amazon.com/pt/xray/)

## Resumo sobre os serviços

![Resumo de Monitoramento](../images/10_fig_monitoramento.png)

[<img align="center" src="../images/botao-home.png" height="25" width="25"/> Home](../README.md)