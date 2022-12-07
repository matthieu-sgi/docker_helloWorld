FROM python:3

ADD TODO_FastApi .

RUN pip3 install --no-cache-dir --upgrade -r ./requirements.txt


CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "80"]
