⚠️ **README Under Construction** ⚠️  
This README is still being revised. Some sections may change or be updated soon!

# 📍 Interactive Travel Planner with RAG

## 📝 Overview
This project is an **interactive travel planner** that leverages a **Retrieval-Augmented Generation (RAG) system** to provide personalized trip recommendations. It combines **web scraping, data processing, and OpenAI's LLM** to generate context-aware responses based on real-world travel data.


## 🛠️ Key Features
- **RAG-Based Recommendation System**: Uses a **vector database (Chroma)** to store and retrieve travel-related information efficiently.
- **Web Scraping & API Integration**: Collects up-to-date travel data from multiple sources.
- **Natural Language Processing (NLP)**: Implements **OpenAI's embedding models** to process and understand user queries.
- **Frontend & Deployment**: Built using **HTML, Bootstrap**, and deployed on a **cloud server** for accessibility.

## 🔍 Data Collection & Processing
- **Data Sources**: Web scraping and API retrieval.
- **Chunking & Embeddings**: Text data is split into chunks, embedded using **OpenAI embeddings**, and stored in **ChromaDB**.
- **Retrieval Mechanism**: User queries trigger similarity searches in the vector database, retrieving relevant travel information.

## 🚀 Technologies Used
- **Programming & Frameworks**: Python, Flask
- **Machine Learning & NLP**: OpenAI API (for embeddings & LLM), ChromaDB
- **Data Handling**: BeautifulSoup, requests, pandas
- **Frontend**: HTML, Bootstrap
- **Deployment**: Cloud server

## 👥 Collaboration & Contributions
This project was co-developed with Javier A. Dastas. My primary contributions include:
- Implementing **data scraping and processing** for travel data retrieval.
- Designing and optimizing the **RAG framework**, including **chunking, embedding, and vector storage**.
- Integrating the **OpenAI API for NLP-based responses**.

## 📌 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-github-username/interactive-travel-planner.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python app.py
   ```
4. Access the planner via `http://localhost:5000` in your browser.


## Future Work
Some of the future works that have been discussed during development were:
- Weather API integration for live weather updates.
- TripAdvisor API data integration in order to include more robust information about locations.

## 📜 Acknowledgments
- This project was co-developed with Javier A. Dastas during our time in the Data Science and Machine Learning bootcamp with IronHack.
- The full version is available [here](https://github.com/javierdastas/project-dsml-interactive-travel-planner)
- The link to the live site can be found [here](https://discoverpuertorico.live/#)
