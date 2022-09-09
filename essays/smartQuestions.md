---
layout: essay
type: essay
title: "How to Communicate Effectively between Developers"
# All dates must be YYYY-MM-DD format!
date: 2022-09-08
published: true
labels:
  - StackOverflow
  - Smart Questions
  - Communication
---

<img width="1000px" class="rounded float-start pe-4" src="../img/javascript-illustration.png">

### Smart Questions

Asking smart questions are one of the key elements in effective communication and collaboration among developers. By asking smart questions, you should receive and equally effective and relevant answer to it. There are many nuances to asking a good question, especially when asking people who have no context to what you’re working on. Forums like StackOverflow can be exceptionally helpful when developing software. It’s a website where people come together to solve each other’s issues and errors. By asking smart questions on StackOverflow it allows others to help you more effectively. But what is a smart question?

### Stack Overflow

Anyone is able to post questions on StackOverflow, but not everyone’s questions receive the same level of detail and attention as others. Many questions often go unanswered or even removed from the forum. Why is this? When others are unable to quickly read, understand and evaluate the issue it often leads to people unable to answer or worse, don’t want to answer at all. Spending additional time trying to decipher or asking too many additional questions leads others to ignore the problem entirely. 

________________________________________________________________________________________________________

This [Question](https://stackoverflow.com/questions/73655082/i-dont-know-what-i-am-doing-wrong-please-tell-me) is an example of a question that should be avoided. 

#### I don't know what I'm doing wrong, please tell me

*I know this is probably stupid but I am new to python and I just came from javascript so please don't be rude*

I coded it as a fail safe so it is only supposed to say 'no' if it is not a integer or a number between 1 and 9. I have tried adding brackets and I have done everything I can think of

________________________________________________________________________________________________________

The author did not add the code into the question itself. Instead they opted to screenshot their code and link it to the post. Other developers often copy and paste code into their own software to debug it and to see if there are any errors that are easily visible. Not doing so often leads to irritation and confusion among those trying to help. The question is also is not clear into what the issue is itself and what the desired outcome is. Without knowing what to solve for, it requires additional questions to answer the initial question, which is often more work than other developers are willing to put in when solving other people’s questions. The author also did not write a question in the header in the post “Please Help” provides no context into what needs to be solved and who might be a good fit in answering the question. Asking the right question and providing sufficient information is key to getting answers solved.

Writing the right question takes some time, but it is not difficult once you understand some of the key points. The right context is the first step in getting a concise answer. Is your question title eye-catching, does it provide information, are you using tags? It helps to draw attention and provide basic context in who, and how someone can help. Does your post provide enough context; language, operating system, IDE and version, and relevant information to the background of the issue. The most importantly, What you did, what you’ve done and any research you’ve done into the topic. This includes any code and other resources you’ve tried and used. The code must be written into StackOverflow properly using the correct markdowns. Providing clear sample code is essential to writing a good question. Once you’ve built a good post, its important to make sure to double-check and make sure the question is clear, free of any grammar and spelling errors. Maintaining professionalism is important in building trust and garnering any rapport among other users. Once you're ready and have posted your question, when others ask additional questions and provide answers, it’s important to keep an eye on your question and provide information as it comes up. Be polite, no one is getting paid to answer your questions, being rude hinders your odds of an answer greatly. 

________________________________________________________________________________________________________

This [Question](https://stackoverflow.com/questions/1642028/what-is-the-operator-in-c) is a great example of a good question. 

#### What is the "-->" operator in C++?

*After reading Hidden Features and Dark Corners of C++/STL on comp.lang.c++.moderated, I was completely surprised that the following snippet compiled and worked in both Visual Studio 2008 and G++ 4.4.*

Here's the code:

```
#include <stdio.h>
int main()
{
    int x = 10;
    while (x --> 0) // x goes to 0
    {
        printf("%d ", x);
    }
}
```
Output:

`9 8 7 6 5 4 3 2 1 0`

I'd assume this is C, since it works in GCC as well. Where is this defined in the standard, and where has it come from?

________________________________________________________________________________________________________

Although the question is not long in length; it’s clear, provides sample code and asks for a specific answer. You can see by the amount of upvotes and clarity provided in responses that the question was clear and well received.
