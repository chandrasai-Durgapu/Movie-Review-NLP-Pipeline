# Movie-Review-NLP-Pipeline
end to end NLP Pipeline of Movie review

 'conda create -n movie-review python=3.13 -y (⚠️ Until stable release + community support, Python 3.13 is not ready for production. I got so many errors while installing necessary pacakges....so I had de-activated conda environment and i deleted that environment)'

DVC, MLOPS present in this project


conda clean --all -y  

conda create -n nlp-movie-review python=3.10 -y

conda activate nlp-movie-review

pip install -r requirements.txt

pip install -r requirements.txt --verbose


pip install build

pip install --upgrade pip setuptools wheel
pip install numpy  # matplotlib depends on this
pip install matplotlib


pip cache purge

pip install -r requirements.txt

conda install matplotlib

python -m pip install --upgrade pip setuptools wheel
python -m pip install numpy  # matplotlib dependency
python -m pip install matplotlib

conda install numpy matplotlib -y

python -m pip install --upgrade pip setuptools wheel


pip install C:\path\to\downloaded_file.whl


pip install C:\Users\Chandra\Downloads\matplotlib-3.9.1-cp310-cp310-win_amd64.whl

<!-- cd C:\Users\Chandra\Downloads

pip install matplotlib-3.9.1-cp310-cp310-win_amd64.whl -->

pip install --only-binary :all: -r requirements.txt

---
requirements.txt file has....>>>>   antlr4-python3-runtime==4.9.3

replace it--->>>    antlr4-python3-runtime>=4.11.0

2) fusepy==3.0.1 (delete it)


pip install -r requirements.txt


pip install --only-binary :all: -r requirements.txt

---
edit requirements.txt 
Change the line matplotlib==3.9.1 to matplotlib==3.9.4 or simply matplotlib to let pip choose the newest compatible version.

pip install -r requirements.txt
----
Edit your requirements.txt file. Find the line for hydra-core.
Change the version constraint to a more recent one, or remove the version to get the latest.
Original: hydra-core==1.3.2
Change to: hydra-core (to get the latest) or hydra-core>=2.0.0 (to ensure a newer release).
Re-run the installation. This will let pip find a compatible combination of all dependencies.

pip install -r requirements.txt
---

dvc init

create a folder as "local_s3" (temporary work)
dvc remote add -d mylocal local_s3

dvc repro

git add 'data/.gitignore' 'models/.gitignore' dvc.lock 'reports/.gitignore'

dvc config core.autostage true

dvc push

dvc remote list


dvc commit

dvc push

---
flask app added

python flask_app/app.py

http://127.0.0.1:5000

---


