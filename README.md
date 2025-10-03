# DermGPT_ch

Welcome to the repository for **DermGPT_ch**, an open-source lightweight Chinese dermatology-specific large language model and curated dermatology Question-Answer dataset.  

**DermGPT** was developed as part of the study:  
*"Developing a Fine-Tuned Retrieval-Based Dermatological Large Language Model Enhanced by Domain-Specific Question-Answer Pairs."*  

This repository provides access to the **Structured High-quality Dermatology Q&A Dataset** and the **DermGPT model weights**, aiming to support research and applications in dermatology-focused AI systems, especially in resource-limited healthcare settings.  

## Datasets

This repository provides the curated dermatology dataset:

- **Structured High-quality Dermatology Question-Answer Dataset**  
  - 4,531 Q&A pairs  
 <img width="2464" height="2686" alt="图片2" src="https://github.com/user-attachments/assets/02a430cc-1b17-49b5-b793-1da7543cdd4e" />
  - Covering **43 dermatological disease categories**  

  - Generated from authoritative Chinese clinical guidelines and expert consensus  
  - Validated by board-certified dermatologists  

**Data Access**:  
The dataset is shared here for academic and research purposes.  

---

## Model

**DermGPT** is a lightweight Chinese dermatology-specific LLM, trained with:

- **Base model**: Qwen-2.0-7B  
- **Fine-tuning**: LoRA (Low-Rank Adaptation) for parameter efficiency  
- **Retrieval module**: FAISS IndexFlatL2 with 768-d medical embeddings (`nlp_corom_sentence-embedding_chinese-base-medical`)  


## Code

The code will come soon.



