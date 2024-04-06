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
git clone https://github.com/your-username/char-level-language-model.git
cd char-level-language-model
```

2. Create a text file named `names.txt` in the repository directory and add your dataset of words, with one word per line.

3. Run the `model.py` script:

```
python model.py
```

This will train the language model on the dataset and display the training loss curve. After training, the script will evaluate the model on the development set and generate 10 samples of text from the trained model.

## Code Structure

- `model.py`: Contains the PyTorch implementation of the character-level language model, including data loading, model definition, training loop, and text generation.

## Customization

You can customize various aspects of the model by modifying the code:

- **Dataset**: Change the `names.txt` file to use a different dataset of words or text.
- **Model architecture**: Modify the model architecture by changing the dimensions of the character embedding, hidden layer, and output layer.
- **Training parameters**: Adjust the training hyperparameters, such as the learning rate, number of epochs, and batch size.
- **Text generation**: Modify the text generation process by changing the context length or the sampling strategy.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
