# Aplicação para auxiliar a detecção e fiscalização do uso de máscaras na prevenção de transmissão do COVID-19

# 1 - Introdução
Sob a pandemia de COVID-19 em andamento (causada pelo coronavírus SARS-CoV-2) a lei 140.19, de 2020, é muito clara, é obrigatório o uso de máscaras de proteção individual para a circulação em espaços públicos e privado acessíveis ao público, em vias públicas e transportes públicos.

A medida segue as comprovações levantadas pela OMS comprovou para a efetividade da máscara no combate ao contágio do COVID-19.
Ficou a cargo da Vigilância Sanitária a verificação do uso de máscaras e o respeito as orientações com relação ao distanciamento social nos estabelecimentos comerciais, estão sujeitos a multas pessoas que estiverem sem máscara nos locais exigidos e os estabelecimentos que permitirem a presença de pessoas sem proteção e/ou situação irregular.

## 1.1 - Motivação
O uso de máscara se tornou obrigatório durante a pandemia, entretanto não existe e não é possível verificar se todos estão utilizando de forma eficiente a máscara.

## 1.2 - Objetivo
A criação de um modelo de Deep Learning que consegue identificar quem está usando ou não as máscaras, com o propósito de auxiliar na fiscalização e alertar sobre uma pessoa transitando sem máscara.
Um modelo que possa se integrar a outros sistemas e assim criando uma aplicação cada vez maior para ele.

# 2 - Fundamentação Técnica

Neste capítulo será abordado a definição das tecnologias e a justificativa para a escolha delas.

## 2.1 - Python
Um dos motivos da popularidade do Python é o seu forte apoio na área de inteligência artificial (IA), de acordo com o IEEE. O Python também oferece um bom número de bibliotecas e pacotes que os programadores podem usar para que não construam determinado código do zero.

O grande número de bibliotecas e pacotes disponíveis para o Python contêm código para certas funções básicas, para que os programadores não precisem escrevê-las do zero. Especificamente, o estudo do IEEE e vários especialistas apontaram para a biblioteca Keras e o TensorFlow, por meio dos quais os programadores que usam IA podem trabalhar com redes neurais.

## 2.2 - Tensorflow
O TensorFlow proporciona flexibilidade e controle com recursos como a API funcional Keras e a API de subclassificação de modelos para a criação de topologias complexas. Use a execução rápida para simplificar a prototipagem e acelerar a depuração.

## 2.3 - Keras
O Keras foi criado para ser amigável, modular, fácil de estender e trabalhar com o Python. A API foi “projetada para seres humanos, não para máquinas” e “segue as melhores práticas para reduzir a carga cognitiva”.

Camadas neurais, funções de custo, otimizadores, esquemas de inicialização, funções de ativação e esquemas de regularização são todos módulos independentes que você pode combinar para criar modelos. Novos módulos são simples de adicionar, como novas classes e funções. Os modelos são definidos em código Python, não em arquivos de configuração de modelo separados.

## 2.4 - Open CV
OpenCV (Open Source Computer Vision Library) é uma biblioteca de software de visão computacional e aprendizado de máquina de código aberto. O OpenCV foi construído para fornecer uma infraestrutura comum para aplicativos de visão computacional e para acelerar o uso da percepção da máquina em produtos comerciais.

A biblioteca possui mais de 2.500 algoritmos otimizados, que incluem um conjunto abrangente de algoritmos de visão computacional e aprendizado de máquina clássicos e de última geração. Esses algoritmos podem ser usados para detectar e reconhecer rostos, identificar objetos, classificar ações humanas em vídeos, rastrear movimentos de câmera, rastrear objetos em movimento etc.

A biblioteca é amplamente utilizada em empresas, grupos de pesquisa e por órgãos governamentais.

# 3 - Desenvolvimento
![Resultado](https://j.gifs.com/k25O96.gif)
