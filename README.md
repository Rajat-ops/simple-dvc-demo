create env

```bash

conda create -n wineQ python=3.7 -y
```

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

one liner Change
git add . && git commit -m "Updated REAdME.md"
 
git remote add origin "Origin-Path"

git branch -M main

git push origin main

setup commands -
```bash
pip install -e .
```

build your own packages
```bash
python setup.py sdist bdist_wheel
```