# regex_nlp_


Regular Expressions are used in various tasks such as data pre-processing, rule-based information mining systems, pattern matching, text feature engineering, web scraping, data extraction, etc.

Whenever we deal with text data it is almost always never in the form we want it to be. The text may have words we want to remove, punctuation that is not needed, hyperlinks or HTML that can be done away with and dates or numerical entities that can be made simpler. In this article, I will describe some basic Regular expressions in Python using the re module and some common situations in NLP where I end up using them.


\w  represents any alphanumeric characters (including underscore)
\d  represents any digit
.   represents ANY character (do not confuse it with a period )
abc literally matches characters abc in a string
[abc] matches either a or b or c (characters within the brackets)
?   after a character indicates that the character is optional
*   after a character indicates it can be repeated 0 or more times
+   after a character indicates it can be repeated 1 or more times
\   is used to escape special characters (we'll use this alot!)
