# Disciplina: Fundamentos da Ciência de Dados 
# Trabalho T2 - Analise Exploratória com Statsmodel 

## Descrição

O dataset Iris contém informações sobre flores de três espécies diferentes de íris (setosa, versicolor e virginica). Para cada flor, são fornecidas quatro características: comprimento e largura da sépala, e comprimento e largura da pétala.

### 💡 Objetivo da Análise 
Construir um modelo de regressão linear que permita: - Entender quais variáveis têm maior impacto sobre o comprimento da sépala. - Quantificar essa influência com base nos coeficientes do modelo. - Avaliar a qualidade do modelo por meio de métricas estatísticas e testes de diagnóstico.  

### 🔍 Metodologia 

1. **Análise Exploratória**:    - Estatísticas descritivas das variáveis.    - Matriz de correlação para identificar relações entre as variáveis.    - Gráficos de dispersão para visualizar as relações entre as variáveis.  
2. **Regressão Linear**: 
   - Ajuste de um modelo de regressão linear com a variável alvo sendo o comprimento da sépala.    - Avaliação dos coeficientes do modelo para entender a influência de cada variável.    - Testes de diagnóstico para verificar a normalidade dos resíduos. ### Resultados Esperados - Identificação das variáveis que mais influenciam o comprimento da sépala. - Modelo de regressão linear com boa capacidade preditiva (R² elevado). - Resíduos do modelo seguindo uma distribuição normal, sem evidência de heterocedasticidade ou 
autocorrelação.  

### 📄 Conclusão 

A análise exploratória e a regressão linear permitirão entender melhor as relações entre as 
características morfológicas das flores de íris e o comprimento da sépala.  

## Dependências

Para rodar este notebook, você precisa das seguintes bibliotecas:

```bash
# instalar dependencias no ambiente virtual deste workspace\ usando amnbiente virtual do workspace em /.venv
%pip install pandas scikit-learn matplotlib seaborn statsmodels polar numpy
```

## Como Usar

1. Clone este repositório para sua máquina local.
2. Execute o notebook no seu ambiente Python preferido.
3. Acompanhe os resultados da análise exploratória.

## Resultados

O notebook faz uso de visualizações para identificar padrões nas variáveis do dataset Iris e permite uma fácil integração com modelos de aprendizado de máquina para classificação e previsão.
