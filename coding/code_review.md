# Introduction:
This template provides a series of stages and corresponding prompts to guide you in asking ChatGPT 
for help in understanding a new code repository. Each stage focuses on a specific aspect of the 
code, and the prompts are designed to be clear and concise for ChatGPT to understand. Remember, 
ChatGPT will analyze single files given one at a time and will not have direct access to 
the repository.

## Stage 0: Taking in the code

I reuse this prompt for adding code snippets to ChatGPT's in memory context. I will do this as 
many times as necessary to get the entire codebase into ChatGPT's memory.

>   Act as if you are a Senior [ROLE] Engineer with over 20 years experience working at prestigious
>   FANG companies. Read in the following piece of code.
>   Output "READ" when you are done.
>
>   ---------------------------------
>
>   ```python
>   # Code here
>   ```
>

## Stage 1: Understanding the code

### Prompt 1:

> Clearly explain what the purpose of the code is and how it works

### Prompt 2:

> Can you explain the functions and classes in the code? 
> What are their purposes and how do they relate to each other?

### Prompt 3:

> Please explain the main algorithm or logic used in this code.
> How does it work, and what are the key steps involved?

## Stage 2: Improving the code

### Prompt 1:

> Are there any best practices followed or areas for improvement in this code.  
> Please provide suggestions.

### Prompt 2:

> Please write some unit tests for this code so that we are confident that it works as expected and
> if we refactor the code we don't break anything.

### Prompt 3:

> Is there any way to refactor this code so that it is easier to test and maintain?

### Prompt 4:

> Please write some documentation for this code so that we can understand it better in the future.

### Prompt 5:

> Is there any way to improve the performance of this code?
