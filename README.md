# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization


🎯 AIM

The primary aim of this experiment is to evaluate and compare how different prompting strategies perform across major AI platforms when summarizing a moderately technical article. Specifically, it seeks to find out which combination of AI platform and prompt style produces the most accurate, coherent, simple, and user-friendly summary of a 500-word article on "The Basics of Blockchain Technology." This will help determine the most effective setup for content curation teams aiming to deliver quick, digestible educational material to undergraduate students.

🧠 Prompting Techniques Overview

This section introduces the four different prompt strategies that guide how an AI generates responses:
Zero-shot: The AI is simply asked to perform the task without any examples. It tests the model’s general understanding of instructions.


Few-shot: The AI is given 1–3 examples of what kind of input/output is expected. This helps the model understand the pattern or style needed.


Chain-of-thought (CoT): The prompt instructs the AI to reason step-by-step before giving a final summary. This is especially useful for complex or technical material that requires logical structuring.


Role-based: The prompt assigns the AI a specific role (e.g., "You are a college professor explaining to first-year students"). This frames the response in a more tailored, audience-appropriate way.


Each of these techniques may guide the model’s behavior differently, and their effectiveness can vary depending on the platform.

⚙️ Algorithm (Procedure)

This outlines the systematic steps used to run the experiment:
Choose the article: A consistent, 500-word technical article on blockchain is selected for all tests to ensure fairness.


Design prompts: Create one prompt for each technique—zero-shot, few-shot, CoT, and role-based.


Run on platforms: Use the same prompts on four platforms—ChatGPT, Claude, Gemini, and Copilot.


Set evaluation metrics: Define criteria such as accuracy, coherence, simplicity, speed, and user experience.


Generate and collect summaries: For each combination (platform + prompt), generate the summary and note down the response time.


Score each output: Have evaluators rate each summary using the pre-defined criteria on a scale (e.g., 1–5).


Analyze results: Tabulate and compare the scores to determine which combination is most effective.


Draw conclusions: Identify patterns and make recommendations based on the scores.



📊 Result Template (Example Format)

This table is used to record and compare the results across different combinations. It has:
Platform and Prompting Technique: Lists the tested combinations.



This format makes it easy to visually compare and identify top-performing methods.
