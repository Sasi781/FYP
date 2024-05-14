PRECIPS - PREDICTION OF RESIDUE SWITH
 ENHANCED CHANGES IN PROTEIN STRUCTURE
 UPON DRUG INTERACTION

 
Understanding the interactions between drugs and proteins is crucial
for drug discovery and development. This project focuses on predicting binding
residues in a protein sequence following interaction with a drug, as well as
identifying amino acid changes induced by drug-protein interactions and their
impact on binding affinity. Additionally this project explores the ramifications
of drug-drug-target interactions by observing changes in the interaction scores
when one drug interacts with another and it aims to predict the increase or
decrease in adverse effects arising from the combination of two drugs. Data
from DrugBank and the Protein Data Bank (PDB) are utilized to construct
datasets for drug-target interaction (DTI) and binding residue prediction. Also,
ThermomutDB is employed to capture protein representation changes resulting
from amino acid mutations induced by drug interactions.
To represent the features of drugs and proteins, Morgan fingerprints
for drugs and a protein encoder for protein sequences are utilized. These
features are then fed into a transformer model, where self-attention mechanisms
enable accurate prediction of binding residues. In parallel, a Siamese network
architecture is employed to predict protein sequence changes induced by drug
interactions. In addition Long Short Term Memormy (LSTM) network is
utilized for selecting important genes related to drug drug interaction prediction.
This integrated approach combines deep learning and machine
learning techniques with domain-specific knowledge from bioinformatics
databases to provide insights into drug-protein interactions. By accurately
predicting binding residues and identifying protein sequence changes, this
methodology contributes to the optimization of drug design and understanding
of molecular mechanisms underlying drug action.
