# Instructions

Clone this repo:
...
git clone
...

# Install

Set up a virtual environment
...
python3.9.2 -m pip install virtualenv
python -m virtualenv venvv
.\venvv\Scripts\activate
python -m pip install requirements.txt
...

Be sure to install Prodigy!(https://prodi.gy/docs/install using your level key.

# Data Preprocessing

Rerurn full jupyter notebook.


...
python -m prodigy train --textcat annotated_dataset --label "CORPORATE,PRIVACY,CRIMINAL,FINANCE,HEALTH"
...

