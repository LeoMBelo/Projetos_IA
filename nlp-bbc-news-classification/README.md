Classificação de Notícias com NLP Clássico vs BERT

**Ideia Geral**
Este projeto investiga como diferentes abordagens de Processamento de Linguagem Natural (NLP) se comportam em uma tarefa de classificação multiclasse de textos.

O objetivo é classificar notícias em categorias como:

. Negócios (Business)
. Entretenimento (Entertainment)
. Política (Politics)
. Esportes (Sport)
. Tecnologia (Technology)

Comparamos pipelines clássicos de machine learning com modelos modernos baseados em transformers, focando não apenas no desempenho, mas também nos trade-offs entre complexidade, interpretabilidade e custo computacional

**Objetivos**
. Construir um pipeline completo de NLP (do pré-processamento à avaliação)
. Comparar representações clássicas de texto (BoW, TF-IDF)
. Avaliar múltiplos modelos:
    - Regressão Logística
    - SVM Linear
    - Naive Bayes
    - BERT
. Realizar avaliação robusta (validação cruzada + conjunto de teste)

**Dataset**
BBC News Dataset
. ~2000 notícias
. 5 categorias
. Dataset limpo e bem estruturado, ideal para benchmark
. Analisar desempenho e erros dos modelos
. Fornecer uma comparação crítica entre abordagens clássicas e deep learning
