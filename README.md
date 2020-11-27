# Question-for-Assignment-by-Pooling-Demo
This is a demo of latex file I use to generate questions for assignment where questions are randomly given to set by pooling a collection of questions.

# DEMO of  Adding questions
To use this format with random question pooling create a .tex file and keep all the questions of similar type in a file. 
Each questions should be in the format below.
```latex
\begin{questionblock} 
Your questions here. 
You can use enumeration and itemize to create multiple parts of a question.
\end{questionblock}
```
To add questions randomly use the following format.
```latex
\randomquestionsfrombank{File name}{Number of questions to provide}
```
example:
```latex
\randomquestionsfrombank{2. secondType.tex}{5}
```