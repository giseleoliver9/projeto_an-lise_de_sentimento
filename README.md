# Análise de Sentimentos em Avaliações de Produtos
<div align="center">
  <img src="https://github.com/giseleoliver9/projeto_an-lise_de_sentimento/blob/main/NLPWordCloud-1.png" alt="Nuvem de Palavras" width="500"/>
</div>

Este projeto faz parte da disciplina **Processamento de Linguagem Natural (NLP) e Reconhecimento de Padrões** do curso de especialização em Inteligência Artificial e Data Science pela FETES.

## 🎯 Objetivo

Analisar sentimentos expressos em quase 10 mil avaliações de produtos coletadas de plataformas como Amazon e Mercado Livre. O foco foi identificar padrões de opinião dos consumidores a partir de técnicas de NLP e visualização de dados.

## 🗂️ Dataset

Este dataset contém avaliações de produtos de duas das maiores plataformas de comércio eletrônico no Brasil: **Amazon** e **Mercado Livre**. Possui 4 colunas e 9.815 linhas.

📎 [Link para o dataset no Kaggle](https://www.kaggle.com/datasets/sampaiovitor/avaliaes-em-portugus-amazon-e-mercado-livre)

## 🧰 Ferramentas Utilizadas

- Python
- Google Colab
- Bibliotecas:
  - `TextBlob` e `VADER` – análise de sentimentos
  - `NLTK` e `spaCy` – pré-processamento textual
  - `matplotlib`, `seaborn`, `wordcloud` – visualizações

## 🔎 Etapas do Projeto

1. **Coleta de Dados**  
   Dataset obtido do Kaggle com avaliações reais em português.

2. **Pré-Processamento**  
   - Remoção de duplicatas e ruídos
   - Limpeza de caracteres especiais e stopwords
   - Tokenização e lematização dos textos

3. **Análise de Sentimentos**  
   - Classificação em *Positivo*, *Negativo* e *Neutro*
   - Uso de `TextBlob` e `VADER` com modelos pré-treinados

4. **Visualizações**  
   - Nuvem de palavras
   - Gráficos de distribuição dos sentimentos
   - Análise de frequência de palavras

## 📊 Resultados

- A maioria dos comentários foi classificada como **neutra** (7.699), seguida por **positivos** (1.780) e **negativos** (162).
- Termos mais frequentes: `produto`, `gostar`, `funcionar`, `usar`, `bom`.
- Produtos mais avaliados: **mochilas de viagem** e **fones de ouvido**.



## 🧠 Lições Aprendidas

- Modelos simples como TextBlob e VADER funcionam bem para textos curtos e objetivos.
- A limpeza e o pré-processamento são essenciais para garantir bons resultados.
- Avaliações neutras podem refletir limitações dos modelos ou falta de carga emocional.
- Futuramente, o uso de modelos mais avançados (como BERT) pode melhorar a classificação.

---

## 🚀 Executando o Projeto

Você pode acessar o código-fonte diretamente no Google Colab ou baixá-lo do GitHub:

📓 [Notebook no GitHub](https://github.com/giseleoliver9/projeto_an-lise_de_sentimento/blob/main/an%C3%A1lise_de_sentimento.ipynb)

---

## 🖥️ Apresentação Final

📎 [PDF da Apresentação](https://github.com/giseleoliver9/projeto_an-lise_de_sentimento/blob/main/Apresenta%C3%A7%C3%A3o.pdf)

---

## 👩‍💻 Autoria

**Gisele Oliveira**  
Especialização em IA e Data Science – FETES
