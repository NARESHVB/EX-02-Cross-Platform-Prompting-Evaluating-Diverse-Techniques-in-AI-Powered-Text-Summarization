# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization


## 🎯 AIM


The aim of this experiment is to evaluate and compare the effectiveness of different prompting techniques—namely zero-shot, few-shot, chain-of-thought, and role-based—across multiple AI platforms such as ChatGPT, Google Gemini, Anthropic Claude, and Microsoft Copilot in the task of text summarization. The experiment focuses on summarizing a 500-word technical article on "The Basics of Blockchain Technology" for an undergraduate audience. The goal is to determine which combination of prompting strategy and AI platform delivers the most accurate, coherent, and easily understandable summary in the shortest time, while also offering a smooth and user-friendly experience. This evaluation helps content curation teams identify the most suitable tools and prompt styles for producing high-quality educational summaries efficiently.

## 🧠 Prompting Techniques Overview

In this experiment, we explore four core prompting techniques—zero-shot, few-shot, chain-of-thought, and role-based—each representing a different level of guidance provided to the AI model. These techniques are crucial in shaping the behavior, tone, and output quality of large language models (LLMs). Understanding how they influence summarization outcomes helps in selecting the most effective strategy for a given audience and context.

### 1. Zero-shot Prompting
Description: The AI is given only a direct instruction without any examples or reasoning.

Example: “Summarize this article on blockchain technology for undergraduate students.”

#### Advantages:

Fast and simple to implement.

Useful for quick, one-off tasks.

Tests the model’s general understanding of the task.

#### Limitations:

Can result in vague, generic, or inconsistent summaries.

May struggle with adapting tone or simplifying technical content appropriately.

Use Case Fit: Best suited for general-purpose tasks or when time and simplicity are prioritized over precision.
---
### 2. Few-shot Prompting
Description: The AI is provided with a few examples (usually 1–3) of how a task should be performed before being asked to generate a new output.

Example: You might include 2 short blockchain summary examples followed by a new prompt.

#### Advantages:

Helps the model learn the desired style, format, and level of detail.

Greatly improves consistency and alignment with user expectations.

#### Limitations:

Requires careful crafting of relevant examples.

May be limited by input length constraints on some platforms.

Use Case Fit: Highly effective for educational or structured outputs, especially when a specific summary style is needed repeatedly.

### 3. Chain-of-Thought (CoT) Prompting
Description: This technique guides the AI to think step-by-step, simulating human reasoning before arriving at a conclusion.

Example: “First, identify the main topic. Then list key components. Finally, summarize the article for undergraduates.”

#### Advantages:

Improves logical flow and depth of understanding.

Encourages comprehensive breakdown of complex topics like blockchain.

Can reveal the reasoning path used by the model.

#### Limitations:

May increase response time.

Sometimes introduces unnecessary verbosity if not well-structured.

Use Case Fit: Ideal for technical or multi-layered content that benefits from being broken down into simpler concepts.

### 4. Role-based Prompting
Description: The AI is assigned a specific persona or role to take while performing the task.

Example: “You are a university professor explaining blockchain to first-year computer science students.”

#### Advantages:

Aligns the tone, language, and depth with the target audience.

Adds contextual framing, improving clarity and engagement.

Makes summaries more relatable and human-like.

#### Limitations:

Effectiveness depends on how clearly the role is defined.

May occasionally lead to overly informal or opinionated outputs if not well-controlled.

Use Case Fit: Perfect for audience-specific content, especially in education, healthcare, or business domains where tone and perspective matter.



## ⚙️ Algorithm (Procedure)

This outlines the systematic steps used to run the experiment:
Choose the article: A consistent, 500-word technical article on blockchain is selected for all tests to ensure fairness.
This section provides a detailed, systematic procedure to evaluate prompting techniques across multiple AI platforms. The aim is to ensure consistency, objectivity, and clarity in how the experiment is conducted so that the results are valid, comparable, and actionable.

### 1. Select and Prepare the Input Text
Choose a standardized article (~500 words) on a moderately technical topic — here, "The Basics of Blockchain Technology".

Ensure the content is balanced with definitions, processes, and real-world applications so that summary outputs can be evaluated for comprehension.

Remove unnecessary figures or references to avoid biasing the AI's response across platforms.

### 2. Design Prompt Variants
Create four distinct prompts for each technique:

Zero-shot

Few-shot

Chain-of-Thought (CoT)

Role-based

Ensure that prompt wording remains semantically equivalent across platforms, only adjusting syntax or formatting if the platform requires it (e.g., Markdown vs. plain text support).

Store these prompts in a prompt bank or table for reuse and documentation.

### 3. Choose the AI Platforms
Select widely-used, state-of-the-art AI tools for testing:

ChatGPT (OpenAI)

Claude (Anthropic)

Gemini (Google)

Microsoft Copilot (based on OpenAI tech)

Make sure all platforms are accessible, updated, and used under similar settings (e.g., temperature, context length if configurable).

### 4. Run the Experiment
Use each of the four prompts on each AI platform (total: 4 prompt types × 4 platforms = 16 combinations).

Paste the full article and the corresponding prompt into the platform.

Record the output, noting the time taken (from submission to full response).

If the platform limits input/output length, ensure the truncation is consistent across runs or adjust content accordingly.

### 5. Normalize the Outputs
Save each output using a consistent filename format (e.g., ChatGPT_Fewshot_Summary.txt).

Ensure all summaries are comparable in length, tone, and format where possible (though natural variations from prompting styles are expected).



1) Design prompts: Create one prompt for each technique—zero-shot, few-shot, CoT, and role-based.


2) Run on platforms: Use the same prompts on four platforms—ChatGPT, Claude, Gemini, and Copilot.


3) Set evaluation metrics: Define criteria such as accuracy, coherence, simplicity, speed, and user experience.


4) Generate and collect summaries: For each combination (platform + prompt), generate the summary and note down the response time.


5) Score each output: Have evaluators rate each summary using the pre-defined criteria on a scale (e.g., 1–5).


6) Analyze results: Tabulate and compare the scores to determine which combination is most effective.


Draw conclusions: Identify patterns and make recommendations based on the scores.



## 📊 Result Template (Example Format)

This table is used to record and compare the results across different combinations. It has:
Platform and Prompting Technique: Lists the tested combinations.



This format makes it easy to visually compare and identify top-performing methods.
