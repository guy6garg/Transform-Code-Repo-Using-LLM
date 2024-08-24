# Transform Code Repo Using LLM
In this assignment, I have developed a small end to end module to transform files in code repository using large language model (CodeLLama 7B)
Here is an example scenario. 
1. Given an input repo with some code files. Let's say we have a function log(str) defined in one of the class, and it gets called at various locations across classes.
2. Using an LLM, construct appropriate calls and add a "loglevel" argument into this method, and change the logging statement accordingly. So, the function now looks like log(str, loglevel). Given that the function signature has changed, all its callers need to be updated as well.
3. Using TreeSitter based output and LLM, correct the function calls in the other classes as well

Code with necessary comments and explanation is attached in the notebook
