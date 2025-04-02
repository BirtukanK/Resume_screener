FROM python:3
ENV PYTHONUNBUFFERED 1
WORKDIR /app/api
COPY requirements.txt ./ 
RUN pip install -r requirements.txt
COPY . ./
EXPOSE 8000

# FROM python:3
# ENV PYTHONUNBUFFERED 1

# WORKDIR /app

# COPY requirements.txt .
# RUN pip install -r requirements.txt

# COPY . .  

# WORKDIR /app/backend  # Move into the Django project directory

# EXPOSE 8000
