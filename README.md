# ASSIGNMENT--LOGIC-CLUTCH

- Flask Dynamic Form Application 

This is a simple Flask web application that conditionaly render forms based on user
selection and displays submitted form data.

- Features

   1. Homepage: Allows users to select a form type.
      
   2. Form1: A form with 5 text fields, every fields are required.
   
   3. Form2: A form with 2 text fields and a radio button group, every fields are required.
   
   4. Form Submission**: Submits the data to the server and displays the submitted information.


- Setup Instructions 

Follow these steps to set up and run the project:


 1. Clone the Repository 

git clone https://github.com/ROHITKUMBHAR6800/Assignment---Logic-Clutch.git

cd Assignment---Logic-Clutch   (flask--app--dir)


 2. Create and Activate Virtual Environment 

python -m venv venv

For Windows:
venv\Scripts\activate


 3. Install Dependencies 
Install the required packages listed in requirements.txt:

pip install -r requirements.txt


 4. Run the Flask Application 
Start the Flask development server:

python app.py

The application will run at http://127.0.0.1:5000/.


- Usage 

1. Open http://127.0.0.1:5000/ in a web browser.
2. Select a form type from the dropdown.
3. Submit the selected form.
4. Fill out the form fields and click submit to see the submitted data.
