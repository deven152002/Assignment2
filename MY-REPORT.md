![GenI-Banner](https://github.com/genilab-fau/genial-fau.github.io/blob/8f1a2d3523f879e1082918c7bba19553cb6e7212/images/geni-lab-banner.png?raw=true)

# Enhancing Automatic Prompt Engineering and Requirement Analysis Using AI

An advanced AI-driven approach to improving requirement analysis through iterative prompt optimization.
<!-- WHEN APPLICABLE, REMOVE THE COMMENT MARK AND COMPLETE
This is a response to the Assignment part of the COURSE.
-->

* Authors: [Deven Patel](http://www.YOURPAGE.xxx), [Preet chokshi](http://www.YOURPAGE.xxx), [Jeel sathwara](http://www.YOURPAGE.xxx)
* Academic Supervisor: [Dr. Fernando Koch](http://www.fernandokoch.me)

  
# Research Question 

How can AI-driven automatic prompt engineering improve the accuracy, clarity, and depth of requirement analysis?

## Arguments

#### What is already known about this topic

* AI can assist in requirement analysis but often lacks structured reasoning.

* Retrieval-Augmented Generation (RAG) enhances AI's contextual awareness.

* Reinforcement learning can be used to optimize AI-generated prompts iteratively.

#### What this research is exploring

<!-- Free-format; use the topics that are applicable to your exploration  -->

* We employ AI-driven iterative prompt engineering using AI-Critic feedback.

* We integrate Wikipedia-based retrieval for enhanced knowledge augmentation.

* We implement reinforcement learning techniques for self-improving prompt generation.

#### Implications for practice

<!-- Free-format; use the topics that are applicable to your exploration  -->

* AI-generated requirement analysis will be clearer, more detailed, and more accurate.

* Automated feedback mechanisms will improve AI responses without human intervention.

* The approach can be extended to other AI-driven text generation tasks.

# Research Method

Wikipedia-Based Retrieval-Augmented Requirement Analysis

Initial Implementation:

* Retrieved Wikipedia data for requirement analysis but lacked structured integration with AI responses.

* No caching mechanism, leading to redundant API calls.

* Basic AI model parameters without fine-tuning for requirement analysis.

Enhancements:

* Structured Integration: AI-generated responses now dynamically incorporate Wikipedia knowledge.

* Efficient Caching: Implemented lru_cache to improve response times.

* Optimized AI Parameters: Adjusted temperature, max tokens, and repetition penalties for more precise responses.

AI-Critic Feedback for Automatic Prompt Optimization

Initial Implementation:

* Basic evaluation of responses using word count and keyword matching.

* Static scoring with no iterative refinement.

* Limited adaptability—did not dynamically improve prompts over time.

Enhancements:

* Meta-Prompting for Structured Prompt Generation: AI generates a structured prompt for requirement analysis.

* Execution & Evaluation Loop: AI executes the prompt, evaluates the response, and suggests improvements.

* AI-Critic Feedback Mechanism: AI scores responses based on clarity, depth, and accuracy.

* Reinforcement Learning-Based Optimization: The best prompts and responses are stored, improving future iterations.

<!-- WHEN APPLICABLE AND AVAILABLE -->

# Results

* Enhanced Context Awareness: AI-generated responses are more informative and precise.

* More Intelligent Evaluations: AI now critiques and refines responses over multiple iterations.

* Adaptive Learning: AI dynamically adapts to previous performance, optimizing prompts over time.

# Further research

Future Techniques to Explore

1. Automatic Reasoning – AI-driven logical assessment for structured requirement analysis.

2. Active-Prompt – AI dynamically modifies prompts based on user interaction.

3. Directional Stimulus Prompting – AI conditions responses based on subtle cues.

4. Program-Aided Language Models (PALM) – AI integrates external tools for enhanced response generation.

5. ReAct & Reflexion – AI combines reasoning, action, and self-monitoring for self-improving prompt execution.

Next Steps

* Expand retrieval sources to domain-specific databases for improved relevance.

* Implement reinforcement learning to further optimize prompt selection.

* Test the system on real-world AI-driven requirement analysis tasks.

By integrating these techniques, AI-driven requirement analysis can become more precise, scalable, and self-improving for real-world applications.
