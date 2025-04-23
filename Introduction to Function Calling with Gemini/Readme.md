# Gemini Function Calling Lab using Vertex AI

This lab provides a hands-on introduction to **function calling** using the **Gemini API** within **Vertex AI**. The notebook demonstrates how to generate structured function call responses from natural language prompts using the **Gemini 2.0 Flash** model.

## What This Notebook Covers

- **Installing and using Vertex AI SDK for Python**
- **Interacting with Gemini 2.0 Flash (gemini-2.0-flash)**
- **Function Calling Tasks**:
  - Generate function calls to fetch product info from Google Store
  - Generate function calls and interact with an external **geocoding API**
  - Extract structured entities from **log data**

## Key Concept: Function Calling

- Create a **function schema**
- Pass it to the Gemini model along with a **text prompt**
- Gemini returns **JSON output** containing the function name and arguments
- You execute the function in your application using the response

> Function calling differs from Vertex AI Extensions:
>
> - **Function Calling** returns structured JSON (function name + arguments)
> - **Vertex AI Extensions** calls the function directly for you

## Gemini Overview

**Gemini** is a generative AI family by **Google DeepMind**, capable of multimodal understanding and content generation across text, code, images, audio, and video.

### Gemini Model Variants

- **Gemini Pro**

  - Best for complex reasoning and large-scale summarization
  - Supports deep cross-modal analysis

- **Gemini Flash**
  - Fast and efficient with **low latency**
  - Supports multimodal inputs and native tool use (e.g., Search, code execution)

## Learning Objectives

By completing this lab, you will:

- Set up and use **Vertex AI SDK for Python**
- Leverage **function calling** with Gemini 2.0 Flash
- Implement **real-world tasks** using generated function calls
- Integrate Gemini responses into external **APIs and services**
