# 18th-Regulation-CO-PO-Calculator
SRM 18th Regulation CO PO Attainment Calculator
The 18th Regulation CO PO Attainment Calculator Portal is a web-based application designed to streamline the administrative tasks of faculty members. This portal allows faculty to upload and manage PDF files, enter registration numbers, and generate CAM (Continuous Assessment Mark) tables for student evaluations. The user-friendly interface ensures efficient and organized handling of files and data, making it an essential tool for academic administration.

Features:
Registration Number Input:
Faculty can enter multiple registration numbers in a text area, facilitating the management of student data.

PDF File Upload:
Allows for the upload of multiple PDF files, with the file names displayed dynamically as they are added.

CAM Table Generation:
Automatically generates a CAM table based on the uploaded data, providing a structured format for assessing student performance.

Dynamic Interaction:
Responsive buttons for generating CAM tables and calculating attainment, enhancing user interaction.

Downloadable Results:
Option to download the generated results for offline access and record-keeping.

Technologies Used
Frontend: HTML, CSS, JavaScript

Backend: Flask

Usage
Enter Registration Numbers:
In the provided text area, input one or more registration numbers separated by commas.

Upload PDF Files:
Use the file input to select and upload PDF files. Click the add button (+) to display the names of the uploaded files in a list.

Generate CAM Table:
Click on the "Generate CAM" button to display the CAM table section. The CAM table will be populated with placeholders for CO (Course Outcome) attainment.

Calculate Attainment:
After generating the CAM table, click the "Calculate Attainment" button to process the data. The "Download Results" button will then be displayed, allowing you to download the calculated results.

Installation and Setup
To run tests, run the following command

Clone the repository:
git clone https://github.com/SAHARSHARUNSRM/18th-Regulation-CO-PO-Calculator.git
Change to project directory:
cd 18th-Regulation-CO-PO-Calculator
Setup the project:

3.1 Create virtual environment
python -m venv venv 
3.2 Activate the virtual environment

venv\Scripts\activate
3.3 Install the dependencies

pip install flask pdfplumber pandas openpyxl
3.4 Check the dependencies

python -m flask --version
3.5 Create the flask app

set FLASK_APP=FINALTEST  
Running the project:
flask run
Portal Visibility:
The Project can be accessed here

Used By
This project is used by:

Department of Computer Science Engineering, SRM Institute of Science and Technology, Vadapalani.

Demo
The demonstration of the project can be accessed here
