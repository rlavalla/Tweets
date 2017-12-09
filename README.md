Affective Demonstrative Tweets and Sentiment Analysis
By Rhianna LaValla and Kristen Acker


First download all of the Tweet files to somewhere that your computer will be able to find it with just the title.
For example, "trump.txt". The actual names of all the files you need to save are the same names as the files in here.

Then run the "official code". #Rename without spaces for ease. Will be a .py file

Overall, the project aimed to the sentimentality of political tweets with affective demonstratives.
We collected tweets from Ben Carson, ______ Conway, Ivanka Trump, John McCain, Sarah Palin, Paul Ryan, ____ Pence, Rick Perry, Marco Rubio,  Ted Cruz, and Donald Trump. Tweets containing the affective demonstrates "these" and "those" were separated by hand for our data. 

The program does not currently contain a control group. However, this improvement would be possible in the future. 

Following the data collection, the data is imported with .readlines which separates the data by tweet as a list. ########Does this do that, or does the .word_tokenize do that?
Then, we arranged an empty counter to capture our data.
With a for loop, we iterated the .lower() method over every line within our data, making it assessible to the words within the opinion lexicon offered by nltk. 
#####whatever word_tokenize does


The main problem we encountered was the need to run a string method on a list. 
The list was needed to separate our data sets by tweet, which we accomplished with .readlines when opening the file.



