# Prompt Rewriting: An LLM Project

## Project Description
<p align='justify'>Large Language Models (LLMs) often struggle with user inputs that are ambiguous, underspecified, or ill-structured, leading to suboptimal outputs.</p>
<p align='justify'>This project investigates whether having an LLM **rewrite a given input prompt** into a clearer, more detailed prompt can improve the quality of the final response.</p>

### Approach
1. An auxiliary LLM first rephrases or elaborates the user’s query.  
2. The rewritten prompt is then passed to the main LLM to generate the final answer.  

We hypothesize that this intermediate **prompt rewriting step** helps:
- Expose hidden assumptions  
- Add necessary detail  
- Improve accuracy and usefulness of responses (especially for complex reasoning tasks)  

<p align='justify'>Our experiments compare outputs **with and without prompt rewriting** across multiple models and benchmarks.</p>
<p align='justify'>We also design **automatic metrics** and conduct **human evaluation** to assess improvements in output quality.</p>


<p align='justify'>If successful, this project could introduce a new **prompt-engineering strategy** for boosting LLM performance without retraining the main model.</p>

---

## Latest Files
- Report: `LLM_final_report.pdf`  
- Code: `GRPO.ipynb`
