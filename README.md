GIR 

Project Overview

This project focuses on enhancing a minimum viable search engine to optimize its ability to return accurate documents for predefined user queries. The primary objective was to develop a system capable of effectively handling information retrieval tasks.

The project was completed in multiple stages, involving a pre-task, two milestones, and the integration of relevant tools to ensure system accuracy and functionality.

Purpose

The aim of the project was to:
	•	Build a robust search engine that utilizes Elasticsearch for efficient document retrieval.
	•	Process a dataset of approximately 25,000 English-speaking Wikipedia movie pages from 2000 onwards.
	•	Improve the search engine to accurately respond to user queries by matching predefined expectations.

Methodology

Data Handling

The dataset consisted of Wikipedia pages about movies. A preprocessor was used to download, clean, and structure the data into JSON format, which was then indexed using Elasticsearch.

Search Engine Implementation

The system was implemented with the following steps:
	1.	Indexer Setup: Elasticsearch was used to create and populate indices with the processed movie dataset.
	2.	Search Engine Service: A Python-based service handled incoming user queries, searched the indexed data, and returned relevant results.
	3.	Frontend (Optional): A Streamlit-based interface provided a simple frontend to test queries visually.

Query Testing

Predefined queries were categorized into two milestones:
	•	Milestone 1: Focused on basic search queries (e.g., “Johnny Depp as a Vampire”).
	•	Milestone 2: Addressed more complex or less obvious queries (e.g., “COVID movie featuring murder case”).
Each query was evaluated for accuracy against expected results.

Key Features
	•	Elasticsearch Integration: Enabled efficient indexing and retrieval of movie-related data.
	•	Scalable Design: The modular architecture supported updates and enhancements without disrupting functionality.
	•	Testing Framework: Comprehensive tests ensured the reliability of the search engine.
	•	Optional Frontend: Provided an intuitive way to test and visualize search results.

Tools and Technologies
	•	Python: For system development and integration.
	•	Elasticsearch: As the core search engine.
	•	Streamlit: Optional frontend for testing queries.
	•	Pytest: For automated testing.

Challenges and Solutions
	•	Data Processing: Managing large datasets was addressed by optimizing the preprocessor script.
	•	Query Accuracy: Iterative testing and debugging ensured high accuracy for predefined queries.
	•	System Performance: Elasticsearch configurations were fine-tuned for faster response times.

Conclusion

This project demonstrates expertise in search engine development and information retrieval. It successfully achieved the goal of building a scalable system that retrieves relevant movie-related documents based on user queries. The combination of Elasticsearch, Python, and automated testing ensured a reliable and efficient solution.
