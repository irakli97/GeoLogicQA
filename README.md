# GeoLogicQA
# LLM Benchmark

This project evaluates the mathematical capabilities of several large language models (LLMs). The goal is to compare their performance on a custom set of logical problems to understand their strengths and weaknesses.

---

### Methodology

The benchmark consists of 100 questions covering various topics, including arithmetic, logic, and word problems. Each question was posed to four LLMs: Gemini, Grok, ChatGPT, and Deepseek.

An answer was considered **correct** only if it was an exact match to the expected solution.

### Sample Questions

Here are a few examples from the benchmark to illustrate the types of questions used. The results for each model on these specific problems are also included.

| Question | Answer | Gemini | Grok | ChatGPT | Deepseek |
|---|---|---|---|---|---|
| იპოვეთ 1 · 2 · 3 · 4 · 5 · 4 · 3 · 2 · 1 ნამრავლის ბოლო ორი ციფრის ჯამი | 8 | ✅ | ❌ | ❌ | ✅ |
| წრიული დიაგრამა გვიჩვენებს თუ რა საშუალებით დადიან მოსწავლეები სკოლაში. ცნობილია, რომ თითქმის ორჯერ მეტი მოსწავლე იყენებს ველოსიპედს, ვიდრე საზოგადოებრივ ტრანსპორტს. ასევე, მანქანით და ფეხით დაახლოებით ტოლი რაოდენობის მოსწავლეები დადიან. დანარჩენები იყენებენ მოპედს. რა პროცენტი იყენებს მოპედს? დიაგრამა დაყოფილია შემდეგნაირად: 47%, 11%, 6%, 12%, 24% | 6% | ❌ | ✅ | ❌ | ❌ |
| რისი ტოლია (1010^2 + 2020^2 + 3030^2)/2020 გამოსახულები მნიშვნელობა | 7070 | ✅ | ❌ | ✅ | ✅ |

---

### Evaluation Results

The table below summarizes the overall performance of each model on the 100-question benchmark.

| Model | Correct Answers | Answered Questions | Accuracy (%) |
|---|---|---|---|
| **Gemini** | 83 | 100 | **83.00%** |
| **Deepseek** | 74 | 100 | **74.00%** |
| **Grok** | 67 | 100 | **67.00%** |
| **ChatGPT** | 64 | 100 | **64.00%** |

---

### Conclusion

Based on this evaluation, **Gemini** achieved the highest accuracy, demonstrating a strong capability in mathematical problem-solving. This project provides a clear comparison of how these models perform on a specific set of challenges.
