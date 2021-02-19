# Personalized_cancer_diagnosis

Problem Statement: Classify the given genetic variations/mutations based on evidence from text-based clinical literature.

Explanation:
1) Once sequenced, a cancer tumor can have thousands of genetic mutations. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers). 
2) Currently this interpretation of genetic mutations is being done manually. This is a very time-consuming task where a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature.
3) We need to develop a Machine Learning algorithm that, using this knowledge base as a baseline, automatically classifies genetic variations.


The workflow is as follows
1. A molecular pathologist selects a list of genetic variations of interest that he/she want to analyze
2. The molecular pathologist searches for evidence in the medical literature that somehow are relevant to the genetic variations of interest
3. Finally this molecular pathologist spends a huge amount of time analyzing the evidence related to each of the variations to classify them
Our goal here is to replace step 3 by a machine learning model. The molecular pathologist will still have to decide which variations are of interest, and also collect the relevant evidence for them. But the last step, which is also the most time consuming, will be fully automated.

#Data Overview
• We have two data files: one conatins the information about the genetic mutations and the other contains the clinical evidence (text) that human experts/pathologists use to classify the genetic mutations.
• Both these data files are have a common column called ID
• Data file's information:
	○ training_variants (ID , Gene, Variations, Class)
	○ training_text (ID, Text)


