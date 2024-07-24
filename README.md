#digit_predict
# AI-Digit-Classifier

## Overview
This project is developed for an edtech startup to demonstrate how neural networks work by classifying handwritten digits. The tool allows users to draw a digit or choose a random digit from a dataset and predicts if it matches a digit between 0 and 9 using a deep learning model.

## Features
- Classify handwritten digits from a dataset.
- Draw and classify digits using a Streamlit interface.
- Validate the model's prediction accuracy.
- Play a game with the model to test its prediction performance.

## Getting Started

### Prerequisites
- Python 3.x
- Streamlit
- TensorFlow/Keras or PyTorch

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/AI-Digit-Classifier.git
    ```
2. Navigate to the project directory:
    ```sh
    cd AI-Digit-Classifier
    ```
3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. Run the Streamlit app:
    ```sh
    streamlit run app.py
    ```
2. Use the interface to either draw a digit or select a random digit from the dataset and see the model's prediction.

## Future Enhancements
- Improve the user interface for a better experience.
- Add more interactive features and games to demonstrate neural network concepts.
- Enhance the model's accuracy with more training data and fine-tuning.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- The dataset source: [MDPI](https://www.mdpi.com/2076-3417/9/15/3169)
- Interface inspiration: [nn_vis by aharley](https://github.com/aharley/nn_vis)
