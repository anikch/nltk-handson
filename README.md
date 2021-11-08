# Extracting, Cleaning and Pre-processing text data using NLTK

1. Write a program to enter a string from user and perform following tasks

- Write a python function named “Tokenize” which returns the tokenized string
- Print tokens along with the frequency of each token using the above function
- Printthe 5 least occurring tokens

2. Write a program to enter a string from user and perform following tasks.
- Write a python function named “RemoveStopWords” which returns the string after removing stop words
- Count frequency ofeach stop word present in a string using the above function
- Plot a bar graph depicting stop words and their frequencies


3. Write a program to enter a string from user and perform following tasks
- Write a python functionnamed “Lemmatize”which returns a string after lemmatizing the string.
- Write a python functionnamed “Stemmed” which returns a string after stemming the string. (Use any stemmer of your preference)
- Print all the words along with their lemmatized and stemmed form using theabove functions
- Save these results in a csv file having 3 columns


4. Create a python file named “PreProcess” and perform the following tasks.

- Copy the function “Tokenize” in this file from question 1
- Copy thefunction “RemoveStopWords” in this file from question 2
- Copy the function “Lemmatize” in this file from question 3
- Create a function named “Refine” which accepts a string and call the above 3 functions in the same order i.e. first Tokenize then RemoveStopWords then Lemmatize

5. Read the file “Brexit.docx” and write a function in Python named “GetNGrams” which takes a string and a number ‘n’ as input and returns n-grams from the string.

6. Read the file “Brexit.docx” and write python functions which take a string as an input and returns:
- Number of Nouns (all forms of noun). Take function name as “NounsCount”
- Number of Pronouns (all forms). Take function name as “PronounsCount”
- Number of Adjectives (all forms).Take function name as “AdjectivesCount”
- Number of Verbs (all forms).Take function name as “VerbsCount”
- Number of Adverbs (all forms).Take function name as “AdverbsCount”
- Plot a pie chart showing the distribution of nouns, pronouns, verbs, adverbsand adjectives.

7. Read the file “Brexit.docx” and write python functions which take a string as an input and returns:
- Number of geo-Political entities present in the file.Take function name as “GeoPoliticalCount”
- Number of Persons present in the file. Take function name as “PersonsCount”
- Numbers of Organizations mentioned in the file.Take function name as “OrganizationsCount”

8. Find:
- Most frequent bi-gram from the data
- Most frequent Noun
- Most frequent GeoPolitical Entity
- Most frequent person
