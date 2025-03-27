FROM inkeister/spark-base:0.1.0

COPY wordcount.py /app/

ENV SPARK_APPLICATION_PYTHON_LOCATION /app/wordcount.py
ENV SPARK_APPLICATION_ARGS "/spark/README.md"
