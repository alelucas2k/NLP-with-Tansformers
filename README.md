Este repositório contém os notebooks e projetos baseados no livro *Natural Language Processing with Transformers* de **Lewis Tunstall**, **Leandro von Werra** e **Thomas Wolf**. Abaixo, apresento um resumo dos **quatro primeiros capítulos** do livro, que cobrem os fundamentos essenciais do processamento de linguagem natural (NLP) usando a arquitetura Transformer.

## Capítulo 1: Introdução aos Transformers
O primeiro capítulo introduz os fundamentos dos **Transformers**, uma arquitetura que revolucionou o campo de **NLP**. O capítulo explica como os transformers se diferenciam de redes neurais tradicionais e outras abordagens anteriores, como RNNs e LSTMs. A ênfase está na **atenção** e como ela permite que o modelo "preste atenção" em diferentes partes de uma sequência de entrada, ao contrário de processar a sequência de maneira sequencial, como as RNNs.

### Pontos principais:
- Diferenças entre **RNNs**, **LSTMs** e **Transformers**.
- Introdução ao mecanismo de **atenção** e **auto-atenção**.
- Exemplos de arquiteturas Transformer populares, como **BERT** e **GPT**.

## Capítulo 2: Primeiros Passos com Modelos Pré-Treinados
No segundo capítulo, aprendemos a construir um **classificador de sentimentos** para tweets, utilizando modelos **pré-treinados** da biblioteca *Hugging Face Transformers*. O capítulo mostra como ajustar esses modelos para tarefas específicas, sem a necessidade de treinar um modelo do zero, o que economiza tempo e recursos computacionais.

### Pontos principais:
- Como usar modelos **pré-treinados** do Hugging Face.
- Ajuste fino de modelos para tarefas como **classificação de sentimentos**.
- O conceito de **transfer learning** e como ele facilita o treinamento de modelos em tarefas específicas.

## Capítulo 3: Trabalhando com Datasets de NLP
O terceiro capítulo foca em como manipular e trabalhar com **datasets de NLP**. Ele detalha técnicas como **tokenização**, **limpeza de dados** e como usar as ferramentas da *Hugging Face Datasets* para carregar e processar dados de maneira eficiente.

### Pontos principais:
- Técnicas de **tokenização** e **pré-processamento** de textos.
- Como usar a biblioteca **Hugging Face Datasets** para carregar e manipular grandes volumes de dados.
- Estratégias para melhorar a qualidade dos dados e otimizar o treinamento do modelo.

## Capítulo 4: Reconhecimento de Entidades Nomeadas (NER)
O quarto capítulo é especialmente interessante, pois trata do **Reconhecimento de Entidades Nomeadas (NER)**, uma tarefa fundamental em NLP. Neste capítulo, construímos e treinamos um modelo para classificar tokens em três categorias principais: **ORGANIZAÇÃO (ORG)**, **PESSOA (PERSON)** e **LOCALIZAÇÃO (LOC)**. O capítulo destaca a importância de **datasets multilíngues** e o impacto do **custo computacional** no treinamento de modelos, especialmente ao utilizar apenas **CPUs** para o treinamento.

### Pontos principais:
- Implementação de um modelo **NER** para reconhecer entidades como **ORG**, **PERSON** e **LOC**.
- Desafios ao lidar com **dados multilíngues** e como adaptar o modelo a diferentes idiomas.
- Reflexão sobre o **alto custo computacional** no treinamento de modelos e como o uso de **GPUs dedicadas** pode reduzir significativamente o tempo de treinamento.
