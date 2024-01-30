I have used the research paper having title "Exploring Natural Language Processing in Model-To-Model Transformations" which is uploaded in IEEE Xplore. In research paper they mentioned that their trained BERT-BiLSTMCRF outperformed it for the verb phrase detection task. But i have solved it "current_pos.startswith" and "next_pos.startswith". And i did various accuracy test such as F1 Score , precision and recall.# Relation Phrase Extraction Toolkit
This Python toolkit leverages Natural Language Processing (NLP) techniques to extract various types of phrases and abbreviations from input sentences. The functions included in this toolkit are designed to perform verb phrase detection, conjunctive and disjunctive phrase identification, noun phrase extraction, and abbreviation detection. Additionally, the toolkit provides metrics to assess the accuracy of the extracted phrases.

## Functions

### 1. `extract_relation_phrases(text)`

Extracts verb phrases, conjunctive phrases, disjunctive phrases, and noun phrases from the input text using part-of-speech tagging.

### 2. `extract_noun_phrases(text)`

Identifies and extracts noun phrases from the input text using part-of-speech tagging.

### 3. `detect_abbreviations(text)`

Detects abbreviations present in the input text using regular expressions.

### 4. `calculate_metrics(extracted, expected)`

Calculates key metrics, including precision, recall, F1 score, and overall accuracy, based on the extracted and expected phrases. These metrics provide a comprehensive evaluation of the toolkit's performance.

## Evaluation Metrics

- **Accuracy**: Number of correctly extracted instances divided by the total number of instances.

- **Precision**: Concepts correctly identified divided by the total concepts identified.

- **Recall**: Concepts correctly identified divided by the gold standard concepts.

- **F1-Measure**: Harmonic mean of precision and recall, providing a balanced evaluation of the toolkit's performance.

```math
F_1 = \frac{(1 + \beta^2) \times (\text{precision} \times \text{recall})}{\text{precision} + \text{recall}}, \beta = 1
