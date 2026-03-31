# Named Entity Recognition (NER) Annotation Guidelines

## Overview

This project focuses on labeling named entities in text.  
Annotators will identify entities of the following types:

- Person – Names of people (e.g., Mark Rutte, Van Gogh)  
- Location – Geographic locations, cities, countries, landmarks (e.g., Amsterdam, North Sea)  
- Organization – Companies, institutions, government bodies, museums (e.g., Heineken, European Union)  
- Date – Specific years, centuries, or dates mentioned in the text (e.g., 1602, 17th century)  

Each sentence may contain multiple entities.

---

## Labeling Procedure

1. Read the sentence carefully.  
2. Identify all entities in the text that fit the types above.  
3. Record each entity in the format:

Type: Entity Name

4. Separate multiple entities with a semicolon `;`.  
5. Ensure correct spelling and capitalization.  
6. If a word could belong to multiple types, choose the most specific.  

---

## Examples

1. Sentence: `"Mark Rutte has been the Prime Minister of the Netherlands since 2010"`  
   Entities: `Person: Mark Rutte; Location: Netherlands; Date: 2010`

2. Sentence: `"The Rijksmuseum is located in Amsterdam"`  
   Entities: `Organization: Rijksmuseum; Location: Amsterdam`

3. Sentence: `"Queen Maxima was born in Argentina"`  
   Entities: `Person: Queen Maxima; Location: Argentina`

---

## Edge Cases

- Titles: Include the title with the name (e.g., Queen Maxima, Dr. van Leeuwenhoek)  
- Organizations: Include official full names if mentioned  
- Dates: Include centuries, decades, or specific years if referenced  
- General nouns: Do not label generic nouns (e.g., “city”, “museum” without a proper name)  

---

## Purpose

The annotated dataset will be used to:

- Train and evaluate NER systems  
- Demonstrate annotation workflow for AI training  
- Provide portfolio-ready examples of NER dataset creation

