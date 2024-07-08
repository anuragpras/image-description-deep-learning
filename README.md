# image-description-deep-learning
## Overview
- **Dataset:** Utilizes the Flickr dataset comprising 8,000 images, each annotated with 5 captions.

## Technologies Used
### Python Modules
- **os:** File handling using system commands.
- **pickle:** Serialization for storing extracted numpy features.
- **numpy:** Mathematical operations on arrays.
- **tqdm:** Progress bar for iterators.
- **tensorflow.keras:** Deep learning framework for building the model.

### Deep Learning Techniques
- **CNN (Convolutional Neural Network):** Extracts image features.
- **LSTM (Long Short-Term Memory):** Processes natural language sequences.

## Goals
- **Model Objective:** Predict captions for input images by concatenating features extracted from both images and captions.
- **Evaluation Metric:** Utilizes BLEU Score to measure the performance of the trained model.

#### Short Demo: https://www.youtube.com/watch?v=G5UNmKViovw&list=PL-B3lpZNFVZxSBcecbVON4WG-emJgTXNG
