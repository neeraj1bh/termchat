# Langchain test

## Overview

This tool is designed for automatically generating and testing Python code based on a specific task. It leverages OpenAI's language models and a sequence of chains to produce code and corresponding tests.

## Requirements

- Python 3.6+
- Dependencies: aiohttp, aiosignal, annotated-types, langchain, openai, python-dotenv, etc. (Complete list in `requirements.txt`)

## Setup

1. Install dependencies: `pip install -r requirements.txt`
2. Set up environment variables in a `.env` file (template in `.env.example`).

## Usage

```bash
python main.py --task="return a list of numbers" --language="python"
```
