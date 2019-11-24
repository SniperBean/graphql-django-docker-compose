FROM python:3.7.4
ENV PYTHONUNBUFFERED 1
RUN mkdir -p /var/www/code
WORKDIR /var/www/code
ADD graphql/requirements.txt /var/www/code/
RUN apt update
RUN pip install --no-cache-dir --upgrade pip
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 8001
