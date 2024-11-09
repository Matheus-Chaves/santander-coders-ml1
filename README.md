# Santander Coders - Machine Learning I

Projeto do módulo de Machine Learning I do Santander Coders 2024, que consiste em realizar a análise exploratória dos dados e criar um modelo de machine learning baseado no material visto durante as aulas.

 > ℹ️ Mais informações sobre o projeto podem ser vistas no arquivo `project_description.ipynb`.

## Inicializando o projeto

1. Clone o repositório

    ```bash
    git clone https://github.com/Matheus-Chaves/santander-coders-ml1.git
    ```

2. Opcional, mas recomendado: crie e ative o ambiente virtual com `venv`

    ```bash
    python -m venv .venv  
    source .venv/bin/activate
    ```

    > A versão recomendada do Python está no arquivo `.python_version`
    > Dependendo do sistema operacional, o comando pode ser 'python3' ao invés de 'python'

3. Instale as dependências

    ```bash
    pip install -r requirements.txt
    ```

## Integrantes

- Filipe Sousa ([GitHub](https://github.com/filsousa) / [LinkedIn](https://www.linkedin.com/in/filipel-sousa/));
- Giovanni Ornellas ([GitHub](https://) / [LinkedIn](https://www.linkedin.com/in/));
- Matheus Chaves ([GitHub](https://github.com/Matheus-Chaves) / [LinkedIn](https://www.linkedin.com/in/matheus-chavess/));

## Sobre

Escolhemos construir um **modelo de regressão** para prever a **qualidade** de vinhos com base em suas propriedades químicas - como acidez, pH, sulfatos, etc. Para isso, optamos por seguir com o dataset de vinhos da [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/): [Wine Quality](https://archive.ics.uci.edu/dataset/186/wine+quality).

O objetivo é construir um bom modelo após uma eficaz análise exploratória dos dados (EDA), pré-processamento e testes com diferentes modelos de machine learning - também garantindo uma boa documentação do passo a passo durante as etapas.

## Limitações do projeto

O modelo e os dados estão limitados a:

- Dados tabulares
- Apenas modelos de machine learning
- Apenas algoritmos supervisionados - classificação ou regressão
- Evitar fugir muito do conteúdo visto em aula
- Evitar o uso de ferramentas de AutoML (ex.: PyCaret)

## Referências

<https://archive.ics.uci.edu/>
<https://archive.ics.uci.edu/dataset/186/wine+quality>
