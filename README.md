## General Desc

The primary goal of this project is to explore the capabilities of Large Language Models (LLMs) for generating improved versions of argumentative texts. 
Specifically, this project focuses on the task of _inappropriateness mitigation_, i.e., rewriting arguments to make them more appropriate while preserving the original meaning. 

The key areas of exploration include:

- **Zero-shot Prompting:** Utilizing the LLM's pre-trained knowledge without providing any additional examples related to the task.
- **Few-shot Prompting:** Supplying a small number of examples to guide the LLM in generating improved texts.
- **Personas in Text Generation:** Experimenting with generating text from different perspectives or voices (personas) to see how it affects the output.



Large Language Models have revolutionized natural language processing by enabling sophisticated text generation, understanding, and transformation capabilities. 

This project leverages these capabilities to enhance inappropriate argumentative texts. The assignment involves working with the appropriateness corpus of [Ziegenbein et al. (2023)](https://aclanthology.org/2023.acl-long.238/). 

The provided dataset (`./data/dataset.csv`) includes fields such as `post_id`, `issue`, `post_text`, `fold0.0`, and annotations for various aspects of inappropriateness. 
Additionally, human rewrites from 5 different annotators are available in `./data/example_rewrites.csv`.
