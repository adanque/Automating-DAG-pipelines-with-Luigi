# Automating DAG pipelines with Luigi

## _For creating Directed Acyclic Graphs to manage workflows_

<a href="https://www.linkedin.com/in/alandanque"> Author: Alan Danque </a>

<a href="https://adanque.github.io/">Click here to go back to Portfolio Website </a>

![A remote image](https://adanque.github.io/assets/img/MachineLearning.jpg)

Creating automation of data pipelines and workflows.

## Pythonic Libraries Used in this project
- zipfile
- json
- os
- pandas
- bs4
- luigi
- time
- pathlib
- shutil
- email

## Repo Folder Structure

├───data

├───examples

│   ├───html

│   └───plain

└───results

    └───words

## Python Files 

| File Name  | Description |
| ------ | ------ |
| run_email_Sparck_Processor.py | Using Spark to parse email mime archives  |
| run_email_Luigi_DAG_Build.py | Create a DAG using Luigi to read email folders  |
| run_email_Luigi_DAG_Processor.py | Build a DAG using Luigi to read through folders containing emails to count words contained in the files|

