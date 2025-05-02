# Nutrition Specialist Bot

An AI-powered nutrition specialist bot that provides personalized nutrition advice and guidance based on medical and nutritional references.

Check the live version in https://huggingface.co/spaces/daniela-veloz/nutrition_bot

## Overview

This project implements an AI agent specialized in nutrition and dietary guidance. The bot is designed to provide accurate, evidence-based nutritional advice while considering individual health factors and dietary requirements.

## Project Structure

- `nutrition_specialist_bot.ipynb`: The main Jupyter notebook containing the bot's implementation
- `Nutritional_Medical_Reference.zip`: Reference materials and data used by the bot for providing accurate nutritional information
- `README.md`: This documentation file

## Features

- Personalized nutrition advice
- Evidence-based dietary recommendations
- Medical reference integration
- Interactive consultation capabilities

## Requirements

To run this project, you'll need:

- Python 3.x
- Colab
- Open AI API key
- Llama API Key
- Required Python packages (specified in the notebook)

## Getting Started

1. Clone this repository
2. Extract the `Nutritional_Medical_Reference.zip` file
3. Open `nutrition_specialist_bot.ipynb` in Colab
4. create `config.json` with the following keys
    - API_KEY (open_ai api key)
    - OPENAI_API_BASE (open_ai api base, default https://api.openai.com/v1/, you still need to add default")
    - LLAMA_KEY (Llamma key)
4. Run the cells in sequence to start using the bot

## Usage

The bot can be interacted with through the Jupyter notebook interface. It's designed to:
- Answer nutrition-related questions
- Provide personalized dietary recommendations
- Consider medical conditions and dietary restrictions
- Offer evidence-based nutritional guidance

## Note

This bot is designed to provide general nutritional guidance and should not replace professional medical advice. Always consult with healthcare professionals for specific medical conditions or dietary requirements.

