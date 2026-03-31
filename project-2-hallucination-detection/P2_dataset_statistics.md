# Dataset Statistics

## Overview

This document provides a summary of the hallucination detection dataset used in this project.

The dataset contains Netherlands-themed factual prompts and AI-generated responses labeled for hallucination detection.

---

## Dataset Size

Total entries: 35

Each entry contains:

- Prompt
- AI-generated response
- Annotation label
- Explanation

---

## Label Distribution

| Label | Count |
|------|------|
| correct | 25 |
| partially_correct | 4 |
| hallucination | 6 |


---

## Dataset Characteristics

The dataset intentionally includes:

- Correct responses
- Clearly incorrect responses
- Subtle factual inaccuracies

This mixture helps simulate real AI evaluation scenarios, where models may produce both accurate and misleading information.

---

## Example Entry

Prompt: Which sea borders the Netherlands?

AI Response:  
The Netherlands borders the Baltic Sea.

Label: hallucination

Explanation:  
The Netherlands borders the North Sea, not the Baltic Sea.

---

## Limitations

This dataset is intentionally small and designed as a portfolio demonstration project.

Limitations include:

- Limited dataset size
- Single annotator
- No automated evaluation metrics

---

## Potential Improvements

Future extensions could include:

- Expanding the dataset to 500+ prompts
- Adding multiple annotators
- Measuring inter-annotator agreement
- Training a hallucination detection model

---

## Purpose

The dataset demonstrates the process of:

- Creating evaluation prompts
- Identifying hallucinated model outputs
- Structuring annotation data
