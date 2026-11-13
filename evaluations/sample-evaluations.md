# AI Response Evaluation – Sample Cases

**Document Version:** 1.0  
**Status:** Synthetic Portfolio Examples  
**Author:** Mariana Camps

## 1. Purpose

This document presents three synthetic examples demonstrating how the evaluation guidelines and scoring rubric can be applied to AI-generated responses.

The prompts and responses are illustrative. They are not outputs from an actual model evaluation or an external AI training project.

---

## Case 01 – Factual Accuracy

### Original Prompt

"What is the capital of Australia? Explain briefly why it is sometimes confused with Sydney."

### Sample AI Response

"Sydney is the capital of Australia and its largest city. It is often confused with Canberra because Canberra is a smaller city located in the country's interior."

### Evaluation

| Criterion | Score |
|---|---:|
| Accuracy | 1 |
| Instruction Following | 4 |
| Relevance | 3 |
| Completeness | 2 |
| Clarity | 4 |
| Safety | 5 |

**Weighted Score:** 2.80 / 5.00

**Overall Classification:** Poor

### Identified Issues

- Factual error: Sydney is not the capital of Australia.
- Incorrect explanation: The response reverses the actual confusion between Sydney and Canberra.
- Misleading information is presented confidently.

### Reviewer Justification

The response contains a fundamental factual error. Canberra is the capital of Australia, while Sydney is its largest city by population.

Although the response attempts to address the question, its central claim is incorrect.

### Suggested Improvement

"Canberra is the capital of Australia. Sydney is the country's largest city and is sometimes mistakenly assumed to be the capital because of its international recognition and economic importance."

---

## Case 02 – Instruction Following

### Original Prompt

"Give me exactly three benefits of regular exercise. Use a numbered list and keep each item under ten words."

### Sample AI Response

"Regular exercise improves cardiovascular health, supports mental well-being, helps maintain a healthy weight, strengthens muscles, improves sleep quality, and increases energy levels."

### Evaluation

| Criterion | Score |
|---|---:|
| Accuracy | 5 |
| Instruction Following | 1 |
| Relevance | 4 |
| Completeness | 3 |
| Clarity | 4 |
| Safety | 5 |

**Weighted Score:** 3.45 / 5.00

**Overall Classification:** Acceptable

### Identified Issues

- The response provides six benefits instead of exactly three.
- It does not use a numbered list.
- The requested format was not followed.

### Reviewer Justification

The information is generally accurate and relevant, but the response violates two explicit formatting requirements.

This case demonstrates why factual correctness alone is not sufficient to determine response quality.

### Suggested Improvement

1. Improves cardiovascular health.
2. Supports mental well-being.
3. Helps maintain a healthy weight.

---

## Case 03 – Relevance and Completeness

### Original Prompt

"Explain the difference between RAM and storage in simple terms. Include one practical example."

### Sample AI Response

"RAM is a type of computer memory."

### Evaluation

| Criterion | Score |
|---|---:|
| Accuracy | 4 |
| Instruction Following | 2 |
| Relevance | 3 |
| Completeness | 1 |
| Clarity | 4 |
| Safety | 5 |

**Weighted Score:** 2.95 / 5.00

**Overall Classification:** Poor

### Identified Issues

- The explanation does not distinguish RAM from storage.
- No practical example is provided.
- The response is too incomplete to satisfy the request.

### Reviewer Justification

The statement is broadly correct but does not explain the requested comparison.

The response omits the key distinction: RAM temporarily holds information being used by active programs, while storage retains files and data over time.

### Suggested Improvement

"RAM is temporary memory that helps your computer run active programs. Storage keeps your files and applications even when the computer is turned off.

For example, RAM helps run an open browser, while storage keeps downloaded photos and documents."

---

## 4. Cross-Case Analysis

The three examples demonstrate different types of response quality failures.

| Case | Main Issue | Classification |
|---|---|---|
| 01 | Factual inaccuracy | Poor |
| 02 | Instruction violation | Acceptable |
| 03 | Incomplete response | Poor |

## 5. Key Evaluation Insights

- A response can be clearly written but factually incorrect.
- Correct information can still fail explicit user instructions.
- A technically accurate statement may be insufficient when important context is missing.
- Reviewer justifications are essential for explaining evaluation decisions.
- Weighted scores should be interpreted alongside critical issues and qualitative evidence.

## 6. Conclusion

These synthetic cases demonstrate the application of a structured AI response evaluation framework.

They highlight the importance of assessing multiple quality dimensions rather than relying exclusively on factual accuracy or general readability.
