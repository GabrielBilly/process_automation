# Automação Processo
 
### Objetivo do Projeto:
	Treinar e criar um Projeto que envolva automatização de um processo feito pelo computador,
	nosso papel é conseguir criar um processo da forma mais automática possível para calcular o OnePage de cada Loja e 
	Enviar um email para cada gerente de cada loja
	com seu OnePage no corpo do e-mail e o arquivo completo com os dados da sua respectiva loja em anexo.

### Descrição:
	O projeto consiste em uma rede de lojas de roupa com 25 Lojas pelo Brasil
	Todo dia pela manhã a equipe de análise de dados calcula os One Pages e envia para o gerente de cada Loja
	Um one Page é um breve resumo, usado pela equipe de gerência de loja para saber os principais indicadores de cada loja e permitir em 1 página,
	quanto quais indicadores aquela loja conseguiu cumprir naquele dia ou não.


## Inspirações e Créditos:
	Curso PythonImpressionador - Professor Jõao Paulo Lira


## Requisitos:
### Bibliotecas Utilizadas:
	import pandas as pd
	import smtplib
	from email.mime.multipart import MIMEMultipart
	from email.mime.text import MIMEText
	from email.mime.base import MIMEBase
	from email import encoders
	import pathlib

## Pastas e Arquivos Utilizados no Projeto:
	Bases de Dados (Emails.xlsx, Lojas.csv, Vendas.xlsx)
	Backup Arquivos Lojas (Garanta que está vazia)

### Att, Gabriel Souza
