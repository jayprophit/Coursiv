# Prompt Engineering Technique's

In this lesson, we're going to enhance your basic prompt engineering skills to create more complex and effective prompts.
We'll explore [Zero-Shot], [Few-Shot], and [Chain-of-Thought] prompting.
By the end of this lesson, you'll be able to craft precise prompts that manage complex instructions and optimize AI responses.

## Zero-Shot Prompting
Remember when we used to ask ChatGPT directly for a response? This method is called zero-shot prompting. It involves generating responses without providing any prior examples.
This technique is particularly useful when you want ChatGPT to perform a task on which it hasn't been explicitly trained.

## Let's Practice!
What will you do if TechMobile's customer is having trouble logging into their account?

### example 01.01

```markdown
[Task] a [Person] who is having trouble with [Specific Issue] their account.

(Task) = [Assist]
(Person) = [customer]
(Specific Issue) = [logging into]
```

## Few-shot Prompting
Now that we've covered zero-shot prompting, let's move on to few-shot prompting.

This technique improves ChatGPT's responses by providing a few examples to demonstrate the expected outcome.

### example 02.01

```markdown
Here are examples of how to respond to customer inquiries: "How can I [Issue 1] password ?" - "To reset your password, go to the settings page and click on "Reset password."
"Where can I [Issue 2] my order?" - "You can track your order by visiting the " [Page] " section in your account." Now respond to: "update [Customer Inquiry]"

(Issue 1) = [reset my]
(Issue 2) = [track]
(Page) = [My Orders]
(Customer Inquiry) = [billing information]
```

## chain-of-thought prompting.
This technique helps in improving response accuracy. To apply - break down complex tasks into manageable steps.

What is the primary advantage of using Chain-of-Thought prompting?
It breaks down tasks into logical sequences

### example 03.01

```markdown
You are a [Role] for a customer support team. Your task is to gather [Task] about the customer's issue.
Ask [Step 1] and extract all [Step 2] about the problem, ensuring you understand the context and specifics.

(helpful assistant) = [Assist]
(detailed information) = [customer]
(clarifying questions) = [logging into]
(relevant details) = [logging into]
```

## Customer's Response:
"I'm experiencing a problem with my H-Pad, which randomly shuts down even though the battery appears charged. This started about a week ago and is now frequent. There are no error messages, but the screen flickers, and the device overheats before shutting down."
Now, after receiving detailed information from the customer, analyze the issue and find out possible solutions or steps for resolution.

It may also determine if the issue needs to be escalated.

### example 04.01

```markdown
Please [Step 1] the [Subject] and [Step 2] step-by-step solutions.

(Task) = [Analyse]
(Person) = [issue]
(Specific Issue) = [suggest]
```
