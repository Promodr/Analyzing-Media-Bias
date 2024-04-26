# Analyzing Media Bias in ESG Coverage: A Semantic Similarity Approach

## Project Overview

In the rapidly evolving landscape of corporate responsibility, Environmental, Social, and Governance (ESG) criteria have become central to business practices, investor decisions, and public policy. As companies integrate ESG considerations into their strategic frameworks, the media plays a pivotal role in shaping public and investor perceptions by reporting on these issues. However, the nature of this coverage can significantly influence stakeholder views and decisions, making it crucial to understand media biases and reporting patterns.

This research project, "Analyzing Media Bias in ESG Coverage: A Semantic Similarity Approach," aims to dissect the coverage patterns of ESG topics across prominent news outlets to detect potential biases or specializations. By scrutinizing how different media platforms report on ESG themes, this study seeks to illuminate the subtleties of media influence on public and corporate engagement with sustainability issues.

## Research Question

Our research investigates whether certain news companies show a propensity to cover specific ESG topics more frequently than others, and if these patterns indicate a bias or specialization in their reporting.

## Significance of the Study
The importance of this study stems from the increasing integration of ESG factors into the core strategies of S&P 500 companies and their impact on financial performance and corporate reputation. Given the significant role media plays in disseminating ESG-related information, understanding media biases is essential for investors, policymakers, and the public to navigate the complexities of ESG issues accurately. This research could inform critical stakeholders, aiding in the formulation of strategies to address media influence and ensure a balanced understanding of ESG metrics.

##  Approach
Our methodological framework employs a combination of data analytics and natural language processing (NLP) techniques to perform a semantic similarity analysis between the content of news articles and predefined ESG topics from the Sustainability Accounting Standards Board (SASB). We analyze a corpus of 24,000 news articles from four major news outlets—CNBC, Forbes, Business Insider, and Daily Mail—focusing on their coverage of ESG topics.

1. Data Collection and Preprocessing: We gather and preprocess news articles, ensuring they are cleaned and standardized for analysis. This involves removing noise such as HTML tags and non-alphanumeric characters, as well as employing linguistic techniques to reduce text to its base components.
2. Semantic Similarity Analysis: Using SpaCy's NLP capabilities, we compute the semantic similarity between the content of each article and SASB’s ESG definitions. This process helps identify which ESG topics are most frequently discussed in the context of various industries and sectors covered by S&P 500 companies.
3. Statistical Analysis: We conduct both descriptive and inferential statistics to explore the distribution of ESG topics across different news providers and to test for significant differences in coverage patterns. This involves hypothesis testing to determine whether the observed patterns indicate bias or specialization.
4. Visualizations and Reporting: To aid in the interpretation of our results, we employ various data visualization techniques, presenting our findings through charts, graphs, and heatmaps that highlight significant trends and anomalies in the data.
This project's GitHub repository includes all datasets, scripts, and notebooks necessary to replicate the analysis, providing transparency and fostering collaboration within the academic and research community interested in media studies, ESG reporting, and data science.

# Data Sources

We utilize three primary datasets:

News Articles Dataset: Contains 24,000 articles from CNBC, Forbes, Business Insider, and Daily Mail.
ESG Definitions Dataset: Definitions from the Sustainability Accounting Standards Board (SASB) to classify ESG topics.
S&P 500 Companies Dataset: Maps companies to their respective sectors and industries.

## Key Findings

Significant differences in ESG topic coverage among the analyzed news providers.
Patterns in data suggest potential media bias or editorial specialization towards certain ESG topics.
