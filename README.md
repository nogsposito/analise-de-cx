# CX Analytics Engine

Este projeto tem como objetivo analisar a experiência dos clientes de e-commerces explorando dados de pedido, entregas e avaliações numéricas e textuais para medir a implicação dos atrasos na insatisfação do cliente e percepção dos serviços.

O objetivo é que o projeto explore a área de Dados de uma forma expansiva e que continue em constante desenvolvimento e melhora com base no que é tangível e possível fazer com o dataset.

## Objetivos do Projeto

- Analisar padrões de tempo de entrega (Contraste entre tempo estimado e tempo real)
- Investigar relação de dados operacionais e avaliações dos clientes e medir sua relação
- Aplicar NLP para análise para que dados estruturados e não estruturados trabalhem juntos.
- Criar base sólida para análises preditivas e NLP.

## Planejamento do projeto seguindo Project Model Canvas

![Project Model Canvas do projeto](assets/cx_project_model_canvas.png)

## Metodologia

Separada pelos respectivos notebooks.

#### 1: Compreensão dos dados

- Compreensão dos dados e inspeção dos dados brutos.
- Analisando o que se pode ser tirado deles.

#### 2: Limpeza dos dados

- Limpeza dos dados e filtrando o que será revelante de ser analisado no projeto
- Agrupando dados que devem funcionar juntos

#### 3: Análise Exploratória

- Análise de correlações entre atrasos e problemas técnicos com as avaliações (Supondo que essas representam a experiência do cliente)
- Agrupamentos em gráficos e obtenção de insights por eles.

#### 4: Conclusões da análise

- Aprofundamento da análise, medida de correlações
- Entrada de NLP para comprovar o que os dados numéricos reenforçavam
- Conclusões sobre as análises

## Achados principais

Atrasos de entrega e quantidade de dias de espera podem afetar significantemente a experiência do cliente. Experiências negtivas dos clientes apresentam padrões linguísticos que associam bastante à frustração aos problemas logísticos e falta de entrega eficiente. A combinação de métricas de delay com análise textual proveram uma compreensão mais rica sobre a experiência do cliente que se auto-validava.

## Tech Stack

- Python
- Pandas & Matplotlib
- Scikit-learn
- NLTK

## Limitações & Escopo

Até agora o projeto focou em uma análise para geração de insights, ainda não possui um modelo funcional em produção. Ainda não há pipeline de começo à fim e o NLP ainda está sendo usado para fins de interpretabilidade apenas.

## Próximos passos

- Definção de score de risco de experiência.
- Construção de pipeline completo.
- Treinamento de modelo de classificação / regressão.
- Automação que monitore novas entregas.

## Importância do projeto

Uso de análise de dados para provar e definir problemas reais do mercado. Habilidade de conectar os dados operacionais com a perspectiva do cliente. Comprovações concretas e maleáveis do que tenta provar.

## Sobre o desenvolvedor:

Olá! Meu nome é Vinícius Spósito, sou um estudante de Ciência da Computação e estou explorando a área de Ciência de Dados.

Este projeto vêm sendo extremamente importante para meu desenvolvimento na área e vem me ensinando de forma muito prática o workflow de um projeto real de Dados.

Conecte-se comigo! 

Contato: nogsposito@gmail.com
[LinkedIn](www.linkedin.com/in/vinicius-sposito)