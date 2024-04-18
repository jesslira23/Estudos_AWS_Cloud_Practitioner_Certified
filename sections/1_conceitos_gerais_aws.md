# Conceitos Gerais da AWS

## Modelos de infra existentes

* Cloud: 100% provisionada na cloud
* Híbrido: cloud + on-premise
* On-premise: todos os recursos são implementados localmente

## Tipos Serviços Cloud

* Infraestructure as a Service (IaaS)
    - fornece blocos de contrução para TI na nuvem
    - fornece rede, computadores, espaço de armazenamento de dados
    - o mais alto nível de flexibilidade
    - paralelo fácil com a TI local tradicional
    - Exemplos: Amazon EC2 (AWS), GCP, Azure
* Platform as a Service (PaaS)
    - concentra na implantação e no gerenciamento dos aplicativos
    - Exemplos: Elastic Beanstalk (AWS), Google App Engine (GCP), Windows Azure (Microsoft)
* Software as a Service (SaaS)
    - produto concluído que é executado e gerenciado pelo provedor de serviços
    - Exemplos: Rekognition para ML, Google apps, Dropbox

## Infraestrutura Global da AWS

1. AWS Regions (Região)
2. AWS Availability zones (zonas de disponibilidade)
3. AWS Data center
4. AWS Edge Locations

Para mais informações: [https://aws.global-infrastructure/](https://aws.amazon.com/pt/about-aws/global-infrastructure/regions_az/)

### 1. Regions
* AWS tem região em todo mundo
* Área geográfica que hospeda 2 a 6 (geralmente 3) AZs (Availability Zones, em portugês, Zonas de disponibilidade)
* Os nomes pordem ser: us-east-1


### 2. Availability Zone
* Região física que separa um ou mais datacenters com redundância de energia, rede e conectividade
* As AZs ficam separadas entre si, de modo que fiquem isolados de desastres
* Eles são conectados com high bandwidth, ultra-low latency networking


## Benefícios e vantagens do uso de computação na AWS Cloud

* Troca despesas fixas por despesas variáveis:
    - Você pode reduzir despesas fixas, como a manutenção de servidores físicos e infraestrutura local, e passar a pagar apenas pelos recursos que realmente utiliza, o que pode resultar em economias significativas.
    - pague sob demanda: não possua hardware
    - custo total de propriedade (TCO) e despesas operacionais reduzidos

* Alta escala de economias:
    - A AWS oferece descontos significativos para uso em grande escala, incentivando a consolidação de recursos e possibilitando que empresas de todos os tamanhos obtenham benefícios econômicos consideráveis ao usar seus serviços.

* Capacidade sob demanda:
    - A AWS permite que você ajuste facilmente a capacidade dos seus recursos de acordo com as necessidades do seu negócio.

* Velocidade e agilidade:
    - As organizações podem experimentar um aumento significativo na velocidade e agilidade de suas operações. Isso se deve à capacidade da AWS de fornecer recursos computacionais rapidamente, permitindo que as equipes de desenvolvimento e operações respondam rapidamente às demandas do mercado e implementem novos recursos e atualizações com mais rapidez.

* Redução de custos com datacenters:
    - Você elimina os custos associados à infraestrutura física, como compra de equipamentos, energia, refrigeração, manutenção e espaço físico, reduzindo significativamente os gastos operacionais.

* Lançamento global em minutos:
    - Com a presença global da AWS em várias regiões ao redor do mundo, você pode lançar seus aplicativos e serviços em escala global em questão de minutos, aproveitando a infraestrutura e a rede global da AWS para oferecer uma experiência consistente e de alta qualidade para seus usuários em qualquer lugar.

[<img align="center" src="../images/botao-home.png" height="20" width="20"/> Home](../README.md)