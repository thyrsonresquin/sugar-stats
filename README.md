# sugar-stats

Este projeto foi desenvolvido como parte de um laboratório de testes para o curso de Desenvolvimento de IA. O objetivo principal é explorar um conjunto de dados de pacientes para entender a relação entre características biométricas (idade, peso, altura) e os resultados de exames relacionados à diabetes.

📌 Sobre o Projeto

O foco deste repositório é aplicar técnicas de Ciência de Dados e Machine Learning para analisar a saúde de pacientes. Através deste dataset, é possível realizar tarefas como:
- Análise Exploratória de Dados (EDA): Identificar correlações entre peso/idade e o resultado do exame.
- Engenharia de Recursos (Feature Engineering): Cálculo de IMC (Índice de Massa Corporal).
- Modelagem Preditiva: Treinar modelos para prever o resultado do exame com base nas demais variáveis.

📊 O Conjunto de Dados

O arquivo utilizado é o exame_diabes.csv, que contém 100 registros com as seguintes colunas:
|     Coluna    |               Descrição           |
|---------------|-----------------------------------|
| id_paciente   | identificador único de paciente   |
| genero        | gênero dos pacientes (M/F)        |
| idade         | idade em anos                     |
| peso          | peso do paciente (kg)             |
| altura        | altura do paciente (cm)           |
| resultado     | valor numérico obtido             |

🛠️ Tecnologias Recomendadas

Para executar este projeto, sugere-se o uso das seguintes bibliotecas Python:
- **Pandas**: Para manipulação e análise de dados.
- **Matplotlib/Seaborn**: Para visualização de dados.
- **Scikit-learn**: Para criação de modelos de Machine Learning.
- **Jupyter Notebook**: Para documentação interativa do código
