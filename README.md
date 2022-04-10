# Pegasus-xsum
Install dependencies i.e. pytorch, transformers
# Import and load the model
importing dependencies from transformers
# Create tokenizer
get pretrained data from huggingface.
There are alot of datas related to NLP. I used google/pegasus-xsum
# Loading the model
Create a variable and again use pretrained data i.e. google/pegasus-xsum
# Create tokens(which representes as numbers)
using tokenizer and keeping truncation "True", this will make the article as short as and meaningful it can make.
# Summarize the model
Generate the token as **tokens
# Decode
Finally decoding the summary and the new summary of the article will be there. 
