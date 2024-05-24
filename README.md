Sequence based PPI prediction algorithm is developed using Xgboost. Around 73,000 positive and negative interacting protein pairs were extracted from Pan’s PPI dataset (http://www.csbio.sjtu.edu.cn/bioinf/LR_PPI/Data.htm)

Supp-A contains positive protein pairs while Supp-B contains negative protein pairs. The 'Data_Loading' file extracts protein paris from these files into csv files. PPI Prediction file has the algorithm. 

The function aa_composition(sequence) calculates the amino acid composition of a given protein sequence. It iterates over each amino acid (represented by the letters 'ACDEFGHIKLMNPQRSTVWY'), counts the occurrences of each amino acid in the sequence, and stores the counts in a dictionary. The final output is a list containing the count of each amino acid, which represents the feature vector for that protein sequence. This feature vector captures the relative abundance of different amino acids in the sequence and can be used as input. The model has accuracy of around 98%.
## Authors

- [@spandan_sureja](https://github.com/Spandan2308)

