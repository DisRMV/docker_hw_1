FROM python
WORKDIR ~/docker_hw/task_3
COPY . .
ENV PYTHONUNBUFFERED=1
RUN pip install -r requirements.txt
EXPOSE 8000
CMD gunicorn stocks_products.wsgi -b 0.0.0.0:8000
