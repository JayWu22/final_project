# final_project
The project is for semantic segmentation comparison of 4 models including UNet, Segnet, RefineNet, and HRnet.

# Installation
Install the required Python packages:

```bash
pip install -r requirements.txt
```

Download the datasets and checkpoint from the google drive link: [link](https://drive.google.com/file/d/1C-Ggk8glo8UlmG9Z6A-QluKHIEtCgdIK/view?usp=sharing)
and organize the files as follows:
```markdown
project_root/
|-- citycscapes_data/
|-- best_segnet_weight.npy
|-- best_Unet_weight.npy
|-- HRnet/
|   |-- best_HRNet_weight.npy
|-- refineNet/
    |-- best_RefineNet_weight.npy
```
# Usage

There are four main notebooks in the project:

1. `UNet.ipynb`
2. `Segnet.ipynb`
3. `RefineNet.ipynb`
4. `HRnet.ipynb`

## Running the Notebooks

- Each notebook can be executed independently.
- If you only want to perform inference, you can skip the training code blocks within the notebooks.

## Example Workflow

1. Open the desired notebook (e.g., `UNet.ipynb`).
2. Follow the instructions within the notebook.
3. Run the cells for inference to generate results without training.  