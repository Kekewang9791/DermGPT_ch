# Dataset Description

## Overview

This document provides detailed information about the **Structured High-quality Dermatology Question-Answer Dataset**, which was constructed and validated for training  **DermGPT**, a lightweight Chinese dermatology-specific large language model.  

The dataset consists of **4,531 expert-reviewed Q&A pairs** covering **43 dermatological diseases**, designed to capture diverse diagnostic, therapeutic, and patient education knowledge in line with authoritative Chinese dermatology clinical guidelines and expert consensus.  

---

## Data Sources

- **Chinese Dermatology Clinical Guidelines and Expert Consensus**  
  Latest versions of clinical guidelines and consensus statements issued by Chinese dermatological associations and medical societies.  

---

## Dataset Selection and Construction Criteria

- **Guideline Coverage**: Included guidelines and consensus covering **43 skin disease categories**.  
- **Logical Decomposition**: Each guideline was segmented according to hierarchical logical structure (definitions, diagnosis, treatment, prevention, patient education).  
- **Automated Generation**: GPT-assisted generation of multiple candidate Q&A pairs per section.  
- **Expert Validation**: Multi-round review by dermatology specialists, removing inaccurate or non-standard content.  
- **Final Dataset**: Retained **4,531 high-quality Q&A pairs** after validation and optimization.  

---

## Dataset Statistics

| Category Example                            | #Q&A Pairs |
| ------------------------------------------- | ---------- |
| Basic Dermatologic Physiology and Knowledge | 150        |
| Bullous Skin Diseases                       | 256        |
| Dermatologic Therapeutics                   | 111        |
| Physical Skin Disorders                     | 149        |
| Viral Skin Diseases                         | 348        |
| Pruritic Skin Disorders                     | 39         |
| Cutaneous Neoplasms                         | 390        |
| Diseases of Skin Appendages                 | 575        |
| Fungal Skin Diseases                        | 378        |
| Erythematous, Papulosquamous Skin Diseases  | 655        |
| Bacterial Skin Diseases                     | 228        |
| Connective Tissue Diseases                  | 570        |
| Pigmentary Disorders                        | 156        |
| Urticarial Disorders                        | 62         |
| Drug Eruptions                              | 57         |
| Nutritional and Metabolic Skin Disorders    | 154        |
| Vascular Skin Diseases                      | 131        |
| Others                                      | 122        |

- **Total Q&A pairs**: 4,531  
- **Disease categories**: 43  
- **Language**: Chinese (Mandarin)   

---

## Key Characteristics

- **Domain specificity**: Focused exclusively on dermatology knowledge.  
- **Structured coverage**: From basic definitions to advanced clinical decision-making.  
- **Clinical validity**: Validated against national clinical guidelines.  
- **Balanced composition**: Includes both recall-based and reasoning-based Q&A pairs.  
- **Educational utility**: Can be used for clinical training, evaluation, and LLM fine-tuning.  

---

## Citation

If you use this dataset in your research, please cite:

```bibtex

```