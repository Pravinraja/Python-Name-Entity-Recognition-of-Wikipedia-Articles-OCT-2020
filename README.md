# Python-Name-Entity-Recognition-of-Wikipedia-Articles-OCT-2020
This will involve the identification of key information in the text and classification into a set of predefined categories of wiki articles 

Use given script to download 1 Wikipedia page

Run NLTK’s NER tool.

Examine both the PERSON and LOCATION Entities

Calculate Precision, Recall, and F-Measure for both Person or Location (whichever your document has)
 

pip install pymediawiki

To Harvest WIKI

from mediawiki import MediaWiki

wikipedia = MediaWiki()

p = wikipedia.page('Marymount University')

content= p.content

print(content)




To Tag Named Entities

1) Word Tokenize a Sentence

2) POS tag the tokens
