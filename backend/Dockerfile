FROM python:3.11-alpine3.15

WORKDIR /gng-farm

COPY req.txt req.txt
RUN pip3 install -r req.txt

COPY . .

EXPOSE 5000

CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0"]