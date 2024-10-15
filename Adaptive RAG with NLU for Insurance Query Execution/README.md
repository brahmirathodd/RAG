# Adaptive RAG with NLU for Insurance Query Execution

### Overview
The **Insurance Policy Recommendation System** is an AI-powered platform that provides personalized insurance recommendations, real-time quotations, and risk assessments. It leverages **LangChain**, **OpenAI**, and various data science techniques on **Google Cloud Platform (GCP)**, and is deployed as a user-friendly web application using **Streamlit**.

### Features
- **AI-Powered Recommendations**: Uses advanced **NLP** and **machine learning** models to recommend suitable insurance policies.
- **Real-Time Quotations**: Provides instant premium quotes based on user inputs.
- **Risk Assessment**: Evaluates the likelihood of policy approval using a predictive algorithm based on user profiles.
- **User Profiling**: Collects and processes detailed user information (e.g., health, financial status) to tailor policy suggestions.
- **Web-Based Interface**: Deployed using **Streamlit** for easy interaction and seamless user experience.

### Project Architecture
The system is designed with a modular architecture to ensure scalability and flexibility:
1. **User Input Module**: Gathers user data (e.g., demographics, health, financial status).
2. **Recommendation Engine**: Processes data to suggest insurance policies using **LangChain** and **OpenAI**.
3. **Risk Assessment Module**: Predicts the likelihood of policy approval using a custom **ML model**.
4. **Quotation Generation**: Retrieves real-time quotes based on insurance API data.
5. **Web App**: Streamlit-based UI for seamless interaction.

### Tech Stack
- **LangChain**: For managing conversational flows and recommendations.
- **OpenAI**: For **NLP** and generating intelligent responses.
- **Google Cloud Platform (GCP)**: For hosting, data storage, and machine learning deployment.
- **Streamlit**: For building an interactive and responsive web interface.
- **MongoDB/SQL**: For database management of user profiles and insurance data.
- **APIs**: For integrating real-time data from insurance providers.
- **Python**: Backend logic, data processing, and algorithm implementation.

