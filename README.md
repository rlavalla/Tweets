Affective Demonstrative Tweets and Sentiment Analysis
By Rhianna LaValla and Kristen Acker


First download all of the Tweet files to somewhere that your computer will be able to find it with just the title.
For example, "trump.txt". The actual names of all the files you need to save are the same names as the files in here.

Then run the "official code". #Rename without spaces for ease. Will be a .py file

Overall, the project aimed to the sentimentality of political tweets with affective demonstratives.
We collected tweets from Ben Carson, ______ Conway, Ivanka Trump, John McCain, Sarah Palin, Paul Ryan, ____ Pence, Rick Perry, Marco Rubio,  Ted Cruz, and Donald Trump. Tweets containing the affective demonstrates "these" and "those" were separated by hand for our data. 

The program does not currently contain a control group. However, this improvement would be possible in the future. The data also has inconsistent numbers. We have more tweets for certain politicians than others. 

Following the data collection, the data is imported with .readlines which separates the data by tweet as a list. ######## Does this do that, or does the .word_tokenize do that?
Then, we arranged an empty counter to capture our data.
With a for loop, we iterated the .lower() method over every line within our data, making it assessible to the words within the opinion lexicon offered by nltk. 
##### whatever word_tokenize does
The for loop will then take the results from the designed function (which will be explained later) and add them to the counter. The counter will result in the total positivity or negativity of each political person's tweets. 
The finddemons(variable) function takes an if-else statement. The if statement erases the possibility of accidentally taking in data that does look at the entire tweet. The else statement divides the number of positive and negative words by the length of the tweet. The resulting positive and negative score are added together. This attains the tweets sentimentality score.This is accomplished for every tweet, and then returned for the for loop. The for loop completes the process by adding all of the tweets' sentimentalities to arrive at the politician's overall sentimentality within his or her tweets. 
This process is repeated for each politician's data. The functions are called, which prints the results of the politician's sentimentality.

This is interesting because it not only examines the immediate sentimentality of a person's tweets with demonstrative affect, but also opens up future research into the difference between affective demonstrative tweets and nonaffective demonstrative tweets. By applying this program to political leaders, the analysis of tweet sentimentality and political popular in twitter polls might also be a future avenue of research. 

One of the main problems we encountered was when we attempt to run a string method on a list. 
The list was needed to separate our data sets by tweet, which we accomplished with ######### .readlines ######## when opening the file. However, we needed the dada in a string type in order to lowercase the data. Without the lowercase data, not all of the words would be comparable to the opinion lexicon. This was recovered by #########

###### What other problems do you think we should discuss?



