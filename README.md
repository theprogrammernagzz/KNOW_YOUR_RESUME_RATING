# KNOW_YOUR_RESUME_RATING
The resume rating project focuses on defining criteria and techniques for evaluating candidates, reducing biases, leveraging technology for effective assessment, and addressing ethical concerns. By applying holistic assessment methods, the project aims to enhance objectivity, fairness, and the overall quality of applicant evaluation.

# TECH STACK
1.) Frontend
2.) Backend
3.) Database
4.) Modules

# FEATURES
## Setup & Installation 

To run this project, perform the following tasks 😨

Download the code file manually or via git
```bash
git clone https://github.com/Charanreddy-08/Know-your-resume-rating.git
```

Create a virtual environment and activate it **(recommended)**

Open your command prompt and change your project directory to ```Know-your-resume-rating``` and run the following command 
```bash
python -m venv myenv

myenv\Scripts\activate


```

Downloading packages from ```requirements.txt``` inside ``App`` folder
```bash
cd../..

cd App

pip install -r requirements.txt

python -m spacy download en_core_web_sm

```

After installation is finished create a Database ```cv```

Go to ```venvapp\Lib\site-packages\pyresparser``` folder

And replace the ```resume_parser.py``` with ```resume_parser.py``` 

which was provided by me inside ```pyresparser``` folder


I hope that your ``myenv`` is activated and working directory is inside ``App``

Run the ```App.py``` file using
```bash
streamlit run App.py

```

## Known Error 
If ``GeocoderUnavailable`` error comes up then just check your internet connection and network speed


## Usage
- After the setup it will do stuff's automatically
- You just need to upload a resume 
- Try first with my resume uploaded in ``Uploaded_Resumes`` folder
- Admin userid is ``admin`` and password is ``admin@resume-analyzer``
## For Xampp
1. Check Database Existence
Open phpMyAdmin by navigating to http://localhost/phpmyadmin in your browser.
Look for the database named cv in the list of databases.
2. Create the Database
If the database cv does not exist, create it:

Open phpMyAdmin.
Go to the Databases tab.
Enter cv as the database name and click Create.
