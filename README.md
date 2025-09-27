# Google GenAI Internship

This repository contains a collection of notebooks and projects from the Google Generative AI Internship program. It covers a wide range of topics from fundamental prompt engineering to advanced applications using Google's Gemini models on Vertex AI.

## Repository Structure

The repository is organized into the following learning modules:

-   **[01 Prompt Design in Vertex AI](01%20Prompt%20Design%20in%20Vertex%20AI)**: Introduces the fundamentals of prompt design and engineering using Vertex AI. It includes introductory notebooks, examples of using the Gen AI SDK, and challenge labs.
-   **[02 Gemini for Google Cloud Learning Path](02%20Gemini%20for%20Google%20Cloud%20Learning%20Path)**: Focuses on developing applications with the Gemini models. This section covers using the Gemini API with cURL, function calling, and building Streamlit applications.
-   **[03 Advanced - Generative AI for Developers Learning](03%20Advanced%20-%20Generative%20AI%20for%20Developers%20Learning)**: Dives into more advanced topics, including multimodal applications with Gemini for inspecting rich documents (multimodal RAG) and principles of Responsible AI.

## Key Concepts and Technologies

This repository explores several key technologies and concepts in the field of Generative AI:

-   **Cloud Platform**: Google Cloud Platform (GCP)
-   **AI/ML Platform**: Vertex AI
-   **Generative Models**: Gemini Pro
-   **Programming Language**: Python
-   **Development Environment**: Jupyter Notebooks
-   **Core SDK**: Google Gen AI SDK
-   **Key Concepts**:
    -   Prompt Engineering
    -   Function Calling
    -   Multimodality (Text, Image, Video)
    -   Retrieval-Augmented Generation (RAG)
    -   Text Embeddings
    -   Responsible AI (Fairness, Bias, Interpretability)

## Getting Started

The projects in this repository are primarily Jupyter Notebooks (`.ipynb`). To run them, you will need a Python environment with the necessary packages installed.

Most notebooks begin with a cell to install dependencies, typically including:

````python
%pip install --upgrade --quiet google-genai pandas google-cloud-aiplatform
