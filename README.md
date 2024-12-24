# ChurnGuard: Customer Churn Prediction System

An intelligent system that predicts customer churn probability using Artificial Neural Networks (ANN). Built with TensorFlow and deployed via Streamlit for easy interaction.

## Features

- Real-time churn prediction using ANN
- Interactive web interface
- Support for multiple customer attributes
- High accuracy prediction model
- Easy-to-use dashboard

## Technology Stack

- TensorFlow/Keras for ANN model
- Streamlit for web interface
- Scikit-learn for data processing
- Pandas & NumPy for data manipulation

## Quick Start

1. **Clone repository:**
   ```bash
   git clone https://github.com/duanshi-26/MNITJaipur-Hackathon-Loyalty-Lens
   cd ChurnGuard
   ```

2. **Setup environment:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch application:**
   ```bash
   streamlit run app.py
   ```

## Model Details

### Input Features
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Products Number
- Credit Card Status
- Active Member Status
- Estimated Salary

### Model Architecture
- Input Layer: Matches feature dimensions
- Hidden Layers: Dense layers with ReLU activation
- Output Layer: Single neuron with sigmoid activation
- Optimization: Adam optimizer
- Loss: Binary crossentropy

## Usage Guide

1. Launch application
2. Enter customer details in the form
3. Click "Predict" button
4. View churn probability result

## Development

### Prerequisites
- Python 3.8+
- Git
- Virtual environment (recommended)

### Local Setup
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

## License

MIT License

## Acknowledgments

Based on original work by Krish Naik. Modified and enhanced for improved performance and usability.
