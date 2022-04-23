# How to run?

Clone the repository  and go to app directory

 Open Terminal/Command Prompt

Open the Cloned Repository Folder

Create Virtual Environment by typing **`python -m venv env_name`**

Activate Virtual Environment by typing **`source/env_name/bin/activate`** for **mac**

Activate Virtual Environment by typing **`source/env_name/Scripts/activate`** for **bash**

Activate Virtual Environment by typing **`.env_name\Scripts\activate`** for **windows**

After Activating Virtual EnvironmenT install the required modules by typing **`pip install -r requirements.txt`**

when requirements installed, run the python code by typing **`python app.py`**

## Access you web app by typing `127.0.0.1:5000 `in your web browser

[<img alt="alt_text" width="100%" height="100%" src="app/static/img/app.png" />](https://github.com/zubairwazir/skills-based-job-matching/tree/master/app/static/img/app.png)

### Functionality  
The web app offers the following functionality:
* upload csv files
* view initial rows (equivalent to df.head() in pandas)
* change column names
* select columns for regression analysis
* select columns using jquery (without page refresh)
* compare regressions with different tools (linear, random forest, etc)
* demo mode


### Technologies Employed
* python
* numpy
* pandas
* flask
* jinja
* javascript
* jquery
* ajax
* bootstrap
* html
* css

# Special Requirements 
## **Note**: I have Tested On Ubuntu 22.04

`sudo apt-get install libmagickwand-dev`

### Packages needs for ImageMagick
`sudo apt install tesseract-ocr` <br>
`sudo apt install libtesseract-dev`

### if any error of policy permission denied type the below command
`sed -i '/disable ghostscript format types/,+6d' /etc/ImageMagick-6/policy.xml`

## Cheers
### Zubair Ahmad

