# 🧠 Previsão de Score de Crédito com Machine Learning

Projeto de **Inteligência Artificial aplicada ao setor financeiro**, desenvolvido em Python durante aulas da **Hashtag Programação**. O objetivo é prever automaticamente o **score de crédito de clientes** (Ruim, Ok ou Bom) com base em dados históricos, utilizando modelos de **Machine Learning supervisionado**.

> Projeto desenvolvido com base nas aulas da Hashtag Programação. Implementação, experimentação de modelos e estruturação por **Caio Marques** para fins de estudo e portfólio.

---

## 📌 Problema de Negócio

Um banco precisa automatizar a análise de crédito para:

* Reduzir decisões manuais
* Diminuir riscos financeiros
* Aumentar a velocidade de aprovação de clientes

Este projeto cria um modelo capaz de **classificar o perfil de crédito de um cliente** com base em seus dados financeiros e comportamentais.

---

## ⚙️ Solução Desenvolvida

A solução utiliza um pipeline de Machine Learning que:

1. Importa e trata a base de dados
2. Separa dados em treino e teste
3. Treina dois modelos diferentes
4. Compara a performance usando métricas de acurácia
5. Avalia possíveis melhorias para o modelo

---

## 🧠 Modelos Utilizados

* 🌳 **Árvore de Decisão (Decision Tree Classifier)**
* 📍 **K-Nearest Neighbors (KNN)**

Os dois modelos são comparados para identificar qual apresenta melhor desempenho no problema de classificação de score de crédito.

---

## 📊 Métricas de Avaliação

* **Accuracy Score (Acurácia)**

A métrica mede a proporção de previsões corretas em relação ao total de previsões realizadas no conjunto de teste.

---

## 🛠️ Tecnologias Utilizadas

* **Python 3.10+**
* **Pandas** — Manipulação e análise de dados
* **Scikit-learn** — Modelos de Machine Learning e métricas
* **Jupyter Notebook** — Ambiente de desenvolvimento
* **NumPy** — Operações matemáticas

---

## 📂 Estrutura do Projeto

```bash
📁 previsao-score-credito
 ├── inicial.ipynb
 ├── dados.csv
 └── README.md
```

---

## ▶️ Como Executar o Projeto

### 1️⃣ Clone o repositório

```bash
git clone https://github.com/seu-usuario/previsao-score-credito.git
cd previsao-score-credito
```

### 2️⃣ Crie e ative o ambiente virtual

```bash
python -m venv venv

# Windows
venv\\Scripts\\activate

# Linux/Mac
source venv/bin/activate
```

### 3️⃣ Instale as dependências

```bash
pip install pandas numpy scikit-learn jupyter
```

### 4️⃣ Execute o notebook

```bash
jupyter notebook
```

Abra o arquivo `inicial.ipynb` no navegador e execute as células em ordem.

---

## 🔄 Fluxo do Projeto

```text
Base de Dados
     ↓
Tratamento dos Dados
     ↓
Separação Treino/Teste
     ↓
Treinamento dos Modelos
     ↓
Avaliação com Métricas
     ↓
Comparação de Resultados
```

---

## 🔮 Melhorias Futuras

* 🔍 Implementar **GridSearchCV** para otimização de hiperparâmetros
* 📈 Testar novos modelos (Random Forest, XGBoost, Logistic Regression)
* 📊 Criar visualizações de desempenho (Matriz de Confusão, ROC Curve)
* 💾 Persistir o modelo treinado com `joblib` ou `pickle`
* 🌐 Criar uma API com FastAPI para consumo do modelo em produção
* 🐳 Containerizar o pipeline com Docker

---

## 🧑‍💻 Autor

Desenvolvido por **Caio Marques**
🎯 Ciência da Computação | Machine Learning | Backend | APIs | Data-Driven Systems

---

## ⭐ Considerações Finais

Este projeto representa minha introdução prática à aplicação de **Machine Learning em problemas reais de negócio**, com foco em análise de crédito e tomada de decisão automatizada. Ele serve como base para evoluir a solução para um ambiente de produção com API, banco de dados e monitoramento de modelos.

Se esse projeto te ajudou ou inspirou, deixa uma ⭐ no repositório — isso fortalece muito meu portfólio! 🚀🔥
