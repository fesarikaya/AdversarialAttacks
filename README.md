# Adversarial Attacks on Question Answering Models

This repository contains the code and results for my MSc thesis project on adversarial attacks on question answering models: [here](https://doi.org/10.5281/zenodo.1395357)

## Adversarial Attack Results

Detailed attack result files for each model can be found [here](https://drive.google.com/drive/folders/1inV6yUf7AhrWto45wA5YWfemqvSwQpSL).

- BERT-base: `bert-base-uncased_adversarial_attack_results.csv`
- BERT-finetuned: `bert-base-uncased-squad2_adversarial_attack_results.csv`
- RoBERTa-base: `roberta_adversarial_attack_results.csv`
- RoBERTa-finetuned: `roberta-base-squad2_adversarial_attack_results.csv`
- ELECTRA-base: `electra_adversarial_attack_results.csv`
- ELECTRA-finetuned: `electra-base-squad2_adversarial_attack_results.csv`

## Adversarial Attack Result Summaries

Summary files for each model can be found in the `Results/Summary/` directory:

- BERT-base: `bert-base-uncased_adversarial_attack_summary.csv`
- BERT-finetuned: `bert-base-uncased-finetuned-squad2_adversarial_attack_summary.csv`
- RoBERTa-base: `roberta_adversarial_attack_summary.csv`
- RoBERTa-finetuned: `roberta-base-squad2_adversarial_attack_summary.csv`
- ELECTRA-base: `electra_adversarial_attack_summary.csv`
- ELECTRA-finetuned: `electra-base-squad2_adversarial_attack_summary.csv`

## Adversarial Attack Notebooks

Jupyter notebooks for running attacks:

- No Attack (Baseline): `no_adversarial_attack_all_models.ipynb`
- BERT-base: `adversarial_attack_to_bert-base-uncased.ipynb`
- BERT-finetuned: `adversarial_attack_to_bert-base-uncased-squad2.ipynb`
- RoBERTa-base: `adversarial_attack_to_roberta.ipynb`
- RoBERTa-finetuned: `adversarial_attack_to_roberta-base-squad2.ipynb`
- ELECTRA-base: `adversarial_attack_to_electra.ipynb`
- ELECTRA-finetuned: `adversarial_attack_to_electra-base-squad2.ipynb`

## Adversarial Attack Datasets

Attack dataset JSON files can be found [here](https://drive.google.com/drive/folders/1uHXSwKBT-AiU0vgRwFeo9gKk1ev-pAvI).

- Baseline: `train-v2.0.json`
- AddAny: `squad-v2.0-addany.json`
- AddSent: `squad-v2.0-addsent.json`
- CEIA: `squad-v2.0-CEIA.json`
- DPAEG: `squad-v2.0-dpaeg.json`
- TextFooler: `squad-v2.0-textfooler.json`

## Adversarial Attack Dataset Generation Notebooks

Jupyter notebooks for generating attack datasets:

- AddAny: `CreateAttackDataset_AddAny.ipynb`
- AddSent: `CreateAttackDataset_AddSent.ipynb`
- CEIA: `CreateAttackDataset_CEIA.ipynb`
- DPAEG: `CreateAttackDataset_DPAEG.ipynb`
- TextFooler: `CreateAttackDataset_TextFooler.ipynb`

## Evaluation Framework Notebook

- `AttackResultsAnalysis.ipynb`

## RoBERTa Specific Analysis Notebook

- `RoBERTa Analysis.ipynb`

## Architecture Diagram Files

SVG files for architecture diagrams:

- Transformer: `transformer-architecture.svg`
- BERT: `bert-architecture.svg`
- RoBERTa: `roberta-architecture.svg`
- ELECTRA: `electra-architecture.svg`

## Contributer

Ferhat Sarikaya
