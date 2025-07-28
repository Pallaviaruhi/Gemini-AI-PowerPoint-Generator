# Gemini-AI-PowerPoint-Generator
## Overview

This project is an **AI-powered PowerPoint Generator** that leverages Google Gemini's advanced language models to automatically create high-quality, engaging presentation slides from any topic. Whether you’re a student, educator, or business professional, this tool saves valuable time and enhances the quality of your presentations.

## Why This Project?

As a Machine Learning enthusiast, I created this tool to simplify complex tasks using the power of generative AI. By automating slide creation, it boosts not only efficiency but also the informativeness and engagement level of your presentations.

## Technologies Used

- **Python**
- **Google Gemini AI** (`google-generativeai`)
- **python-pptx**
- **Pillow**
- **Requests**
- **dotenv**
- Other supporting Python libraries

## Features

- **AI-powered content generation**: Uses Gemini Pro to build detailed, structured presentation outlines based on your chosen topic.
- **Professional slide layouts**: Automatically formats each slide with titles, content, and images.
- **Automatic image suggestions**: Generates concise prompts for relevant images and fetches them using free APIs.
- **Robust error handling**: Designed to handle common issues gracefully.
- **Highly customizable**: Easily update the slide count, topic, or visual style.
- **Interactive Jupyter notebook**: Provides hands-on, step-by-step generation—ideal for learning and quick experimentation.

## How It Works

1. **Generate Outline**: The Gemini model generates a tailored outline for your presentation.
2. **Slide Creation**: For each slide, content and optional image prompts are generated and added using python-pptx.
3. **Visual Enhancement**: Images relevant to each slide can be fetched and embedded automatically.
4. **Output**: A fully formatted `.pptx` file ready for download and editing.

## Quickstart

1. Clone the repository
2. Install the required dependencies:
    ```
    pip install -r requirements.txt
    ```
3. Set up your [Google Gemini AI API key](https://ai.google.dev/)
4. Launch and follow the steps in `PPTGenerator.ipynb`

## Example

Generates a complete presentation (e.g., "Artificial Intelligence in Healthcare") with:
- Introduction, applications, benefits, ethical challenges, and a compelling conclusion
- Professionally formatted slides, all created with a single command

## File Structure

- `PPTGenerator.ipynb` — Interactive notebook with code and demo
- `ppt_generator.py` — Core code (can be modularized)
- `README.md` — Project documentation



