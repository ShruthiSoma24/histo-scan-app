# HistoScan Application

HistoScan is a web application designed for breast cancer detection via histopathology tissue analysis using deep learning techniques. This application leverages a ResNet-50 Convolutional Neural Network to classify breast tissue as either Benign or Malignant, assisting pathologists and clinicians in making faster and more reliable diagnoses.

## Project Structure

```
histo-scan-app
├── app.py                # Main application file
├── requirements.txt      # Python dependencies
├── templates             # HTML templates
│   ├── base.html        # Base template
│   ├── index.html       # Home page
│   └── about.html       # About page
├── static                # Static files
│   ├── css              # CSS styles
│   │   └── style.css    # Stylesheet
│   └── js               # JavaScript files
│       └── main.js      # Client-side scripts
└── README.md             # Project documentation
```

## Getting Started

To run the application locally, follow these steps:

1. **Install Python and pip**: Ensure you have Python and pip installed on your machine. You can download Python from [python.org](https://www.python.org/downloads/).

2. **Navigate to the project directory**: Open your terminal or command prompt and change the directory to the project folder:
   ```
   cd path/to/histo-scan-app
   ```

3. **Install the required dependencies**: Use pip to install the necessary libraries listed in `requirements.txt`:
   ```
   pip install -r requirements.txt
   ```

4. **Run the application**: Start the Flask web server by executing:
   ```
   python app.py
   ```

5. **Access the application**: Open your web browser and go to `http://127.0.0.1:5000` to view the application.

## Features

- **User Authentication**: Users can log in to access tissue analysis features.
- **Tissue Analysis**: Upload histopathology images for analysis.
- **Automated Reporting**: Receive classification results with confidence scores.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for details.