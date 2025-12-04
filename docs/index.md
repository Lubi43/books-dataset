# Book search project

## Project description<br>

**Book Search** 📚 is a Python-based tool for searching and analyzing a publicly available kaggle dataset produced by [middlelight](https://www.kaggle.com/datasets/middlelight/goodreadsbookswithgenres). Developed as a course project, it enables users to:  
- Search books by title, author, or genre  
- Filter by publication year or rating  
- Analyze reading trends and patterns  

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
