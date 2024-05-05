Here is the rewritten text with corrected grammar and punctuation:

# CAT3-MCQs-MAY

## Workflow

1. First, I generated questions using GPT-4-Turbo by giving AI prompt shown in the image below. 

![Prompt](https://github.com/Adhithya03/CAT3-MCQs-MAY/assets/77617084/3acce5a2-92d9-4e46-a2ab-60915e16c29f)

I used https://chatkit.app as a frontend for chatting with GPT-4-Turbo, and I have a developer account from https://platform.openai.com, which enables me to access these AI models. (I don't have a ChatGPT Plus subscription; in my opinion, it has very limited model-accessing features, which will be useful for the general public, but I don't prefer it.)


2. Then, I configured .tex files to create questions in a specific format, as shown in https://github.com/Adhithya03/CAT3-MCQs-MAY/blob/main/biomed.tex#L12-L27.

3. Then, the questions from GPT-4-Turbo were given to **GEMINI-1.5-Pro**, which is a free AI model from Google. It formats the questions specifically to create them in the style I want.

Finally, I compiled the .tex file with a LaTeX compiler, for which there are many options available.


## Prompt explained


![Prompt](https://github.com/Adhithya03/CAT3-MCQs-MAY/assets/77617084/3acce5a2-92d9-4e46-a2ab-60915e16c29f)

1. First, I provide portions enclosed between 3 backticks, so that the AI model doesn't confuse the portion with the instruction that I will give.

2. Then, I assign it a personality, `University professor`, so that it gets into Professor mode, making the questions technical. This may sound silly, but LLMs like GPT-4-turbo have read an unimaginably large amount of internet text and can imitate any personality. We specifically want this personality for our questions.

3. Then, I specify the number of questions and format.

4. Lastly, since LLMs may generate unclear MCQs, I am specifically instructing to make them relevant and unambiguous.
