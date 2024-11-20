# Utiliser l'image officielle de Node.js
FROM python:3.9-slim-buster AS base
#FROM node:18

# Créer un répertoire de travail
WORKDIR /app
COPY . .

RUN pip install --upgrade pip
#RUN npm install
RUN pip install -r build/requirements.txt

CMD ["python", "src/preprocess.py"]
