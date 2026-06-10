# 🧠 Neurônio Artificial — Função Sigmoide

Simulação de um neurônio artificial com visualização da função de ativação Sigmoide, desenvolvido em Python no Google Colab.

## 📌 Sobre o Projeto

Este projeto simula o funcionamento de um neurônio artificial, componente fundamental das Redes Neurais Artificiais (ANNs).

O neurônio recebe entradas, aplica pesos e um bias, calcula o somatório ponderado e passa o resultado pela função de ativação Sigmoide, gerando uma saída entre 0 e 1.

## 🧱 Arquitetura do Neurônio

```
Entradas        Pesos           Somatório         Ativação
x1 = i   →   w1 = 10  ─┐
x2 = 0   →   w2 = 10  ──→  Σ(w*x) + b  →  Sigmoid  →  saída
x3 = 0   →   w3 = -2  ─┘        ↑
                                b = 3 (bias)
```

### Fórmulas utilizadas

**Somatório ponderado:**

```
somatorio = (w1 * x1) + (w2 * x2) + (w3 * x3) + b
```

**Função de ativação Sigmoide:**

```
saída = 1 / (1 + e^(-somatorio))
```

## 📊 Resultado

O gráfico gerado mostra o comportamento da saída do neurônio conforme o valor de x1 varia de -20 até 19:

- Valores muito negativos → saída próxima de 0
- - Valores muito positivos → saída próxima de 1
  - - Transição suave entre 0 e 1 — característica da função Sigmoide
   
    - ## 🛠️ Tecnologias Utilizadas
   
    - - Python 3
      - - Math — cálculo do número de Euler
        - - Matplotlib — geração do gráfico
         
          - ## ▶️ Como Executar
         
          - **Google Colab**
         
          - 1. Acesse o notebook pelo link do repositório
            2. 2. Clique em "Abrir no Colab"
               3. 3. Execute todas as células
