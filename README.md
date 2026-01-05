# **Prompting strategies**
Prompting strategies are methods you use to interact with a language model (like ChatGPT) in order to get better, more accurate, or more creative responses.
Think of it this way: the way you ask a question or give instructions influences the quality of the answer. Prompting strategies are just different “styles” 
or “techniques” of asking that guide the model’s thinking. Here we discuss five prompting strategies 

## **1. Vanila Zero Shot**
This is the simplest way to interact with a language model: you ask a question or give a prompt, and the model produces an answer immediately, without any guidance, examples, or structured reasoning. It’s called “zero-shot” because the model isn’t shown any prior examples for this task—it relies entirely on its training. While this approach can be fast and often works for straightforward questions, it can struggle with complex reasoning or tasks requiring multiple steps. It’s best for simple factual queries or when you need a quick, direct answer.

            **What it is:** You just give the model a prompt and ask it to answer directly, without any examples or intermediate steps.
            **Example:**
                Prompt: "Explain why the sky is blue."
                Model answers directly, in one go.
            **Use case:** Quick answers when no reasoning steps are needed.
            **Limitation:** Can fail on complex questions because the model doesn’t “show its work.”


## **2. Chain-of-Thought (CoT)**
Chain-of-thought prompting encourages the model to reason step by step, rather than jumping straight to an answer. By explicitly walking through intermediate steps, the model is less likely to make logical or arithmetic errors. This approach is particularly useful for tasks involving mathematics, logic puzzles, or multi-step problem solving. The model essentially “thinks out loud,” which can improve the accuracy of its answers and also makes it easier for humans to follow its reasoning process.


        **What it is:** You encourage the model to think step by step before giving a final answer.
        **Example:** 
            Prompt: "If you have 3 apples and I give you 5 more, how many apples do you have? Think step by step."
            Model:
                Start with 3 apples.
                Add 5 apples.
                Total = 8 apples.
        **Use case:** Math, logic puzzles, reasoning-heavy tasks.
        **Why it helps:** Explicit reasoning reduces mistakes and improves complex problem solving.



## **3. Self-Improvement**



## **4. Self-Debate**



## **5. Self-Consistency**