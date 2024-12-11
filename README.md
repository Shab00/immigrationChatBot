# Immigration Law UK Chat Bot

This project is a chat bot designed to answer questions about UK immigration law. The bot scrapes legislation content from the UK legislation website, processes the data, and uses a vector library with LangChain to provide accurate responses.

## Project Structure

## Notebooks

- `dataManipulation.ipynb`: Processes the scraped data and prepares it for use.
- `retrieveBasedApproach.ipynb`: Implements the retrieval-based approach for the chat bot.
- `scr5ap.ipynb`: Additional data processing and analysis.
- `secondDataMan.ipynb`: Further data manipulation and cleaning.
- `textClass.ipynb`: Text classification tasks.
- `vectorLibWLangchain.ipynb`: Uses a vector library with LangChain for creating the chat bot.
- `webScraperGov.ipynb`: Scrapes additional content from the UK government website.
- `webScrapper.ipynb`: Scrapes legislation content from the UK legislation website.

## Data Files

- `dataFolder/legislation_content.csv`: Raw legislation content scraped from the website.
- `dataFolder/legislation_content_renamed.csv`: Processed and cleaned legislation content.
- `dataFolder/gov_additional_content.csv`: Additional content scraped from the UK government website.

## How to Run

1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter notebooks in the following order:
   - `webScrapper.ipynb`
   - `webScraperGov.ipynb`
   - `dataManipulation.ipynb`
   - `secondDataMan.ipynb`
   - `retrieveBasedApproach.ipynb`
   - `vectorLibWLangchain.ipynb`
4. Follow the instructions in each notebook to scrape, process, and analyze the data.

## Dependencies

- pandas
- selenium
- BeautifulSoup
- LangChain
- Other dependencies as specified in the notebooks

## Usage

The chat bot can be used to answer questions about UK immigration law by leveraging the processed legislation content and additional government content. The bot uses a vector library with LangChain to provide accurate and relevant responses.

## License

This project is licensed under the MIT License.
