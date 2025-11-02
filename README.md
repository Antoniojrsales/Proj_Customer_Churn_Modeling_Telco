# 🚀 Projeto: Previsão de Churn (Rotatividade de Clientes) em uma Empresa de Telecomunicações

Este é um projeto clássico, relevante para o negócio, e que permite explorar todas as etapas que você deseja treinar.
Construir um modelo de Machine Learning (Classificação) que preveja quais clientes têm maior probabilidade de cancelar seus serviços (churn) nos próximos 30 dias.

## ✅ Etapas de Inicialização

- Estruturação do projeto em pastas
- Criação do ambiente virtual
- Definição das bibliotecas principais (via `requirements.txt`)
- Configuração do `.gitignore`
- Primeiros arquivos adicionados ao controle de versão

## 📁 Estrutura Inicial de Pastas

```
Proj_Customer_Churn_Modeling_Telco/
├── Data/
│   └── Telco-Customer-Churn.csv
├── Notebook/
│   └── exploration.ipynb    
├── Visualization/
│   ├── ???.ipynb 
├── ML/
├── venv/
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt
```
## 🛠 Tecnologias Utilizadas

Este projeto foi construído utilizando as seguintes ferramentas e bibliotecas:

* **Python 3.x**
* **Pandas:** Para manipulação e processamento de dados.
* **Numpy:** Para suporte a grandes arrays e matrizes multidimensionais, juntamente com uma coleção de funções matemáticas de alto nível para operar nesses arrays. 
* **Jupyter:** Para documentação passo a passo do projeto (EDA e Modelagem).
* **Plotly:** Para a geração de gráficos de alta qualidade e interativos.
* **Scikit-learn:** Para a fase de Modelagem de classificação (Regressão Logística, Random Forest, XGBoost), avaliação de métricas (Acurácia, Precisão, Recall, F1, AUC-ROC).

## ⚙️ Como Instalar e Rodar o Projeto
Para executar a aplicação em sua máquina local, siga os passos abaixo:

1. Clonagem e Configuração do Ambiente
```
# Clone o repositório
git clone [https://github.com/Antoniojrsales/Proj_Customer_Churn_Modeling_Telco]
cd Proj_Customer_Churn_Modeling_Telco

# Crie e ative o ambiente virtual
python -m venv venv
-nix/Linux: venv/bin/activate  
-Windows: venv\Scripts\activate

## Instale as dependências
pip install -r requirements.txt
```

## 🚧 Próximas Etapas (Roadmap)
- [ ] Concluir a Análise Exploratória de Dados (EDA).
- [ ] Realizar o Pré-processamento e Feature Engineering.
- [ ] Treinar e avaliar modelos de Machine Learning (Classificação).
- [ ] Documentar o modelo final e os principais insights.