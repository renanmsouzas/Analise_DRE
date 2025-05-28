# Analise_DRE

### Dashboard Gerencial no Power BI

Neste projeto, construí um painel que integra diferentes visões de análises financeiras com foco gerencial e estratégico. Um dos grandes desafios foi estruturar as medidas para simular corretamente os valores em cada etapa da DRE, como Receita, Margem, EBITDA e Lucro, respeitando a hierarquia e os agrupamentos.

### Destaques do projeto:
Análise Orçado x Realizado (O x R)
Segmentação por ano/mês e filial, com indicadores visuais claros e rótulos de referência nos cartões, permitindo leitura rápida de metas e desempenho.

### Análise Horizontal (AH)
#### Desafio: construir a lógica para filtrar corretamente os dados ao nível do grupo da DRE, como por exemplo a Receita Bruta, exigindo identificar o nome completo do grupo e depois o ID para aplicar os cálculos pois alguns grupos não possuem valores na tabela fato, pois são grupos calculados.
Comparativo por ano/mês/ano-mês  e filial com % de crescimento com indicadores visuais para ajudar a detectar facilmente tendências positivas ou negativas.

### Análise Vertical (AV)
Comparativo por ano/mês/ano-mês e filial com % de relevância de cada grupo sobre a receita bruta para entender a estrutura de custos e despesas da empresa, com indicadores visuais para auxiliar na análise.

### Análise What If (WIF)
Simulação de cenários com parâmetros ajustáveis para Receita, Custos e Despesas. A cada mudança, o modelo recalcula automaticamente todos os níveis da DRE, mostrando o impacto direto sobre Margem, EBITDA e Lucro Líquido.

Utilizei convenções comuns de DRE, como números negativos entre parênteses e valores divididos por mil, facilitando a leitura executiva.

Esse painel foi um grande aprendizado na criação de medidas dinâmicas, uso de parâmetros e estruturação lógica de uma DRE flexível no Power BI. 
