# Self-attention-driven-Retrieval-of-Chest-CT-Images-for-COVID-19-Assessment

This work introduces a novel, self-attention-driven method for content-based image retrieval (CBIR) of chest CT images. The proposed method analyzes a query CT image and returns a classification result, as well as a list of classified images, ranked according to similarity with the query. Each CT image is accompanied by a heatmap, which is derived by gradient-weighted class activation mapping (Grad-CAM) and represents the contribution of lung tissue and lesions to COVID-19 pathology.

## Research Paper Reference

This project is conducted for research purposes and is closely tied to our paper. Please refer to the following paper for in-depth details, methodologies, and findings:

**Title:** Self-attention-driven-Retrieval-of-Chest-CT-Images-for-COVID-19-Assessment

**Authors:** Victoria Fili, Michalis Savelonas

## Dependencies

- Python 3.9
- Jupyter Notebook
- Keras
- Tensorflow
- GPU

## How to run 
### Locally

1. Clone the repository

```shell
  git clone 
```
2. Download the dataset from 'https://www.kaggle.com/datasets/plameneduardo/sarscov2-ctscan-dataset'
3. Navigate to the notebook file and open it.
4. Run the notebook cells to execute the code.

## Important Notes
Run the files in the above order:
1. classification.ipynb
2. grad_cam.ipynb
3. cbir.ipynb
4. evaluation_metrics.ipynb
5. creation_of_figure3.ipynb
