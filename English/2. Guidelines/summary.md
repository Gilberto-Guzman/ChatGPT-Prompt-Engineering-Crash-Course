# Prompting Principles

### **Principle 1: Write clear and specific instructions**<br>

Tactic 1: Use delimiters.<br>

- Triple quotes: """,<br>
- Triple backtips: ```,<br>
- Triple dashes ---,<br>
- Angle brackets: < >,<br>
- XML tags: `<tag> </tags>`<br>

Using delimiters is also a helpful technique to try to avoid prompt injections.

Tactic 2: Ask for structured output.<br>

- HTML<br>
- JSON<br>

Tactic 3: Check whether conditions are satisfied.<br>
Check assupmptions require to do the task.

Tactic 4: Few-shot prompting.<br>
Give successfull examples of completing tasks.

### **Principle 2: Give the model time to “think”**

If a model is making errors by rushing to an incorrect conclusion, you should try reframing the query.

Tactic 1: Specify the steps to complete a task.<br>
Step 1: ...<br>
Step 2: ...<br>
...
Step N: ...

Tactic 2: Instruct the model to work out its own solution before rushing to a conclusion.

# Model Limitations.

- Hallucination.
- Makes statements that sounds plausible but are not true.

Reducing hallucinations.
First find relevant information,<br>
then answer the question<br>
based on the relevant information.