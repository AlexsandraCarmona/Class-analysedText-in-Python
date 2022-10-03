# Class-analysedText-in-Python
This is a class in Python created as an assignment of the "Python for Data Science, AI and Development" IBM course in Cousera.
The class 'analysedText' has the following methods:

1 - Constructor (__init__) - This method should take the argument text, make it lower case, and remove all punctuation. 
    It is assumed that only the following punctuation is used: period (.), exclamation mark (!), comma (,) and question mark (?). 
    This newly formatted text is assigned to a new attribute called fmtText.
    
2 - freqAll - This method should create and return dictionary of all unique words in the text, along with the number of times they 
    occur in the text. Each key in the dictionary should be the unique word appearing in the text and the associated value should 
    be the number of times it occurs in the text. This dictionary is created from the fmtText attribute.
    
3 - freqOf - This method should take a word as an argument and return the number of occurrences of that word in fmtText.
