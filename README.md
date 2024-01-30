I have used the research paper having title "Exploring Natural Language Processing in Model-To-Model Transformations" which is uploaded in IEEE Xplore. In research paper they mentioned that their trained BERT-BiLSTMCRF outperformed it for the verb phrase detection task. But i have solved it "current_pos.startswith" and "next_pos.startswith". And i did various accuracy test such as F1 Score , precision and recall.


**Functions**


**1. extract_relation_phrases(text)**


Extracts verb phrases, conjunctive phrases, disjunctive phrases, and noun phrases from the input text.

**2. extract_noun_phrases(text)**

Extracts noun phrases from the input text.

**3. detect_abbreviations(text)**


Detects abbreviations in the input text.

**4. calculate_metrics(extracted, expected)**


Calculates precision, recall, F1 score, and accuracy metrics based on the extracted and expected phrases.
#accuracy = number of correctly extracted instances/number of total instances
#precision = concepts correctly identified/concepts identified total
#recall = concepts correctly identified/gold standard concepts
#F1-measure (also referred to as F1-score) is defined as a harmonic mean of these two measures:
Fβ = (1 + β^2) × (precision × recall)/precision + recall , β = 1
**5. User Input and Expected Results**


Modify the user_input and expected_relation_phrases variables in the script to test different sentences and expected results.
