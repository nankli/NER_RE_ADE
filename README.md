# ucb_mids_w266_project
UCB NLP with Deep Learning (W266) final project
Authors: Diana Nguyen and Nan K. Li

Introduction
  1. Drug-related adverse effects (ADE) are negative reactions followed by the use of medication.
  2. According to the CDC, “Adverse drug events cause approximately 1.3 million emergency department visits each year.”  
  3. Example sentence: 
  'Massive prolapse of the urethral mucosa following periurethral injection of calcium hydroxylapatite for stress urinary incontinence.' 
  Entity: drug: 'calcium hydroxylapatite', effect: 'prolapse of the urethral mucosa'
 	Relation:  relevant/irrelevant
  
  
Dataset
  1. Ade_corpus_v2_drug_ade_relation
  2. Ade_corpus_v2_classification
  
Methodology
  1. NER Models: BERT, BioBERT
  2. Relation Classification Models: BioBERT, Traditional machine learning (SVM, Gradient Boosting)
  
Conclusion
  1. For the named entity recognition task, with room for improvement, the BioBERT model did better compared to BERT with an F1 score of 0.88. 
  2. For the relation classification task, the BioBERT model stood out with its exceptional performance, achieving a state-of-the-art F1 score of 0.94 and accuracy of 0.95. 
  3. The findings suggest that utilizing models (BioBERT) trained on domain-specific datasets is advisable to achieve optimal results.


