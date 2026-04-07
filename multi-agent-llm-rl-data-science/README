# Multi-Agent LLM + Reinforcement Learning for Data Science

Projeto desenvolvido para explorar como **Modelos de Linguagem (LLMs)** podem colaborar entre si usando **Aprendizado por Reforço (Reinforcement Learning)** para resolver problemas reais de **Ciência de Dados**.

---

## Visão Geral

Neste projeto, dois agentes baseados em LLMs — **Coder** e **Revisor** — trabalham de forma iterativa para:

- Resolver problemas de regressão e classificação
- Melhorar código com feedback contínuo
- Otimizar métricas de desempenho
- Gerar relatórios automáticos ao final

A interação entre os agentes é guiada por um ambiente de **Q-Learning**, onde decisões são tomadas com base em recompensas associadas à qualidade do código e dos resultados.

---

## Arquitetura do Sistema

### Coder (Agente 1)
- Gera código Python para resolver problemas de ciência de dados
- Implementa modelos (regressão, classificação, PCA, etc.)
- Ajusta soluções com base no feedback recebido

### Revisor (Agente 2)
- Avalia o código gerado
- Sugere melhorias (refatoração, métricas, boas práticas)
- Utiliza ferramentas como `pylint` e análise de complexidade

---

## Aprendizado por Reforço

O sistema é modelado como um problema de RL:

- **Estados:** qualidade do código + métricas + complexidade
- **Ações:** refatorar, reescrever ou melhorar métricas
- **Recompensa:**
  - Código executa corretamente
  - Score do pylint
  - Complexidade do código
  - Qualidade das métricas
- **Política:** ε-greedy
- **Algoritmo:** Q-learning

---

## Ambiente

Ferramentas utilizadas:

- `pylint` → qualidade do código
- `radon` → complexidade ciclomática
- `ast` → análise estrutural
- `subprocess` → execução de verificações

---

## Exemplos de Problemas

### Regressão
- Dataset: `fetch_california_housing`
- Métricas: MSE, R²
- Evolução: uso de normalização, múltiplos modelos e PCA

### Classificação
- Dataset: `breast_cancer`
- Métricas: Accuracy, F1-score, Confusion Matrix
- Melhorias: validação cruzada e métricas mais robustas

---

## Geração de Relatórios

Após a interação, o sistema gera automaticamente um relatório estruturado contendo:

- Descrição do problema
- Análise dos dados
- Metodologia
- Resultados
- Conclusões

---

## Principais Insights

- Feedback estruturado (pylint + métricas) melhora significativamente o desempenho
- LLMs conseguem iterar e melhorar soluções, mas nem sempre seguem todas as instruções
- Excesso de informação pode prejudicar o desempenho (overload cognitivo do agente)
- Métricas explícitas incentivam otimização real do modelo

---

## Diferenciais do Projeto

✔ Multi-agent collaboration com LLMs  
✔ Integração de RL com geração de código  
✔ Pipeline completo: problema → código → avaliação → relatório  
✔ Aplicação real em Data Science  
✔ Simulação de ciclo de trabalho semelhante ao de times técnicos  

---

## Executar no Google Colab

Acesse o notebook aqui:

👉 [Abrir no Google Colab](https://drive.google.com/file/d/1O9hdAkwdcD3eofk1cgwwGSFr-UDCoW8k/view?usp=sharing)

---

## Tecnologias Utilizadas

- Python
- Ollama (LLMs locais)
- Reinforcement Learning (Q-learning)
- Scikit-learn
- Pylint
- Radon

---

## Contato

Se quiser discutir o projeto ou oportunidades:

- LinkedIn: www.linkedin.com/in/leobelo
- Email: lmbelo94@gmail.com

---
