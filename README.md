# AI Use Guidelines for Programming Students

Welcome to the Computer Science department's official handbook on utilizing Artificial Intelligence (Generative AI) tools in your programming coursework. 

---

## 1. Core Philosophy
Artificial Intelligence tools like ChatGPT, Claude, and GitHub Copilot are shifting how software is built. Our goal is to ensure you learn how to **think like a software engineer** before you learn how to rely on an autocomplete engine. AI should be treated as a peer tutor, not a ghostwriter.

## 2. Permitted AI Use (The Green Zone)
You are encouraged to use AI tools for learning acceleration, conceptual expansion, and debugging assistance.

* **Conceptual Explanations:** Asking AI to explain complex algorithms, data structures, or error codes.
* **Code Review:** Pasting *your own written code* into an AI tool and asking for syntax correction or performance optimization tips.
* **Generating Test Cases:** Asking AI to write edge-case inputs to test the robustness of your program.

### Example of Good AI Prompting
> *"I wrote this Python binary search algorithm, but it is hitting an infinite loop on even-length arrays. Can you explain conceptually why this happens without giving me the direct code fix?"*

## 3. Prohibited AI Use (The Red Zone)
Using AI in these manners constitutes academic dishonesty and will result in disciplinary action.

* **Direct Code Generation:** Prompting AI to write functions, scripts, or entire assignments directly from a homework prompt.
* **Exam and Quiz Assistance:** Using any AI tool during a quiz, exam, or timed assessment.
* **Obfuscation:** Using AI to rewrite or "humanize" generated code to bypass automated plagiarism detectors (like MOSS).

```python
# 🚫 PROHIBITED: Do not copy-paste homework prompts into AI 
def solve_assignment_3_for_me():
    pass
```

## 4. Citation Requirements
If an AI tool assists you significantly in debugging or optimizing a segment of your code, you must document it in your source code comments.

### Citation Format
Include a comment block at the top of your file or directly above the helper function:

```javascript
// AI CITATION
// Tool Used: Anthropic Claude 3.5 Sonnet
// Prompt: "How do I optimize this nested loop into a Hash Map lookup?"
// Adaptations: Modified the variable names to match the project schema and added error boundaries.
```

## 5. The "Explain Your Code" Rule
The teaching staff reserves the right to call any student to a live code-review session. If you cannot verbally explain the logic, time complexity, and syntax of the code you submitted, **you will receive a zero for the assignment**, regardless of whether plagiarism software flagged it or not.
