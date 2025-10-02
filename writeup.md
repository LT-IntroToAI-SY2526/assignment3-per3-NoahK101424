# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
Key programming concepts that I learned while completing this assignment are the general syntax and way that I am supposed to write code for python, such as the differences in instantaniating my variables, which I don't really have to do in python compared to Java. Additionally, understanding the assert statements and how they work, such as the term `sorted` which is a function that sorts the return list, which I did not know before. Finally, fully understanidng how for loops work in python, where it is very similar to an enhanced for loop in Java. 

2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.
First, the user types a query into the chatbot, which is then taken by the search_pa_list function. Taking the user input, it matches it against the known patterns (the other functions) and calls that corresponding action, which is then returned to the user. If it finds a match but has no answers it returns ["No answers"]. If it finds no match it returns ["I don't understand"].

3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?
Some real-world applications where this type of pattern-matching chatbot system could be useful is exactly as a movie sorter like we did in this assignment. However, there are countless other applications such as a search engine, taking user input and matching that with the functions in the chatbot. I could extend this system for practical use by adding more functions that take into account more senarios or questions that the user might ask.