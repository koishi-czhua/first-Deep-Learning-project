FROM python:3.7
WORKDIR /app
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
RUN pip install jupyter
COPY . .
CMD [ "jupyter", "notebook", "--ip=0.0.0.0", "--no-browser", "--allow-root" ]

