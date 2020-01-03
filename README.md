# flask-webapp
Simple Python WebApp

Included:
Dockerfile
Unitest

Every new commit will envoke a jenkins ci/cd pipeline wich includes:

1) Download the new code
2) Run unitest on it.
3) Containerize it.
4) Pack it and deploy to remote server
4) Delete older environments on remote server
4) Install the new container FRESH


This project was writed for Tikal.


Thank you.



