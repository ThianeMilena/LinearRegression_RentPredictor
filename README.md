# Predição de Preço de Aluguel - Modelo de Regressão Linear

Este projeto visa desenvolver um modelo de regressão linear para prever o preço de aluguel de imóveis com base em diversas variáveis. O conjunto de dados utilizado neste projeto foi obtido do Kaggle e contém informações sobre propriedades para aluguel no Brasil. Você pode acessar o conjunto de dados [aqui](https://www.kaggle.com/rubenssjr/brasilian-houses-to-rent).

**Conjunto de Dados**

O conjunto de dados inclui diversas variáveis, como cidade, área, número de quartos, número de banheiros, vagas de estacionamento, entre outras. No processo de modelagem, foram escolhidas as seguintes variáveis como características principais:

- city
- area
- rooms
- bathroom
- parking spaces
- fire insurance (R$)
  
As variáveis foram selecionadas com base na relevância para a previsão do preço do aluguel e na simplificação do modelo. A escolha de características específicas pode ser crucial para obter um equilíbrio entre a precisão do modelo e a simplicidade.

**Pré-processamento e Tratamento de Outliers**

O pré-processamento dos dados incluiu a padronização de variáveis numéricas usando **StandardScaler** e a codificação de variáveis categóricas usando **OneHotEncoder**. Além disso, outliers foram tratados usando o escore Z (z-score) para remover valores além de um limite especificado.

**Avaliação do Modelo**

O modelo de regressão linear foi encapsulado em um pipeline, incorporando todas as etapas de pré-processamento. As métricas de avaliação incluem:

- R² Score: Mede a proporção da variabilidade na variável dependente que é explicada pelo modelo.
- RMSE (Root Mean Squared Error): Representa a raiz quadrada da média dos quadrados dos erros entre os valores preditos e reais.
- MAE (Mean Absolute Error): Representa a média dos valores absolutos dos erros entre os valores preditos e reais.

**Por que Essas Variáveis?**

A escolha das variáveis foi guiada pela relevância para o problema de prever o preço do aluguel. As variáveis selecionadas são consideradas como tendo maior impacto no preço do aluguel, proporcionando um modelo mais explicativo e interpretável.

**Como Contribuir**

Se você deseja contribuir para este projeto, sinta-se à vontade para sugerir melhorias ou enviar solicitações de pull. Todas as contribuições são bem-vindas!
