# 📊 Análise de Score de Clientes
Este projeto tem como objetivo prever o score de clientes de um banco utilizando técnicas de análise de dados e machine learning. Com base em uma base de dados com 100.000 clientes, o modelo identifica se um cliente possui um bom, médio ou ruim score para ajudar o banco a tomar decisões como concessão de crédito ou empréstimos.

## 🎯 Objetivo
O objetivo principal do projeto é ajudar o banco a:
- Identificar clientes com alto risco de inadimplência.
- Propor soluções baseadas em dados para minimizar prejuízos financeiros.
- Melhorar a análise preditiva do score de crédito, utilizando modelos de machine learning com boa precisão.
Com isso, o banco pode tomar decisões mais informadas sobre concessões de crédito e estratégias de negócio.

## ⚙️ Funcionalidades
📥 **Importação de dados:** Carregar uma base com 100.000 clientes e 25 colunas.
🛠️ **Tratamento de dados:**
- Verificar e remover valores nulos.
- Converter colunas de texto para números com `LabelEncoder`.
🤖 **Treinamento de modelos:**
- Separar os dados em treino e teste.
- Treinar dois algoritmos: Árvore de Decisão e KNN.
📈 **Avaliação de modelos:**
- Comparar a acurácia dos modelos.
- Identificar o modelo mais eficaz (Árvore de Decisão com 82% de precisão).
🔍 **Análise de características importantes:**
- Identificar os atributos mais relevantes, como dívida total, mix de crédito e juros do empréstimo.

## 📋 Pré-requisitos
Antes de começar, você precisará instalar as seguintes ferramentas:
- **Python 3.x**: [Instalar Python](https://www.python.org/)
- Biblioteca **pandas** para manipulação de dados:
  ```bash
  pip install pandas
  ```
- Biblioteca **scikit-learn** para manipulação de dados:
  ```bash
  pip install scikit-learn
  ```

## 📁 Estrutura do Projeto
- `Base de dados dos clientes.csv`: Base de dados com informações dos clientes.
- `scripts/main.ipynb`: Código para importação tratamento dos dados, avaliação dos modelos.
- `README.md`: Documentação do projeto.
- `requirements.txt`: Lista de dependências.

## 🔧 Como Usar
1. Clone este repositório:
  ```bash
  git clone https://github.com/arielm11/analise_score_cliente.git
  cd analise-score-cliente
  ```
2. Certifique-se de ter o arquivo `Base de dados dos clientes.csv` no mesmo diretório do script.
3. Execute o script:
  ```bash
  python scripts/main.ipynb
  ```
5. Confira os resultados de acurácia e as características mais importantes no terminal.

## 🖥️ Tecnologias Utilizadas
- Python: Linguagem principal para análise e machine learning.
- Pandas: Manipulação e limpeza de dados.
- Scikit-learn: Treinamento de modelos de machine learning.
- Jupyter Notebook (opcional): Para testes e exploração inicial dos dados.
