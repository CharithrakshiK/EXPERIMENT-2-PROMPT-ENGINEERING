# EX-02 – Cross-Platform Prompting: Evaluating Diverse Techniques in AI-Powered Text Summarization

## Aim

To evaluate and compare the effectiveness of different prompting strategies (zero-shot, few-shot, chain-of-thought, role-based) across multiple AI platforms (ChatGPT, Gemini, Claude, Copilot) for the task of summarizing text.

---

## Scenario

As part of a content curation team for an educational platform, the task was to generate **concise and accessible summaries** of research papers for undergraduate students. A 500-word technical article on *“The Basics of Blockchain Technology”* was chosen as the test input.

The objective was to determine which **platform + prompting technique** combination delivers the most effective summary, based on:

* **Accuracy**
* **Coherence**
* **Simplicity**
* **Speed**
* **User Experience (UX)**

---

## Algorithm

1. **Platform Selection** – Identify popular AI platforms for summarization: ChatGPT, Gemini, Claude, and Copilot.
2. **Prompting Strategies** – Define four prompting approaches: Zero-shot, Few-shot, Chain-of-thought, Role-based.
3. **Dataset Preparation** – Use a 500-word article on blockchain as the test document.
4. **Execution** – Apply each prompting strategy across all platforms to generate summaries.
5. **Data Collection** – Record outputs while noting generation speed and usability.
6. **Evaluation** – Rate summaries on Accuracy, Coherence, Simplicity, Speed, and UX (scale: 1–5).
7. **Comparison** – Tabulate results and analyze strengths/weaknesses of each combination.
8. **Conclusion** – Identify the most effective platform–prompting pair.

---

## Prompting Techniques

Prompting strategies influence how effectively AI models generate responses. Each technique interacts differently with the underlying model.

* **Zero-shot prompting** – Provides the task directly, without examples.
  *Example*: “Summarize the following article in 150 words for undergraduates.”

* **Few-shot prompting** – Supplies a few sample outputs first, guiding the model.
  *Example*: “Here are two summaries: \[A], \[B]. Now summarize this article.”

* **Chain-of-thought prompting** – Instructs the model to reason step by step before summarizing.
  *Example*: “Identify the key points → explain briefly → produce a summary.”

* **Role-based prompting** – Assigns a role or persona to tailor tone and complexity.
  *Example*: “You are a professor explaining blockchain to beginners. Summarize in 150 words.”

---

## Evaluation Criteria

Summaries were evaluated along five dimensions:

1. **Accuracy** – Coverage of blockchain fundamentals.
2. **Coherence** – Logical organization and readability.
3. **Simplicity** – Accessibility for undergraduate students.
4. **Speed** – Time taken to generate results.
5. **User Experience (UX)** – Presentation and ease of interpretation.

---

## Results

**Table 1 – Comparative Evaluation of Platforms & Prompting Styles**

| Platform | Prompt Style     | Accuracy (5) | Coherence (5) | Simplicity (5) | Speed (5) | UX (5) | Total (25) |
| -------- | ---------------- | ------------ | ------------- | -------------- | --------- | ------ | ---------- |
| ChatGPT  | Zero-shot        | 4            | 4             | 4              | 5         | 4      | 21         |
| ChatGPT  | Few-shot         | 5            | 5             | 4              | 4         | 5      | 23         |
| Gemini   | Role-based       | 4            | 4             | 5              | 4         | 5      | 22         |
| Claude   | Chain-of-thought | 5            | 5             | 4              | 3         | 4      | 21         |
| Copilot  | Zero-shot        | 3            | 3             | 3              | 5         | 3      | 17         |

---

## Discussion

The evaluation highlights the following insights:

* **ChatGPT Few-shot** achieved the highest overall score (23/25). Providing structured examples helped it produce **highly accurate and coherent** summaries.
* **Gemini Role-based** stood out in **simplicity (5/5)**, delivering beginner-friendly outputs ideal for undergraduate audiences.
* **Claude Chain-of-thought** performed strongly in **accuracy and coherence**, though response speed was slightly slower.
* **Copilot Zero-shot** was fast but lacked **depth and clarity**, making it less suitable for educational summaries.

These findings confirm that the **prompting strategy is as critical as the platform itself**. While ChatGPT offers the best balance overall, Gemini is more effective for introductory learners, and Claude is useful when deeper reasoning is required.

---

## Conclusion

The experiment demonstrates that **ChatGPT with Few-shot prompting** provides the most accurate, coherent, and balanced summaries, making it the strongest option overall. However, **Gemini with Role-based prompting** excels in simplicity, producing highly accessible content for undergraduates. Ultimately, the choice of platform and prompting method should depend on the target audience and task requirements.

---


