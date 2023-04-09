# Ensemble Approach for Sexist Text Detection in Semeval-2023 Task 10

This repository contains the code for an ensemble approach for detecting sexist text in the context of the Semeval-2023 Task 10. The approach leverages 18 models, including DeBERTa-v3-base models with different input sequence lengths, a BERT-based model trained on identifying hate speech, and three more models pre-trained on a filtered version of the task's unlabeled data with varying input lengths. The results of the framework on the development set show an f1-score of 84.92%, and on the testing set, 84.55%, effectively demonstrating the strength of the ensemble approach in getting accurate results.

## Usage
We used Kaggle with GPU P100 to run the "Generate Probabilities" code


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
We would like to acknowledge the organizers of the Semeval-2023 Task 10 for providing the data and resources for this research.
