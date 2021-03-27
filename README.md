create env

'''bash

conda create -n wineQ python=3.7 -y
'''

activate env
'''bash
conda activate wineQ
'''

create req file
'''bash
requirements.txt

'''

install req
'''bash
pip install -r requirements.txt
'''

download the data --> put in data_given

"""
drive link
https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec
"""

git init

dvc init

dvc add data_given / winequality

git add .

git commit