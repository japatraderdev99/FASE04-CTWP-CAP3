# Classificação de Grãos de Trigo usando Machine Learning

## 📋 Descrição do Projeto

Este projeto aplica a metodologia CRISP-DM para desenvolver modelos de aprendizado de máquina que classificam variedades de grãos de trigo com base em suas características físicas. O objetivo é automatizar o processo de classificação realizado manualmente em cooperativas agrícolas de pequeno porte, aumentando eficiência e precisão.

## 🎯 Objetivo

Desenvolver um sistema de classificação automática de três variedades de grãos de trigo:
- **Kama**
- **Rosa**
- **Canadian**

## 📊 Dataset

Utilizamos o **Seeds Dataset** do [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/236/seeds), contendo 210 amostras de grãos com 7 características físicas:

1. **Área**: medida da área do grão
2. **Perímetro**: comprimento do contorno do grão
3. **Compacidade**: relação geométrica do grão
4. **Comprimento do Núcleo**: eixo principal da elipse equivalente
5. **Largura do Núcleo**: eixo secundário da elipse
6. **Coeficiente de Assimetria**: medida de assimetria
7. **Comprimento do Sulco do Núcleo**: comprimento do sulco central

## 🔬 Metodologia CRISP-DM

### 1. Análise e Pré-processamento
- Estatísticas descritivas
- Visualização de distribuições
- Análise de correlações
- Tratamento de valores ausentes
- Normalização/Padronização

### 2. Modelagem
Implementação e comparação de 5 algoritmos:
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest
- Naive Bayes
- Logistic Regression

### 3. Otimização
- Grid Search para hiperparâmetros
- Validação cruzada
- Métricas de desempenho

### 4. Avaliação
- Acurácia
- Precisão
- Recall
- F1-Score
- Matriz de Confusão

## 📁 Estrutura do Projeto

```
FASE04-CTWP-CAP3/
├── .github/          # Configurações GitHub
├── assets/           # Imagens e recursos visuais
├── config/           # Arquivos de configuração
├── document/         # Documentação adicional
│   └── other/
├── scripts/          # Scripts auxiliares
├── src/              # Código-fonte principal
│   └── seeds_classification.ipynb
├── seeds_dataset.txt # Dataset original
├── diretrizes-projeto.txt
├── .gitignore
└── README.md
```

## 🚀 Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/japatraderdev99/FASE04-CTWP-CAP3.git
cd FASE04-CTWP-CAP3
```

2. Instale as dependências:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

3. Execute o notebook:
```bash
jupyter notebook src/seeds_classification.ipynb
```

## 📦 Dependências

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

## 👥 Autores

Projeto desenvolvido para FIAP - Graduação em Inteligência Artificial

## 📄 Licença

Este projeto é desenvolvido para fins educacionais.
