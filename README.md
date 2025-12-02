# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

## AIM : 
To test and compare how different prompting patterns (Zero-Shot, Few-Shot, Chain-of-Thought) respond to naïve (unstructured) prompts versus basic (clear and refined) prompts across various scenarios. The goal is to analyze improvements in quality, accuracy, and depth of responses when prompt design becomes more structured.

## AI Tools Required : 

ChatGPT (any advanced LLM model)
Optional: Any text editor to document results (VS Code, Sublime, Notepad++)

## Explanation :

### 1. Defining Prompt Types : 
a. Naïve Prompt
A short, unclear, broad, or unstructured instruction.
Example:
“Write a story.”

b. Basic Prompt
A structured, detailed, and refined instruction that gives context, constraints, and clear expectations.
Example:
“Write a 150-word motivational story about a student overcoming failure in exams.”

### 2. Prompt Pattern Activities

Below are the required transformations for each test scenario.
● Start with a Basic Prompt
Clear, refined instruction.
● Convert into a Zero-Shot Prompt
Model is asked to perform the task without guidance/examples.
● Create a Few-Shot Prompt
Provide at least 2 examples before giving the actual task.
● Rewrite into a Chain-of-Thought Prompt
Encourage step-by-step reasoning.

### 3. Selected Test Scenarios

We apply the above method to four different tasks:
Creative Story Generation
Factual Question Answering
Summarization
Advice / Recommendation

## SCENARIO 1: Creative Story Generation
Basic Prompt
Write a 150-word inspirational story about a student who overcomes fear and becomes confident through hard work.

Zero-Shot Prompt
Write an inspirational story about overcoming fear and gaining confidence.

Few-Shot Prompt
Example 1:
A girl afraid of public speaking joins a debate club and slowly becomes confident after practicing daily.
Example 2:
A student who struggled in maths improved dramatically by practicing every night for three months.

Task:
Write a 150-word inspirational story about a student overcoming fear and becoming confident through hard work.

Chain-of-Thought Prompt
Explain step by step how the story will be structured:
Identify the student and their fear.
Describe the initial struggles.
Show the effort made to improve.
End with how confidence was achieved.
Now write a 150-word story following your reasoning.

## SCENARIO 2: Factual Question Answering
Basic Prompt
Explain the working of a solar panel in simple terms, covering energy conversion and electricity generation.

Zero-Shot Prompt
How does a solar panel work?

Few-Shot Prompt
Example 1:
Wind turbines convert wind energy into electricity using rotating blades.
Example 2:
Hydroelectric dams generate electricity using falling water pressure.

Task:
Explain how solar panels work in simple terms.

Chain-of-Thought Prompt
Reason step-by-step:
What happens when sunlight hits a solar cell?
How is energy converted?
How does electricity flow?
Now explain the working of a solar panel in simple terms.

## SCENARIO 3: Summarization
Basic Prompt
Summarize the concept of Artificial Intelligence (AI) in 5–6 lines covering definition, purpose, and applications.

Zero-Shot Prompt
Summarize Artificial Intelligence.

Few-Shot Prompt
Example 1:
Summary of Machine Learning: “ML helps systems learn from data to make predictions and automate tasks.”
Example 2:
Summary of IoT: “IoT connects physical devices to the internet to exchange and collect data.”

Task:
Summarize Artificial Intelligence in 5–6 lines.

Chain-of-Thought Prompt
Explain step by step:
Define AI.
Mention its goal.
Mention how it works.
Provide examples.
Now write a 5–6 line summary of AI.

## SCENARIO 4: Advice / Recommendation
Basic Prompt
Provide study recommendations for a student preparing for an exam in 10 days with tips on time management, revision, and smart planning.

Zero-Shot Prompt
Give study tips.

Few-Shot Prompt
Example 1:
To lose weight: exercise regularly and maintain a calorie deficit.
Example 2:
To learn coding: practice daily and build small projects.

Task:
Give 10-day study strategy recommendations for exam preparation.

Chain-of-Thought Prompt
Think step by step:
Break the 10 days into phases.
Plan revision.
Suggest daily habits.
Now write a complete study plan.

## Experimental Results Table
| Scenario              | Naïve Prompt Output Quality     | Basic Prompt Output Quality    | Accuracy  | Depth       | Observations                              |
| --------------------- | ------------------------------- | ------------------------------ | --------- | ----------- | ----------------------------------------- |
| Creative Story        | Generic, short, lacks direction | Rich story, emotional detail   | Higher    | High        | Structure improves narrative richness     |
| Factual Question      | Partial explanation             | Correct scientific explanation | Very High | Medium-High | Basic prompt provides clarity of concepts |
| Summarization         | Too vague, incomplete           | Clear 5–6 lines, focused       | High      | High        | Better constraint handling                |
| Advice/Recommendation | Random tips                     | Organized 10-day plan          | Very High | High        | Structure greatly improves usefulness     |

## Evaluation Method Used : 

Rubric-based Evaluation
Each response was scored based on:
Quality (clarity, structure)
Accuracy (correctness of information)
Depth (detail and explanation richness)

## Analysis & Findings

✔ Basic prompts consistently improved output quality
They delivered more structured, informative, and accurate responses.

✔ Naïve prompts worked only for very simple tasks
(e.g., short story or general advice)

✔ Few-shot prompts improved pattern consistency
The model followed examples to maintain tone and style.

✔ Chain-of-thought prompts gave the deepest reasoning
Outputs became more logical and detailed.

## OUTPUT
All prompt patterns were applied, executed successfully, and documented.
A full comparative analysis is completed as per requirements.

## RESULT
The prompt for the above-said problem executed successfully, and a detailed comparative report was generated with all scenarios, evaluations, and findings.
