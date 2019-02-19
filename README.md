# Generalized model that can be used to test 5' UTR sequences up to 100 nt upstream of coding sequence
We created a 5' UTR library where the length of the random sequence upstream of the start codon ranged from 25 to 100 nt. The model was trained on the 90% of the library and tested on the held-out 10%. Native human 5' UTR sequences that are shorter than 100 nt were also tested using this generalized model. 

Random sequences and human native sequences are in the same dataset. Random sequences or human sequences can be selected by choosing the key word in set. For example: 'df = df1[df1['set']=='random']' or 'df = df1[df1['set']=='human']'. 

Sequences shorter than 100 nt are filled with Ns on the 5' to reach the full length 100 nt. More details were shown in the ipython notebook.

Current storage of the data 'varying_length_25to100_1.pkl' available here: https://drive.google.com/file/d/1w7o4vg04-2ujr5oBmjft-sCzFSDzQ9FI/view?usp=sharing
