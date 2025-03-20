# Activity Recognition Project

## Project Description

This project is focused on recognizing human activities using sensor data. It utilizes a decision tree classifier to predict activities based on accelerometer data. The project includes data preprocessing, feature extraction, model training, and live classification capabilities.

## Features

- **Data Preprocessing**: Noise removal and magnitude calculation from raw accelerometer data.
- **Feature Extraction**: Extracts statistical features such as average, max, median, etc., from the data.
- **Model Training**: Trains a decision tree classifier to recognize activities.
- **Live Classification**: Classifies activities in real-time using pre-trained models.

## Installation

1. Clone the repository.
2. Install the required Python packages using pip:
   ```bash
   pip install -r requirements.txt
   ```
3. Ensure you have the necessary data files in the `data/Activities` directory.

## Usage

- **Training the Model**: Run the `activity_recognition.py` script to train the decision tree model.
- **Live Classification**: Use the `classify_live_window` function to classify activities in real-time.
- **Visualization**: Visualize the decision tree using the `viz_tree` function.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License.

## Contact

For any questions or issues, please contact [Your Name] at [Your Email]. 