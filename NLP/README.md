## Project 1 - Statastical NLP Use Case

### PART 1
•`CONTEXT`: Classification  is  probably  the  most  popular  task  that  you  would  deal  with  in  real  life.  Text  in  the  form  of  blogs,  posts,  articles, etc.  is  written  every  second.  It  is  a  challenge  to  predict  the  information  about  the  writer  without  knowing  about  him/her.  We  are  going  to create a classifier that predicts multiple features of the author of a given text. We have designed it as a Multi label classification problem.

•`DATA  DESCRIPTION`: Over  600,000  posts  from  more  than  19  thousand  bloggers  The  Blog  Authorship  Corpus  consists  of  the  collected posts of 19,320 bloggers gathered from blogger.com in August 2004. The corpus incorporates a total of 681,288 posts and over 140 million words  -  or  approximately  35  posts  and  7250  words  per  person.  Each  blog  is  presented  as  a  separate file,  the  name  of  which  indicates  a blogger id# and the blogger’s self-provided gender, age, industry, and astrological sign. (All are labelled for gender and age but for many, industry and/or sign is marked as unknown.) All bloggers included in the corpus fall into one of three age groups:•8240 "10s" blogs (ages 13-17), •8086 "20s" blogs(ages 23-27) and •2994 "30s" blogs (ages 33-47)For each age group, there is an equal number of male and female bloggers.Each blog in the corpus includes at least 200 occurrences of common English words. All formatting has been stripped with two exceptions. Individual posts within a single blogger are separated by the date of the following post and links within a post are denoted by the label url link. 
Link to dataset: https://www.kaggle.com/rtatman/blog-authorship-corpus

•`PROJECT OBJECTIVE`: The need is to build a NLP classifier which can use input text parameters to determine the label/s of the blog.

### PART 2

•`CONTEXT`: Great  Learning  has  a  an  academic  support  department  which  receives  numerous  support  requests  every  day  throughout  the year.  Teams  are  spread  across  geographies  and  try  to  provide  support  round  the  year.  Sometimes  there  are  circumstances  where  due  to heavy  workload  certain  request  resolutions  are  delayed,  impacting  company’s  business.  Some  of  the  requests  are  very  generic  where  a proper resolution procedure delivered to the user can solve the problem. Company is looking forward to design an automation which can interact with the user, understand the problem and display the resolution procedure [ if found as a generic request ] or redirect the request to an actual human support executive if the request is complex or not in it’s database.

•`DATA  DESCRIPTION`: A sample corpus is attached for your reference. Please enhance add more data to the corpus using your linguistics skills.

•`PROJECT OBJECTIVE`: Design a python based interactive semi - rule based chatbot which can do the following: 
  1.Start chat session with greetings and ask what the user is looking for.
  2.Accept dynamic text based questions from the user. Reply back with relevant answer from the designed corpus. 
  3.End the chat session only if the user requests to end else ask what the user is looking for. Loop continues till the user asks to end it.

---

## Project 2 - Sequential NLP Use Case

### PART 1

•`CONTEXT`: The  objective  of  this  project  is  to  build  a  text  classification  model  that analyses the customer's sentiments based on their reviews in the IMDB database. The model uses a complex deep learning model to build an embedding layer followed by a classification algorithm to analyse the sentiment of the customers.

•`DATA  DESCRIPTION`: The  Dataset  of  50,000  movie  reviews  from  IMDB,  labelled  by sentiment  (positive/negative).  Reviews  have  been  preprocessed,  and  each  review  is encoded  as  a  sequence  of  word  indexes  (integers).  For  convenience,  the  words  are indexed  by  their  frequency  in  the  dataset,  meaning  the  for  that  has  index  1  is  the most  frequent  word.  Use  the first  20  words  from  each  review  to  speed  up  training, using  a  max  vocabulary  size  of  10,000.  As  a  convention,  "0"  does  not  stand  for  a specific word, but instead is used to encode any unknown word.

•`PROJECT  OBJECTIVE`: Build  a  sequential  NLP  classifier  which  can  use  input  text parameters to determine the customer sentiments

### PART 2

•`CONTEXT`: Past studies in Sarcasm Detection mostly make use of Twitter datasets collected using   hashtag   based   supervision   but   such   datasets   are   noisy   in   terms   of   labels   and language.  Furthermore,  many  tweets  are  replies  to  other  tweets  and  detecting  sarcasm  in these  requires  the  availability  of  contextual  tweets.In  this  hands-on  project,  the  goal  is  to build a model to detect whether a sentence is sarcastic or not, using Bidirectional LSTMs.

•`DATA DESCRIPTION`: The dataset is collected from two news websites, theonion.com and huffingtonpost.com. This new dataset has the following advantages over the existing Twitter datasets:Since  news  headlines  are  written  by  professionals  in  a  formal  manner,  there  are  no  spelling  mistakes  and informal usage. This reduces the sparsity and also increases the chance of finding pre-trained embeddings.Furthermore,  since  the  sole  purpose  of  TheOnion  is  to  publish  sarcastic  news,  we  get  high-quality  labels  with much less noise as compared to Twitter datasets.Unlike tweets that reply to other tweets, the news headlines obtained are self-contained. This would help us in teasing apart the real sarcastic elements
Content: Each record consists of three attributes:is_sarcastic: 1 if the record is sarcastic otherwise 0headline: the headline of the news article

article_link: link to the original news article. Useful in collecting supplementary data     
`Reference`: https://github.com/rishabhmisra/News-Headlines-Dataset-For-Sarcasm-Detection

•`PROJECT OBJECTIVE`: Build a sequential NLP classifier which can use input text parameters to determine the customer sentiments
