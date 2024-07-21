# Emotion_Analysis_Manzoni

This repository contains the output of different ongoing works aimed at creating new datasets of the Alessandro Manzoni's novel "I Promessi Sposi" (The Betrothed) annotated with emotions.

Currently, the repository gives access to:
- chapter VIII annotated with 3 emotion classifications of different granularity released with both aggregated and non-aggregated annotations. The first classification takes into consideration the polarity of the emotions conveyed by the text using 4 labels (positive, negative, mixed, neutral). The second is made of Plutchik’s basic emotions (anger, fear, sadness, disgust, surprise, anticipation, trust, and joy) plus neutral. The third classification is the one adopted for the [GoEmotions dataset](https://github.com/google-research/google-research/tree/master/goemotions) and made of 27 emotion labels (admiration, amusement, anger, annoyance, approval, caring, confusion, curiosity, desire, disappointment, disapproval, disgust, embarrassment, excitement, fear, gratitude, grief, joy, love, nervousness, optimism, pride, realization, relief, remorse, sadness, and surprise) plus neutral.
- a new lexicon created by assigning a polarity value to 18,885 tokens taken from 19th-century Italian narrative texts.
- an extended emotion polarity dataset made of 3,095 sentences taken from 12 Chapters. The file *emotion-polarity-chapters.tsv* is made of 5 columsn: ID, sentence, polarity (one label: POSITIVE, NEGATIVE, NEUTRAL or MIXED), irony (0 or 1, if present), chapter (chapter number).

**References**

Sprugnoli, Rachele e Arianna Redaelli. "How to Annotate Emotions in Historical Italian Novels: a Case Study on I Promessi Sposi." Proceedings of the Proceedings of the third Workshop on Language Technologies for Historical and Ancient Languages, 2024.

**Acknowledgments**

Questa risorsa è stata realizzata da ricercatrice con contratto di ricerca cofinanziato dall’Unione europea - PON Ricerca e Innovazione 2014-2020 ai sensi dell’art. 24, comma 3, lett. a, della Legge 30 dicembre 2010, n. 240 e s.m.i. e del D.M. 10 agosto 2021 n. 1062. Questa ricerca è stata anche finanziata dall’Università degli Studi di Parma attraverso l’azione Bando di Ateneo 2022 per la ricerca co-finanziata dal MUR-Ministero dell’Università e della Ricerca - D.M. 737/2021 - PNR - PNRR - NextGenerationEU.
