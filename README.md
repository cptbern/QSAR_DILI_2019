# Prediction of clinically relevant drug-induced liver injury from structure using machine learning
Hammann et al., J Appl Toxicol. 2019 Mar;39(3):412-419 
[Link to the original publication](https://doi.org/10.1002/jat.3741) 

## Abstract
Drug-induced liver injury (DILI) is the most common cause of acute liver failure and often responsible for drug withdrawals from the market. Clinical manifestations vary, and toxicity may or may not appear dose-dependent. We present several machine-learning models (decision tree induction, k-nearest neighbor, support vector machines, artificial neural networks) for the prediction of clinically relevant DILI based solely on drug structure, with data taken from published DILI cases. Our models achieved corrected classification rates of up to 89%. We also studied the association of a drug's interaction with carriers, enzymes and transporters, and the relationship of defined daily doses with hepatotoxicity. The results presented here are useful as a screening tool both in a clinical setting in the assessment of DILI as well as in the early stages of drug development to rule out potentially hepatotoxic candidates. 

## Contents
Models were trained on 588 substances whose SMILES codes are given in dili.smi. Descriptors calculated using [PaDEL](http://www.yapcwsoft.com/dd/padeldescriptor/) along with associated outcomes (0 for **no DILI**, 1 for **DILI**) are in dili_padel_2d.csv. This file can directly be used for training.
