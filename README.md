# Book Chapter Summaries with LLMs

# Overview

This project leverages the power of Large Language Models (LLMs) to generate concise and informative summaries of book chapters. Integrates technologies such as LangChain, MapReduce and Sentence Transformers we aim to create an efficient and scalable system capable of processing and summarizing extensive texts accurately. 

# Features

1. Automated Chapter Summarization: Generate summaries for book chapters automatically, saving time and effort in understanding key concepts and narratives.
2. Advanced NLP Techniques: Utilizes LangChain for connecting LLM capabilities, Sentence Transformers for capturing the semantic meaning of texts, and a custom MapReduce implementation for handling large datasets efficiently.
3. Customizable Summary Length: Users can specify the desired summary length, allowing for flexibility between detailed overviews and brief outlines.
4. Cross-Domain Applicability: Effective across a wide range of genres, including fiction, non-fiction, textbooks, and scientific papers.

# Usage

To generate a summary for a book chapter, run the following command in the terminal, specifying the path to your book chapter file (in plain text format) and the desired summary length

python summarize.py --chapter_path /path/to/chapter.txt --summary_length 

# How It Works

1. Preprocessing: The input text is first preprocessed to remove any formatting issues and split into relevant sections
2. Sentence Embeddings: Sentence Transformers are used to generate semantic embeddings for each sentence, in order to understand context and meaning 
3. Summarization: Utilizies LangChain and a custom MapReduce workflow, the system efficiently processes the text to generate a coherent and concise summary based on the desired length.
4. Postprocessing: The summary is then postprocessed to ensure readability and coherence

