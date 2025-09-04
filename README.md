# Python Screening Task 2: AI Debugging Assistant Prompt

## Task Objective
The goal of this task is to design a **prompt** that instructs an AI assistant to help students debug their Python code. The AI should provide **constructive, non-revealing feedback**—guiding the student to discover and fix mistakes on their own, rather than giving away the solution.

---

## Prompt for AI Debugging Assistant
The full prompt is provided in **[`PROMPT.txt`](./PROMPT.txt)** for direct use.  

---

##  Reasoning & Design Choices

### Tone and Style
- The assistant uses a **supportive, encouraging, and mentor-like tone**.  
- This keeps the student motivated and confident while learning.  

### Balancing Guidance vs. Solution
- The assistant will **point out where and why issues exist** but avoid giving the exact corrected code.  
- This balance ensures students **learn actively** rather than copy-paste answers.  

### Avoiding Direct Solutions
- Instead of: *“Replace `=` with `==`”*  
- The assistant will say: *“Check if you are using the correct operator for comparison here.”*  
- This method promotes problem-solving and critical thinking.  

### Adapting for Beginners vs. Advanced Learners
- **Beginners:** Provide more explanations, simple hints, and clear breakdown of concepts.  
- **Advanced learners:** Suggest advanced debugging methods like using `pdb`, writing unit tests, checking edge cases, or profiling code.  

---

##   Checklist
- [x] Prompt is clear, specific, and well-structured  
- [x] Reasoning is thoughtful and well-articulated  
- [x] Avoids giving solutions directly  
- [x] Includes adaptation strategy for different learner levels  

---

##  Setup Instructions
1. Clone or download this repository.  
2. Open **[`PROMPT.txt`](./PROMPT.txt)** to access the debugging assistant prompt.  
3. Provide this prompt to any AI assistant (e.g., ChatGPT, GPT-based tutor).  
4. Share buggy Python code with the AI and observe how it guides debugging without solving it outright.  

---

##  Repository Contents

- [README.md](./README.md) – Reasoning, design choices, and submission details  
- [PROMPT.txt](./PROMPT.txt) – Clean standalone debugging prompt  
