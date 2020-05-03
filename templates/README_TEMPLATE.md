> :memo: A README.md template for releasing a paper code implementation to a GitHub repository.  
> * Version: 1.0.2020.124  
> * Provide general sections  
> * Modify sections depending on needs  

# Model name, Paper title, or Project Name

This repository is the official or unofficial implementation of the following paper.

* Paper title: [Paper Title](https://arxiv.org/abs/YYMM.NNNNN)
* Authors:  
* ArXiv: [arXiv:YYMM.NNNNN](https://arxiv.org/abs/YYMM.NNNNN)

## Maintainers

> :memo: Provide maintainer information  

* Last name, First name ([@GitHub username](https://github.com/username))
* Last name, First name ([@GitHub username](https://github.com/username))

## Description

> :memo: Description of the model  
> * Provide brief information of the algorithms used  
> * Provide links for demos, blog posts  

## Table of contents

> :memo: Provide a table of contents to help readers navigate a lengthy README document.

## Requirements
> :memo: Provide details of the software required  
> * Describe how to install requirements  

* TensorFlow requirement: 2.1

To install requirements:

```setup
pip install -r requirements.txt
```

## Results

> :memo: Provide results with pre-trained models (checkpoint, SavedModel files)  
> * Recommend to publish TensorFlow SavedModel files on TensorFlow Hub (tfhub.dev)  
> * Add links to [TensorBoard.dev](https://tensorboard.dev/) for visualizing metrics  
>  
> An example table for image classification results  
> ### Image Classification  
>  
> | Model name | Download | Top 1 Accuracy | Top 5 Accuracy |  
> |------------|----------|----------------|----------------|  
> | Model name | [Checkpoint](https://drive.google.com/...), [SavedModel](https://tfhub.dev/...) | xx% | xx% |  

## Dataset

> :memo: Provide information of the dataset used  

## Training

> :memo: Provide training information  
> * Provide details for preprocessing, hyperparameters, random seeds, and environment  
> * Provide a command line example for training  

Please run this command line for training.

```shell
python3 ...
```

## Evaluation

> :memo: Provide an evaluation script with details of how to reproduce results  
> * Describe data preprocessing / postprocessing steps  
> * Provide a command line example for evaluation  

Please run this command line for evaluation.

```shell
python3 ...
```

## References

> :memo: Provide links to references  

## Contribution

> :memo: Communicate your expectations clearly  
> * How will you review and accept a contribution? (e.g., Use an issue template)  
> * What types of contributions will you accept? (e.g., Bug fixes only)  

## License

> :memo: Place your license text in a file named LICENSE.txt (or LICENSE.md) in the root of the repository.  
> * Include information about your license  
> * GitHub help: [Adding a license to a repository](https://help.github.com/en/github/building-a-strong-community/adding-a-license-to-a-repository)  

This project is licensed under the terms of the **Apache License 2.0**.

## Citation

> :memo: Make your repository citable  
> * GitHub guides: [Making Your Code Citable](https://guides.github.com/activities/citable-code/)  

If you want to cite this repository in your research paper, please use the following information.
