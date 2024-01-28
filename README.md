# 102103247_Topsis_pretrained_model
This is an Assignment Task for finding the best pre-trained model taken from Hugging Face for comparing the best model for text classification.
# Title
To find the best pre-trained Model by applying Topsis for text classification.
# Description
In the initial phase, sentence data was gathered, comprising various sentence pairs intended for evaluation based on distinct parameters. Subsequently, tokenization was applied, and models were retrieved from Hugging Face. These models were then employed to compute text classification for the given text pairs across five evaluation parameters. The outcomes were recorded and stored in a CSV file for further analysis.After getting the output in a csv file we then run topsis analysis to find topsis score for each model and rank them accordingly. For topsis analysis we wrote a python code to generate a csv file with topsis score and ranking
# Result
I found 'roberta-base-uncased' model showed the best outcomes for sentence similarity with a Topsis Rank of 1 and score 94.84.
![image](https://github.com/Mayank-Gupta-9/102103247_Topsis_pretrained_model/assets/98733807/5baa20a8-a2b1-46e3-aff3-edcb3e721269)
# Comparison graph between topsis score v/s models
![102103247-1](https://github.com/Mayank-Gupta-9/102103247_Topsis_pretrained_model/assets/98733807/678c116f-4f2f-4559-b623-6b1d515d786e)
