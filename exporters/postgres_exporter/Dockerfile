FROM python:3
COPY requirements.txt /
RUN pip install --no-cache-dir -r requirements.txt
COPY exporter.py /
CMD [ "python", "exporter.py" ]