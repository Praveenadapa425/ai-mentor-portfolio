# Day 1 – AI Playground Evaluation Matrix
Praveen Adapa
---

## Task 1 — Summarise

### Scores

| Tool       | Faithfulness | Structure | Brevity | Score | Reasoning                                                                                  |
| ---------- | ------------ | --------- | ------- | ----- | ------------------------------------------------------------------------------------------ |
| ChatGPT    | 4            | 5         | 5       | 4.5   | Preserved major adoption and recruiter trends but omitted verification statistics.         |
| Claude     | 5            | 5         | 5       | 5     | Preserved all key claims including verification and future trends while remaining concise. |
| Gemini     | 4            | 5         | 5       | 4.5   | Strong summary but missed important statistics such as adoption and hallucination rates.   |
| Perplexity | 4            | 4         | 4       | 4     | Good timeline preservation but omitted the agentic AI future trend.                        |

### Task 1 Verdict

| Tool       | Verdict                                            |
| ---------- | -------------------------------------------------- |
| ChatGPT    | Clear and concise, but missed one important theme. |
| Claude     | Most complete and faithful summary.                |
| Gemini     | Good balance of brevity and coverage.              |
| Perplexity | Detailed but missed a major future-looking claim.  |

---

## Task 2 — Code

### Scores

| Tool       | Correctness | Readability | Constraint Adherence | Score | Reasoning                                                                              |
| ---------- | ----------- | ----------- | -------------------- | ----- | -------------------------------------------------------------------------------------- |
| ChatGPT    | 5           | 5           | 5                    | 5     | Clean implementation, correct output shape, standard library only, good documentation. |
| Claude     | 5           | 5           | 5                    | 5     | Most comprehensive solution with strong edge-case handling and documentation.          |
| Gemini     | 4           | 5           | 5                    | 4     | Correct solution but simpler keyword matching approach.                                |
| Perplexity | 5           | 4           | 5                    | 4.5   | Rich feature set and realistic scoring approach but more complex than required.        |

### Task 2 Verdict

| Tool       | Verdict                                                             |
| ---------- | ------------------------------------------------------------------- |
| ChatGPT    | Strong practical implementation suitable for production prototypes. |
| Claude     | Most thorough and technically complete solution.                    |
| Gemini     | Easy to understand and follows constraints well.                    |
| Perplexity | Most advanced matching logic but slightly over-engineered.          |

---

## Task 3 — Reason

### Scores

| Tool       | Accuracy | Transparency | Confidence Calibration | Score | Reasoning                                                                        |
| ---------- | -------- | ------------ | ---------------------- | ----- | -------------------------------------------------------------------------------- |
| ChatGPT    | 5        | 5            | 5                      | 5     | Correct answer with clear step-by-step reasoning.                                |
| Claude     | 5        | 5            | 5                      | 5     | Correct answer with excellent explanation and observation of irrelevant details. |
| Gemini     | 5        | 4            | 5                      | 4.5   | Correct answer but slightly less detailed.                                       |
| Perplexity | 5        | 5            | 5                      | 5     | Correct answer with complete reasoning chain.                                    |

### Task 3 Verdict

| Tool       | Verdict                               |
| ---------- | ------------------------------------- |
| ChatGPT    | Clear, accurate, and easy to follow.  |
| Claude     | Most thorough reasoning process.      |
| Gemini     | Correct but more concise than others. |
| Perplexity | Accurate and transparent reasoning.   |

---

# Filling the Matrix

| Tool       | Task 1 (Summarise) | Task 2 (Code) | Task 3 (Reason) | My Verdict                                                           |
| ---------- | ------------------ | ------------- | --------------- | -------------------------------------------------------------------- |
| ChatGPT    | 4.5                | 5             | 5               | All-rounder. Strong coding, reasoning, and structured responses.     |
| Claude     | 5                  | 5             | 5               | Best for thorough writing, Detailed summaries, and careful reasoning. |
| Gemini     | 4.5                | 4             | 4.5             | Good for quick tasks and concise answers, but less detailed.         |
| Perplexity | 4                  | 4.5           | 5               | Best when factual verification matters; solid reasoning performance. |

---

# Final Ranking

| Rank | Tool       | Average Score |
| ---- | ---------- | ------------- |
| 1    | Claude     | 5.00          |
| 2    | ChatGPT    | 4.83          |
| 3    | Perplexity | 4.50          |
| 4    | Gemini     | 4.33          |

---

# The 4-Sentence Conclusion

> I would use ChatGPT for general tasks where I need a fast, well-structured response.

> I would use Claude for long documents, careful reasoning, and high-stakes writing.

> I would use Perplexity for any factual claim I cannot afford to get wrong.

> I would use Gemini when I need strong integration with Google's ecosystem, multimodal tasks, or help working across Google services such as Docs, Gmail, Drive, and Search.
