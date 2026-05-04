# EXP-2-PROMPT-ENGINEERING-
# NAME: Charithrakshi K
# REG.NO: 212224040053
## Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

Experiment: Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. Analyze the quality, accuracy, and depth of the generated responses.

## ALGORITHM 

Common Scenario: A user wants to generate creative writing about a "mysterious old book."

## 1. Zero-Shot Prompting
### Description:
This is the simplest form of prompting, where the model is given a prompt without any examples or specific instructions beyond the core request. It relies entirely on the model's pre-trained knowledge to generate a response.

### Test Scenario:
"Write a short story about a mysterious old book."

### Algorithmic Output Aim:
A creative and coherent short story, potentially incorporating elements of suspense, discovery, or hidden knowledge, based on the model's understanding of "mysterious old book" and "short story."

## 2. Few-Shot Prompting

### Description: 
In this pattern, the model is provided with a few examples of input-output pairs before being given the actual prompt. This helps the model understand the desired format, style, or type of response.

### Test Scenario: 
"Example 1:

Input: "Describe a talking dog."

Output: "Barnaby, a scruffy terrier with an uncanny vocabulary, greeted me with a polite 'Good morning, chap!' and a wag of his tail. He then proceeded to explain the merits of chasing squirrels."

Now, write a short story about a mysterious old book."

### Algorithmic Output Aim:
A short story that mimics the descriptive and somewhat whimsical style of the provided examples, focusing on characterization and perhaps anthropomorphizing the book or its effects.

## 3. Chain-of-Thought (CoT) Prompting

### Description:
CoT prompting encourages the model to break down complex problems into intermediate steps, showing its reasoning process. This is particularly effective for tasks requiring logical deduction or multi-step problem-solving. While primarily for reasoning tasks, it can guide creative outputs towards a more structured narrative.

### Test Scenario: 
"Think step-by-step about how a mysterious old book would reveal its secrets in a short story. First, consider its appearance. Second, imagine the initial interaction. Third, what kind of secret would it hold? Finally, how does the protagonist discover it?

Now, write a short story about a mysterious old book."

### Algorithmic Output Aim: 
A more structured short story with a clear narrative arc, where the discovery of the book's secrets unfolds logically, following the outlined steps.

## 4. Role-Play Prompting

### Description:
This pattern assigns a specific persona or role to the AI, instructing it to generate content from that perspective. This can significantly alter the tone, vocabulary, and overall style of the output.

### Test Scenario:
"You are a seasoned antique dealer with a penchant for the arcane. Write a short story about your encounter with a mysterious old book."

### Algorithmic Output Aim:
A short story told from the perspective of an antique dealer, featuring specialized vocabulary (e.g., patina, provenance), a tone that suggests knowledge and perhaps a touch of skepticism, and an emphasis on the physical characteristics and history of the book.

## Output

## Zero-Shot Prompting 
<img width="500" height="500" alt="Gemini_Generated_Image_myjy4vmyjy4vmyjy1" src="https://github.com/user-attachments/assets/6e8eb670-330a-4cb4-abca-927aff1c12bd" />


## Few-Shot Prompting
<img width="500" height="500" alt="Gemini_Generated_Image_myjy4vmyjy4vmyjy 2" src="https://github.com/user-attachments/assets/5055c115-cdaa-4d9a-8834-f4baf4f47b92" />

## Chain-of-Thought (CoT) Prompting
<img width="500" height="500" alt="Gemini_Generated_Image_myjy4vmyjy4vmyjy3" src="https://github.com/user-attachments/assets/5f56daca-e1aa-4fd5-8d8b-88378a40784a" />


## Role-Play Prompting
<img width="500" height="500" alt="Gemini_Generated_Image_myjy4vmyjy4vmyjy 4" src="https://github.com/user-attachments/assets/ca929071-1131-46df-9b0e-86a43c633e86" />

## Result

Thus the Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios was created successfully.
