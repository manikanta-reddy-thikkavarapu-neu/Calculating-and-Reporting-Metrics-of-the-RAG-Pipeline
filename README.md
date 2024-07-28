# Healthcare Guide Chatbot with RAG and Vector Database

## Overview
This project is a domain-specific chatbot application that combines the strengths of Large Language Models (LLM) for understanding and processing natural language queries with the efficiency of a vector database for data storage and retrieval. The chatbot generates personalized healthcare recommendations using Retrieval-Augmented Generation (RAG) based solely on user inputs. The application is developed using Flowise and integrates various components to provide accurate and relevant healthcare advice to the users.

## Features
- **Domain**: Healthcare guide, providing personalized health recommendations and advice.
- **RAG-Based Recommendations**: Utilizes Retrieval-Augmented Generation to provide personalized healthcare recommendations.
- **Components Used**:
  - **Recursive Character Text Splitter**: For splitting the text into manageable chunks.
  - **CSV File**: For uploading and managing the healthcare data.
  - **OpenAI Embeddings**: For embedding queries and context using OpenAI's text-embedding-3-large model.
  - **Pinecone Upsert Document**: For storing and indexing data in Pinecone vector database.
  - **Conversational Retrieval QA Chain**: For retrieving relevant information.
  - **ChatOpenAI**: The main chat interface for interaction.

## User Base
The application is designed for individuals seeking personalized healthcare advice and recommendations. It helps users by providing quick and accurate responses to their healthcare queries based on their input.

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm
- Flowise

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/manikanta-reddy-thikkavarapu-neu/Calculating-and-Reporting-Metrics-of-the-RAG-Pipeline.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Calculating-and-Reporting-Metrics-of-the-RAG-Pipeline
    ```

### Running the Application
1. Start Flowise:
    ```sh
    npx flowise start
    ```
2. Open your browser and navigate to `http://localhost:3000` to access the chatbot interface.
3. Ensure your OpenAI API and Pinecone API are correctly set up and running.
4. Run **chatbot.html** using Live Server.

### Usage
- Upload the healthcare data CSV file via the provided interface.
- Type your healthcare-related query into the input box.
- The chatbot will process your query and provide a relevant response based on the healthcare data and LLM.

## Evaluation and Testing
The application has been tested with a variety of healthcare queries to ensure its performance, accuracy, and usability. Below are some example queries:
- "What are the symptoms of diabetes?"
- "Suggest a diet plan for hypertension."
- "How to manage stress effectively?"

## Video Demonstration
A detailed video walkthrough of the application demonstrating its features and usage can be found [here]().

## Documentation
- **Flowise Documentation**: [Flowise Documentation](https://docs.flowiseai.com/)
- **OpenAI Documentation**: [OpenAI Documentation](https://beta.openai.com/docs/)
- **Pinecone Documentation**: [Pinecone Documentation](https://docs.pinecone.io/)
