---
layout: essay
type: essay
title: "Smart Questions, Smart Answers"
# All dates must be YYYY-MM-DD format!
date: 2024-09-11
published: true
labels:
  - Software Engineering
  - Reflection
  - Learning
---
<h2>Understanding How to Ask</h2>

<center> <img width="500" height="500" class="img-fluid" src="../img/smartqs1.jpg"> </center>

  To get clear and concise answers, one should learn how to ask what’s known as a “smart” question first. This idea of a “smart” question comes from Eric Raymond’s essay, How To Ask Questions The Smart Way, in which he dives into what he believes is the correct way to ask questions so that people like him, hackers and tech wizards, are more inclined to give straight and insightful answers.

  According to Eric Raymond’s essay, a smart question starts with your research. Being able to look for the results on your own allows you to avoid duplicating previously answered questions. In addition to that, it also stops you from wasting others' time with questions that already have information on how to solve out there. After doing your research, the next step is to find an appropriate message board that fits your question's topic and skill level. Then the question should be structured clearly and concisely, with appropriate subject headers to attract the right audience. Along with a clear question, it should be followed up with your prior findings through either experimentation or research.

  These findings should be structured clearly and provide context to the situation. Lastly, if your question is about a problem you are facing make sure that the symptoms are in chronological order. Essentially, a smart question is designed to streamline the help process by providing all the necessary information upfront for others to assist effectively.

<h2>Getting a Smart Answer</h2>

  The reason to ask smart questions is to demonstrate that the asker has put thought into their query while also making it easier for others to engage. These types of questions tend to be well-structured, concise, and respectful of the community’s time. When a question includes details of the asker’s attempts to solve the problem, it shows that the asker is invested in finding the solution and willing to put in the work to find a solution. 
  
  In addition to that, the responder can jump into the problem without needing to clarify basic information. This allows for the responder to give an accurate and in-depth answer because they can pinpoint the issue more effectively. As a result, asking smart questions usually get smarter and more insightful answers.

<h2>"Not-so-Smart" Question Fails</h2>

  A useful example of a “not so smart” question would be shown in <a href="https://stackoverflow.com/questions/78974826/javascript-loop-and-conditional-statement">StackOverflow</a>. The example asks, “Prompt the user to enter a number between 0 and 1 million. If the number does not fall in the specified range, give a message as ‘Invalid number’. If number is valid, display in the screen, the sum of numbers upto the given number,” fails on being a smart question. 
  
  This question lacks many aspects of a smart question like being precise, having background research, providing context, and lastly seems to be a basic homework question. This question could be improved by fixing some of the grammatical errors along with first providing what language this function should be programmed in. In addition to that, it should also show what they have to start with and possibly a snippet of their code so that responders do not have to create a function from scratch, but rather help to fix their already written code.
  
  The consequence of this question was that StackOverflow flagged this question as needing to be more “focused”. As a result, the question was closed by StackOverflow, indicating that without focus and details, a question is not likely to receive quality responses. It also becomes burdensome for others to try and help with questions like this.

<h2>Effectiveness of a "Smart" Question</h2>

<center> <img width="500" height="500" class="img-fluid" src="../img/smartqs2.png"> </center>

  To show the contrary, on <a href="https://stackoverflow.com/questions/8547778/why-are-elementwise-additions-much-faster-in-separate-loops-than-in-a-combined-l
">StackOverflow</a> an example of a smart question was asked which was about the idea of memory optimization and loop performance. This example provided a scenario they have been experimenting with which involves adding four big arrays (labeled a1, b1, c1, d1). The first method of adding the array had a loop that adds b1[j] to a1[j] and immediately after, adds d1[j] to c1[j]. Which ultimately makes the loop do two tasks. However, the second method runs one loop to add b1[j] to a1[j] for all elements and then does the same in a separate loop for d1 and c1. 
  
  In addition to showing that the second method almost doubled the speed of the first method he also provided what he compiled the program on and the specs of his computer. Finally, he finishes off his findings with a graph of the cache behaviors and poses the clear question,” Could you provide some solid insight into the details that lead to the different cache behaviors as illustrated by the five regions on the following graph?”. The asker provides a clear, focused problem which includes specific details such as the hardware and software environment, and provides code that highlights the issue they are facing.
  
  Due to their smart question, in return, the asker got an in-depth response that showed off some of the responder's findings. The community appreciated the specificity and responded with well-thought-out, comprehensive explanations that addressed the behavior of CPU cache behavior and memory management. As a result, this made a rich learning experience for both the asker and other readers.

<h2>Sum it Up</h2>

  In conclusion, smart questions are essential in software engineering because they allow for efficient and effective problem-solving. A smart question is detailed, well-researched, and appropriate for the specific platform, making it much more likely to receive high-quality responses. In contrast, underdeveloped questions, like the one asking for a simple solution to a sum calculation, often get ignored or get unwanted answers in retaliation.
  
  By analyzing both smart and not-so-smart questions on StackOverflow, we can better understand how to ask questions in a way that benefits both the asker and the community. This exercise underscores the importance of thoroughness, precision, and thoughtfulness in communication as a software engineer.





