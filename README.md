# Machine Learning with Python

This project demonstrates a machine learning application using Flask and linear regression to predict insurance charges based on user input.

## Features

- User-friendly web interface for inputting data.
- Predicts insurance charges based on user-provided features.
- Trained model saved for future predictions.

## Requirements

- Python 3.x
- Flask
- Pandas
- Scikit-learn
- Pickle

## Setup

### Cloning the Repository Using GitHub Desktop

1. Open GitHub Desktop.
2. Go to `File` > `Clone Repository...`.
3. In the `Clone a Repository` window, select the `URL` tab.
4. Enter the repository URL (e.g., `https://github.com/username/repository.git`).
5. Choose a local path where you want to save the project.
6. Click the `Clone` button.

### Cloning the Repository Using Command Line

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

5. Run the application:
   ```bash
   python app.py
   ```

6. Open your web browser and go to `http://127.0.0.1:5000/`.

## License

This project is licensed under the MIT License. 