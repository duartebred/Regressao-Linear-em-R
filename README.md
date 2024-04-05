# Métodos Estatísticos para a Bioinformática, 2023/24

## Sobre o Projeto

Este repositório contém os materiais e resultados de um projeto de análise estatística focado na construção e avaliação de modelos de regressão linear. O objetivo deste trabalho é explorar relações entre uma variável dependente contínua e várias variáveis independentes de diferentes tipos, provenientes de conjuntos de dados relevantes para a bioinformática. Este repositório foi criado no ambito da UC Métodos Estatísticos para a Bioinformática (2023/24), do Mestrado em Bioinformática da Escola de Engenharia da Universidade do Minho, seguindo um conjunto estruturado de instruções para pesquisa, análise exploratória de dados, construção de modelo, avaliação e verificação das condições de aplicabilidade.


## Datasets Utilizados

Os datasets utilizados neste projeto foram selecionados de fontes públicas confiáveis:
- [Kaggle](https://www.kaggle.com/datasets)

Escolhemos esta base de dados, pois oferece uma ampla gama de variáveis que permitem uma análise detalhada e uma modelagem eficaz.

## “Anemia Diagnosis Dataset”
Este trabalho, teve como referência o conjunto de dados “Anemia Diagnosis Dataset”, extraído da base de dados kaggle.

Segundo a Organização Mundial da Saúde, a anemia é uma condição caraterizada pela diminuição do número de glóbulos vermelhos ou da concentração de hemoglobina no sangue (World Health Organization,2022).
O hemograma é um exame que, por meio de colheita de amostra sanguínea, avalia o número e a morfologia de células do sangue, sendo um exame laboratorial fundamental para o diagnóstico da anemia. 

O conjunto de dados disponibilizado (dataset_anemia.xlsx) é utilizado para diagnosticar a prevalência de diferentes tipos de anemia, incluindo a sua severidade, com base em parâmetros de entrada como o sexo, a idade e vários valores resultantes de um hemograma realizado a 364 pacientes. Deste estudo foram excluídos lactentes, crianças com menos de 10 anos e grávidas.

De acordo com a teoria, níveis de RBC e/ou PCV menores levarão a níveis de HGB menores. Também um RDW alto no hemograma pode indicar anemia. Através dos conteúdos abordados nas aulas, iremos abordar a relação entre as variáveis em estudo, tentando construir um modelo de regressão linear que se ajuste aos nossos dados e que nos permita tirar informações no que diz respeito aos valores de um hemograma que podem estar alterados quando estamos perante valores de hemoglobina indicativos de anemia. 

Assim, a nossa variável dependente será o nível de hemoglobina no sangue (HGB), e as variáveis independentes selecionadas serão: a idade (Age), o sexo (Sex), os níveis de glóbulos vermelhos no sangue (RBC), o volume de glóbulos vermelhos no sangue (PCV), o volume celular médio (MCV), a hemoglobina celular média (MCH), a distribuição do tamanho dos glóbulos vermelhos (RDW) e a contagem de glóbulos brancos (TLC).


## O que é Regressão Linear?

A regressão linear é um método estatístico usado para modelar a relação entre uma variável dependente contínua e uma ou mais variáveis independentes. Ao ajustar uma linha que minimiza a distância entre os pontos de dados e a linha em si, a regressão linear permite fazer previsões dentro do conjunto de dados. Este método é amplamente utilizado em várias disciplinas, incluindo bioinformática, para identificar potenciais fatores influenciadores sobre um fenômeno de interesse.

## Contribuições
- [Duarte Velho](https://github.com/duartebred) (pg53841)
- [Joana Lopes](https://github.com/joanalopes0711) (pg53498)
- [João Ferreira](https://github.com/B-Neil) (pg52182)
- [Ricardo Oliveira](https://github.com/ricardofoliveira61) (pg53501)


