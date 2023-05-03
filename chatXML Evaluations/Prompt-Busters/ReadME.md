# Prompt-Busting

I will rigorously analyze popular prompt engineering techniques using statistical methodology and open-source datasets from OpenAI and others. The goal is to determine which techniques are:

✅ **Confirmed** - Statistically shown to improve performance  
🌀 **Plausible** - Some evidence of improved performance but not statistically significant    
❌ **Busted** - No evidence of impact or may worsen performance  

**Prompt engineering** refers to crafting prompts to optimize model performance and coverage. The **"evals dataset"** is an open dataset from OpenAI and user contirbution that provides examples of topics and data types that models struggle with, allowing for fair technique comparisons.  

## Techniques to be tested include:   

- Use of emojis  🤓   
- Chain of thought structure   
- Exclamation points!   
- Word/phrase repetition 
- Reflexion

This analysis will account for **prompt latency** (time to generate), **API cost** (based on service pricing), and **prompt length** (number of tokens). Techniques may improve performance while reducing efficiency, and longer prompts provide more context but at higher latency and cost.
 
### Goals  

1. Provide empirical evidence for effective prompt engineering techniques based on rigorous statistical analysis  
2. Determine the optimal balance of performance, latency, and cost for different use cases  
3. Create an open-source repository of "evaluated" prompt engineering tips to turn an art into a science, benefitting both researchers and practitioners.    

I welcome additional prompt techniques to analyze and evaluate. Please let me know if you have any to suggest or want any clarification on this methodology and project overview. I aim to make this work as useful a resource as possible for optimizing prompt engineering.

I will also accept pull requests for additions to the series that follow the organization of the template and that I can replicate on my own machine.