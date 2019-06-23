# GUI-ASAG
A web-based graphical user interface to assist grading jupyter notebook assignments with required active learning query strategy and machine learning model.

Dependencies:

* Vuejs

```
npm install vue
```
* Nodejs

```
sudo apt install nodejs-legacy
```

* Put the notebook files with the student answers in the 'dataset' folder
* Update the path accordingly
* Set the machine learning model and the query strategy which were used here from the [modAL] (https://modal-python.readthedocs.io/en/latest/) framework.

How to run:

```
# from demo-server/node-server
node server.js
```
```
# in a separate terminal
python3 asag.py
```
