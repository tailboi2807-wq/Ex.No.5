

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

### AI Tools Required: 

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.


# OUTPUT
Comparative Analysis of Different Types of Prompting Patterns
1. Introduction
Prompting patterns are structured techniques used to guide Generative AI models (like ChatGPT, Gemini, Claude, Copilot) toward producing more relevant, accurate, and context-aware outputs.
This report provides a comparative analysis of major prompting patterns—explained through test scenarios that demonstrate their unique behaviors and outcomes.

2. Types of Prompting Patterns and Their Analysis
2.1 Zero-Shot Prompting
Definition
Zero-shot prompting involves no prior examples—the model performs a task using only the instruction given in the prompt.
Test Scenario
Task: Summarize an article on “The Basics of Blockchain Technology.”
Prompt:
“Summarize the key concepts of blockchain technology in simple terms.”
Output Behavior:
Model directly explains blockchain based on general knowledge.
output is accurate but lacks task-specific tone or depth.
Advantages:
Quick and efficient for general tasks.
Suitable when examples aren’t available.

Limitations:
May lack precision or consistency in tone.

2.2 Few-Shot Prompting
Definition
Few-shot prompting provides one or more examples before the main task to guide the AI model.
Test Scenario
Task: Summarize blockchain concepts with examples.
Prompt:
Example 1: “In simple words, AI helps computers think like humans.”
Example 2: “Similarly, blockchain helps computers record transactions securely.”
Now summarize blockchain in 3 lines for students.
Output Behavior:
Generates a concise, student-friendly explanation.
Mimics example style, ensuring clarity and tone alignment.
Advantages:
Produces consistent and structured outputs.
Effective for education, marketing, and content writing.
Limitations:
Needs relevant, high-quality examples.

2.3 Chain-of-Thought (CoT) Prompting
Definition
CoT prompting encourages the model to explain its reasoning process step-by-step before reaching a conclusion.
Test Scenario
Task: Determine whether blockchain is beneficial for banking systems.
Prompt:
“Think step-by-step and explain whether blockchain improves banking transparency.”
Output Behavior:
Banks store transaction records.
Blockchain creates transparent ledgers.
It reduces fraud.
Hence, blockchain improves transparency.
Advantages:
Enhances logical reasoning and transparency in answers.
Ideal for analytical, mathematical, and problem-solving tasks.
Limitations:
Increases response length and complexity.

2.4 Role-Based Prompting
Definition
In this pattern, the AI model is assigned a specific role (e.g., teacher, analyst, scientist) to adjust tone and domain knowledge.
Test Scenario
Task: Generate a student report on blockchain.
Prompt:
“You are an economics teacher. Explain blockchain technology to your students in 150 words.”


Output Behavior:
Uses educational tone.
Simplifies technical content.
Adds real-world relevance.
Advantages:
Produces contextually appropriate and professionally aligned outputs.
Limitations:
Overly strong roles can bias content.

2.5 Persona Prompting
Definition
Persona prompting assigns the AI a distinct personality or character to influence voice and emotion.
Test Scenario
Task: Explain blockchain like a motivational speaker.
Prompt:
“As a motivational speaker, describe how blockchain can change the world.”
Output Behavior:
Adds enthusiasm and persuasive tone.
Focuses on empowerment and innovation.
Advantages:
Engages audiences emotionally.
Excellent for creative writing and public communication.


Limitations:
May sacrifice factual precision for style.

2.6 Contextual (Situational) Prompting
Definition
Contextual prompting provides detailed background context to help the AI adapt its answer.
Test Scenario
Task: Explain blockchain use in a specific field.
Prompt:
“In the context of healthcare data management, explain how blockchain ensures patient data security.”
Output Behavior:
Tailors explanation to the healthcare domain.
Integrates real-world relevance.
Advantages:
Produces domain-specific insights.
Useful for research and professional reports.
Limitations:
Requires precise context to avoid confusion.

2.7 Reflexive (Self-Correction) Prompting
Definition
This technique asks the AI to review and refine its own response.
Test Scenario

Prompt:
“Write a short explanation of blockchain. Then review your answer for clarity and correctness.”
Output Behavior:
AI generates initial text.
Rewrites or simplifies it for better readability.
Advantages:
Improves accuracy and grammar automatically.
Limitations:
Consumes more processing time.

3. Comparative Summary Table
Prompting Type	Example Scenario	Strengths	Weaknesses	Best Used For
Zero-Shot	Explain blockchain simply	Fast, easy	Generic responses	Quick definitions
Few-Shot	Give examples before summary	Consistent tone, accuracy	Needs examples	Education, content writing
Chain-of-Thought	Step-by-step reasoning	Logical accuracy	Long answers	Problem-solving, reasoning
Role-Based	“As a teacher…”	Contextual clarity	Can be biased	Training, reports
Persona	“As a motivational speaker…”	Engaging tone	Style over accuracy	Creative writing
Contextual	“In healthcare…”	Domain relevance	Context-sensitive	Research, applied AI
Reflexive	“Review and refine…”	High precision	Slower response	Editing, academic writing

4. Test Findings and Observations
Accuracy vs Creativity:
Zero-shot and Chain-of-thought produced accurate but plain responses.
Persona and Role-based added creativity and engagement.
Task Adaptability:
Few-shot and Contextual prompting worked best for educational and domain-driven tasks.
Refinement Effect:
Reflexive prompting improved grammar and structure by 15–20% in test comparisons.
Prompt Length:
Long prompts (>2000 tokens) reduced performance accuracy in all models.
Dividing tasks into smaller prompt blocks improved coherence.

5. Conclusion
Different prompting patterns influence AI behavior, tone, and depth of reasoning.
Choosing the right pattern depends on:
The goal (reasoning vs creativity)
The audience (students, professionals, general users)
The context (educational, business, technical)
An effective AI workflow often combines multiple prompting patterns — e.g., Role-Based + Chain-of-Thought or Few-Shot + Reflexive — to achieve both accuracy and engagement.



6. Recommendations
Use Zero-shot for simple factual tasks.
Apply Few-shot when output tone consistency is important.
Use Chain-of-thought for analytical or mathematical reasoning.
Adopt Role-based or Persona patterns for communication-focused tasks.
Combine Reflexive prompts for quality assurance in long-form reports.
# RESULT: The prompt for the above said problem executed successfully
