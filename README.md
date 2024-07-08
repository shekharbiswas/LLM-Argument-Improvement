## General Desc

The primary goal of this project is to explore the capabilities of Large Language Models (LLMs) for generating improved versions of argumentative texts. 
Specifically, this project focuses on the task of _inappropriateness mitigation_, i.e., rewriting arguments to make them more appropriate while preserving the original meaning. 

The key areas of exploration include:

- **Zero-shot Prompting:** Utilizing the LLM's pre-trained knowledge without providing any additional examples related to the task.
- **Few-shot Prompting:** Supplying a small number of examples to guide the LLM in generating improved texts.
- **Personas in Text Generation:** Experimenting with generating text from different perspectives or voices (personas) to see how it affects the output.



Large Language Models have revolutionized natural language processing by enabling sophisticated text generation, understanding, and transformation capabilities. 

This project leverages these capabilities to enhance inappropriate argumentative texts.

1. **Checkpoint 1: Select Automatic Evaluation Metrics**
   - Implement two automatic evaluation metrics that capture task-specific characteristics.
   - Use these metrics to compare the results of different prompting techniques in subsequent checkpoints.
   - Explain why the chosen metrics are helpful and how they relate to the task.

2. **Checkpoint 2: Zero-shot Prompting**
   - Generate improved versions of arguments using zero-shot prompting.
   - Save predictions for the test set at `outputs/zero_shot.json` including `post_id`, `post_text`, `improved_text`.
   - Experiment with different prompts and determine the best one using the evaluation metrics.

3. **Checkpoint 3: Few-shot Prompting**
   - Explore few-shot prompting using examples from `./data/dataset/example_rewrites`.
   - Optionally, use your own rewrites of arguments.
   - Save predictions for the test set at `outputs/few_shot.json` including `post_id`, `post_text`, `improved_text`.
   - Evaluate the approach using the evaluation metrics from Checkpoint 1.

4. **Checkpoint 4: Persona-based Generation**
   - Generate improved versions of arguments using zero-shot prompting with different personas.
   - Save predictions for the test set at `outputs/persona.json` including `claim_id`, `original_text`, `improved_text`.
   - Experiment with different personas and determine the best one using the evaluation metrics.
   - Improve upon the baseline scores obtained in Checkpoint 2.

5. **Checkpoint 5: Evaluation Summary**
   - Compare the approaches from previous checkpoints and discuss findings.

