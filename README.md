# ML PROJECT
## TASK 1
This project analyzes features of students and predicts the relationship using machine learning.
### Approach
- Data cleaning and preprocessing using pandas.
- Model training and evaluation with scikit-learn.
- Visualization of results with matplotlib and seaborn.
### Structure of the Notebook
1. **Data Loading:** Import and inspect the dataset.
2. **Data visualisation** Used to tell what features 1,2,3 indicate.
3. **Preprocessing:** Handle missing values and encode categorical variables.
4. **Modeling:** Train regression models and evaluate performance.
5. **Model Interpretation with SHAP**  Visualize feature importance 
## TASK 2 
A project designed to use LangGraph  for creating an intelligent conversational agent.
### Features
Multi-agent architecture: Specialized agents for math, weather, research, and more
Memory: Persistent chat history using LangGraph’s MemorySaver
Tool integration: Supports calculations, weather queries, and web search
Dynamic routing: Supervisor agent intelligently delegates tasks to the right agent
Extensible: Add new tools or agents with minimal code changes
### Setup & Requirements
Python 3.9+
### Required Libraries:
langchain
langgraph
langchain_google_genai
langchain_community
requests
IPython
### Set your API keys as environment variables:
GOOGLE_API_KEY for Gemini
OPENWEATHERMAP_API_KEY for weather queries
