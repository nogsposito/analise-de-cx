# Análise de CX

Este projeto tem como objetivo analisar a experiência do cliente em e-commerces, explorando dados de pedidos, entregas e avaliações (numéricas e textuais) para compreender como atrasos logísticos impactam a insatisfação do cliente e a percepção do serviço, analisando também em que ponto que a experiência do cliente se deteriora significativamente.

Este projeto não tem como objetivo imedato implementar um sistema completo, mas sim avaliar a viabilidade do uso de dados logísticos para antecipar a insatisfação de clientes.

A proposta do projeto é explorar a área de Dados de forma expansiva e incremental, evoluindo continuamente com base no que é tangível, mensurável e possível a partir do dataset disponível.

## 1. Objetivos do Projeto

- Analisar padrões de tempo de entrega, contrastando prazo estimado vs. prazo real.
- Investigar a relação entre dados operacionais e avaliações dos clientes.
- Aplicar técnicas de NLP para integrar dados estruturados e não estruturados
- Criar uma base analítica sólida para análises preditivas e aplicações de NLP.
- Entender o ponto chave em que se evita a insatisfação do cliente.

## 2. Planejamento do projeto seguindo Project Model Canvas

O planejamento do projeto foi estruturado utilizando o Project Model Canvas, com foco em clareza de objetivos, entregáveis e evolução contínua.

![Project Model Canvas do projeto](assets/cx_project_model_canvas.png)

## 3. Metodologia

A metodologia do projeto está organizada em notebooks, cada um representando uma etapa específica do workflow analítico.

#### 1️⃣ Compreensão dos dados

- Inspeção inicial dos dados brutos
- Entendimento das variáveis disponíveis
- Avaliação do potencial analítico do dataset

#### 2️⃣ Limpeza dos dados

- Tratamento de valores ausentes e inconsistências
- Seleção de dados relevantes para o escopo do projeto
- Agrupamento de informações que devem funcionar de forma integrada

#### 3️⃣ Análise Exploratória

- Análise da relação entre atrasos de entrega e avaliações dos clientes
- Uso de visualizações para identificar padrões e correlações
- Extração de insights a partir de distribuições e comparações

#### 4️⃣ Conclusões da análise

- Aprofundamento das correlações observadas
- Aplicação de NLP para validar, via linguagem, padrões já sugeridos pelos dados numéricos
- Consolidação das conclusões analíticas do projeto

#### 5️⃣ Construção de modelo

- Utiliza Regressão Linear para analisar a correlação com os dados de entrega
- Avaliação do modelo e verificação dos coeficientes
- Julgamento da viabilidade do aumento do escopo do projeto

#### 6️⃣ Análise de satisfação e definição de SLA

- Avaliação empírica da relação entre tempo de entrega e taxa de satisfação dos clientes
- Identificação de um limiar a partir do qual a satisfação média apresenta queda significativa
- Estabelecimento de um limite operacional de entrega orientado por dados de experiência do cliente

## 4. Achados principais

Atrasos de entrega e maior tempo de espera afetam de forma significativa a experiência do cliente. Avaliações negativas apresentam padrões linguísticos recorrentes, fortemente associados à frustração com problemas logísticos e falhas na entrega.

A combinação de métricas de atraso com análise textual proporcionou uma compreensão mais rica e consistente da experiência do cliente, com sinais que se reforçam mutuamente.

Porém, por mais que os resultados indicam que exista sinal, ele é insuficiente para sustentar decisões de automação sem a incorporação de outros dados de informação.

## 5. Tech Stack

- Python
- Pandas & Matplotlib
- Scikit-learn
- NLTK

## 6. Limitações & Escopo

Até o momento, o projeto está focado em análise de dados e geração de insights.

Ainda não há um modelo em produção nem um pipeline end-to-end implementado.

O uso de NLP está direcionado principalmente à interpretabilidade, e não à classificação automática.

Essas limitações são intencionais e seguem uma abordagem orientada ao entendimento do problema antes da automação.

## 8. Importância do projeto

Este projeto demonstra o uso da análise de dados para investigar problemas reais de mercado, conectando métricas operacionais à perspectiva do cliente.

Ele evidencia a capacidade de:

- Traduzir dados em insights.
- Integrar diferentes tipos de dados.
- Trabalhar com hipóteses de forma analítica e iterativa.

## 9. Sobre o desenvolvedor:

Olá! Meu nome é Vinícius Spósito, sou estudante de Ciência da Computação e estou explorando a área de Ciência de Dados.

Este projeto tem sido fundamental para o meu desenvolvimento, proporcionando uma experiência prática e realista sobre o workflow completo de um projeto de Dados, desde a exploração inicial até a definição de caminhos futuros.

Contato: nogsposito@gmail.com

[LinkedIn](www.linkedin.com/in/vinicius-sposito)