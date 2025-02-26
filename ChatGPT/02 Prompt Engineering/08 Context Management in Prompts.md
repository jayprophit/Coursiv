# Context Management in Prompts

we're going to focus on context management in prompts.
We'll cover techniques for preserving context, the self-consistency technique, and strategies for writing clear instructions and providing reference text. By the end of this lesson, you'll be able to manage multi-turn conversations effectively.

#### Before we start, why do you think it's a big deal to keep the conversation flowing smoothly when chatting with ChatGPT?
It ensures that ChatGPT can provide relevant and coherent responses over multiple turns

#### So, building on that - what do you think are some good tricks for keeping the conversation on track when you're chatting with ChatGPT?
Referring back to previous points

## Start with The Basics
Let's start with the self-consistency technique. This technique ensures that ChatGPT provides consistent responses across multiple interactions.

By maintaining a coherent and reliable conversation flow, it becomes easier for users to follow and trust the information provided.

This technique is particularly useful in scenarios where maintaining a coherent narrative is important, such as email composition.


### example 01.01

```markdown
Act as a friendly [person].
[Task] an email to [recipients] about a [subject].

(person) = [HR assistant]
(Task) = [Write]
(recipients) = [employees]
(subject) = [survey]
```

## Ask the Model to Adopt a Persona
In the prompt above, you have already used one strategy for getting better results - you asked the model to adopt a persona, HR assistant.
