# Modelos em Machine Learning

Este repositório abriga mini-projetos que exploram modelos de **regressão linear, regressão logística, SVM(Support Vector Machine) e redes neurais.**  

## Regressão Linear

O **modelo de regressão linear** consiste em dois blocos, com o primeiro dedicado à aplicação de técnicas de Machine Learning em Marketing Digital. 
O objetivo principal é desenvolver um modelo capaz de prever o número de usuários convertidos em um cenário fictício, onde uma empresa hipotética emprega diversas 
estratégias de Marketing Digital e gostaria de ter um modelo de Machine Learning capaz de prever quantos usuários serão convertidos
(ou seja, quantas pessoas comprarão os produtos da empresa) após cada campanha. Conseguindo fazer a previsão, a empresa pode ter uma ideia mais clara de quanto deve investir em 
cada campanha e o retorno esperado.  
**Regressão Linear: Prevendo Usuários Convertidos**  [clique aqui](https://github.com/leticiadluz/Machine_learning_modelos/blob/main/Machine.learning_Marketing.digital_Regressao.ipynb)

O Segundo bloco emprega um conjunto de métricas para criar um modelo de regressão linear capaz de prever a nota final dos alunos em um determinado conjunto de dados. Nessa análise, exploram-se múltiplos indicadores e variáveis para construir um modelo preditivo capaz de estimar com precisão as notas finais dos estudantes.  
**Regressão Linear: Prevendo a nota final de alunos**  [clique aqui](https://github.com/leticiadluz/Machine_learning_modelos/blob/main/Previsao_notafinal_Regressao.ipynb)

## Classificação
O segmento dedicado à **classificação** neste repositório traz consigo alguns mini-projetos. O primeiro, assim como no modelo de regressão, incorpora técnicas de Machine Learning no contexto de Marketing Digital. Agora, o foco é antecipar a probabilidade de conversão de leads, ou seja, estimar qual é a probabilidade de um potencial cliente se tornar efetivamente um cliente ao realizar a compra do produto. Para este primeiro utilizamos o modelo de regressão logística. 
A Regressão Logística é utilizada para prever a probabilidade de um evento ocorrer, geralmente em problemas de classificação binária. Ela utiliza uma função logística para mapear a saída para um intervalo entre 0 e 1, representando a probabilidade de pertencer a uma classe ou categoria específica. Se a probabilidade prevista for maior que um certo limite (geralmente 0,5), o modelo classifica a observação como pertencente à classe positiva; caso contrário, à classe negativa.  
**Classificação: Regressão Logística - Prevendo a probabilidade de um lead ser convertido** [clique aqui](https://github.com/leticiadluz/Machine_learning_modelos/blob/main/Machine.learning_Marketing.digital_Classificacao.ipynb)

Neste outro projeto, dedicamo-nos à tarefa de classificação utilizando o dataset do Titanic, amplamente reconhecido por sua aplicação em competições do Kaggle. O objetivo é determinar se um passageiro sobreviverá ou não ao naufrágio. Empregamos, também, a técnica de regressão logística para conduzir essas classificações. Além disso, conduzimos uma análise exploratória dos dados, a qual proporcionou insights significativos sobre o perfil dos sobreviventes.  
**Classificação: Regressão Logística - Análise e Classificação de Sobrevivência no Titanic** [clique aqui](https://github.com/leticiadluz/Machine_learning_modelos_R/blob/main/Titanic_Kaggle.ipynb)

Agora, empregamos o conjunto de dados HouseVotes8, o qual contém informações sobre os votos do congresso em relação a temas específicos. A fim de prever se os votos pertenciam a democratas ou republicanos, optamos por utilizar o modelo Naive Bayes para fins de classificação.    
**Classificação Partidária no Congresso: Uma Análise com Naive Bayes usando o Dataset HouseVotes8** [clique aqui](https://github.com/leticiadluz/Machine_learning_modelos_R/blob/main/Previsao_votos_republicamos_democratas.ipynb)

Neste outro mini-projeto dedicado à classificação, adotamos o modelo SVM (Support Vector Machine). O propósito central é antecipar a identificação de caracteres com base no conjunto de dados fornecido. 
Definindo o Problema: OCR - Optical Character Recognition (Reconhecimento Óptico de Caracteres)
O projeto aborda desafios relacionados à visão computacional, especificamente no âmbito de OCR. O objetivo é treinar o modelo SVM para prever o caractere contido em imagens, tornando-se um componente valioso em sistemas que requerem a interpretação automática de caracteres a partir de documentos, imagens ou outros formatos visuais. Este avanço em Optical Character Recognition promove a automação de processos que envolvem a leitura e interpretação de texto, proporcionando ganhos significativos em eficiência e precisão.  
**Classificação: Modelo SVM - Reconhecimento Óptico de Caracteres** [clique aqui](https://github.com/leticiadluz/Machine_learning_modelos/blob/main/Modelo_SVM.ipynb)

## Rede Neural
No último mini-projeto empregamos um modelo de rede neural para realizar previsões do valor da mediana de ocupação das casas (MEDV) no dataset. A análise concentrou-se nos dados habitacionais da cidade de Boston, EUA. O conjunto de dados utilizado, conhecido como o 'Boston Housing Dataset', proporciona uma visão abrangente das características das residências na região de Boston. Utilizando técnicas avançadas de aprendizado de máquina, aplicamos um modelo de rede neural para prever a MEDV, oferecendo assim uma ferramenta preditiva para compreender e estimar os valores de ocupação das casa.  
**Rede Neural: Prevendo o valor da mediana de ocupação das casas (MEDV) do dataset 'Boston Housing Dataset'** [clique aqui](https://github.com/leticiadluz/Machine_learning_modelos/blob/main/Rede_neural.ipynb)

## Extras
Trouxe também dois notebooks extras para demonstrar a uso do pacote Caret e algoritmo Random Forest

O pacote caret (Classification And REgression Training) em R é uma ferramenta abrangente e flexível para treinar e avaliar modelos de aprendizado de máquina. O pacote caret é 
bastante útil para avaliar e comparar diferentes conjuntos de variáveis (features) em um modelo de aprendizado de máquina. Ele facilita a seleção de variáveis importantes, a avaliação de modelos com diferentes conjuntos de features e a comparação de desempenho entre modelos.
Para veririficar o uso do **Pacote Caret** [clique aqui](https://github.com/leticiadluz/Machine_learning_modelos_R/blob/main/Pacote_Caret.ipynb)


## Ferramentas utilizadas

* Jupyter Notebook

## Linguagem utilizada

* R
