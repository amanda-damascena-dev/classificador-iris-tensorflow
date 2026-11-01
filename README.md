# Classificador de Flores Iris com TensorFlow

Projeto de Machine Learning desenvolvido para classificar flores do conjunto de dados Iris em três espécies:

- **Iris setosa**
- **Iris versicolor**
- **Iris virginica**

A solução utiliza uma rede neural construída com TensorFlow/Keras, considerando as medidas de comprimento e largura das sépalas e pétalas.

## Objetivo

O objetivo deste projeto é aplicar conceitos de Inteligência Artificial e Machine Learning em um problema de classificação multiclasse, passando pelas etapas de preparação dos dados, treinamento, avaliação e realização de novas previsões.

## Tecnologias utilizadas

- Python 3.11
- TensorFlow e Keras
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Etapas do projeto

1. Carregamento do conjunto de dados Iris.
2. Organização e exploração dos dados.
3. Separação entre dados de treinamento e teste.
4. Padronização das variáveis com `StandardScaler`.
5. Construção de uma rede neural com TensorFlow/Keras.
6. Treinamento utilizando validação e `EarlyStopping`.
7. Avaliação com acurácia, precisão, recall e F1-score.
8. Construção da matriz de confusão.
9. Visualização da evolução da acurácia e da função de perda.
10. Realização de previsões com novas amostras.

## Arquitetura da rede neural

A rede neural foi construída com:

- Camada de entrada com 4 características;
- Primeira camada oculta com 16 neurônios e ativação ReLU;
- Segunda camada oculta com 8 neurônios e ativação ReLU;
- Camada de saída com 3 neurônios e ativação Softmax.

O treinamento utiliza o otimizador Adam e a função de perda `sparse_categorical_crossentropy`.

## Resultados

O notebook apresenta:

- Acurácia no conjunto de teste;
- Relatório de classificação por espécie;
- Matriz de confusão;
- Curvas de acurácia e perda;
- Classificação de três novas flores;
- Testes automáticos para validar as previsões e confirmar uma acurácia mínima de 80%.

Os resultados podem variar levemente entre execuções devido ao processo de treinamento da rede neural.

## Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/amanda-damascena-dev/classificador-iris-tensorflow.git
```

### 2. Entre na pasta do projeto

```bash
cd classificador-iris-tensorflow
```

### 3. Crie o ambiente virtual

```bash
python -m venv .venv
```

### 4. Ative o ambiente no Windows PowerShell

```powershell
.\.venv\Scripts\Activate.ps1
```

### 5. Instale as dependências

```bash
python -m pip install -r requirements.txt
```

### 6. Execute o notebook

Abra o arquivo `classificador_iris.ipynb` no VS Code, selecione o ambiente `.venv` como kernel e clique em **Run All**.

## Notebook

O código completo, os gráficos e os resultados estão disponíveis em:

[Visualizar o notebook](./classificador_iris.ipynb)

## Estrutura do projeto

```text
classificador-iris-tensorflow/
├── classificador_iris.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

## Aprendizados

Com este projeto, pratiquei:

- Preparação e padronização de dados;
- Classificação multiclasse;
- Construção de redes neurais;
- Treinamento e avaliação de modelos;
- Análise de métricas;
- Visualização de resultados;
- Organização e documentação de projetos de Machine Learning.

## Autora

**Amanda Gomes Damascena**

Estudante de Engenharia de Software e Técnica em Informática, com interesse em Inteligência Artificial, Machine Learning, automação e desenvolvimento de soluções tecnológicas.

- [GitHub](https://github.com/amanda-damascena-dev)
- [LinkedIn](https://www.linkedin.com/in/amanda-damascena/)