# 🤖 AI & Model Experimentation

## Overview

This project documents my practical experience exploring AI application development, local language model deployment and AI-assisted development. It combines self-hosted AI experimentation with experience using Microsoft AI technologies and integrating AI into useful workflows.

## Technologies & Tools

- Ollama
- Qwen 3.5 (4B)
- Python and REST APIs
- Linux and self-hosted infrastructure
- Microsoft Azure AI
- Microsoft Copilot and Power Platform

## 1. Local AI Model Deployment

I configured a local AI environment using Ollama to serve a language model through an API. The setup used the Qwen 3.5 4B model and provided a foundation for experimenting with local inference and application integration.

Areas explored:

- Deploying a language model through Ollama.
- Serving model responses through an API.
- Understanding model quantisation and hardware resource requirements.
- Exploring the trade-offs between local inference and externally hosted AI services.
- Investigating how local models can support self-hosted applications.

**Architecture:** The model host is a separate HP computer, while Titan provides the wider homelab environment. Local model availability therefore depends on the HP being online.

## 2. Atlas - Local AI Assistant

Atlas is a personal AI assistant project intended to provide useful responses grounded in actual homelab information.

The project explores:

- Connecting an AI model to an application through an API.
- Designing an assistant for practical infrastructure-related tasks.
- Using real system information rather than inventing metrics or service statuses.
- Understanding dependencies between the application, model host and underlying infrastructure.

Atlas is an ongoing project focused on combining local AI inference with practical homelab use cases.

## 3. Microsoft AI & Copilot Experience

My broader AI experience includes working with Microsoft AI tools and Copilot-assisted development.

This experience complements my work in application development and workflow automation, including:

- Exploring AI-assisted development and application workflows.
- Working with Copilot-related model development and training tools.
- Applying AI capabilities to practical business and automation use cases.
- Combining AI tools with Microsoft Power Platform.

I also hold an Azure AI Engineer Associate certification, an NQF Level 5 qualification in Software Development and i am working towards my Redhat Certified Systems Administrator.

## 4. Technical Learning

These experiments have helped me explore:

- Local model deployment and inference.
- API-based model serving and integration.
- Model size, quantisation, memory and hardware constraints.
- Application dependencies in a self-hosted environment.
- The differences between inference, fine-tuning and training.
- The practical considerations involved in building AI-powered applications.

## 5. Screenshots & Evidence

See [AI & Models — Evidence](Screenshots/AI-Models.md) for screenshots documenting the installed Ollama model and successful Qwen inference test.

Planned evidence:

- Ollama model availability and configuration.
- A genuine Qwen 3.5 inference response.
- API request and response testing.
- Atlas application or terminal output.
- Relevant Microsoft AI and Copilot development examples, where available.

## Key Takeaway

This project demonstrates my practical interest in AI engineering, local model deployment and application integration. It brings together AI experimentation, Linux, APIs and self-hosted infrastructure while documenting the technical considerations involved in building useful AI-powered tools.
