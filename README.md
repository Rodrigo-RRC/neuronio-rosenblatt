
# 🧠 Neurônio de Rosenblatt Treinado em Planilha

Este projeto apresenta um neurônio de Rosenblatt (Perceptron de camada única) implementado e treinado **inteiramente em uma planilha**, com visualização e ajustes dinâmicos. O objetivo é demonstrar, de forma didática, os fundamentos do Perceptron, incluindo o cálculo dos pesos, bias e função de ativação.

---

## 📌 Sobre o Projeto

A planilha contém duas abas principais:

1. **Neurônio**: Interface visual onde o RU (limiar) pode ser alterado para observar o comportamento da ativação do neurônio.
2. **Treinamento**: Cálculo manual do ajuste de pesos com base em acertos e erros, incluindo a regra de atualização do Perceptron.

---

## 📊 Conceitos Envolvidos

### 🧮 Fórmulas do Perceptron

A predição y' é calculada da seguinte forma:

Se a soma ponderada dos sinais de entrada for maior ou igual ao RU (limiar), o neurônio ativa (1); caso contrário, inativa (0):

```
y' = 1, se  (x1 * w1 + x2 * w2 + ... + b) ≥ RU  
y' = 0, caso contrário
```

Onde:
- `x` = entradas
- `w` = pesos
- `b` = bias (viés)
- **RU** = limiar ajustável

---

### 🔁 Regra de Atualização dos Pesos

```
w = w + η * (y - y') * x  
b = b + η * (y - y')
```

- `η` = taxa de aprendizado (learning rate)
- `y` = saída esperada
- `y'` = saída prevista

---

## 🔧 RU como Limiar de Ativação

Na aba **Neurônio**, é possível alterar o valor do **RU** dinamicamente. Ele atua como o **limiar de ativação**:

- Se a **soma ponderada** for **maior ou igual ao RU**, o neurônio é ativado (retorna 1).
- Se for **menor**, o neurônio permanece inativo (retorna 0).

O comportamento visual da célula muda conforme o RU:
- ✅ Neurônio ativado: **verde**
- ❌ Neurônio inativo: **vermelho**

⚠️ O valor do RU deve ser um número **natural** (inteiro positivo).

---

## 🧪 Exemplo de Entrada

| x1 | x2 | w1 | w2 | Bias | RU | Ativação |
|----|----|----|----|------|----|----------|
| 1  | 1  | 0.4| 0.6| 0.2  | 1  | ✅       |
| 0  | 1  | 0.4| 0.6| 0.2  | 1  | ❌       |

---

## 📁 Estrutura da Planilha

```
📄 Final - Atividade Pratica.xlsx
├── 🧠 Neurônio          → Interface com limiar (RU)
└── 📈 Treinamento       → Ajuste manual dos pesos e bias
```

---

## 📌 Observações

- Todas as fórmulas estão embutidas diretamente nas células da planilha.
- A aba **Neurônio** é interativa e visual.
- O projeto simula os princípios básicos de uma rede neural linear.

---

## 🧑‍💻 Autor

**Rodrigo Ribeiro Carvalho**  
GitHub: [Rodrigo-RRC](https://github.com/Rodrigo-RRC)  
LinkedIn: [linkedin.com/in/rodrigo-ribeiro-datascience](https://www.linkedin.com/in/rodrigo-ribeiro-datascience)

---

## ✅ Status: Projeto Concluído e Funcional

Este projeto faz parte do meu portfólio de aprendizado prático em ciência de dados e redes neurais.

---

🚀 Projeto simples, prático e totalmente funcional – direto da planilha para o mundo da IA.
