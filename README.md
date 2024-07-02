# UAV-Based Deep Learning Techniques for Early Detection of Corn Plant Diseases

## Project Overview
This project focuses on the early detection of corn plant diseases using UAV imagery and deep learning techniques. The aim is to develop and validate models that can accurately identify healthy and unhealthy corn plant leaves, thereby enabling timely interventions to safeguard food security.

## Features
- Implementation of three deep learning models: CNN, Vision Transformer, and Fully Convolutional Auto-Encoder
- Use of UAV imagery to train and validate the models
- Comparative analysis of model performance to identify the most effective approach

## Models Used
- Convolutional Neural Network (CNN)
- Vision Transformer
- Fully Convolutional Auto-Encoder

## Installation
To run this project, ensure you have Python installed on your system. You can then install the required packages using the provided `requirements.txt` file.

```bash
pip install -r requirements.txt
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/corn-plant-disease-detection.git
   cd corn-plant-disease-detection
   ```
2. Preprocess the data:
   ```bash
   python preprocess.py
   ```
3. Train the models:
   ```bash
   python train.py
   ```
4. Evaluate the models:
   ```bash
   python evaluate.py
   ```

## Project Structure
- `data/`: Contains the dataset of corn plant images acquired from UAV drones
- `preprocess.py`: Script for data preprocessing
- `train.py`: Script to train the models
- `evaluate.py`: Script to evaluate the models
- `models/`: Directory to save trained models
- `notebooks/`: Jupyter notebooks for exploratory data analysis
- `requirements.txt`: List of required packages

## Results
The project demonstrates the effectiveness of the Fully Convolutional Auto-Encoder model in detecting corn plant diseases with an accuracy of 95.09%, outperforming both the Vision Transformer and CNN models. This approach enables early and accurate disease identification, facilitating timely interventions and improving crop protection.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License.

## Contact
For any questions or suggestions, please reach out to [sasank.sonti@example.com](mailto:sasank.sonti@gmail.com).
