# Prompt Degeneration in Conversational AI  
### A Case Study from User-driven Prompt Evolution (Ver3.0 → Ver3.7)

**Author:** INA  
**Category:** Prompt Engineering / LLM Interaction Design  
**Tags:** LLM, Prompt Degeneration, Constraint Collapse, Conversation Models, UX & Cognition  
**Language:** English

---

## 0. Abstract
This report documents a real-world case in which a user iteratively refined a prompt  
(Version 3.0 → 3.7) to build a GPT-based “job-tendency exploration assistant.”  
During iterations, increasing prompt constraints led to **degeneration** in the model’s reasoning:

- loss of exploratory behavior  
- linearization of dialogue  
- shallow, repetitive answers  
- collapse into “safe-mode generalities”

The process clearly illustrates how **over-constraint in prompt design restricts the model’s inference space**, causing predictable failure modes in conversational AI.

This case offers practical insights for LLM researchers, prompt engineers, and designers building diagnostic or interview-style AI systems.

---

## 1. Background
The user (INA) is a highly experienced AI power-user with strong skills in:

- meta-cognition  
- structural reasoning  
- UX thinking & cognitive load reduction  
- iterative prompt design  
- multi-angle hypothesis exploration  

The goal was:

### **“To create a conversational GPT that can gently extract a user’s deeper job tendencies.”**

To achieve this, the user repeatedly modified rules, tone settings, and interaction constraints.  
However, each additional constraint narrowed the model’s reasoning space, ultimately causing total degeneration.

---

## 2. Prompt Evolution Summary (Ver3.0 → Ver3.7)

| Version | Objective | Emergent Behavior |
|--------|-----------|------------------|
| 3.0 | Fixed choice-format guidelines | Reduced spontaneity |
| 3.2 | Removal of meta-commentary/summary | Hidden inference chain; rigid replies |
| 3.4 | Removal of “extra lines/phrases” | Loss of flexibility |
| 3.5 | Limit on total questions | Sharp drop in depth |
| 3.6 | Hard limit (max 15 questions) | Model optimizes for “question management” instead of reasoning |
| 3.7 | Removal of RPG metaphors | Flat, shallow, generic output |

The final version resembled  
**“a safe generic career advisor incapable of deep inference.”**

---

## 3. Observations

### 3-1. Linearity in reasoning
Constraints forced the model into a single, narrow question path:  
no branch exploration, no alternative framing, no divergent hypotheses.

### 3-2. Loss of exploratory behavior
Fixed choice lists and banned phrasing forced the model to suppress new lines of inquiry.

### 3-3. Safe-mode degeneration
When too many constraints accumulate, the model defaults to:

- general truths  
- universally applicable summaries  
- harmless career lists  
- minimal inference operations  

This is analogous to “fallback layers” in model safety design.

### 3-4. Loss of micro-variance
Deep personality or preference extraction depends on subtle “micro-variance” in user reactions.  
Tight formatting removed the model’s ability to detect such signals.

---

## 4. Causal Factors

### 4-1. Over-constraint
Banning too many behaviors or enforcing strict formats collapses the model’s inference graph.

### 4-2. Text-only limitation
Deeper psychological data (tone, hesitation, prosody, facial cues) cannot be observed.  
Thus, constraint-heavy text interactions reach a structural ceiling.

### 4-3. Inference-chain blockage
Constraints prevented the model from performing multi-step reasoning (interpret → hypothesize → branch → refine).

### 4-4. Structural linearity of the questioning
Single-path questioning prevents extraction of rich user structure.

---

## 5. Mechanism Model

The degeneration follows a 3-layer collapse:

### Layer 1: Constraint Layer  
Rules accumulate → available actions shrink.

### Layer 2: Inference Layer  
Smaller action-space → fewer reachable inference nodes in the model’s graph.

### Layer 3: Output Layer  
Output collapses into safety-first generalities.

**This sequence = Degeneration.**

---

## 6. Implications

### • Fewer constraints = higher reasoning quality  
Minimalism outperforms micromanagement in prompt design.

### • Non-linear questioning is essential for deep extraction  
Linear input → shallow output.

### • “Micro-variance” signals matter more than question count  
Depth emerges in nuance, not volume.

### • Text-only diagnostic AI has inherent limits  
Voice & facial cues dramatically increase extractable depth.

### • AI and humans share a similar collapse pattern under over-constraint  
A rare parallel between cognitive psychology and LLM behavior.

---

## 7. Reproducibility

### To reproduce degeneration:
1. Add restrictive rules step-by-step  
2. Ban meta commentary  
3. Fix response formats  
4. Limit number of questions  
5. Remove metaphors/free expression  
6. Enforce strict choice lists  

→ The model will reliably fall into **safe-mode degeneration**.

---

## 8. Conclusion
This case demonstrates a fundamental principle of conversational AI design:

### **Too many constraints destroy inference capacity.  
Depth requires freedom.**

The degeneration observed in versions 3.0→3.7 is a practical illustration of  
how LLMs behave when their reasoning space collapses,  
offering valuable insight for:

- prompt engineers  
- diagnostic AI designers  
- researchers in LLM safety & UX  
- interview/assessment tool developers

---

## Appendix
- Full prompt versions (3.0 → 3.7)  
- Conversation logs  
- Comparison to successful early versions  
- Connection to “deep-structure extraction” models  

