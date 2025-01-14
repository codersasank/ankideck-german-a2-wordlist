# ankideck-german-a2-wordlist
Scripts and resources used to generate the Anki deck for Goethe Institute's A2 wordlist

## About this Deck
This deck will help you optimally prepare for Goethe Institute's A2 level German language exam.
This deck is an Anki import of Goethe Institute's Goethe Zertifikat A2 Wortliste. The original document is available [here](https://www.goethe.de/pro/relaunch/prf/en/Goethe-Zertifikat_A2_Wortliste.pdf) as a PDF.

It includes words (nouns, verbs, adjectives, adverbs, pronouns etc.), and the sentences (to illustrate usage) corresponding to each word, which helps us understand how the meaning of a word might change with context.
If a word contains multiple example sentences, then each sentence has been used to form one note, resulting in repetition of the same word. This was done to keep the layout simple.
The deck starts with the letter A in the wordlist (Page 8) and includes every word till the end. The words are in the same order as they are in the PDF file. The deck contains reversed cards as well.

The translations to English have been generated using DeepL. DeepL claims no copyright for the translations. The audio files have been generated using Google Cloud Text-to-Speech API.
I used the voice name "de-DE-Wavenet-B" for generating audio for the words. I used the voice name "de-DE-Neural2-F" for generating audio for the sentences.

## Contents
1. APKG file (available in the Releases section of this repository)
2. Layout files of the Anki cards (back_template.txt , front_template.txt, styling.txt)
3. CSV file (tab delimited) used to create the deck
4. XLSX file which contains the wordlist and is used to run Python scripts
5. ZIP file containing all the Google Cloud generated audio files (Available in the Releases section of this repository. It is not needed to actually use the repository.)
6. Python scripts to generate DeepL transalations and TTS Audio files
