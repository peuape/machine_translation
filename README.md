# machine_translation

A repo for small machine translation projects. 

### 1. eng_fra.ipynb
In this notebook, I compared the BLEU scores of machine translation from English to French by Bahdanau and Luong attention. I added an encoder and a decoder by luong attention to the code in "NLP From Scratch: Translation with a Sequence to Sequence Network and Attention(https://docs.pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html)". The BLEU scores are as follows:  
Bahdanau:73.26  
Luong:40.83  
The BLEU score of Bahdanau attention was significantly higher than that of Luong attention. 
