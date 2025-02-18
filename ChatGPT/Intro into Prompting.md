# Intro into Prompting

## What is Prompt & a Engineering?
a prompt is a (input) question, statement or a set of instructions that the ai will read, refere to data, recognise patterns and have an interpretation of logic it will return as an answer.
a prompt engineer is someone that askes a question designed to get a spefic answer in a particular way, format or structure.
a promt directs the models repsonse by providing context and specific instructions

example..."Write a story about a cat"

### example 01

'''markdown
write a [Description] story about a cat.  it should contain the word "palyful and "[Word]"

(Description) = [short]
(Word) = [paws]
'''

#### Nevertheless, you might wonder, "Why is prompt engineering so important?"
- it enhances the accuracy of the responses
- it allows to leverage the full potential of LLMs
- it saves time

Prompt engineering enables you to tailor ChatGPT to specific needs or audiences
generating:-
- marketing copy
- technical documentation
- creative stories

## Prompt Engineering Technique's

##### **Specificity**
meaning the specific your prompt the more precise your answer.

#### This prompt is more specific to learn about certain cat breeds
"Explain the history and characteristics of the Persian cat breed"

##### **Role-Playing**
meaning assigning a role to the model, ChatGPT will act in a style when providing an answer

### example 02

'''markdown
You are a [Role] who works in a [Specification] style.  [Task] me a 4-line [Subject] about a cat.

(Role) = [poet]
(Specification) = [whimsical]
(Task) = [Write]
(Subject) = [poem]
'''

#### Why dose providing context and perspective in your prompts help ChatGPT generate better responses?
it helps generate more relevant and accurate responses.

#### as you can see, role-playing helps tap into the model's extensive knowledge base in a structured way, ensuring the responses a detailed and contextually appropriate.  This example of a prompt uses role-playing to improve the response!
"You are a cat behviorist, Explain how to introduce a new kitten to a house with an older cat"

##### **Iterating**
This involves refining and tweaking your prompt based initial outputs to get closer to the desired result

example.... create an ad for cat food targeting cat owners
initial prompt: What makes premium cat food beneficial for cats?

### example 03

'''markdown
[Clarification] [Specification] [Narrowing]

(Clarification) = (detailed)
(Specification) = (premium)
(Narrowing) = (overall health)
'''
