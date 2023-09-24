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

- Python 3.x 🐍
- OpenCV 📸
- Tesseract OCR 🔍
- MySQL Database 🗃️
- Selenium (for web automation) 🌐
- Pytesseract 🔍
- ...

## Installation 🚀

1. Download the Tesseract OCR executable from [here](https://drive.google.com/drive/folders/1lElfRk-vjV9kM27saXX54NUCSTs0bfQ-?usp=sharing). Copy the location of `tessearct.exe` file and replace it in this line:
   ```python
   pytesseract.pytesseract.tesseract_cmd = r'C:\\Tesseract\\tesseract.exe'
Clone the repository:

bash
Copy code
git clone https://github.com/IronPirateDev/Eazepark.git
Install necessary packages:

bash
Copy code
pip install -r requirements.txt
Step 4.1: Sign In Desk (Car Entry)

Run the Python code for the Sign In desk:
bash
Copy code
python reader.py
Step 4.2: Sign Out Desk / Payment

Run the Python code for the Sign Out desk:
bash
Copy code
python Sign_out.py
Contributing 🤝
If you'd like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature/your-feature).
Create a new Pull Request.
License 📜
This project is licensed under the MIT License.

Happy Parking! 🅿️🚀

Delhi Public School Bangalore North;
Class 12 -B (2023-2024);
Project - Eazepark;
Members:
Aadithya S Nair,
Rohan Eipe,
Hashir Ahamed

Tesseract.exe link: Download here
