FROM public.ecr.aws/docker/library/python:3.12.0-slim

WORKDIR /app

COPY . /app/

RUN pip install -r requirements.txt

EXPOSE 8081

CMD ["python", "app2.py"]