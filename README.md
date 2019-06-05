# Dog Breed classifier using CNN
We employ several supervised algorithms to accurately predict individuals' income using data collected from the 1994 U.S. Census. This sort of task can arise in a non-profit setting, where organizations survive on donations and would be greatly benefitted by such a model for better targeting of specific individuals. Aim is to construct a model that accurately predicts whether an individual makes more than $50,000. We try out three models viz. `SVM`, `Decision Trees` and `AdaBoost`. We finally choose the `AdaBoost` implementation as it had higher accuracy on test-set and significantly faster training time compared to the `SVM` algorithm

## Documentation

### Theory
---
The implementation uses the [UCI Machine Learning data](https://archive.ics.uci.edu/ml/datasets/Census+Income)

### Installation
---
* Install jupyter notebook to open the main file. For new users, its recommended to install Anaconda from [here](http://docs.anaconda.com/anaconda/install/)
* Navigate to the specific folder and clone the repository using the following command:
    ```
    git clone https://github.com/jsarneja/finding_donors.git
    ```
* Open the jupyter notebook `finding_donors.ipynb`
    * Some additional datasets would be needed. Relevant links are provided in the jupyter notebook

## Contributing
---
We love pull requests from everyone. Here are some ways you can contribute:
* by reporting bugs
* by suggesting new features
* by writing or editing documentation
* by closing [issues](https://github.com/jsarneja/finding_donors/issues)