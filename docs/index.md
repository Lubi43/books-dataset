# Book search project

## Project description<br>

**Book search** 📚 is a book search tool on publicly available dataset from Goodreads prepared as a project for a python course. Dataset was accessed on kaggle.com, uploaded by jealousleopard, updated by middlelight ([link](https://www.kaggle.com/datasets/middlelight/goodreadsbookswithgenres)).<br>

As a book enthusiast with limited reading time, I needed a way to quickly find books matching my current reading capacity and interests. 
The most common struggles finding books I had were:<br>
   - 📉 Overwhelming number of books published<br>
   - ⏳ Time wasted reading books that are not good enough fit for my interests<br>
   - 🔎 Difficulty finding books with specific page lengths with good ratings (although this metric has skewness with median around 4 out of 5 ⭐)<br> 

## Project files

    mkdocs.yml              # The configuration file.
    docs/
        index.md            # The documentation homepage.
        about.md            # Project parts description
        flowchart.md        # Project flowchart
    book_search.ipynb       # The search code
    graphs_goodreads.ipynb  # Stats code
    readme.md               # readme file
    requirements.txt        # File with requirements
    Goodreads_books_with_genres.csv  # Dataset from kaggle  
