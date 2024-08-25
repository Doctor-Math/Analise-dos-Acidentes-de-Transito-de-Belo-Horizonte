# Análise dos Acidentes de Trânsito em Belo Horizonte (2016-2022)

## Introdução

Este projeto realiza uma análise detalhada dos acidentes de trânsito em Belo Horizonte, Minas Gerais, Brasil, ao longo dos anos de 2016 a 2022. O objetivo é oferecer uma visão abrangente do panorama viário da capital mineira, utilizando ferramentas analíticas para entender o cenário do trânsito, identificar padrões e prever tendências futuras.

## Metodologia

- **Período de Análise:** Os dados analisados abrangem o período de 2016 a 2022, permitindo uma visão completa das tendências e padrões de acidentes de trânsito na cidade.

- **Ferramentas Utilizadas para Análise:**
  - **Gráficos:** Utilizados para visualizar e interpretar os dados de acidentes de trânsito, facilitando a identificação de tendências e padrões ao longo dos anos.
  - **Métodos de Reamostragem (Bootstrap):** Aplicados para avaliar a variabilidade dos dados e obter estimativas mais robustas sobre as características dos acidentes.
  - **Regressão:** Técnicas de regressão foram empregadas para identificar relações entre variáveis e prever tendências futuras, ajudando na formulação de políticas públicas para melhorar a segurança no trânsito.

## Objetivos

O projeto visa descrever aspectos importantes do cenário urbano de Belo Horizonte no contexto do trânsito e projetar tendências futuras. As análises realizadas são fundamentais para orientar políticas públicas e estratégias de segurança no trânsito, com o potencial de melhorar a gestão viária e reduzir a ocorrência de acidentes.

## Índice

1. **Número de acidentes por ano/mês**
2. **Número de acidentes por ano**
3. **Acidentes de trânsito mais comuns por ano**
4. **Acidentes anuais de trânsito mais fatais**
5. **Acidentes anuais de trânsito menos fatais**
6. **Acidentes de trânsito mais letais**
7. **Taxa de mortalidade no trânsito em Belo Horizonte**
8. **Taxa de letalidade no trânsito em Belo Horizonte**
9. **Distribuição de acidentes por Belo Horizonte**
10. **Estimativa mensal de acidentes**
11. **Regressão: Número de acidentes por bairro**
12. **Modelos de previsão**
13. **Limitações dos modelos**
14. **Resumo**

## Resumo

Entre 2016 e 2018, os acidentes de trânsito em Belo Horizonte se mantiveram estáveis. A partir de 2019, houve um aumento significativo, especialmente em maio, seguido por uma queda acentuada em 2020, coincidente com as medidas de distanciamento social e restrições de mobilidade devido à pandemia de COVID-19. Em 2022, os números começaram a se aproximar dos níveis de 2019.

**Principais Achados:**

- **Tipos de acidentes mais fatais:** Atropelamentos de pessoas são consistentemente os mais fatais.
- **Tipos de acidentes menos fatais:** Abalroamentos com vítima tendem a ser os menos fatais.
- **Acidentes mais letais:** Quedas de veículos com vítima têm a maior taxa de letalidade, seguidas por choques mecânicos e capotamentos/tombamentos com vítima.
- **Taxas de mortalidade e letalidade:** A taxa de mortalidade se manteve relativamente constante durante a pandemia (2020-2021), enquanto a taxa de letalidade foi mais alta nesses anos, com 2020 sendo o ano mais letal da série.

**Hipóteses Consideradas:**

- **Supernotificação em 2019:** O aumento significativo de registros de acidentes pode ser atribuído a mudanças nos procedimentos de notificação ou melhorias na documentação, influenciando os dados e a interpretação de tendências nos anos subsequentes.

**Distribuição Geográfica dos Acidentes:**

- **Hotspots:** O Centro de Belo Horizonte, especialmente a Avenida Afonso Pena, é um local frequente de acidentes devido à alta concentração de tráfego e complexidade viária. Outros pontos críticos incluem o cruzamento entre as avenidas Cristiano Machado, Dom Pedro I e Rua Padre Pedro Pinto.
- **Principais vias:** As avenidas Andradas, Antônio Carlos, Vilarinho, Dom Pedro II, Amazonas e o Anel Rodoviário são destacadas nas distribuições dos tipos de acidentes mais frequentes.

**Modelos de Previsão:**

- **Modelo 2019x2022:** A relação entre os acidentes de 2019 e 2022 mostra que a maioria dos bairros segue uma tendência consistente, exceto por alguns outliers que sugerem influências específicas não capturadas pelo modelo.
- **Modelo 2021x2022:** Mostra uma correlação mais forte e consistente, indicando que os padrões de acidentes durante a pandemia resultaram em previsões mais confiáveis para 2022.

## Conclusão

Este projeto fornece uma análise detalhada e insights sobre os acidentes de trânsito em Belo Horizonte, informando políticas públicas e estratégias de segurança no trânsito. Os resultados mostram a importância de considerar mudanças nos padrões de mobilidade e os impactos de eventos externos, como a pandemia, ao analisar e prever tendências de acidentes.
