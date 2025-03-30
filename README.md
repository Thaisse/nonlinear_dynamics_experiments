# nonlinear_dynamics_experiments
Este repositório contém três códigos-fonte desenvolvidos para a estimação de parâmetros em diferentes sistemas dinâmicos, bem como suas respectivas documentações. Os métodos utilizados combinam técnicas de simulação com abordagens de otimização, utilizando Algoritmos Genéticos (AG) e Mínimos Quadrados Não Lineares (MQNL).
# Estimação de Parâmetros de Sistemas Dinâmicos

Este repositório contém três códigos-fonte desenvolvidos para a estimação de parâmetros em diferentes sistemas dinâmicos, bem como suas respectivas documentações. Os métodos utilizados combinam técnicas de simulação com abordagens de otimização, utilizando Algoritmos Genéticos (AG) e Mínimos Quadrados Não Lineares (MQNL).

## Conteúdo

- **Pêndulo Amortecido Forçado**  
  Código que estima os parâmetros de um pêndulo amortecido forçado, comparando os resultados obtidos pelo Algoritmo Genético e pelo método dos Mínimos Quadrados.  


- **Modelo SIR**  
  Código que implementa o modelo epidemiológico SIR para estimar os parâmetros \(\beta\) e \(\gamma\) através de simulação e ajuste por métodos de otimização.  


- **Pêndulo Duplo (Precisão Aprimorada)**  
  Código que utiliza simulação de alta precisão e um algoritmo genético aprimorado para estimar os parâmetros de um pêndulo duplo.  

## Requisitos

Para executar os códigos, é necessário ter instalados os seguintes pacotes:
- Python 3.x
- NumPy
- SciPy
- Matplotlib
- DEAP

Você pode instalar as dependências utilizando o pip:
```bash
pip install numpy scipy matplotlib deap
