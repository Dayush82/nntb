Neural Network Trading Bot (NNTB)
Overview

This repository contains a neural network-based trading bot (NNTB) developed using Python libraries such as Tensorflow (Keras), Numpy, Pandas, and Pandas_ta. The bot performs technical analysis on financial data and executes trades based on the prediction from the neural network.
Prerequisites

The project uses the following libraries:

    Tensorflow (Keras)
    Numpy
    Pandas
    Pandas_ta

To install these libraries, you can use the following commands:

bash

pip install tensorflow numpy pandas pandas_ta

How to Run the Bot

Please ensure all the prerequisites are installed before proceeding.

    Clone the repository:

bash

git clone https://github.com/Dayush82/NNTB.git

    Navigate to the project directory:

bash

cd NNTB

    Open and run the NNTB V1.ipynb notebook using Jupyter notebook.

Description

The NNTB uses Keras to create a neural network model trained on financial data. Numpy and Pandas are used for data manipulation and Pandas_ta is used for technical analysis computations.

The bot fetches historical financial data, applies various technical analysis computations, then uses the neural network to predict future prices. Trades are executed based on these predictions.
Disclaimer

NNTB is a simple implementation and is not guaranteed to make profitable trades. Financial trading involves risk, and decisions should not be made based solely on the output of a simple algorithm. Always seek advice from a licensed financial planner before making any trading decisions.
Contributions

Contributions, issues, and feature requests are welcome. Feel free to check the issues page if you want to contribute.
License

This project is MIT licensed.
