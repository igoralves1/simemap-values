# Cálculo do Valor da SIMEMAP


# Aplicação IoT e tendências de mercado IoT no Brasil / Mundo

## O que é IoT?

> The Internet of Things (IoT) describes the network of physical objects—“things”—that are embedded with sensors, software, and other technologies for the purpose of connecting and exchanging data with other devices and systems over the internet. These devices range from ordinary household objects to sophisticated industrial tools. With more than 7 billion connected IoT devices today, experts are expecting this number to grow to 10 billion by 2020 and 22 billion by 2025.


# SOME User Cases for IoT
### Energy

### Industrial
- Smart Factory
  - Saves Energy
- Motors repair and maintainance
- Monitor vibrations/temperature/loads/...

### Logistics
- GPS tracking 
- Food Chain
- 
### Health
- Office automation
- Smart devices
- 

### Smart Cities

### Telematics
> method of monitoring cars, trucks, equipment and other assets by using GPS technology and on-board diagnostics (OBD) to plot the asset’s movements on a computerized map and/or using AI/Machine-Learning pipelines and cloud computing to display data to managers - DDD (Data Driven Decisioin)  

### IoT - Smart Houses
- [Smart Houses Saves Energy - Poverty Europe](https://www.youtube.com/watch?v=WGz6RgCMY9E)
### IoT - Smart Condos

### IoT - Security

### IoT - Potenciais Clientes
- Setor Púbico:
  - Prefeituras: 5565 cidades
   - Monitoramento/Controle de Energia
    - Condicionadores de ar
    - Monitoramento de Frotas de Carros/Viaturas/Ambulância (SUS)
  - Segurança
  - Estabelecimentos de Ensino (Escolas, Universidades)
  - 
- Estabelecimentos de Ensino (Escolas, Universidades)
  - Monitoramento/Controle de Energia 
    - Condicionadores de ar
  - Monitoramento/Controle na Segurança
    - Controle e monitoramento de Portas, Janelas, vias de Acesso em geral
  - Monitoramento/Controle de Energia





# SIMEMAP - Milestones
- 2015: Início da pesquisa e testes sobre sensores e circuitos condicionadores de sinais
- 2016: Primeiro protótipo funcional de monitoramento remoto de um sistema fotovoltaico.
  - Selecionado no projeto "Fabin - Fábrica de projetos inovadores" do Conecta-IFB 2016.
- 2017: Aprimoramento do protótipo
  - Publicação de artigos científicos com resultados obtidos: Seel/2017, Semetro/2017
  - Instalação de um lote piloto (10 unidades) no IFTO Campus Palmas
- 2018: 
  - Apresentação do protótipo na Campus Party em São Paulo/SP
  - Software Stack inicial da plataforma: PHP/JavaScript/MySQL/Ionic em virtual remote server (OVH)
  - Início da migração da plataforma Simemap para o cloud AWS e reestruturação da arquitetura:
    - Devices conectados ao AWS IoT Core com certificados X.509
    - Utilização de AWS - API Gateway / AWS - Lambdas
    - Utilização de MongoDB como recurso principal de logs Storage
- 2019
  - Formalização (CNPJ) da empresa Simemap
  - APP Mobile: Migração para Flutter
  - Utilização de AWS - RDS / AWS - Dynamo
  - Instalação de placas para teste piloto na UFT
  - Pesquisa, projeto e prototipação de novos produtos de medição (vazão de agua, circuitos trifásicos) e automação (lâmpadas, motores, etc)
- 2020
  - Homologação do microprocessador ESP32-WROOM-32 para uso nos produtos Simemap
  - Instalação de serviço de automação de portas em área comum de condomínio utilizando comunicação LoRa com criptografia AES128
- 2021
  - Expansão de testes em empresas clientes: Ceulp-Ulbra, Cardiopalmas, Pão da Hora, Condomínio Solar dos Mognos
  - Obtenção de certificação AWS Cloud Practitioner (Marcus André - CTO)
  - Prova de conceito baseada em AWS Greengrass V2 enviada a empresa européia
  - Registro da Marca no INPI
- 2022


# SIMEMAP OUR TECH STACK

## Hardware
- AWS FreeRTOS
- RaspberyPi/Computer + AWS GreeGrass Docker
  - Docker PostGreSql
  - Docker REDIS
  - Docker MongoDB
  - Local Lambdas (Free)
  - Local (Internal/External) Storage (Micro-SSD, SSD/M2.SSD, HD)
  - Docker HADOOP Cluster for Local Data-Lakes
  - Stream Manager
- WiFi ...
- WiFi XXX (1.5 Km range)
- LORA
  - >Radio frequency bands like EU433 (433.05-434.79 MHz) and EU863-870 (863–870/873 MHz) in Europe; AU915-928/AS923-1 (915–928 MHz) in Australia; US902-928 (902–928 MHz) in North America; IN865-867 (865–867 MHz) in India; AU915-928/AS923-1 and EU433 Southeast Asia; and 2.4GHz worldwide
- BT - BluetTooth
- BLE - BluetTooth Low Energy
- Marcus completa

## Software/Cloud
- AWS Cloud
- AWS IoT
  - AWS IoT-Core (MQTT)
  - M 
- AWS-IoT Core
- AWS S3
- AWS DynamoDb
- Mobile APP: Flutter




# Cálculo de Valor da SIMEMAP:

- *Bienes físicos*: Todo aquello que sea tangible; su valor se estima según su precio.
- *Bienes humanos*: El personal que compone tu empresa se valora según sus sueldos y sus cargas sociales. Además, sus contribuciones por incapacidad laboral, desempleo o reposo por enfermedad.
- *Bienes legales*: Es necesario que tomes en cuenta todos los asuntos fiscales y mercantiles pertinentes.
- *Bienes tecnológicos*: Hoy en día, estar al tanto de las nuevas maquinarias e inventos que puedan ser útiles en tu empresa es necesario. Desde equipos y programas, hasta conexión a Internet y páginas web, todo esto entra en el valor de tu empresa.
- *Experiencia*: De igual forma, tomar en cuenta los años que has trabajado en tu empresa es fundamental para valorarla. Este es, sin duda, el punto más complicado.
- Valor agregados ao produto/empresa: 
  - Certificação em Órgãos Reguladores (ANATEL), 
  - Patentes, 
  - Certificação Internacionais 
   - AWS FerrRTOS certificate, 
   - AWS Partner

| Item   |      xxx      |  Total |
|----------|:-------------:|-------:|
| Componentes e placas |    Marcus André   | 70000 |
| Homologação Anatel |  Marcus André | 12000 |
| col 3 is | right-aligned |    $1 |



# References
1. [State of IoT 2021: Number of connected IoT devices growing 9% to 12.3 billion globally, cellular IoT now surpassing 2 billion](https://iot-analytics.com/number-connected-iot-devices/)
2. [IoT technology will save eight times the energy it consumes by 2030, new report shows](https://iottechnews.com/news/2021/apr/21/iot-technology-will-save-eight-times-the-energy-it-consumes-by-2030-new-report-shows/)
3. [Cálculo De Valor De Empresa: Paso A Paso + Fórmulas](https://emprendedoresynegocios.com/valor-de-empresa/)
4. []()
5. []()
6. []()
7. []()
8. []()
9. []()
10. []()
11. []()
12. []()
13. []()
14. []()
15. []()
16. []()
17. []()
18. []()
19. []()
20. []()
21. []()
22. []()
23. []()
24. []()
25. []()
26. []()
27. []()
28. []()
29. []()
30. []()
31. []()
32. []()
33. []()
34. []()
35. []()
36. []()
