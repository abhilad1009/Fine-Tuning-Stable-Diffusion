# Fine-Tuning-Stable-Diffusion

For overview of the approach and evaluation results, please refer to [Fine-tuning-approach.pptx](Fine-tuning-approach.pptx)

## Demo
* Text-to-image demo: [https://huggingface.co/abhilad98/abhi_thumbsup](https://huggingface.co/abhilad98/abhi_thumbsup)
* Dreambooht demo: [https://huggingface.co/abhilad98/db_abhi](https://huggingface.co/abhilad98/db_abhi)

## Requirements
* Memory >= 16 GB
* GPU >= Nvidia T4
* Linux environment
* Note: Training scripts will not work in colab environment

## Data
* Download data from [here](https://drive.google.com/drive/folders/1OIYTrXP1WEtRhFOJItnPb129V2DFQCLF)
* There are 3 data files each for a specific fine-tuning task

## General Instructions
* Install diffusers
* Follow instructions provided in [Training_scripts.ipynb](Training_scripts.ipynb) for training
* For evaluation, load the [SD_Evaluation.ipynb](SD_Evaluation.ipynb) file in GPU enabled machine


