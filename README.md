# Robust-Yield-prediction(Multiple time series)

![Tests](https://github.com/jeremyjordan/data-science-template/workflows/Tests/badge.svg?branch=main) ![Formatting](https://github.com/jeremyjordan/data-science-template/workflows/Linter/badge.svg?branch=main)

> Accurate yield forecasts help farmers, agricultural companies, and governments to plan for the upcoming season. 
By knowing how much yield to expect, they can make informed decisions about the amount of seed, fertilizer, and other inputs needed, as well as the amount of storage and transportation capacity required.

# Problem statement
> A new fast-food chain is seeing rapid expansion over the past couple of years. They are now trying to optimize their supply chain to ensure that there are no shortages of ingredients. For this, they’ve tasked the data science team to come up with a model that could predict the output of each food processing farm over the next few years.These predictions could further increase the efficiency of their current supply chain management systems.

# Data Handling:
> The Data Size is Huge it consumes whole ram (8gb) so handling ,this kind of data needed special approaches.Feather format- fast read and write performance, and support for a wide range of data types.They are designed to be memory-mapped, which means that they can be accessed without the need for loading the entire file into memory.Downcasting refers to the process of converting a numerical data type to a smaller data type that can still accurately represent the original data. This can be useful in situations where memory usage is a concern, as smaller data types require less memory.

# Exploratory Data Analysis:
* The Datasets: There are 5 different datasets (train_data,farm,weather,test_test_weather)

* To explore data and new features need to merge the data

* Merged Train data contains 16(yield) columns and 2,06,00,899 rows

* Merged test data contains 16 columns (id) columns and 2,15,00,309


## Getting started

1. Spin up a [Colab notebook](https://colab.research.google.com/).
2. Install [colabcode](https://github.com/abhishekkrthakur/colabcode).
3. Start the code server.

```
from colabcode import ColabCode
ColabCode(port=10000, mount_drive=True)
```
4. Go to the ngrok link provided.
5. Clone the repo.

```
git clone https://github.com/codejay12/Robust-Yield-prediction-for-various-farms

6. Run `make colab` to set up the project on your Colab instance (or run `make init` if running locally).

## Training a model

(Describe how to train a model for the project)

## Contributing

In order to commit code from a Colab machine, you'll need to do the following:

1. Make sure you have an Github auth token (https://github.com/settings/tokens)
2. Configure the `git` settings on the machine
