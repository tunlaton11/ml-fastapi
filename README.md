# ml-fastapi

### Installing virtualenv
```
python -m pip install virtualenv 
```

### Creating Python virtualenv
```
python3 -m venv <name>
```

### Using Python virtualenv (My device is use Fish shell)
```
source <name>/bin/activate.fish
```

### Installing fastapi and uvicorn
```
pip install fastapi
pip install uvicorn[standard]
```

### Running server
```
uvicorn main:app --reload
```