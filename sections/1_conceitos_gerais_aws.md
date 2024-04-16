# Conceitos Gerais da AWS

## Modelos de infra existentes

* Cloud: 100% provisionada na cloud
* Híbrido: cloud + on-premise
* On-premise: todos os recursos são implementados localmente

## Tipos Serviços Cloud

* Infraestructure as a Service (IaaS)
* Platform as a Service (PaaS)
* Software as a Service (SaaS)
* Code as as Service (CaaS)

## Infraestrutura Global da AWS

* Região: Área geográfica que hospeda 2 a 6 (geralmente 3) AZs (Availability Zones, em portugês, Zonas de disponibilidade);
* Availability Zone: Região física que separa datacenters
    - as AZs ficam separadas entre si de forma que haja redundância de energia, rede e conectividade
    - Cada AZ é composta por N datacenters
* Edge Locations: *TODO*

Para mais informações: [https://aws.global-infrastructure/](https://aws.amazon.com/pt/about-aws/global-infrastructure/regions_az/)

## Benefícios e vantagens do uso de Cloud Computing

1. Você Troca CAPEX(Capital Expense - despesas fixas) por OPEX(Operational Expense - despesas variáveis)
Significa que você não se preocupa mais com o hardware, apenas com as questões operacionais da sua aplicação.
2. Benefícios de enormes economias de escala.
Significa que teu gasto está totalmente adaptado ao teu consumo, não existe ociosidade, nem sobrecarregamento.
3. Pare de adivinhar sua capacidade.
Significa que com a cloud você pode utilizar de ferramentas e métricas para saber com mais exatidão qual será seu gasto com infra.
4. Aumente a tua velocidade e agilidade.
Significa que com a cloud você terá vários impedimentos a menos para ter um desenvolvimento mais ágil, com entregas mais curtas rápidas e contínuas.
5. Pare de gastar dinheiro rodando e mantendo data centers.
Agora quem mantém os datacenters é a AWS, você cuida apenas do contexto do teu negócio.
6. Torne-se global em minutos.
A infra e as ferramentas da AWS permitem que em alguns minutos você publique uma aplicação completa disponível para clientes no mundo todo.
