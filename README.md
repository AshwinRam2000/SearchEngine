# SearchEngine


## Search engine design based on PageRank algorithm:  

	To design a simple search engine on uic domain (uic.edu) as part of a Big data analysis project.
  Implementation of web crawling in UIC domain then extract the documentation.Indexes these documents and documents are preprocessed techniques like parsed,remove symbols, remove stop words and vectorized. 
  Page rank is applied to UIC domain graphs which are generated based on the documents. 
  To develop GUI using python which takes input keywords and returns the most relevant pages to the query in the UIC website. 
  The relevant page is calculated based on cosine similarity and page rank of each document.
## Required packages

- **PyQt5** used to create GUI(Graphical user interface)
- **nltk** used to perform NLP(Natural Language Processing) pre processing techinque
- **BeautifulSoup** used to web scraping 
- **Requests** used to connect with GUI application
- **Pandas** used to read CSV file and mathematical operation
- **sklearn** used to perform various algorithms 
- **pickle** used to store obtained result

The above mentioned packages can be installed using `pip install package_name`

## To Running the programm

Simply run SearchEngine.py file using command :
      `python SearchEngine.py`


![Output](gui.PNG)

      
