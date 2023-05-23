# Beauty Product Search with Embeddings

This project explores the application of OpenAI's text embeddings to create a product search tool for beauty products. The dataset used in this project is sourced from Amazon and processed using OpenAI's embeddings.

## Contents

1. Jupyter Notebook (`BeautyProductSearchWithEmbeddings.ipynb`): This notebook contains the Python code used for preprocessing the data, generating the embeddings, and implementing the product search functionality.
2. Original Data File (`meta_All_Beauty.json`): This is the original dataset used in the project, which includes various beauty products available on Amazon. The data can be found [here](https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/).
3. Processed Data File (`processed.zip`): This zipped file contains the preprocessed data with calculated embeddings for each beauty product. Due to the large file size, the data is provided in a compressed format.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Install the required Python libraries, if not already installed. You can find these at the start of the Jupyter notebook.
3. Unzip the `processed.zip` file to get the preprocessed data (`processed.pickle`).
4. Run the Jupyter notebook to understand the preprocessing, embedding generation, and product search functionalities. Alternatively, you can use the unzipped `processed.pickle` file to directly work with the preprocessed data and embeddings.

## How It Works

This project utilizes OpenAI's text embeddings to generate high-dimensional vectors that represent each beauty product in the dataset. These embeddings capture the semantic meaning of the product titles and descriptions. By comparing these embeddings, we can find similarities and differences between different products.

## Explore

Feel free to explore, experiment, and make any suggestions or ask any questions!
