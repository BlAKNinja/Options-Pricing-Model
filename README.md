# Options-Pricing-Model

## Project Description
This repository contains the code for an options pricing model that utilizes deep learning techniques to optimize option pricing.
The project is based on the research paper titled "Machine Learning for Option Pricing: An Empirical Investigation of Network Architectures" by 
Laurens Van Mieghem, Antonis Papapantoleon, and Jonas Papazoglou-Hennig. The research explores three deep learning models: MLP (Multi-Layer Perceptron), 
Highway Network, and DGM Network, and their effectiveness in option pricing using data from January 2013 to August 2013 of S&P 500 options.

## Research Paper
The research paper by Van Mieghem et al. serves as the foundation for this project. It investigates the application of various neural network architectures to the domain of option pricing,
aiming to enhance pricing accuracy and model performance. The three key network architectures explored in the paper are:

1) MLP (Multi-Layer Perceptron): A traditional feedforward neural network that serves as a baseline model for option pricing.
2) Highway Network: A specialized neural network architecture designed to handle complex hierarchical relationships in data.

3) DGM Network (Deep Gaussian Machine): A deep learning model specifically tailored for modeling option prices by taking into account the underlying dynamics of financial markets.
you can find the link of research paper [here](https://arxiv.org/pdf/2307.07657.pdf)

## Data
The dataset used in this project consists of S&P 500 options data spanning from January 2013 to August 2013. 
This data forms the basis for training and evaluating the deep learning models for options pricing.

you can download the dataset from this free section the this [link](https://optiondata.org/)

## Getting Started
To get started with this project, follow these steps:

1) Clone the Repository: Clone this repository to your local machine using the following command:<br>
git clone https://github.com/BlAKNinja/options-pricing-model.git<br>

2) Install Dependencies: Make sure you have the required Python packages and libraries installed.
3) Run the Code: Explore the Jupyter notebooks and Python scripts provided in the repository to understand the implementation of the deep learning models and how they are applied to options pricing.






## Additional Information
In addition to the research paper's implementation, this repository may include enhancements,
modifications, and additional experiments performed by the project maintainers or contributors. These improvements
aim to further optimize the deep learning models for options pricing and explore novel techniques and architectures.



