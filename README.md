# ðŸ§  NeurÃ´nio de Rosenblatt em Planilha

Este projeto demonstra o treinamento de um **Perceptron de Rosenblatt** utilizando uma **planilha Excel**, com duas abas organizadas para facilitar o entendimento teÃ³rico e prÃ¡tico. Foi desenvolvido como atividade acadÃªmica e demonstra conceitos fundamentais de Redes Neurais.

---

## ðŸ“š O que vocÃª vai encontrar

- ImplementaÃ§Ã£o de um **Perceptron (neurÃ´nio artificial)** com pesos ajustÃ¡veis  
- CÃ¡lculo do **erro**, **atualizaÃ§Ã£o de pesos** e **bias**  
- AplicaÃ§Ã£o da **regra de atualizaÃ§Ã£o de Rosenblatt**  
- Duas abas:
  - `NeurÃ´nio`: visualizaÃ§Ã£o da rede neural e iteraÃ§Ãµes
  - `Treinamento`: registros dos padrÃµes, saÃ­das desejadas e pesos ao longo do processo

---

## ðŸ“Š Como funciona o treinamento

A planilha simula o comportamento de um neurÃ´nio com entradas binÃ¡rias, aplicando a seguinte **fÃ³rmula clÃ¡ssica**:

```text
y = f(w1*x1 + w2*x2 + ... + wn*xn + bias)
```

Com:

- `x` = entradas  
- `w` = pesos  
- `bias` = peso fixo (threshold)  
- `f` = funÃ§Ã£o de ativaÃ§Ã£o degrau

A atualizaÃ§Ã£o dos pesos segue a regra:

```text
w(n+1) = w(n) + taxa_aprendizado * erro * entrada
```

E o **bias** tambÃ©m Ã© atualizado:

```text
bias(n+1) = bias(n) + taxa_aprendizado * erro
```

---

## ðŸ“ˆ Resultado do projeto

ApÃ³s as iteraÃ§Ãµes, o neurÃ´nio aprende a **classificar corretamente os padrÃµes de entrada**, ajustando os pesos com base no erro entre a saÃ­da desejada e a saÃ­da real.

---

## âš ï¸ VisualizaÃ§Ã£o da planilha

> O arquivo estÃ¡ grande e nÃ£o pode ser visualizado diretamente no GitHub.  
> **FaÃ§a o download para acessar todo o conteÃºdo.**

ðŸ“Ž [ðŸ“¥ Clique aqui para baixar a planilha](./Final%20-%20Atividade%20Pratica.xlsx)

---

## ðŸ§  Conceito: O que Ã© o NeurÃ´nio de Rosenblatt?

O **Perceptron de Rosenblatt** foi o primeiro modelo matemÃ¡tico funcional de uma rede neural artificial. Criado por **Frank Rosenblatt** em 1958, Ã© a base para muitas redes modernas.  
Seu objetivo Ã© **aprender** a separar classes lineares com base em exemplos (entradas e saÃ­das desejadas), ajustando pesos sinÃ¡pticos automaticamente.

---

## âœï¸ Autor

**Rodrigo Ribeiro Carvalho**  
ðŸ“ JoÃ£o Pessoa â€“ PB  
ðŸ”— [PortfÃ³lio no GitHub](https://github.com/Rodrigo-RRC)  
ðŸ“§ rodrigoribeiroc.dev@gmail.com

---

## âœ… Status

> Projeto concluÃ­do e disponÃ­vel para consulta acadÃªmica e demonstraÃ§Ã£o de fundamentos de aprendizado de mÃ¡quina.