This file creates an orthographic and semantic network to analyze the relationship between network dynamics of a given word and results in a word-recognition experiment. Data adopted from the English Lexicon Project.




Instructions for Use:

1) Run the top cell to activate relevant modules
2) Run the next two cells to access the word list and sample a few words from the list
3) The next two cells are the creation of the orthogonality network. Skip this and scroll to the cell that loads the pickle called hermitless Dict
4) Continue running each cell in order to access each statistic from the ortho. network
5) Continue running each cell to load RT/accuracy data, create the data matrix, and run hierarchical regression
6) Scroll back up to the loading pickle file, and change hermitlessDict to hermitlessSimilarDict to access the semantic network
7) Repeat steps 4-6 with the semantic network in the cells below the creation of the semantic network (underneath the first hierarchical regression output)