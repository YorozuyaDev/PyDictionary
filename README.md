# PyDictionary
 
PyDictioanry is an offline English dictionary made using Python along with the Wordnet Lexical Database and Enchant Spell Dictionary. The project is a very simple one made to understand the complete functionality of Wordnet and to test the extent of its resources. It also includes a spell checker, and the option to add in custom words to the dictionary. The application returns any query with a list of results - the various word forms and their meanings along with a sample sentence using the given word.

PyDictionary is a complete project, and can be used as a full fledged offline English dictionary. Although limited, it does the same job Google search does when searched with a word.

## Dependencies 
Python dependencies are in requierements.txt to install:
	`pip install -r requirements.txt`
Also you will need to install hspell, nuspell, hunspell, libvoikko, aspell and aspell-en packages.

## Usage
`PyDictionary word-to-search`   

**Example:** 
``` 
./PyDictionary.py pizza
1.noun - pizza
Definition : Italian open pie made of thin bread dough spread with a spiced mixture of e.g. tomato sauce and cheese.
```
