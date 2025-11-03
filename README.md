# LungcancerAI

LungcancerAI is a research project exploring deep learning techniques for lung cancer staging and subtyping. The work focuses on experimenting with convolutional neural network (CNN) architectures using the **NSCLC Radiomics** dataset, with the goal of helping clinicians interpret imaging data more effectively.

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

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/LungcancerAI.git
   cd LungcancerAI
   ```

2. **Install dependencies**
   Create a Python virtual environment (optional) and install packages required by the notebooks. The experiments rely on common deep learning libraries such as `tensorflow`, `keras`, `numpy`, `pandas`, and `scikit-learn`. You can install them with:
   ```bash
   pip install -r requirements.txt
   ```
   > If a `requirements.txt` file is not available, review the import cells in each notebook and install the corresponding packages manually.

3. **Launch Jupyter**
   ```bash
   jupyter notebook
   ```
   Open any of the notebooks listed above to reproduce the experiments or adapt them for your own research.

## Dataset

The experiments use the **NSCLC Radiomics** dataset, which provides curated imaging features for non-small cell lung cancer cases. Ensure you have appropriate access to the dataset and update the notebook paths so they point to your local copy. Refer to the dataset's license and usage guidelines before incorporating it into your work.

## Reproducing Results

Each notebook contains the preprocessing, training, and evaluation steps required to reproduce the reported accuracies. To replicate the findings:

1. Prepare the dataset according to the instructions in the notebooks.
2. Execute all cells sequentially, paying close attention to the configuration blocks for data paths and training hyperparameters.
3. Review the final metrics printed or plotted in each notebook.

## Contributing

Contributions that extend the analysis, compare additional models, or improve documentation are welcome. Please open an issue or submit a pull request describing your proposed changes.

## License

Please consult the repository owner for licensing details or add a LICENSE file if you intend to distribute the project.
