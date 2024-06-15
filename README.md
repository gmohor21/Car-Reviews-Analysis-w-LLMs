# Car-Reviews-Analysis-w-LLMs
This repository is based on a project for analyzing car reviews with Large Language models. It contains a Jupyter notebook for analyzing car reviews and other tasks, along with the dataset and other required files. 

##  Getting Started
To get started with this project, follow these steps:

 - Clone the repository to your local machine using `git clone https://github.com/<your-username>/car-review-analysis.git`.
 - Install the required dependencies.
 - Open the `Analyzing-Car-Reviews-with-LLMs.ipynb` notebook in Google Colab.
 - Run the cells in the notebook. Make sure to run them in order, as some cells depend on the results of previous cells.

## Dependencies
The project requires the following dependencies:

 - pandas
 - numpy
 - scikit-learn
 - transformers
 - evaluate
 - sacrebleu
 - detoxify

You can install them using the `pip` command: 

`!pip install transformers pandas numpy scikit-learn sacrebleu detoxify` 

## Dataset
The dataset used in this project is included in the `data` folder. It contains the following files:

 - `car_reviews.csv`: This file contains car reviews and their class (positive or negative). The reviews were collected from various sources and were classified based on their sentiment.
 - `reference_translation.txt`: This file contains the Spanish versions of some reviews. The translations were done using a machine translation system and were used to evaluate the performance of the chatbot model.

## File Descriptions
Here's a brief description of each file in the repository:

 - `Analyzing-Car-Reviews-with-LLMs.ipynb`: This is the main notebook that contains the analysis. It includes steps for loading the dataset, preprocessing the data, building a chatbot model, and evaluating the model's output and performance for various NLP tasks like text classification, language translation, question answering, and text summarization.
 - `data`: This folder contains the dataset used in the analysis.

## Contributing
If you'd like to contribute to this project, please follow these steps:

 - Fork the repository.
 - Create a new branch from the dev/car-review-analysis branch.
 - Make your changes and commit them to the new branch.
 - Create a pull request to merge the changes into the `dev/car-review-analysis` branch.
 - Wait for others to review the changes and provide feedback.
 - Address any feedback and make any necessary changes.
 - Once the changes are approved, merge the pull request into the `dev/car-review-analysis` branch.

Please make sure that your changes are well-documented and that they do not break any existing functionality.

## License
This project is licensed under the MIT License.
