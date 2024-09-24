# Dobble Player Project: Automatic Vision and Perception

This project develops an automatic player for the game Dobble using computer vision and deep learning techniques, implementing the YOLO-NAS architecture for real-time detection of common symbols between two cards.

## Description

The aim of the project is to create an artificial intelligence system capable of quickly and accurately identifying the repeated symbols on two cards in the game Dobble. Data augmentation and neural network training techniques have been used to improve the model's capability and accuracy.

## Project Content

- Model Training:** A YOLO-NAS model was trained with images of the animal and Disney versions of the Dobble game, optimising parameters such as batch size and number of images.
- Player Function:** Implements an automatic player that detects and annotates repeated symbols on the cards.
- Results and Evaluation:** The results obtained from the model are presented, including accuracy and confidence in the detections.

## Files

- Project_Dobble.pdf: Complete project document, including methodology, model development, results and conclusions.

## Requirements

- Python 3.x
- Libraries: PyTorch, SuperGradients, Roboflow, OpenCV, among others specified in the document.
- Access to Google Colab to train the model due to the high demand of computational resources.

## Use

1. Load the trained model and the Player function into the runtime environment.
2. Input an image of two playing cards so that the system identifies the repeated symbol.
3. Review the output with annotations of the detected symbols.

## Contribution

This project is open to improvements and contributions. If you have ideas or find bugs, feel free to open an issue or send a pull request.

## License

This project is licensed under the MIT license. See the LICENSE file for more details.
