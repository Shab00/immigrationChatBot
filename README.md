# Immigration ChatBot

This project is a chat bot designed to answer questions about UK immigration law. The bot scrapes legislation content from the UK legislation website, processes the data, and uses a vector library with LangChain to provide accurate responses.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Data Manipulation](#data-manipulation)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The Immigration ChatBot is designed to assist users in finding relevant immigration documents based on their queries. It leverages LangChain for natural language processing, web scraping to gather data from immigration legislation websites, and vector search to efficiently locate the correct documents.

## Features
- **Natural Language Processing:** Understands and processes user queries.
- **Web Scraping:** Collects and updates immigration documents from various sources.
- **Vector Search:** Quickly finds the most relevant documents based on user queries.
- **Data Manipulation:** Cleans and preprocesses data for better accuracy.

## Project Structure

### Notebooks
- `dataManipulation.ipynb`: Processes the scraped data and prepares it for use.
- `retrieveBasedApproach.ipynb`: Implements the retrieval-based approach for the chat bot.
- `scr5ap.ipynb`: Additional data processing and analysis.
- `secondDataMan.ipynb`: Further data manipulation and cleaning.
- `textClass.ipynb`: Text classification tasks.
- `vectorLibWLangchain.ipynb`: Uses a vector library with LangChain for creating the chat bot.
- `webScraperGov.ipynb`: Scrapes additional content from the UK government website.
- `webScrapper.ipynb`: Scrapes legislation content from the UK legislation website.

### Data Files
- `dataFolder/legislation_content.csv`: Raw legislation content scraped from the website.
- `dataFolder/legislation_content_renamed.csv`: Processed and cleaned legislation content.
- `dataFolder/gov_additional_content.csv`: Additional content scraped from the UK government website.

## Installation
To install and set up the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/immigrationChatBot.git
   cd immigrationChatBot
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
To use the chatbot, run the main script:
```bash
python main.py
```
Then, interact with the chatbot through the command line or a web interface, depending on your implementation.

## Data Manipulation
The project includes a Jupyter notebook for data manipulation. This notebook demonstrates how to clean and preprocess the data used by the chatbot.

### Notebook: `dataManipulation.ipynb`
- **Load Data:** Reads the CSV file containing legislation content.
- **Rename Columns:** Renames columns for consistency.
- **Handle Missing Values:** Replaces missing values with placeholders.
- **Reorder Columns:** Reorders columns for easier analysis.

## Future Work
I will come back to this project and add more features, such as:
- Enhancing the natural language processing capabilities.
- Adding more data sources for comprehensive coverage.
- Improving the accuracy and relevance of responses.

## Contributing
Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines on how to contribute to this project.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
