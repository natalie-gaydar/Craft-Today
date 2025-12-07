# Developer Guide - Craft Today!

## Overview

Streamlit web application that scrapes craft projects from Instructables and uses OpenAI to format instructions. Uses Streamlit, Playwright, Pandas, and OpenAI GPT API.

## Current Implementation Status

Core modules:
- `main.py` - Main application entry point
- `data_handler.py` - Data loading and filtering
- `ui_components.py` - UI components
- `scraper.py` - Web scraping and AI analysis
- `keys.py` - API key configuration

## Installation

See README.md

## User Interaction Flow

User selects category and preferences → App displays filtered project table → User selects project → App scrapes Instructables page → OpenAI formats instructions → Results displayed.

`main.py` handles initialization and UI orchestration. `data_handler.py` loads CSV data with caching and filtering. `ui_components.py` manages table display and project selection. `scraper.py` uses Playwright for web scraping and OpenAI for content analysis.


## Future Improvements

Currently, the table has too much useless information. 
It would be better to make the links to projects clickable and to make the dropdown menu list the projects instead of the number of the index.

Selecting the number of projects with a slider also feels weird. There's certainly a better way to pick a number, maybe just an input.
