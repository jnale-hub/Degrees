# Degrees
AI Algorithm using Breadth-First Search that looks into IMDB database and finds how many “degrees of separation” between two actors.

## Task
Write a program that determines how many "degrees of separation" apart two actors are, behaving as shown below:
```
$ python degrees.py large
Loading data...
Data loaded.
Name: Emma Watson
Name: Jennifer Lawrence
3 degrees of separation.
1: Emma Watson and Brendan Gleeson starred in Harry Potter and the Order of the Phoenix
2: Brendan Gleeson and Michael Fassbender starred in Trespass Against Us
3: Michael Fassbender and Jennifer Lawrence starred in X-Men: First Class
```
[View the full assignment description on CS50's OpenCourseWare](https://cs50.harvard.edu/ai/2020/projects/0/degrees/)

## How to Run
Requires Python(3) to run:

Small database usage:
`$ python degrees.py small`

Large database usage:
`$ python degrees.py large OR $ python degrees.py`

## Acknowledgements
Actor / Movie information courtesy of IMDb.
