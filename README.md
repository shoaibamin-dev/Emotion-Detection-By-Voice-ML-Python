# Audio Classification

This project focuses on audio classification using Mel-Frequency Cepstral Coefficients (MFCC) features and a neural network model. The dataset is organized into three main directories: `Dataset`, `main.ipynb`, and `saved_models`.

## Dataset

The `Dataset` directory contains audio files and metadata necessary for training the model.

- **`Dataset/labels.txt`:** Text file containing class labels.
- **`Dataset/metadata.csv`:** CSV file with metadata related to the audio files.
- **`Dataset/metadata2.csv`:** Another CSV file with metadata for audio file processing.

## Audio Files

Audio files are stored in the `Dataset/combined` directory.

- **Sample Audio File:** `Dataset/combined/03-01-05-02-01-02-03.wav`

## Jupyter Notebook

- **`main.ipynb`:** Jupyter Notebook containing the main code for data preprocessing, feature extraction, model creation, and training.

## Saved Models

The `saved_models` directory stores trained models.

- **`saved_models/audio_classification.hdf5`:** HDF5 file containing the trained audio classification model.
- **`saved_models/audio_classification1.hdf5`:** Another version of the trained model.
- **`saved_models/audio_classification3.hdf5`:** Yet another version of the trained model.

### Working Directory

- **`saved_models/working`:** A subdirectory containing additional files related to the working of the models.
  - `audio_classification3.rar`: Compressed file associated with `audio_classification3.hdf5`.

## How to Use

1. Open the `main.ipynb` Jupyter Notebook to view and run the code.
2. Ensure that the necessary dependencies are installed (NumPy, TensorFlow, etc.).
3. Explore the different sections for data preprocessing, feature extraction, and model training.
4. The trained models are saved in the `saved_models` directory.
5. Feel free to use and modify the code for your audio classification tasks.

## Dependencies

- NumPy
- TensorFlow
- Librosa
- Matplotlib
- SciPy

Feel free to experiment with different audio files, adjust parameters, and enhance the model for better performance.

Happy coding!
