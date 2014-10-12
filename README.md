hs-logic
========

homeserver logic files
------------------------

Step 1:
Create an empty template (i.e. BS-ID:10050, BS-Name:Testbaustein):

`python.exe LogikGenerator.py --new=10050:Testbaustein`

Step 2:
Open new file 10050_Testbaustein.py. Now fill in your component config as usual (range 5000-5004)

Step 3:
Generate your logic file(s):

`python.exe 10050_Testbaustein.py`
