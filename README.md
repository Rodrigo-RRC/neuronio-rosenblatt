# 🧠 Neurônio de Rosenblatt em Planilha

Projeto de demonstração prática de um **perceptron de camada única**, implementado diretamente em uma **planilha de cálculo**. O objetivo foi treinar o neurônio com entradas lógicas, ajustando pesos e bias até atingir a classificação correta com base na lógica aprendida.

---

## 📌 O que é um Neurônio de Rosenblatt?

O neurônio de Rosenblatt é a base do perceptron, um modelo simples de rede neural proposto por Frank Rosenblatt em 1958. Ele realiza:

- Soma ponderada das entradas (input * peso)
- Soma com um bias (limiar de ativação)
- Aplicação de uma função de ativação (geralmente degrau)

Esse processo permite **classificar padrões binários** (como AND, OR, etc.), sendo o princípio das redes neurais modernas.

---

## 📊 O que contém neste projeto?

O projeto foi implementado em uma planilha Excel com duas abas:

### ✅ `Treinamento`
Nesta aba, os dados de entrada são processados e a planilha realiza iterações de treinamento, ajustando os pesos com base no erro obtido.

- Taxa de aprendizado (α)
- Cálculo do erro (desejado - obtido)
- Atualização dos pesos com:  
  `peso_novo = peso_anterior + α * erro * entrada`
- Atualização do bias

### ✅ `Neurônio`
Nesta aba são aplicados os valores dos pesos e bias obtidos no treinamento para prever novas saídas. Ou seja, aqui está a **rede já treinada**.

---

## 🧮 Estatística envolvida

O projeto inclui os seguintes conceitos fundamentais:

- **Erro quadrático**
- **Gradiente para ajuste de pesos**
- **Aprendizado supervisionado**
- **Função de ativação tipo degrau (step function)**
- **Balanceamento com pesos e bias (limiar)**

Essa é uma introdução sólida à matemática por trás do aprendizado de máquina, em um ambiente acessível como o Excel.

---

## 🚀 Como usar

1. Abra a planilha no Excel ou Google Sheets
2. Acesse a aba `Treinamento` para acompanhar os ajustes dos pesos
3. A aba `Neurônio` mostra como as entradas são processadas com os pesos finais
4. Você pode alterar as entradas e observar como o neurônio responde

---

## 🖼️ Captura de Tela (opcional)

> *(Aqui você pode adicionar futuramente um print das duas abas da planilha com destaque nos pesos, bias e respostas)*

---

## 📁 Arquivo

> O arquivo `.xlsx` está disponível neste repositório com o nome:  
📄 Final - Atividade Prática.xlsx

---

## ✍️ Autor

**Rodrigo Ribeiro Carvalho**  
Analista de Dados e entusiasta em IA e automações  
GitHub: [Rodrigo-RRC](https://github.com/Rodrigo-RRC)

---

> “A base do futuro está nas conexões simples que aprendem com o passado.”
