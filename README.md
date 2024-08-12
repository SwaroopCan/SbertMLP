# Enhanced SBERT for Advanced NLP Tasks

This project extends the basic Sentence-BERT (SBERT) implementation to create a more versatile and powerful Natural Language Processing (NLP) tool. It demonstrates how to leverage SBERT for various NLP tasks and includes an interactive chatbot functionality.

## Original SBERT Implementation

The original code provided a basic implementation of sentence embedding and similarity calculation:

- Load a pre-trained SBERT model
- Encode a small set of sentences
- Compute similarities between these sentences

This simple implementation was limited to basic similarity computations between sentences.

## Our Enhancements

We have significantly expanded the capabilities of the original SBERT implementation:

1. **Modular Class Structure**: Encapsulated all functionalities into an `EnhancedSBERT` class for better organization and reusability.

2. **Fine-Tuning Capability**: Added ability to fine-tune the SBERT model on custom datasets.

3. **Advanced Clustering**: Implemented K-means clustering on sentence embeddings with automatic optimization of cluster numbers.

4. **Sentence Classification**: Added functionality to classify new sentences into existing clusters.

5. **Enhanced Semantic Search**: Improved semantic search to return both sentences and similarity scores, optimized for larger datasets.

6. **Knowledge Base Management**: Introduced a system to store and manage a corpus of information.

7. **Interactive Chatbot**: Developed a chatbot interface that uses semantic search to answer user queries.

8. **Error Handling and Robustness**: Added checks and error messages to handle various edge cases.

## Key Differences and Benefits

- **Scope**: From basic similarity computation to a comprehensive NLP toolkit.
- **Functionality**: Expanded to include clustering, classification, semantic search, and interactive query-answering.
- **Usability**: More user-friendly, especially with the chatbot interface.
- **Flexibility**: Allows for continuous learning and expansion of the knowledge base.
- **Performance**: Optimized for efficiency with larger datasets.

## How It Helps

This enhanced version provides:

1. **Versatile NLP Tool**: Useful for various text analysis tasks in one package.
2. **Improved Information Retrieval**: Better semantic search capabilities for finding relevant information.
3. **Text Classification**: Ability to categorize new text based on learned patterns.
4. **Interactive Learning**: Chatbot interface for easy interaction with the system's knowledge.
5. **Customization**: Fine-tuning option allows adaptation to specific domains or languages.

## Usage Instructions

1. Open the provided Jupyter notebook (`Final_Project_Machine_Learning_Programming.ipynb`).
2. All required libraries are already imported in the notebook.
3. Run the cells sequentially to see demonstrations of each new functionality.
4. The final cell runs the interactive chatbot. Enter your queries to interact with it.
5. To exit the chatbot, type 'quit'.

## Note

This project demonstrates the practical applications of sentence embeddings in tasks such as information retrieval, text classification, and question-answering systems. It provides a solid foundation for further research and development in NLP applications.
