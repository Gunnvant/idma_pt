
# 1

### Class Demonstration [Common Programming Interview problems](https://www.geeksforgeeks.org/python-uppercase-half-string/)
- input : test_str = dino
- Output : diNO
- Explanation : Latter half of string is uppercased.

- Input : test_str = apples
- Output : appLES
- Explanation : Latter half of string is uppercased.

# 2

### Class Excercise [source](https://www.geeksforgeeks.org/python-program-to-check-if-a-string-has-at-least-one-letter-and-one-number/) (Try to solve on your own)

- Input: welcome2ourcountry34
- Output: True

- Input: stringwithoutnum
- Output: False

- Hints: Look at the output of dir() for any string object and find out the methods which can help in finding which element is a string and which is a number

# 3

### Using lists and strings to analyse data -  Class Case Study 1

```python
amazon_review = '''
What can I say!
SIMPLY SPECTACULAR.
PUBG - smooth +90 FPS
Smashing all the bench marks by some margin (140%~~)
4 SPEAKERS are like home theatre.
Battery backup is excellent
Could have been better than 20 wts charger

I will keep u guys posted...stay tuned

'''
```
#### Q1. Count the number of sentences in the review

Understand what new line, line feed and carraige return is: **[reading](https://www.loginradius.com/blog/async/eol-end-of-line-or-newline-characters/)**

#### Q2 Find out how many words (approximately, consider "say!" as one word) are there in each sentence?

# 4

### Class Excercise 

```python
dinkar = '''
वर्षों तक वन में घूम-घूम,
बाधा-विघ्नों को चूम-चूम,
सह धूप-घाम, पानी-पत्थर,
पांडव आये कुछ और निखर।
सौभाग्य न सब दिन सोता है,
देखें, आगे क्या होता है।

मैत्री की राह बताने को,
सबको सुमार्ग पर लाने को,
दुर्योधन को समझाने को,
भीषण विध्वंस बचाने को,
भगवान् हस्तिनापुर आये,
पांडव का संदेशा लाये।

‘दो न्याय अगर तो आधा दो,
पर, इसमें भी यदि बाधा हो,
तो दे दो केवल पाँच ग्राम,
रक्खो अपनी धरती तमाम।
हम वहीं खुशी से खायेंगे,
परिजन पर असि न उठायेंगे!

दुर्योधन वह भी दे ना सका,
आशीष समाज की ले न सका,
उलटे, हरि को बाँधने चला,
जो था असाध्य, साधने चला।
जब नाश मनुज पर छाता है,
पहले विवेक मर जाता है।

हरि ने भीषण हुंकार किया,
अपना स्वरूप-विस्तार किया,
डगमग-डगमग दिग्गज डोले,
भगवान् कुपित होकर बोले-
‘जंजीर बढ़ा कर साध मुझे,
हाँ, हाँ दुर्योधन! बाँध मुझे।

यह देख, गगन मुझमें लय है,
यह देख, पवन मुझमें लय है,
मुझमें विलीन झंकार सकल,
मुझमें लय है संसार सकल।
अमरत्व फूलता है मुझमें,
संहार झूलता है मुझमें।
'''
```
#### Q1. Programmatically find out how many paras/अनुच्छेद are there in the poem?

#### Q2. ### Q2 Count the number of words in a paragraph and each sentence

# 5

### Class Excercise : Gender Neutral Job Descriptions

```python
job_description1 = '''We are a dominant engineering firm that boasts many leading clients. We are determined to stand apart from the competition.'''
job_description2 = '''We are a community of engineers who have effective relationships with many satisfied clients. We are committed to understanding the engineer sector intimately. '''
job_description3 = '''Strong communication and influencing skills. Ability to perform individually in a competitive environment. Superior ability to satisfy customers and manage company’s association with them.'''
job_description4 = '''Proficient oral and written communications skills. Collaborates well in a team environment. Sensitive to clients’ needs, can develop warm client relationships.'''
job_description5 = '''Direct project groups to manage project progress and ensure accurate task control. Determine compliance with client’s objectives.'''
job_description6 = '''Provide general support to project team in a manner complimentary to the company. Help clients with construction activities.'''

```
#### Q1. Write the following functions:

1. get_sentences(): This takes job descriptions as an input and returns list of sentences as output
2. get_words(): This takes a sentence as an input and returns a list of words in the sentence as an output

```python
feminine_coded_words = [
    "agree",
    "affectionate",
    "child",
    "cheer",
    "collab",
    "commit",
    "communal",
    "compassion",
    "connect",
    "considerate",
    "cooperat",
    "co-operat",
    "depend",
    "emotiona",
    "empath",
    "feel",
    "flatterable",
    "gentle",
    "honest",
    "interpersonal",
    "interdependen",
    "interpersona",
    "inter-personal",
    "inter-dependen",
    "inter-persona",
    "kind",
    "kinship",
    "loyal",
    "modesty",
    "nag",
    "nurtur",
    "pleasant",
    "polite",
    "quiet",
    "respon",
    "sensitiv",
    "submissive",
    "support",
    "sympath",
    "tender",
    "together",
    "trust",
    "understand",
    "warm",
    "whin",
    "enthusias",
    "inclusive",
    "yield",
    "share",
    "sharin"
]

masculine_coded_words = [
    "active",
    "adventurous",
    "aggress",
    "ambitio",
    "analy",
    "assert",
    "athlet",
    "autonom",
    "battle",
    "boast",
    "challeng",
    "champion",
    "compet",
    "confident",
    "courag",
    "decid",
    "decision",
    "decisive",
    "defend",
    "determin",
    "domina",
    "dominant",
    "driven",
    "fearless",
    "fight",
    "force",
    "greedy",
    "head-strong",
    "headstrong",
    "hierarch",
    "hostil",
    "impulsive",
    "independen",
    "individual",
    "intellect",
    "lead",
    "logic",
    "objective",
    "opinion",
    "outspoken",
    "persist",
    "principle",
    "reckless",
    "self-confiden",
    "self-relian",
    "self-sufficien",
    "selfconfiden",
    "selfrelian",
    "selfsufficien",
    "stubborn",
    "superior",
    "unreasonab"
]
```
#### Q2. Now write a function which can take a list of words in a sentence and match how many words start with the root form of either masculine or feminine words.

```python
def get_coded_count(list_words,coded_word_list):
    '''
    
    parameters:
    __________
    list_words: list of words in a sentence in JD
    coded_word_list: either masculine_coded_words or feminine_coded_words
    
    returns:[counts, words]
    counts: count of words that are in the sentence of the jd as well as the coded list
    words: words that are in the sentence of the jd as well as the coded list
    
    '''
    ### Your code goes here
    
    
    return [counts,words]
```

# 6

    ### Class Excercise (Travering tuples and using set operations)

```python
import pickle ## ignore this for the while
with open("../../data/ner_dataset_list","rb") as f:
    ner_data = pickle.load(f)
```

#### Q1. Use your knowledge about lists and tuples to extract all the entries that have been labelled as GPE

#### Q2. Find the number of unique GPES in the data. Use the idea of sets. Also find out the the number of duplicated entries.

# 7

#### Class Excercise ([Word Frequency Counter](http://www.thehypertexts.com/Mirza%20Ghalib%20English%20Translations%20by%20Michael%20R.%20Burch.htm))

```python
ghalib = [
'''
It’s only my heart, not unfeeling stone,
so why be dismayed when it throbs with pain?
It was made to suffer ten thousand darts;
why let one more torment impede us?
''',

'''
The miracle of your absence
is that I found myself endlessly searching for you.
''',

'''
On the subject of mystic philosophy, Ghalib,
your words might have struck us as deeply profound
and we might have pronounced you a saint ...
Yes, if only we hadn't found
you drunk
as a skunk!
''',
    
'''
Not the blossomings of songs nor the adornments of music:
I am the voice of my own heart breaking.
You toy with your long, dark curls
while I remain captive to my dark, pensive thoughts.
We congratulate ourselves that we two are different:
that this weakness has not burdened us both with inchoate grief.
Now you are here, and I find myself bowing—
as if sadness is a blessing, and longing a sacrament.
I am a fragment of sound rebounding;
you are the walls impounding my echoes.
''',
    
'''
All your life, O Ghalib,
You kept repeating the same mistake:
Your face was dirty
But you were obsessed with cleaning the mirror!
'''
]
```

# 8

### Class Excercise (Organize the text)

#### Q1 Use the ner_data and and organize the data in the following manner in a dictionary:

    ```json
    {
        "PERSON":['Pierre'...],
        "ORGANIZATION":['Boeing'.....],
        "GPE":['DUTCH'.....],
        "LOCATION":['Missisipi'.....]
    }

    ```

You can ignore to handle the cases where a Named Entity is contiguously many words long, e.g. for New York, you can treat New and York as separate words.

#### Q2. Now modify the existing dictionary so that duplicate entries are removed

# 9

### Class Assignment 

- Use the data tweets_assignment.txt
- Find out how many tweets were tweeted on each day, i.e. how many tweets were made on 26th December, how many on 25th December and so on.