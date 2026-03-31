# AI Hallucination Detection Dataset (Netherlands-Themed)

## Overview

This project demonstrates a small dataset designed to identify hallucinations in AI-generated responses.  
In large language models (LLMs), hallucinations occur when the model produces incorrect, fabricated, or misleading information that appears plausible.

The goal of this project is to simulate a real evaluation task used in AI development, where annotators must detect factual inaccuracies in model outputs.

The dataset focuses on Netherlands-related topics such as geography, politics, culture, and history.

---

## Project Goals

This project demonstrates the ability to:

- Detect factual errors in AI-generated text
- Build a structured evaluation dataset
- Apply annotation labels for hallucination detection
- Document annotation decisions with explanations

These skills are commonly required in AI evaluation, RLHF pipelines, and data labeling workflows.

---

## Project Structure

project-2-hallucination-detection
├── P2_README.md
├── P2_dataset.csv
├── P2_annotation_guidelines.md
├── P2_examples.md
└── P2_dataset_statistics.md

Files
	•	P2_dataset.csv – AI-generated prompts and responses with labels and explanations
	•	P2_annotation_guidelines.md – Instructions for annotators on labeling hallucinations
	•	P2_examples.md – Example labeled responses demonstrating correct, partially correct, and hallucinated answers
	•	P2_dataset_statistics.md – Overview of dataset size, label distribution, and topic coverage

⸻

Dataset Structure

Each dataset entry contains:

Field	Description
prompt	A factual question related to the Netherlands
ai_response	A simulated AI-generated answer
label	Classification of the response (correct, partially_correct, hallucination)
explanation	Reason for the assigned label


⸻

Label Definitions
	•	correct – The response is factually accurate.
	•	partially_correct – The response contains some correct information but also includes inaccuracies or misleading details.
	•	hallucination – The response contains clearly incorrect or fabricated information.

Detailed guidelines are available in P2_annotation_guidelines.md.

⸻

Example Dataset Entry

Prompt: Which sea borders the Netherlands?
AI Response: The Netherlands borders the Baltic Sea.
Label: hallucination
Explanation: The Netherlands borders the North Sea, not the Baltic Sea.

Additional examples are provided in P2_examples.md.

⸻

Dataset Statistics
	•	Total entries: 35
	•	Label distribution:
	•	correct: 25
	•	partially_correct: 4
	•	hallucination: 6

Full statistics are documented in P2_dataset_statistics.md.

⸻

Annotation Methodology
	1.	Read the prompt and AI-generated response.
	2.	Verify factual accuracy using reliable sources.
	3.	Assign one of the three labels: correct, partially_correct, hallucination.
	4.	Provide a short explanation for the assigned label.

This simulates common LLM evaluation workflows and demonstrates human-in-the-loop annotation.

⸻

Purpose of the Project

Hallucination detection is a key challenge in modern AI systems.
This dataset demonstrates:
	•	Evaluating factual reliability of LLM outputs
	•	Structuring annotations for dataset creation
	•	Documenting reasoning behind labeling decisions

⸻

Possible Extensions

Future improvements could include:
	•	Adding multiple annotators
	•	Measuring inter-annotator agreement
	•	Expanding dataset size to hundreds of prompts
	•	Training a simple hallucination detection model

