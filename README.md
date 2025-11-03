# LungcancerAI

LungcancerAI is a personal research project exploring deep learning techniques for lung cancer staging and subtyping. The work focuses on experimenting with convolutional neural network (CNN) architectures using the **NSCLC Radiomics** dataset, with the goal of helping clinicians interpret imaging data more effectively. This work was presented at the North American Conference for Lung Cancer.

## Highlights

- Achieved **98.06% accuracy** on the lung cancer staging task.
- Achieved **99.6% accuracy** on the lung cancer subtyping task.
- Presented at the **North American Conference on Lung Cancer**.

## Repository Structure

The project is organized as a collection of Jupyter notebooks that document the analysis, experiments, and findings:

| Notebook | Description |
| --- | --- |
| `AI_lung_cancer_research.ipynb` | Baseline exploration of CNN-based approaches for lung cancer staging. |
| `Stage_2_AI_lung_cancer_research.ipynb` | Follow-up experiments with refined training strategies and model tuning. |
| `AI_stage_and_type_lung_cancer.ipynb` | Consolidated notebook covering both staging and subtyping tasks. |


## Dataset

The experiments use the **NSCLC Radiomics** dataset, which provides curated imaging features for non-small cell lung cancer cases. Ensure you have appropriate access to the dataset and update the notebook paths so they point to your local copy. Refer to the dataset's license and usage guidelines before incorporating it into your work.

## Reproducing Results

Each notebook contains the preprocessing, training, and evaluation steps required to reproduce the reported accuracies. To replicate the findings:

1. Prepare the dataset according to the instructions in the notebooks.
2. Execute all cells sequentially, paying close attention to the configuration blocks for data paths and training hyperparameters.
3. Review the final metrics printed or plotted in each notebook.


