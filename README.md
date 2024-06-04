# Análise Exportação de Vinhos - Tech Challenge - Fase 1 - Pos Tech - Data Analytics - FIAP 

![image](https://github.com/victorcbarros/Analise-Exportacao-de-Vinhos/blob/363d14771c1b1b8828b0b67a6c402d16819683b7/reports-relatorios/figures-figuras/Projeto%20Analise%20Exporta%C3%A7%C3%A3o%20de%20Vinhos%20Banner.jpg)

## 📌 Introdução

Este projeto faz parte do projeto Tech Challenge da Pós Tech Data Analytics FIAP e conta como nota da primeira fase da pós-graduação.
O grupo que desenvolveu esse projeto é composto por:


Aelton Pereira de Lacerda

André Martins Pontes

Arthur do Nascimento Siqueira

Matheus Martins Matias Rodrigues

Victor Campanha Barros 


## 📌 Visão Geral

O problema da previsibilidade de cenários futuros é uma preocupação significativa para empresas de produção e exportação de vinhos. Mudanças inesperadas no mercado internacional de compra e venda podem levar à perda de mercado e até a prejuízos enormes se a empresa não acompanhar essas alterações. Nesse sentido, a análise de dados, tanto da empresa quanto do cenário mundial, torna-se uma ferramenta indispensável para auxiliar na tomada de decisão. Essa prática oferece uma vantagem competitiva frente às concorrentes que não utilizam essa ferramenta, permitindo uma adaptação mais rápida e eficaz às mudanças de mercado.

Este projeto tem como objetivo analisar o montante de vendas de exportação de vinhos provenientes do Brasil nos últimos 15 anos. Utilizamos a linguagem de programação Python, através da biblioteca Pandas, para a extração, limpeza, tratamento e carregamento dos dados. Para a visualização dos dados, utilizamos a biblioteca Matplotlib e Seaborn além do software Power BI, criando gráficos para facilitar a análise. A partir disso, sugerimos possíveis ações para melhorias nas exportações com base nos dados analisados.

## 💼 Entendimento do Negócio

No cenário atual de globalização e competitividade no mercado de vinhos, compreender os padrões de exportação é fundamental para as empresas do setor. Com o aumento do comércio internacional e a diversificação dos gostos dos consumidores, entender as tendências de exportação de vinhos torna-se crucial para desenvolver estratégias de negócios eficazes.

A análise dos dados de exportação de vinhos do Brasil ao longo dos últimos 15 anos oferece uma visão detalhada das mudanças no mercado global, permitindo que as empresas identifiquem padrões, sazonalidades e preferências dos consumidores em diferentes regiões do mundo. Essa compreensão é essencial para a tomada de decisões informadas em relação à produção, marketing e distribuição dos produtos, visando maximizar as oportunidades de negócio e minimizar os riscos associados às flutuações do mercado.

**Tipos de Análise Realizados:**
- Análise exploratoria dos dados de exportação,importação, produção e comercialização
- Análise das tendências de mercado 
- Análise do cenario mundial de vinhos

**Principais Indicadores Chave de Desempenho:**
- Quantidade em litros de vinho exportado(1Kg = 1L)
- Valor exportado (US\$)
- Valor por litro exportado(US\$)
- Quantidade em litros de vinho importado(1Kg = 1L)
- Valor Importado (US\$)
- Valor por litro importado(US$)
- Quantidade em litros de vinho produzido(1L)
- Quantidade em litros de vinho comercializado(1L)

## 📜 Estrutura do Projeto

A estrutura de diretórios do projeto foi organizada da seguinte forma:
```
├── README.md 
├── data - dados
│ ├── processed - processados
│ └── raw - iniciais
├── notebooks - codigos
├── reports - relatorios 
│ └── figures
│ └── PowerBi 
```
## 🛠 Tratamento e Limpeza dos Dados

A análise de dados de vinhos exige um processo meticuloso de tratamento e limpeza para garantir a confiabilidade e a qualidade das informações. Este estudo detalha as etapas realizadas para preparar os dados para análise subsequente, utilizando a biblioteca Pandas do Python.

_Considerações Importantes:_
1. Foram utilizados conjuntos de dados reais e de plataformas de dados abertos, com referências disponíveis no relatório em PDF na pasta "reports - relatorios".
2. Os dados brutos foram filtrados para incluir apenas informações relevantes para vinhos, excluindo dados irrelevantes ou inconsistentes.
3. As etapas de tratamento de dados incluíram remoção de valores ausentes, duplicados,inconsistentes; Identificação e correção de erros de digitação, formatação,codificação conversão de unidades,  e padronização de nomes e categorias.
   
_Etapas do Tratamento e Limpeza dos Dados:_
1. Importação dos dados e biblioteca
2. Tratamento e Limpeza dos Dados de Produção e Comércio de Vinhos no Brasil
3. Tratamento e Limpeza dos Dados de Importação e Exportação do Brasil
4. Tratamento e Limpeza dos Dados de Mercado Global de Vinhos e Cotação de Moeda 

## 📊 Análise dos Dados

A etapa de análise de dados se configura como o cerne deste projeto, onde todo o conhecimento adquirido sobre o negócio se converte em insights valiosos para o mercado nacional e internacional de vinhos. Através de técnicas robustas e análises aprofundadas, desvendamos as tendências e oportunidades que impulsionam esse setor dinâmico.

_Etapas da Análise dos Dados:_
1. Importação dos dados e biblioteca
2. Análise dos Dados de Produção e Comércio de Vinhos no Brasil
3. Análise dos Dados dos Dados de Importação e Exportação do Brasil
4. Análise dos Dados dos Dados de Mercado Global de Vinhos e Cotação de Moeda
5. Criação do Modelo matematico para retirada de insights sobre os melhores países para investir.

## 📈 Insights e Conclusões

Nossa análise aprofundada do mercado global de vinhos revelou um panorama promissor para o Brasil, com um vasto potencial de crescimento nas exportações. Identificamos países que representam oportunidades estratégicas de investimento comercial e marketing, abrindo portas para o sucesso internacional dos vinhos brasileiros

Países-Alvo para Investimento:
- Rússia
- Estados Unidos
- Japão
- China
- Uruguai
- Alemanha
- Reino Unido

Ao explorar as oportunidades e implementar as estratégias descritas neste estudo, os produtores brasileiros de vinho podem alcançar um sucesso significativo nos mercados internacionais. O Brasil possui um enorme potencial para se tornar um player global de destaque na indústria vinícola, e este estudo oferece um mapa detalhado para guiar o caminho para o sucesso.

Recomendamos a leitura do relatório completo de Análise de Dados, disponível neste repositório na pasta "reports - relatorios". Este relatório fornece uma análise detalhada dos dados, metodologias e insights utilizados neste estudo, oferecendo uma visão abrangente do potencial exportador dos vinhos brasileiros.

Acreditamos que este estudo se configura como uma ferramenta valiosa para o desenvolvimento da indústria vinícola brasileira, contribuindo para o aumento das exportações e o reconhecimento internacional da qualidade dos vinhos brasileiros.

