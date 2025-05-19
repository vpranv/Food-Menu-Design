# Food/Mood Menu

This is a simple NLP-based project that recommends food items for their menu based on user input. It supports two modes: mood-based and region-based suggestions.

## Overview

Input: A natural language prompt from the user.

Process: Extracts keywords using basic NLP techniques.

Output: Returns food items matching the user's mood or region using a dataset.

## Setup Instructions

Create a virtual environment

```
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

Install dependencies

```
pip install -r requirements.txt
```

Run the script

```
python food.py
```

### Customize prompts

You can edit the prompt strings directly inside food.py to test different moods or regions.

Example Use Cases
>"I feel not feeling up, recommend me something good to eat"
>"Recommend me something spicy from South India"