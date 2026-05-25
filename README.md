*🇺🇸 Read in English | 🇧🇷 [Ler em Português](README.pt-br.md)*

# CX Analysis

This project aims to analyze the customer experience in e-commerce by exploring order, delivery, and review data (both numerical and textual). The goal is to understand how logistical delays impact customer dissatisfaction and service perception, as well as to identify the point at which the customer experience deteriorates significantly.

This project does not aim to immediately implement a complete system, but rather to evaluate the feasibility of using logistical data to anticipate customer dissatisfaction.

The project's proposal is to explore the Data field in an expansive and incremental way, continuously evolving based on what is tangible, measurable, and possible from the available dataset.

[Dataset used](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?select=product_category_name_translation.csv)

## 1. Project Objectives

- Analyze delivery time patterns, contrasting estimated vs. actual delivery times.
- Investigate the relationship between operational data and customer reviews.
- Apply NLP techniques to integrate structured and unstructured data.
- Create a solid analytical foundation for predictive analysis and NLP applications.
- Understand the key tipping point to avoid customer dissatisfaction.

## 2. Project Planning using Project Model Canvas

The project planning was structured using the Project Model Canvas, focusing on clear objectives, deliverables, and continuous evolution.

![Project Model Canvas](assets/cx_project_model_canvas.png)

## 3. Methodology

The project methodology is organized into notebooks, each representing a specific stage of the analytical workflow.

#### 1️⃣ Data Understanding

- Initial inspection of raw data
- Understanding of available variables
- Evaluation of the dataset's analytical potential

#### 2️⃣ Data Cleaning

- Handling missing values and inconsistencies
- Selection of relevant data for the project scope
- Grouping information that should work seamlessly together

#### 3️⃣ Exploratory Data Analysis (EDA)

- Analysis of the relationship between delivery delays and customer reviews
- Use of visualizations to identify patterns and correlations
- Extraction of insights from distributions and comparisons

#### 4️⃣ Analysis Conclusions

- Deepening the observed correlations
- Application of NLP to validate, through language, patterns already suggested by numerical data
- Consolidation of the project's analytical conclusions

#### 5️⃣ Model Building

- Uses Linear Regression to analyze the correlation with delivery data
- Model evaluation and coefficient verification
- Assessment of the feasibility of expanding the project scope

#### 6️⃣ Satisfaction Analysis and SLA Definition

- Empirical evaluation of the relationship between delivery time and customer satisfaction rate
- Identification of a threshold from which the average satisfaction shows a significant drop
- Establishment of an operational delivery limit driven by customer experience data

## 4. Key Findings

Delivery delays and longer waiting times significantly affect the customer experience. Negative reviews show recurring linguistic patterns, strongly associated with frustration over logistical issues and delivery failures.

Combining delay metrics with textual analysis provided a richer and more consistent understanding of the customer experience, with signals that mutually reinforce each other.

However, although the results indicate a signal exists, it is insufficient to support automation decisions without incorporating additional data sources.

## 5. Tech Stack

- Python
- Pandas & Matplotlib
- Scikit-learn
- NLTK

## 6. Limitations & Scope

So far, the project is focused on data analysis and insight generation.

There is no production model or end-to-end pipeline implemented yet.

The use of NLP is primarily directed towards interpretability, not automatic classification.

These limitations are intentional and follow an approach focused on understanding the problem prior to automation.

## 8. Project Importance

This project demonstrates the use of data analysis to investigate real market problems, connecting operational metrics to the customer's perspective.

It highlights the ability to:

- Translate data into insights.
- Integrate different types of data.
- Work with hypotheses in an analytical and iterative manner.

## 9. About the Developer

Hello! My name is Vinícius Spósito, I am a Computer Science student currently exploring the field of Data Science.

This project has been fundamental to my development, providing a practical and realistic experience of the complete workflow of a Data project, from initial exploration to the definition of future paths.

Contact: nogsposito@gmail.com

[LinkedIn](https://www.linkedin.com/in/vinicius-sposito)
