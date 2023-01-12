# DVC_basics

This repository contains a codespace tutorial for a data versioning tool

# Prerequesits

Codespaces come pre installed with Git, python, pip and sklearn 
We'll need to install DVC using the command 

```
pip install dvc
```

# Follow along Tutorial

## initialize git

Usually in a local machine we would start by 
```
git init
```
or
```
git clone <project_http_url>
cd <project_name>
```
to initialize a github repository
However being in github codespaces we are required to make this workspace *inside* a repository in the first place.

## initialize dvc 
```
dvc init
```