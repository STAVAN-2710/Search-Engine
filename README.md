# Search-Engine
Live Link - https://search-engine-a8ofhg5tmmwez4appxr3m7p.streamlit.app/
 USE GROK API = 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
 
## Overview
This repository contains a project focused on creating a versatile search engine using tools and utilities from the LangChain community. The search engine is capable of querying multiple data sources such as Arxiv, Wikipedia, and DuckDuckGo, integrating them into a cohesive AI or NLP pipeline like a Retrieval-Augmented Generation (RAG) system.

## Components Breakdown

1. ArxivQueryRun
Purpose: This tool allows querying the Arxiv database, a repository of research papers across various fields like physics, computer science, and mathematics.
Functionality: Retrieve relevant research papers based on specific queries to integrate into your application.
Use Case: Ideal for searching academic papers on topics of interest and processing them within AI systems.

2. WikipediaQueryRun
Purpose: Fetches information from Wikipedia based on a given query.
Functionality: Retrieve summaries or specific articles from Wikipedia, useful for background information or context.
Use Case: Perfect for obtaining factual information or summaries to use as context or background in applications.

3. WikipediaAPIWrapper
Purpose: Offers a more detailed and configurable interaction with the Wikipedia API.
Functionality: Perform complex interactions such as customized searches or extracting specific content from Wikipedia.
Use Case: Useful when detailed control over data retrieval from Wikipedia is needed.

4. ArxivAPIWrapper
Purpose: Provides an interface for advanced interactions with the Arxiv API, similar to the WikipediaAPIWrapper.
Functionality: Tailor your searches on Arxiv by filtering results or extracting specific metadata.
Use Case: Essential for advanced research or integration of Arxiv data into broader AI pipelines.

5. DuckDuckGoSearchRun
Purpose: Executes web searches using DuckDuckGo.
Functionality: Retrieve information from the web when specialized sources like Arxiv or Wikipedia don't suffice.
Use Case: General-purpose searches to complement academic or encyclopedic data retrieval.

## Installation
To use this project, you need to have Python installed. Clone this repository and install the required dependencies:

git clone https://github.com/STAVAN-2710/Search-Engine

cd https://github.com/STAVAN-2710/Search-Engine
  
pip install -r requirements.txt

## Usage
You can utilize the tools provided in this repository by following the example usage above. Customize the queries and configurations to suit your specific needs.

