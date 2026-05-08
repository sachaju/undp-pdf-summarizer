# UNDP PDF Summarizer

An AI-powered tool that automatically extracts structured insights 
from UNDP project reports using Python and the Gemini API.

## What it does
- Reads any UNDP project report in PDF format
- Sends the content to Google Gemini AI
- Returns a structured summary including country, sector, 
  project status, key risks and a brief summary

## Tech Stack
- Python
- pdfplumber
- Google Gemini API
- Jupyter Notebook

## How to run
1. Clone this repository
2. Create a `.env` file with your `GOOGLE_API_KEY`
3. Install dependencies: `pip install pdfplumber google-generativeai`
4. Open `summarizer.ipynb` and run all cells