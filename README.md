# Surmadi-daen429finalproject
DAEN 429 Final Project – ASL Sign Recognition

## Phase 1 – Static ASL Alphabet (Images)

- Dataset: `asl_alphabet_train` / `asl_alphabet_test` (from Kaggle)  
- Models:
  - T-A: Head-only fine-tuning of ResNet-18
  - T-B: Last block + head
  - T-C: Layer3+4 + head (best)
  - S-A: Full ResNet-18 trained from scratch
- Notebook: `daen429project.ipynb`

> **Note:** Datasets are **not** included in this repository per assignment instructions. 
> You must download them separately from Kaggle and place them in the expected paths.
