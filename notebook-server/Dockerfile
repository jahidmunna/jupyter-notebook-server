# For Apple Sillicon
FROM jupyter/datascience-notebook:aarch64-python-3.10.5 
# FROM jupyter/base-notebook
# FROM jupyter/minimal-notebook:notebook-6.5.1

# Install Additional Requirements
COPY requirements.txt .
RUN pip install -r requirements.txt

# Expose Port
EXPOSE 8888