FROM python:3
RUN pip3 install --upgrade pip
WORKDIR /app
COPY ./data/ .
RUN pip3 install -r requirements.txt
# RUN pip3 install sqlite
ENTRYPOINT [ "python" ]
CMD ["app.py" ]