# Chatbot for Exploratory Data Analysis (EDA)

This project implements a conversational chatbot for performing Exploratory Data Analysis (EDA) using the Iris dataset. The chatbot leverages Microsoft's DialoGPT for natural language processing to interact with users, answer dataset-related queries, and provide visualizations.

## Features
1. Summary: Provides basic statistics and insights about the dataset.
2. Visualization: Generates plots for better data understanding.
3. Correlation: Analyzes and visualizes the correlation between features.
4. Exit: Ends the chatbot session gracefully.

## Dataset
The chatbot uses the Iris dataset from the Scikit-learn library. This dataset is loaded and processed into a Pandas DataFrame.

#### How to Run
1. Run the Notebook
Open the provided Jupyter notebook (Chatbot_EDA) in your environment and execute the cells sequentially.

2. Interact with the Chatbot
Query the chatbot with commands such as:
summary: Get dataset statistics.
visualize: Generate visualizations (e.g., histograms, scatter plots).
correlation: Perform correlation analysis and show heatmaps.
exit: Close the chatbot session.

## Code Overview
#### Key Components
1. Dataset Loading:
The Iris dataset is loaded using Scikit-learn and converted into a Pandas DataFrame.
2. Chatbot Logic:
User input is processed to handle EDA-related queries.
Hugging Face models power conversational responses.
3. EDA Functions:
summarize_data(df): Returns a summary of the dataset.
visualize_data(df): Plots various visualizations.
correlation_analysis(df): Displays a correlation matrix or heatmap.
4. Model Interaction:
Hugging Face transformers are used for generating conversational responses.

## Conclusion
The Chatbot for Exploratory Data Analysis (EDA) project showcases the integration of Natural Language Processing (NLP) with data analysis,
enabling users to perform basic EDA tasks through natural language queries. By leveraging Hugging Face's state-of-the-art models and
Python's data science ecosystem, this chatbot provides an intuitive and interactive way to analyze datasets.

This chatbot is particularly useful for beginners in data science, data analysts, and professionals looking for a quick and 
conversational approach to data exploration. It also serves as a foundation for future enhancements, such as adding support 
for custom datasets, advanced statistical analysis, and deployment as a web or mobile application.
By combining the power of NLP and data science, this project paves the way for smarter, more accessible data analysis tools.

