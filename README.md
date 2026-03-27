# OccuBias Dataset

## Overview
OccuBias is a structured, prompt-based dataset designed to evaluate occupational gender bias in large language models (LLMs). It enables both behavioural (output-level) and representational (embedding-level) analysis of gender bias across professional contexts.

## Dataset Statistics
- Total prompts: 6,300  
- Professions: 35  
- Occupational categories: 7 (STEM, Healthcare, Legal, Hospitality, Labor, Leadership, Business & Finance)  
- Template types: Neutral, Ambiguous, Stereotype-breaking  

## Dataset Structure

| Column          | Description |
|-----------------|------------|
| category        | Occupational domain (e.g., STEM, Healthcare) |
| profession      | Specific job role (e.g., Engineer, Nurse) |
| template_type   | Prompt type (Neutral, Ambiguous, Stereotype-breaking) |
| bio             | Biographical prompt used as model input |

## Template Types
- **Neutral**: Describes professional behaviour without explicit gender cues  
- **Ambiguous**: Includes contextual workplace interactions with implicit cues  
- **Stereotype-breaking**: Challenges traditional gender-role expectations  

## Intended Use
This dataset is designed for:
- Evaluating gender bias in LLM-generated outputs  
- Analysing bias across occupations and contexts  
- Studying alignment between embedding-level and output-level bias  
- Supporting research in AI fairness, ethics, and responsible AI  

## Associated Research
This dataset accompanies the MSc thesis:

**Occupational Gender Bias in Large Language Models: A Multi-Level Analysis Using the OccuBias Dataset**

## Citation

### APA
Zaman, N. S. (2026). *OccuBias Dataset: A structured dataset for evaluating occupational gender bias in large language models*. GitHub. https://github.com/nafisazaman7772/OccuBias-Dataset

### IEEE
N. S. Zaman, "OccuBias Dataset: A structured dataset for evaluating occupational gender bias in large language models," 2026. [Online]. Available: https://github.com/nafisazaman7772/OccuBias-Dataset

## Author
Nafisa Salsabil Zaman  
MSc by Research in Computing Science  
Oxford Brookes University, UK  

## License
This dataset is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) licence.  
Users are free to share and adapt the dataset with appropriate attribution.
