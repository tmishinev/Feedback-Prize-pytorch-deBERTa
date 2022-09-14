# Feedback-Prise-pytorch-deBERTa
### Feedback Prize - English Language Learning (Kaggle) - Evaluating language knowledge of ELL students from grades 8-12

## 1. Goal of the Competition
The goal of this competition is to assess the language proficiency of 8th-12th grade English Language Learners (ELLs). Utilizing a dataset of essays written by ELLs will help to develop proficiency models that better supports all students.

Your work will help ELLs receive more accurate feedback on their language development and expedite the grading cycle for teachers. These outcomes could enable ELLs to receive more appropriate learning tasks that will help them improve their English language proficiency.


## 2. Dataset
The dataset presented here (the ELLIPSE corpus) comprises argumentative essays written by 8th-12th grade English Language Learners (ELLs). The essays have been scored according to six analytic measures: cohesion, syntax, vocabulary, phraseology, grammar, and conventions.

Each measure represents a component of proficiency in essay writing, with greater scores corresponding to greater proficiency in that measure. The scores range from 1.0 to 5.0 in increments of 0.5. Your task is to predict the score of each of the six measures for the essays given in the test set.

Some of these essays have appeared in the datasets for the Feedback Prize - Evaluating Student Writing and Feedback Prize - Predicting Effective Arguments competitions. You are welcome to make use of these earlier datasets in this competition.

## 3. Model

5 Fold CV of deBERTa

### Results:

CV: [0.4533, 0.4526, 0.4564, 0.4534, 0.4545]
Average CV: 0.4541
