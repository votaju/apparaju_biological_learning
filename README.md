## Author 
Anirudh Apparaju
Based on:
1) Krotov, D., & Hopfield, J. J. (2019). Unsupervised learning by competing hidden units. Proceedings of the National Academy of Sciences of the United States of America, 116(16), 7723–7731. https://doi.org/10.1073/pnas.1820458116
2) Dmitry Krotov's starting code (https://github.com/DimaKrotov/Biological_Learning).
3) Guido Tapia's code based in PyTorch (https://github.com/gatapia/unsupervised_bio_classifier).
paper Dmitry Krotov's starting code (https://github.com/DimaKrotov/Biological_Learning).

## Files
- NN_with_end_to_end_backprop.ipynb: Neural Network with a single hidden layer trained for classification tasks using classic end-to-end backpropagation.
- Unsupervised_bio_learning_pytorch.ipynb: Apparaju's implementation of unsupervised learning algorithm based on numpy and pytorch. Based on references above. Makes use of GPU (cuda) if available.
- Unsupervised_learning_algorithm_MNIST.ipynb: Dmitry Krotov's provided unsupervised learning algorithm based on numpy. Accentuated with cells to debug and understand workings of the algorithm.

## Getting started
Install jupyter notebook and the following libraries:
numpy, scipy, matplotlib, pytorch, sklearn, seaborn, statsmodels, pandas, joblib

```bash
> jupyter notebook
```
run cells in `Unsupervised_bio_learning_pytorch.ipynb` until the comment "------ THIS IS THE END OF MNIST WORK -------".

# Biological_Learning
Example of "biological" learning for MNIST based on the paper [Unsupervised Learning by Competing Hidden Units](https://doi.org/10.1073/pnas.1820458116) by D.Krotov and J.Hopfield. If you want to learn more about this work you can also check out this [lecture](https://www.youtube.com/watch?v=4lY-oAY0aQU) from MIT's [6.S191 course](http://introtodeeplearning.com/).  

Krotov's Github: https://github.com/DimaKrotov/Biological_Learning which was used as a starting point for the project.

