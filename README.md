# Team Cogni solution for meesho challenge

Instructions:

- Clone the repository.
- Create conda environment and activate it.
```
conda env create -f environment.yml
conda activate attr_clip
```
- Download dataset from competition website and unzip the files.
- (Optional) Prepare the data using `prepare_data.ipynb`. This step outputs `cods_dataset_CLIP.json`
- Train the notebook using `train_notebook.ipynb`
- Inference on test data using `inference_notebook.ipynb` (update checkpoint path accordingly)
