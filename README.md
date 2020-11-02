# A Practical Guide to Graph Neural Networks

This repository contains the code for the extended examples in the paper ["A Practical Guide to Graph Neural Networks"](https://arxiv.org/abs/2010.05234).

If using the code here, or referencing the paper, please use the following bibtex citation entry for our preprint. 

```
@misc{ward2020practical,
      title={A Practical Guide to Graph Neural Networks}, 
      author={Isaac Ronald Ward and Jack Joyner and Casey Lickfold and Stash Rowe and Yulan Guo and Mohammed Bennamoun},
      year={2020},
      eprint={2010.05234},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```

## Folder structure

```
.
├── html            # Exported .html files of the notebooks
├── notebooks       # The .ipynb files of the example code
├── .gitignore                     
├── env.yml         # The conda environment dependencies file
├── LICENSE
└── README.md
```

## Running on your own computer

Although Jupyter notebooks (```notebooks/```) and exported HTML files (```html/```) have been included in this repository for ease of viewing and sharing, you may still want to clone this repository and run / modify the code yourself.

To do this, use a conda-based package manager and install dependencies from the file ```env.yml``` .yml file. Do this using the following command (or similar):

```
conda env create -f env.yml
```

Activate this environment and run the ```jupyter notebook``` command.

This code has been tested using Python 3.8.3.
