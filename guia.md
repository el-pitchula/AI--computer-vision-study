# Guia de estudo para projetos com Inteligência Artificial

## Requisitos Necessários:
- Conhecimento em lógica de programação e Python, incluindo estruturas condicionais e de repetição.
- Noções básicas de Data Science.

## Área do Conhecimento Responsável:
Ciência de Dados.

## Base de Estudo sobre IA:
- Algoritmos de otimização.
- Lógica Difusa (Fuzzy Logic).
- Machine Learning.
- Classificações:
  - Naive Bayes.
  - Árvore de Decisão.
  - Orange.
  - kNN.
- Regressão.
- Agrupamento.
- Associação.
- Pré-processamento.
- Séries Temporais.

## Compreensão dos Tipos de IA:
- Machine Learning (ML), Deep Learning (DL) e Reinforcement Learning (RL).
- Processamento de Linguagem Natural (PLN).
- Visão Computacional (Interpretação e análise de imagens/dados visuais).
- Robótica Inteligente.

## Sobre a Visão Computacional:
- Ferramentas principais: Python e OpenCV.
- Conteúdo abrangente:
  - Coordenadas e manipulação de pixels.
  - Processamento de imagens.
  - Identificação e rastreamento de objetos em vídeos.
- Bibliotecas de apoio:
  - OpenCV.
  - NumPy, SciPy, Matplotlib.
  - PyTesseract.

## Sugestões para Estudo:
- Defina claramente os problemas a serem identificados nas radiografias.
- Aprofunde-se na lógica difusa e sua aplicação em sistemas de classificação.
- Amplie a seção sobre visão computacional, incluindo detecção de padrões e segmentação de imagens.
- Veja sobre bibliotecas específicas de Machine Learning como TensorFlow e Keras também.
- Teste algoritmos, técnicas e bancos de dados (em áreas de trabalho diferentes) antes de implementar.
- Intercale o estudo referente ao objetivo e à base (faça esse tipo de estudo complementar para otimizar o tempo).
- Explore bibliotecas mais específicas.
- Pesquise por artigos e repositórios git próximos do seu objetivo.
- Recorra mais às documentações oficiais das bibliotecas utilizadas e do próprio Python.
- Evite depender do ChatGPT e de outras IAs; o Stack Overflow e outros fóruns como o Reddit já têm a solução completa e detalhada do seu problema, principalmente se for em relação a bugs ou ao software em si (boa parte dos problemas já são conhecidos pelas comunidades).

## Links para Estudo:
- [Introdução à Visão Computacional (PDF)](https://nca.ufma.br/~geraldo/vc/1.introducao.pdf)
- [Detectar Objetos em Imagens com Visão Personalizada de IA do Azure](https://learn.microsoft.com/pt-br/training/modules/detect-objects-images-custom-vision/)
- [Vídeo: Introdução à Visão Computacional](https://www.youtube.com/watch?v=_LHebVofdwo)
- [Reconhecer Imagens](https://www.youtube.com/watch?v=4RO-3QllHZk)
- [Curso de OpenCV](https://www.youtube.com/watch?v=JiC9iBNRWdQ&list=PLsyobOqUhkthjvmA_s7tTjb7V2EiwYYGC)

## Links Git:
- [Projetos com Visão Computacional](https://github.com/topics/visao-computacional)
- [Curso Básico de IA](https://github.com/VitoriaCarvalho/VisaoComputacional)
- [Exemplos de Trabalhos com Visão Computacional (MIT)](https://github.com/VitoriaCarvalho/VisaoComputacional)
- [Classificador de Cores](https://github.com/MariaEduardaDeAzevedo/classificador-de-cores)

## Links de Artigos:
- [Detecção de Tumor Cerebral](https://repositorio.ufu.br/bitstream/123456789/37641/1/DeteccaoTumorCerebral.pdf)
- [Estimativa da Idade Óssea por Radiografia](https://www.scielo.br/j/rb/a/pDQRNvzWMWng4R7jJqPm5XK/?lang=pt)
- [IA para Radiologias de Emergência](https://www.mdpi.com/2075-4418/12/12/3223)

## Documentação das Bibliotecas:
- [Python](https://docs.python.org/3/)
- [OpenCV](https://docs.opencv.org/4.x/index.html)
  - [Cascade Classifier](https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html)
  - [Arquivos .xml para Cascade](https://github.com/opencv/opencv/tree/master/data/haarcascades)


# Guia básico de Inteligência Artificial

## 1. Conceitos Fundamentais
  
- **Machine Learning (Aprendizado de Máquina):** Subcampo da IA que se concentra em desenvolver algoritmos e técnicas que permitem aos computadores aprender a partir de dados.

- **Deep Learning (Aprendizado Profundo):** Técnica de Machine Learning que utiliza redes neurais profundas para aprender padrões complexos nos dados.

- **Reinforcement Learning (Aprendizado por Reforço):** Subcampo da IA em que os agentes aprendem a partir de interações com o ambiente, recebendo feedbacks de recompensa ou penalidade (na robótica por exemplo).

## 2. Bibliotecas Importantes

- **NumPy:** Fundamental para computação numérica em Python, utilizada em manipulação de dados.

- **Pandas:** Para análise de dados que oferece estruturas de dados flexíveis.

- **Scikit-Learn:** Fornece uma variedade de algoritmos de Machine Learning prontos para uso, além de ferramentas para pré-processamento de dados.

- **TensorFlow e PyTorch:** Para implementar modelos de Deep Learning.

- **OpenCV:** Utilizada para processamento de imagens e visão computacional.

## 3. Conceitos de Machine Learning

- **Dados de Treinamento:** Conjunto de dados usados para treinar um modelo de Machine Learning.

- **Algoritmos de Classificação:** Usados para prever a classe ou categoria a que um exemplo pertence.

- **Algoritmos de Regressão:** Usados para prever valores numéricos com base em dados de entrada.

## 4. Fluxo de Trabalho Básico

1. **Entendimento do Problema:** Definir claramente o problema que se deseja resolver com IA.

2. **Coleta e Preparação de Dados:** Adquirir dados relevantes e prepará-los para análise e treinamento.

3. **Escolha do Modelo:** Selecionar o algoritmo ou modelo de Machine Learning adequado para o problema.

4. **Treinamento do Modelo:** Utilizar os dados de treinamento para ajustar o modelo aos padrões nos dados.

5. **Avaliação do Modelo:** Avaliar o desempenho do modelo utilizando métricas apropriadas.

6. **Implantação e Monitoramento:** Colocar o modelo em produção e monitorar seu desempenho ao longo do tempo.

## 5. Projetos Práticos

- **Classificação de Imagens:** Implementar um modelo de classificação de imagens utilizando TensorFlow ou PyTorch.

## 6. Desafios Comuns

- **Overfitting:** Quando um modelo se ajusta demais aos dados de treinamento e não generaliza bem para novos dados.

- **Underfitting:** Quando um modelo é muito simples para capturar os padrões nos dados de treinamento.

- **Seleção de Características:** Escolher as características certas dos dados é crucial para o desempenho do modelo.
