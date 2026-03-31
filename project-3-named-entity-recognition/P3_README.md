# Named Entity Recognition (NER) Dataset Project

## Overview

This project demonstrates a small NER dataset designed for labeling entities in text.  
NER (Named Entity Recognition) is a common task in AI training, used to identify people, locations, organizations, and dates in text.

The dataset includes sentences related to the Netherlands, as well as general knowledge and cultural references.  
It is designed as a portfolio project to demonstrate annotation skills for AI training workflows.

---

## Project Goals

- Create a structured NER dataset  
- Annotate entities with clear labels  
- Demonstrate understanding of AI data annotation workflows  

---

## Project Structure

project-3-named-entity-recognition
│
├── P3_dataset.csv
├── P3_annotation_guidelines.md
└── P3_README.md

	•	P3_dataset.csv – Annotated sentences with labeled entities
	•	P3_annotation_guidelines.md – Instructions for annotators and label definitions
	•	P3_README.md – Project overview and purpose

⸻

Dataset Structure

Each dataset entry contains:

Field	Description
sentence	A full sentence with named entities
entities	Annotated entities in the format Type: Entity Name, separated by semicolons if multiple


⸻

Example Dataset Entries

Sentence	Entities
Mark Rutte has been the Prime Minister of the Netherlands since 2010	Person: Mark Rutte; Location: Netherlands; Date: 2010
The Rijksmuseum is located in Amsterdam	Organization: Rijksmuseum; Location: Amsterdam
Van Gogh painted Starry Night in 1889	Person: Van Gogh; Date: 1889
Shell is a multinational company headquartered in The Hague	Organization: Shell; Location: The Hague
Queen Maxima was born in Argentina	Person: Queen Maxima; Location: Argentina


⸻

Label Types
	•	Person – Names of people
	•	Location – Geographic locations, cities, countries, landmarks
	•	Organization – Companies, institutions, museums, or governmental bodies
	•	Date – Years, centuries, or specific dates mentioned in the text

Refer to P3_annotation_guidelines.md for detailed annotation instructions and edge cases.

⸻

Annotation Guidelines Summary

Annotators follow these steps:
	1.	Read each sentence carefully
	2.	Identify all entities of the types above
	3.	Record each entity in the format: Type: Entity Name
	4.	Separate multiple entities with a semicolon ;
	5.	Ensure correct spelling, capitalization, and proper titles when applicable

Edge cases, such as ambiguous organization names or historical dates, are explained in P3_annotation_guidelines.md.

⸻

Purpose of the Project

NER datasets like this are commonly used to:
	•	Train AI systems to extract entities from text
	•	Evaluate entity recognition performance
	•	Demonstrate annotation and data preparation skills for AI training

