# python fastapi

## poetry-fastapi

https://fastapi.tiangolo.com/

```sh
poetry new python-fastapi
cd python-fastapi

poetry add fastapi
poetry add -D uvicorn

# dependency install
poetry install

# poetry env start
poetry shell
uvicorn main:app --reload #  fastapi server start command
# localhost:8000
exit
```
