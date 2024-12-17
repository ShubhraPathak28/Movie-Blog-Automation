# Find Movie Similarity from Plot Summaries
Utilizing NLP and clustering techniques to assess movie similarities based on plot summaries.

# Project Description
Natural Language Processing (NLP) is a fascinating domain where data scientists create algorithms to interpret and analyze human language. In this project, you'll apply NLP methods to determine the similarity between movies using their plot summaries.  

# Dataset
The dataset includes:
1. wiki_plot: Plot summaries extracted from Wikipedia.
2. imdb_plot: Plot summaries sourced from IMDb.

These summaries are combined into a single plot column for further processing.

# Key Steps
1. Import and Clean Data: Load movie plot data and combine wiki_plot and imdb_plot into a unified column.
2. Tokenization: Break down plot summaries into words using NLTK while removing numbers and punctuation.
3. Clustering: Use similarity measures to determine closeness between movie plots and visualize results using a dendrogram.
4. Insights: Identify which movies cluster together based on shared themes or narrative styles.

# Technologies Used
1. Python 3.7: Building the entire project
2. Pandas: Data manipulation and analysis.
3. NumPy: Numerical computations.
4. NLTK: Text tokenization and processing.
5. Matplotlib/Seaborn: Visualizing clustering results.
