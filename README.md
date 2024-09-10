
---

### **Título do Projeto:**
[Impacto das Mudanças Climáticas na Agricultura](notebook/EDA.ipynb)

### **Descrição:**
Este projeto visa analisar o impacto das mudanças climáticas na agricultura utilizando um conjunto de dados relevante. O objetivo é entender diferentes variáveis climáticas podem afetar a produção agrícola e entender os padrões que podem ser utilizados para a tomada de decisão na área.

### **Objetivo Principal:**
Fazer uma análise exploratória para compreensão dos dados presentes no dataset.

### **Etapas:**
1. Definição do problema.
2. Obtenção e exploração dos dados.

### **Requisitos:**
- Python 3.11.9
- Bibliotecas: pandas, numpy, matplotlib, seaborn, scipy, plotly

---

O dataset contém 10.000 registros e 15 colunas, com diferentes tipos de variáveis, incluindo atributos numéricos e categóricos. Aqui está uma visão geral das colunas:

| **Nome da Coluna**               | **Descrição**                                    | **Tipo de Dado** |
|----------------------------------|--------------------------------------------------|------------------|
| **Year**                         | Ano da coleta dos dados                          | int64            |
| **Country**                      | País onde os dados foram coletados               | object           |
| **Region**                       | Região dentro do país                            | object           |
| **Crop_Type**                    | Tipo de cultura                                  | object           |
| **Average_Temperature_C**        | Temperatura média em graus Celsius               | float64          |
| **Total_Precipitation_mm**       | Precipitação total em milímetros                 | float64          |
| **CO2_Emissions_MT**             | Emissões de CO2 em milhões de toneladas          | float64          |
| **Crop_Yield_MT_per_HA**         | Produção de culturas em toneladas por hectare    | float64          |
| **Extreme_Weather_Events**       | Número de eventos climáticos extremos            | int64            |
| **Irrigation_Access_%**          | Porcentagem de acesso à irrigação                | float64          |
| **Pesticide_Use_KG_per_HA**      | Uso de pesticidas em kg por hectare              | float64          |
| **Fertilizer_Use_KG_per_HA**     | Uso de fertilizantes em kg por hectare           | float64          |
| **Soil_Health_Index**            | Índice de saúde do solo                          | float64          |
| **Adaptation_Strategies**        | Estratégias de adaptação adotadas                | object           |
| **Economic_Impact_Million_USD**  | Impacto econômico em milhões de dólares          | float64          |

---
