RAG-basics
A beginner-friendly introduction to Retrieval-Augmented Generation (RAG) implemented in Python with Jupyter notebooks.
This repository explores the fundamentals of RAG, a technique that combines information retrieval with generative language models to produce more accurate and contextually relevant responses. It includes interactive notebooks for experimentation and modular source code for building simple RAG pipelines.
Features

Step-by-step Jupyter notebooks demonstrating core RAG concepts
Modular Python source code in src/ for reusable components (e.g., retrieval, embedding, generation)
main.py as an entry point to run a basic RAG application
Dependency management via requirements.txt

Technologies Used

Python – Core implementation
Jupyter Notebook – Interactive tutorials and examples
Common RAG libraries (likely including LangChain, LlamaIndex, Sentence Transformers, or similar – install from requirements.txt)

Quick Start

Clone the repositoryBashgit clone https://github.com/atharva-coolkarni/RAG-basics.git
cd RAG-basics
Install dependenciesBashpip install -r requirements.txt
Explore the notebooks
Open the notebooks in the notebook/ directory using Jupyter:Bashjupyter notebook notebook/
Follow along with the examples to understand retrieval, embedding, and generation steps.

Run the main scriptBashpython main.py(This may demonstrate a complete end-to-end RAG query example.)

Project Structure

notebook/ → Interactive Jupyter notebooks with tutorials and experiments
src/ → Source code modules for RAG components
main.py → Main executable script
requirements.txt → Python dependencies
README.md → This file

Goals
This project serves as a learning resource for understanding and implementing basic RAG systems. It's ideal for beginners getting started with advanced LLM applications that require external knowledge retrieval.
Feel free to fork, contribute, or open issues for improvements! 🚀