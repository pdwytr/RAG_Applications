# 🤖 Scalable RAG Chatbot Systems

Ilcome to the Scalable Chatbot Systems project. This framework is designed to facilitate the development of highly intelligent, deployable chatbot systems.

## 🌟 Key Features

- **🔒 Data Privacy and Security**: This solution prioritizes data privacy by eliminating the need for internet connectivity and avoiding reliance on external APIs such as OpenAI.
- **🏠 Local Deployment**: Locally deployed Large Language Models (LLMs) that are both scalable and configurable to meet your specific requirements.
- **🏗️ Long-term Stability and Scalability**: built on highly stable libraries, ensuring long-term stability and scalability. This robust foundation makes it ideal for commercial applications and enterprise-level deployments.

## 💼 Commercial Viability

The architecture and chosen technologies make this framework particularly suitable for commercialization. Whether you're a startup looking to build a MVP or an enterprise seeking to integrate advanced chatbot capabilities, this system provides a solid, scalable foundation.

### The following features have been kept in mind while developing the project

1. Using Poetry for Project managmeent which provides an easy method for deployment of the project anywhere, with py-project.toml file
2. Pylint has been used to ensure that best practices have been followed during development and a score of 8+ is maintained

## Technical Cnnfigurations

The System be part of a larger application. It will be hosted as docker container for intitial development. 

## 🚀 Quick Start

To get started with our system, follow these steps:

1. Build the custom Docker image:
```docker build -t custom-ollama .```
2. Run the Docker container:
```docker run -d -v ollama:/root/.ollama -p 11434:11434 --name ollama custom-ollama```
