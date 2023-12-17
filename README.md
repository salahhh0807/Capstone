#  Project name: GE-Information Privacy Controls for Corporate Use of Public LLMs

## Group Members

- Jiawen Song (js6123)
- Kaiyuan Liu (kl3447)
- Longcong Xu (lx2305)
- Shaonan Wang (sw3720)
- Shukai Wang (sw3715)
  
Emails <UNI> @ columbia.edu

## General Electric (GE) Mentor & Co-Mentors

- Liang Tang

## Instructor/CA

- Sining Chen (sc4549) (Project main)
- Jiaxuan Li (jl6300) Head CA, assisting SC
- Vivian Zhang (Project)
- Peter Chao (jc5859) assisting VZ
- Adam Kelleher (Project)
- Rufina George (rg3466) assisting AK, ST
- Savannah Thais (AI Ethics)

## Project Description

This Capstone project is a collaborative effort between Columbia University's Data Science Institute and General Electric (GE) with a central focus on developing an Information Privacy Control mechanism. The project aims to address the challenge of safeguarding data privacy while using public online Large Language Models (LLM) in corporate settings. To achieve this, we utilize and fine-tune GPT and Llama2 models to assist corporations in de-identifying sensitive information before employing LLMs, ensuring data protection and compliance with corporate policies. Our primary efforts revolve around utilizing Llama2 and GPT models within the 2014 i2b2/UTHealth de-identification challenge dataset, crafting prompts for effective protected health information (PHI) removal, enhancing GPT's performance, and engaging in transfer learning by applying Llama2 to the Aviation Safety Reporting System (ASRS) dataset for aviation safety narrative analysis.

The evaluation results indicate that GPT-4 with explicit prompts outperforms implicit prompts in all metrics, especially recall for comprehensive data anonymization. Fine-tuning GPT-3.5 further enhances its performance, achieving near-perfect scores in all metrics, and demonstrating its effectiveness in identifying and anonymizing private information. In contrast, Llama2 70B-Chat excels in de-identifying private data with implicit prompts but falls short of the GPT models' performance. In aviation data, Llama2 shows acceptable accuracy and recall but lacks precision, highlighting successful transfer learning through prompt tuning.

Our comprehensive comparative analysis of the performance of Llama2 and GPT on both datasets has yielded significant insights, with the fine-tuned ChatGPT-3.5 emerging as the superior performer. This finding underscores the impactful role of both the prompts and the model itself in determining performance outcomes. These elements warrant further exploration in future research, highlighting the meaningful contributions of our work to ongoing advancements in the field.

## Directory Tree
```shell
├── First Progress Result
│   ├── GPT4_result.v1.json
│   └── Llama_result.v1.json
├── Notebooks
│   ├── De-Identification by GPT-4.ipynb
│   ├── De_ID_RNN_LSTM.ipynb
│   ├── De_Identification_by_Llama2.ipynb
│   ├── Explorary_Data_Analysis.ipynb
│   ├── GPT_3_5_finetune.ipynb
│   ├── Llama2 13b-chat.ipynb
│   ├── Llama2_70bchat_Transfer_Learning_ASRS.ipynb
│   ├── Llama2_70bchat_i2b2.ipynb
│   └── Llama2_quantized_13bchat_i2b2.ipynb
└── README.md
```
## Feedback & Contributions

We welcome feedback, bug reports, and pull requests. For major changes, please open an issue first to discuss what you would like to change.

---

