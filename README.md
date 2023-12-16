#  Project name: GE-Information Privacy Controls for Corporate Use of Public LLMs

## Group Members

- Jiawen Song (js6123)
- Kaiyuan Liu (kl3447)
- Longcong Xu (lx2305)
- Shaonan Wang (sw3720)
- Shukai Wang (sw3715)
  
Emails <UNI> @ columbia.edu

## General Electric (GE) Mentor & Co-Mentors

- Dr. Bhushan
- Surajit Sen
- Priyanka Pandey

## Instructor/CA

- Sining Chen (sc4549) (Project main)
- Jiaxuan Li (jl6300) Head CA, assisting SC
- Vivian Zhang (Project)
- Peter Chao (jc5859) assisting VZ
- Adam Kelleher (Project)
- Rufina George (rg3466) assisting AK, ST
- Savannah Thais (AI Ethics)

## Project Description

This Capstone project represents a collaborative effort between the Data Science Institute at Columbia University and General Electric (GE). The central aim of this project is to develop an Information Privacy Control mechanism in response to the concerns of exposing private data while using public online Large Language Models (LLM) in corporate settings. This initiative addresses this critical problem of how to maintain data privacy and security while applying public LLM in compliance with corporate policies by anonymizing private information from input data. Given the existing constraints of conventional privacy techniques and the distinctive risks of using public LLM within corporations, we were motivated to use and finetune GPT and Llama2 models to aid corporations to de-identify before applying LLMs for the protection and assurance of data privacy.

In this project, the primary focus of our team centers on the utilization of the Llama2 and GPT models within the framework of the 2014 i2b2/UTHealth de-identification challenge dataset. Our aim is to develop suitable prompts that effectively remove protected health information (PHI), adhering to the standards set by the Health Insurance Portability and Accountability Act (HIPAA). The subsequent phases involve the refinement and optimization of GPT to enhance its efficacy. Furthermore, we have engaged in transfer learning, applying the Llama2 model to the Aviation Safety Reporting System (ASRS) dataset after manually restoring the masked information, which encompasses aviation safety narratives. 

Our comprehensive comparative analysis of the performance of Llama2 and GPT on both datasets has yielded significant insights, with the fine-tuned ChatGPT-3.5 emerging as the superior performer. This finding underscores the impactful role of both the prompts and the model itself in determining performance outcomes. These elements warrant further exploration in future research, highlighting the meaningful contributions of our work to ongoing advancements in the field.

## Directory Tree










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

