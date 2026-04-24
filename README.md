# Assignnment9-NLTK-DERICK-MOT

The purpose of this project was to perform basic natural language processing (NLP) analysis using Python and the NLTK library! I analyzed multiple text files and compared them using tokenization, stemming, lemmatization, named entity recognition, and n-gram analysis. The goal was to understand how text structure and word patterns can help identify similarities between authors :)

---

## Dataset

For this project, I used four text files:

- `RJ_Lovecraft.txt`
- `RJ_Tolkein.txt`
- `RJ_Martin.txt`
- `Martin.txt` (Text_4)

The first three texts are stylistic versions of the same story (Romeo and Juliet), while the fourth text is used to determine which author it most closely matches.

---

## Methods Used

I applied several NLP techniques using NLTK:

- **Tokenization** – breaking text into individual words  
- **Stopword Removal** – removing common words (the, and, etc.)  
- **Stemming** – reducing words to their root form  
- **Lemmatization** – converting words into their base dictionary form  
- **Named Entity Recognition (NER)** – identifying names and locations  
- **N-gram Analysis (n = 3)** – analyzing common 3-word sequences (trigrams)  

---

## Analysis & Results

### Part 1 – Token + Named Entity Analysis

Across all three texts, common words included *Romeo*, *Juliet*, *love*, *fate*, and *Verona*. Named entities such as *Romeo Montague*, *Juliet Capulet*, and *House Capulet* appeared in each version.

This confirms that all three texts share the same subject: **Romeo and Juliet**, even though each uses a different writing style.

- **Lovecraft style** → darker, cosmic tone (*eldritch, cosmic*)  
- **Tolkien style** → descriptive, fantasy tone (*lands, tapestry, ancient*)  
- **Martin style** → grounded, emotional, and political tone (*house, passion, intrigue*)  

---

### Part 2 – Trigram Analysis

Using trigram analysis (n = 3), I compared patterns across all four texts.

- **Lovecraft** → abstract phrases (*“embrace of a”, “ensnared in the”*)  
- **Tolkien** → descriptive/world-building phrases (*“lands of verona”*)  
- **Martin** → structured narrative phrases (*“walls of house”, “city of verona”*)  
- **Text_4** → dialogue + thought-driven phrases (*“they spoke of”, “she could feel”, “said his voice”*)  

Text_4 shows a strong focus on **dialogue, character interaction, and internal thoughts**, which aligns most closely with the Martin writing style.

---

## Conclusion

All three original texts tell the same story but with different stylistic approaches. Based on both token analysis and trigram patterns, the fourth text most closely matches the **Martin-style writing**, due to its emphasis on dialogue, character perspective, and narrative tension.

---

## Limitations

- Named entity recognition is not always perfectly accurate  
- Small dataset may affect trigram frequency results  
- Some stylistic differences are harder to capture with basic NLP methods  

---
