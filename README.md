# fastapi-tutorial
> tutorial for fastapi

## TODO
- [ ] Postgres Setup
- [ ] SQLAlchemy Model
- [ ] Add entity Route with Controller( `Note` )
- [ ] CRUD with async
- [ ] CQRS

## setup
```bash
python -m venv env
source ./env/bin/activate
python -m pip install --upgrade pip
pip install fastapi
pip install 'uvicorn[standard]'
```

## run:dev
```bash
$ docker-compose up -d --build
# http://localhost:8002/ping
```

## run:test
```bash
$ pytest .
```


## refs

- [awesome-fastapi-async-crud](https://testdriven.io/blog/fastapi-crud/)

