# Example Applications of AI for CIS509 - Fundamentals of AI Systems Management 

## Classification 
Emotional states are difficult to detect from text. Often times NLP will pull keywords and use those words
in the classification instead of taking the semantics of language into consideration and therefore miscategorize
emotional state. For example, one might say that they are hated by others, and the classifiers will note hate as 
an emotional state where sadness might be a more appopriate state. 

The noteboke contained herein attempts to use classify the emotional state of the author of text based on very short 
text. The data set was pulled from [Kaggle](https://www.kaggle.com/datasets/simaanjali/emotion-analysis-based-on-text)

I am using Mistral locally for cost savings, but OpenAI will work just as well and likely better due to function calling.

I have had difficulties getting Mistral to reliably to limit its response to single word only. 

TODO: 
    Update to show example of using OpenAI API instead of just Ollama



*Requirements*:
    Note you must have [Ollama](https://ollama.com/download) installed on your machine with Mistral, Gemma, Llama or whatever model you want to use downloaded. 