# EazePark 🚗

EazePark is an automated parking system that uses computer vision technology to read and manage car number plates. It consists of two main functionalities:

1. **Number Plate Recognition (NPR) 📸**:
   - This component captures live video feed or images to recognize car number plates.
   - Detected plates are stored in a MySQL database along with date and time stamps.

2. **Parking Management 💰**:
   - This component checks the database for registered plates and calculates parking charges.
   - The system charges 30 Rs for the first 2 hours and an additional 10 Rs for every hour beyond the initial 2 hours.
   - It also generates a QR code for easy payment.

## Features 🌟

- Real-time car number plate recognition.
- Integration with MySQL database for data storage.
- Automatic calculation of parking charges based on time.
- QR code generation for easy payment.

## Requirements 🛠️

To set up and run EazePark, you'll need the following:

- Python 3.x 🐍
- OpenCV 📸
- Tesseract OCR 🔍
- MySQL Database 🗃️
- Selenium (for web automation) 🌐
- Pytesseract 🔍
- Additional Python libraries (check `requirements.txt` for the full list)

## Installation 🚀
### Step 1: Download Tesseract Executable
1. Download the Tesseract executable from this [Google Drive folder](https://drive.google.com/drive/folders/1lElfRk-vjV9kM27saXX54NUCSTs0bfQ-?usp=sharing).
2. Copy the location of `tesseract.exe` file in this folder.
### Step 2: Update Tesseract Path
3. In the code, replace the path to Tesseract executable:
   ```python
   pytesseract.pytesseract.tesseract_cmd = r'YOUR_PATH_TO_TESSERACT\tesseract.exe'
### Step 3: Clone the Repository 
Clone the repository:
   ```python
   pytesseract.pytesseract.tesseract_cmd = r'YOUR_PATH_TO_TESSERACT\tesseract.exe'
###Step 4.1: Sign In Desk(Car Entry)
Install necessary packages:
pip install -r requirements.txt
**Run the Python code for the Sign In desk:**
python reader.py
**###Step 4.2: Sign Out Desk / Payment**
Install necessary packages (if not done already):
pip install -r requirements.txt
Run the Python code for the Sign Out desk:
python Sign_out.py

**Contributing 🤝**
If you'd like to contribute to this project, please follow these steps:

1) Fork the repository.
2) Create a new branch (git checkout -b feature/your-feature).
3) Commit your changes (git commit -m 'Add some feature').
4) Push to the branch (git push origin feature/your-feature).
5) Create a new Pull Request.

**License 📜**
This project is licensed under the MIT License.

Happy Parking! 🅿️🚀





Delhi Public School Bangalore North;
Class 12 -B (2023-2024);
Project - Eazepark;
Members:
Aadithya S Nair,
Rohan Eipe,
Hashir Ahamed

Tesseract.exe link: https://drive.google.com/drive/folders/1lElfRk-vjV9kM27saXX54NUCSTs0bfQ-?usp=sharing
