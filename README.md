# text_Summarization_tool

using pip, install flask, flask_mysqldb, spacy
if you run the code and it says library is not defined import it


open a windows powershell
change dir to the folder you just extracted
run the following commands in the powershell:
$env:FLASK_APP = 'main.py'
$env:FLASL_DEBUG = 1
flask run
	
in a browser, go to http://localhost:5000/login/


if you got an error about "en_core_web_sm"
in a seperate cmd write:
python -m spacy download en_core_web_sm
