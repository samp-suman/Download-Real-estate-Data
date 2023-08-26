# Web Scraper Project

This project is a web scraper designed to gather data from websites. It provides two methods for scraping data: downloading files or saving data directly to Google Drive.

## Getting Started

Follow below ste[s to execute the code in the notebook file.

### Prerequisites

Before you begin, make sure you have the following prerequisites:

- Jupyter Notebook
- Required Python libraries (e.g., BeautifulSoup, requests)

### Installation

1. Install the necessary Python libraries by running the first cell in the notebook.
```
pip install ipywidgets -q
```

3. Import the required libraries in the notebook.

4. Load the city-ID dictionary as required for your project.

### Usage

You have two options for scraping data: downloading files or saving data directly to Google Drive.

#### Download Files

1. Set the parameters for scraping through the widget:
   - City
   - Number of pages
   - Data per page

2. Run the "Start Scraping" cell.

3. Click the "Download Files" button to retrieve the scraped data.

#### Save Files Directly on Google Drive

1. Mount your Google Drive by running the appropriate cell to access Google Drive files in your notebook.

2. Copy the project directory file path (Drive path) where you want to save the scraped data.

3. Set the parameters for scraping through the widget:
   - City
   - Number of pages
   - Data per page

4. Run the "Start Scraping" cell.

5. Click the "Save Files" button to save the scraped data directly to your Google Drive.


## Acknowledgments

- This notebook is based on [@arv-anshul](https://github.com/arv-anshul) work.
```
