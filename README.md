# 🧠 Neurônio de Rosenblatt em Planilha

Este projeto demonstra o treinamento de um **Perceptron de Rosenblatt** utilizando uma **planilha Excel**, com duas abas organizadas para facilitar o entendimento teórico e prático. Foi desenvolvido como atividade acadêmica e demonstra conceitos fundamentais de Redes Neurais.

---

## 📚 O que você vai encontrar

- Implementação de um **Perceptron (neurônio artificial)** com pesos ajustáveis  
- Cálculo do **erro**, **atualização de pesos** e **bias**  
- Aplicação da **regra de atualização de Rosenblatt**  
- Duas abas:
  - `Neurônio`: visualização da rede neural e iterações
  - `Treinamento`: registros dos padrões, saídas desejadas e pesos ao longo do processo

---

## 📊 Como funciona o treinamento

A planilha simula o comportamento de um neurônio com entradas binárias, aplicando a seguinte **fórmula clássica**:

```text
y = f(w1*x1 + w2*x2 + ... + wn*xn + bias)
```

Com:

- `x` = entradas  
- `w` = pesos  
- `bias` = peso fixo (threshold)  
- `f` = função de ativação degrau

A atualização dos pesos segue a regra:

```text
w(n+1) = w(n) + taxa_aprendizado * erro * entrada
```

E o **bias** também é atualizado:

```text
bias(n+1) = bias(n) + taxa_aprendizado * erro
```

---

## 📈 Resultado do projeto

Após as iterações, o neurônio aprende a **classificar corretamente os padrões de entrada**, ajustando os pesos com base no erro entre a saída desejada e a saída real.

---

## ⚠️ Visualização da planilha

> O arquivo está grande e não pode ser visualizado diretamente no GitHub.  
> **Faça o download para acessar todo o conteúdo.**

📎 [📥 Clique aqui para baixar a planilha](./Final%20-%20Atividade%20Pratica.xlsx)

---

## 🧠 Conceito: O que é o Neurônio de Rosenblatt?

O **Perceptron de Rosenblatt** foi o primeiro modelo matemático funcional de uma rede neural artificial. Criado por **Frank Rosenblatt** em 1958, é a base para muitas redes modernas.  
Seu objetivo é **aprender** a separar classes lineares com base em exemplos (entradas e saídas desejadas), ajustando pesos sinápticos automaticamente.

---

## ✍️ Autor

**Rodrigo Ribeiro Carvalho**  
📍 João Pessoa – PB  
🔗 [Portfólio no GitHub](https://github.com/Rodrigo-RRC)  
📧 rodrigoribeiroc.dev@gmail.com

---

## ✅ Status

> Projeto concluído e disponível para consulta acadêmica e demonstração de fundamentos de aprendizado de máquina.
