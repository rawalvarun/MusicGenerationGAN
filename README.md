# MusicGeneration

## Vrawal

1) Make sure visual Studio Code (or VS code) is installed [NOT MANDATORY]
  
3) create a virtual environment named as "env" with python3 (as python interpreter) in the cloned project<br/>
```For Ubuntu: virtualenv -p py3 env```

4) Activate virtual environment<br/>
```For Ubuntu: source env/bin/activate```

5) Install Requirements file:<br/>
```pip install -r requirements.txt```

6) Create necessary directories with script<br/>
```For Ubuntu: sh scripts/directory.sh```

7) Run setup file<br/>
```python setup.py develop```
  
8) Run training file to train the mode<br/>
```python musicgeneration/train.py```

9) Run prediction file to generate and save a music sequence<br/>
```python musicgeneration/predict.py```
