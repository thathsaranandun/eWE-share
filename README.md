# eWE-Share

An electric vehicle charging community cross-platform mobile application that predicts the most appropriate charging location according to user needs using machine learning.

## Features
- Predicts the best charging location based on user preferences.
- Frontend built with **Ionic**.
- Backend powered by **Flask** (located in the `flask-server` folder).
- **Arduino** integration for monitoring power usage and energy consumption.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/thathsaranandun/eWE-share.git
   cd eWE-share
   ```
2. Navigate to the client folder and install dependencies:
   ```sh
   cd client
   npm install
   ```
3. Navigate to the Flask server and install dependencies:
   ```sh
   cd ../flask-server
   pip install -r requirements.txt
   ```
4. Start the Flask server:
   ```sh
   python app.py
   ```
5. Start the Ionic client:
   ```sh
   cd ../client
   ionic serve
   ```

## Usage
- Open the Ionic application to view charging locations.
- The system predicts the best location using machine learning.
- Arduino modules provide real-time power consumption updates.

## Technologies Used
- **Ionic** (Frontend)
- **Flask** (Backend)
- **Machine Learning** (Prediction Algorithm)
- **Arduino** (Power Monitoring)


---

*For inquiries or contributions, feel free to open an issue or contact me!*

