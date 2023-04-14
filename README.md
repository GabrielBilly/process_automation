# Process Automation

 
### Project's goal:
	Train and create a Project that involves automating a process done by the computer,
	our role is to be able to create a process in the most automatic way possible to calculate the OnePage of each Store and
	Send an email to each store manager
	with your OnePage in the body of the email and the complete file with the data of your respective store attached.
	
	
### Recommendations:
	As this project deals with sending e-mails, remember to complete the code with your data!
	
	
### Description:
	The project consists of a network of clothing stores with 25 stores throughout Brazil
	Every morning, the data analysis team calculates the One Pages and sends them to the manager of each Store
	A one page is a brief summary, used by the store management team to know the main indicators of each store and allow, in 1 page,
	as to which indicators that store was able to meet that day or not.


## Inspirations and Credits:
	PythonImpressionador - Professor Jõao Paulo Lira
	https://www.hashtagtreinamentos.com/


## Requirements:
### Libraries Used:
	import pandas as pd
	import smtplib
	from email.mime.multipart import MIMEMultipart
	from email.mime.text import MIMEText
	from email.mime.base import MIMEBase
	from email import encoders
	import pathlib

## Folders and Files Used in the Project:
	Bases de Dados (Emails.xlsx, Lojas.csv, Vendas.xlsx)
	Backup Arquivos Lojas (Make sure it's empty)

### Att, Gabriel Souza
