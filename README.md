$ pip install virtualenv
$ virtualenv env
$ .\env\Scripts\activate
$  pip install -r requirements.txt
$  python app.py
if __name__ == "__main__":
    app.run(debug=True, port=<desired port>)
