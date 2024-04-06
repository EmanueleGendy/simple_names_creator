# Character-Level Language Model

This repository contains a PyTorch implementation of a character-level language model. The model is trained on a dataset of words and can generate new text by sampling from the learned distribution.
This is only a slightly modified version of the same model coded at https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ, to which all the credits go.

## Requirements

- Python 3.6 or higher
- PyTorch
- Matplotlib

You can install the required packages using pip:

```
pip install torch matplotlib
```

## Usage

1. Clone the repository:

```
git clone https://github.com/your-username/simple_names_creator.git
cd simple_names_creator
```

2. Start the Jupyter Notebook server:
```
jupyter notebook
```
This will open the Jupyter Notebook interface in your default web browser.

4. Navigate to the `new_names_MLP.ipynb` notebook and follow the instructions provided in the notebook to train the language model and generate text samples.

## Notebook Structure

The `new_names_MLP.ipynb` notebook contains the following sections:

- **Data Loading**: Code for loading the dataset from the `names.txt` file and preprocessing the data.
- **Model Definition**: Implementation of the character-level language model using PyTorch.
- **Training Loop**: Code for training the model on the dataset and visualizing the training loss.
- **Evaluation**: Code for evaluating the model's performance on the development set.
- **Text Generation**: Code for generating new text samples from the trained model.

## Customization

You can customize various aspects of the model by modifying the code in the notebook:

- **Dataset**: Change the `names.txt` file to use a different dataset of words or text.
- **Model architecture**: Modify the model architecture by changing the dimensions of the character embedding, hidden layer, and output layer.
- **Training parameters**: Adjust the training hyperparameters, such as the learning rate, number of epochs, and batch size.
- **Text generation**: Modify the text generation process by changing the context length or the sampling strategy.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
