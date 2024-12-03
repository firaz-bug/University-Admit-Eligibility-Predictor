# University-Admit-Eligibility-Predictor

# Flask Web Application

This is a simple Flask web application that serves a login page.

## Prerequisites

- Python 3.x
- Flask

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Create a virtual environment:

   ```bash
   python3 -m venv venv
   ```

3. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source venv/bin/activate
     ```

4. Install the required packages:

   ```bash
   pip install flask
   ```

## Running the Application

1. Ensure the virtual environment is activated.

2. Run the Flask application:

   ```bash
   python app.py
   ```

3. Open your web browser and go to `http://127.0.0.1:5000/` to view the login page.

## Project Structure

- `app.py`: The main application file that sets up the Flask server and routes.
- `templates/login.html`: The HTML template for the login page.
