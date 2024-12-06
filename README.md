# Leaf Only Sam

[[`Paper`](https://arxiv.org/abs/2305.09418)] [[`Data`](https://doi.org/10.5281/zenodo.7938231)]


This is the code from the paper Leaf Only SAM: A Segment Anything Pipeline for Zero-Shot Automated Leaf Segmentation

The is a series of post processing steps to be applied to the output of Segment Anything to identify only leaf masks.  The method has been developed and tested on a novel dataset of potato leaf images which is located [here](link)

## Installation

In order to use it you need to have [segment anything](https://github.com/facebookresearch/segment-anything) working on your system and opencv.  

The code requires python>=3.8, as well as pytorch>=1.7 and torchvision>=0.8. 
The easiest way to set up is to create a conda environment by running the command.

```
conda create --name leafonlysam numpy pytorch torchvision torchaudio pytorch-cuda=12.4 opencv matplotlib pandas ipykernel -c pytorch -c nvidia
```

You will then need to add in segment anything by running 

```
pip install git+https://github.com/facebookresearch/segment-anything.git
```

## Citing Leaf Only SAM

If you use Leaf Only SAM in your research, please cite the following BibTeX entry.

```
@misc{williams2023leaf,
      title={Leaf Only SAM: A Segment Anything Pipeline for Zero-Shot Automated Leaf Segmentation}, 
      author={Dominic Williams and Fraser MacFarlane and Avril Britten},
      year={2023},
      eprint={2305.09418},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
