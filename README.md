# LSTM-Based Traffic Flow Prediction

This project implements an **LSTM (Long Short-Term Memory)** deep learning model to predict traffic flow based on historical data. The project handles small datasets, supports dynamic sequence length adjustment, and includes robust preprocessing, model training, and evaluation.

---

## **Features**

- **Dynamic Sequence Length Adjustment**: Automatically adjusts sequence length based on dataset size.
- **Synthetic Dataset Generation**: Generates synthetic traffic data for testing and training if real data is insufficient.
- **Robust LSTM Architecture**:
  - Multi-layer LSTM with Dropout layers to prevent overfitting.
  - Supports tuning of hyperparameters (e.g., sequence length, batch size, epochs).
- **Early Stopping**: Stops training automatically when validation loss stops improving.
- **Comprehensive Visualization**:
  - Training vs. validation loss plots.
  - Predicted vs. actual traffic flow.

---

## **Dataset**

The project uses traffic flow data with the following structure:

| Timestamp          | Traffic Flow |
|--------------------|--------------|
| 2024-01-01 00:00  | 120          |
| 2024-01-01 01:00  | 132          |
| 2024-01-01 02:00  | 140          |

If you don't have sufficient real-world data, the project includes a function to generate synthetic data.

---

## **Installation**

### Prerequisites
- Python 3.7 or higher
- Required libraries: 
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
  - `tensorflow`

