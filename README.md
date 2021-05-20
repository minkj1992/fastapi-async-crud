# fastapi-tutorial
> tutorial for fastapi


## setup
```bash
python -m venv env
source ./env/bin/activate
python -m pip install --upgrade pip
pip install fastapi
pip install 'uvicorn[standard]'
```

## start:dev
```bash
uvicorn main:app --reload
```