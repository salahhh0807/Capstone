# Project name: GE-Information Privacy Controls for Corporate Use of Public LLMs

- Columbia University: Shukai Wang, Shaonan Wang, Jiawen Song, Kaiyuan Liu, Longcong Xu

## General Electric (GE) mentor: Liang Tang

## Project Overview

1. **Objective**: Develop algorithms and mechanisms tailored for the corporate integration of publicly available LLMs like Llama2, with a focus on data privacy assurance.
2. **Key Dataset**: 2014 i2b2/UTHealth de-identification challenge dataset.
3. **Primary Goal**: Generate prompts to de-identify protected health information (PHI) compliant with the Health Insurance Portability and Accountability Act (HIPAA).

## Project Progress & Phases

### Initial Checkpoint:

1. **Environment Setup**:
   - Deployed Llama2 locally.
   - Tested on Google Colab and Google Cloud Platform (GCP) to decide on the best environment considering resource constraints.

2. **Prompt Exploration for De-identification**:
   - Extracted XML files from the 2014 i2b2 dataset.
   - Designed de-identification prompts for both Llama2 and ChatGPT models.
   - Applied prompts and generated masked text for each XML file.

3. **Performance Evaluation**:
   - Processed the generated masked texts.
   - Conducted a comparative analysis with pre-existing masked files to gauge the efficacy of Llama2 vs. ChatGPT.

### Upcoming Phases:

1. **Comparative Analysis**:
   - Comprehensive evaluation of Llama2 and ChatGPT using various metrics.

2. **Model Fine-tuning**:
   - Enhance Llama2 model for optimal performance.
   
3. **Transfer Learning**:
   - Experiment with the ASRS dataset.
   - Use either ChatGPT or the refined Llama2 model to fill in masked information.


## Acknowledgments

This project is made possible through the joint efforts of Columbia University and General Electric. We extend our gratitude to all members of the team involved.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Feedback & Contributions

We welcome feedback, bug reports, and pull requests. For major changes, please open an issue first to discuss what you would like to change.

---

