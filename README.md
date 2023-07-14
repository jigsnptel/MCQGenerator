# MCQGenerator
This code will generate MCQs from the given presentation with 4 options and answers
The code uses Hugging face open source model "flan-alpaca-large" with hugging face embeddings to generate MCQs, but the response is not so good. question is repeating as we can see from the result
The code then use openAI "gpt-3.5-turbo-16k" model and hugging face embeddings to generate MCqs, and it works and gives good 10 MCQs with options and answers.
