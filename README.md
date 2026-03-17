# Algerian Forest Fire Predictor

Hey there! This is a simple Flask app that predicts forest fire risk in Algeria using weather data and a machine learning model.

## Quick Setup

1. Make sure you have Python 3.7+ installed.
2. Install the dependencies: `pip install -r requirement.txt`
3. Run the app: `python application.py`
4. Open your browser to `http://localhost:5000`

## How to Use

- Enter weather details like temperature, humidity, wind speed, etc.
- Hit predict to see the fire risk level.
- Make sure the model files (`ridge.pkl` and `Scaler.pkl`) are in the `models/` folder.

That's it! Easy peasy. If you run into issues, check that all files are in place.

5. Click the predict button to get the fire risk prediction.

## Project Structure

- `application.py`: Main Flask application file
- `models/`: Directory containing the trained model (`ridge.pkl`) and scaler (`Scaler.pkl`)
- `templates/`: HTML templates for the web interface
- `requirement.txt`: List of Python dependencies
- `Notebook/`: Jupyter notebook and dataset (for reference)

## Notes

- The application runs on host `0.0.0.0` by default, making it accessible from other devices on the network if needed.
- Ensure all model files are present before running the application.