FROM mcr.microsoft.com/devcontainers/python:3.10

# Copy environment.yml (if found) to a temp location so we update the environment. Also
COPY requirements.txt /requirements.txt

RUN pip3 install -r /requirements.txt 