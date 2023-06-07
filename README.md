#  Imagem Docker do Airflow

Este projeto tem como objetivo principal a criação de uma Máquina Virtual em <i>Docker</i> do <i>AirFlow 2.5.1</i>.

No <i>docker-compose.yml</i> já contém a criação dos mesmos com os parametros e as dependências.

Na pasta <i>config</i> contém os seguintes arquivos e suas respectivas funcionalidade:

* airflow.cfg - é o arquivo de configuração do <i>AirFlow</i>, ele é inserido quando o script <i>docker-compose.yml</i> for inicializado;

* requirements.txt - são os pacotes <i>pip</i> do <i>Python</i> que serão instalados assim que inicializar o <i>docker-compose.yml</i>.

* <i>conf_airflow.env</i>  e <i>var_dags.env</i> são arquivos onde serão setadas as configurações do <i>AirFlow</i> e as variáveis de ambiente utilizadas nas <i>dags</i>. Nestes arquivos estão setadas algumas configurações mas é somente como exemplo, podendo ser alteradas de acordo com a necessidade.

A Pasta <i>dags</i> é onde está localizado os scripts das dags do <i>AirFlow 2.5.1</i>.

Na pasta <i>plugins</i> estão os plugins criados.

A Pasta <i>storage</i> são os arquivos compartilhados com a VM.

Junto com o <i>AirFlow</i> já serão instalados o Banco de Dados <i>Postgres 13</i>  e o <i>PgAdmin4</i> que é um gerenciador gráfico do <i>Postgres</i>.

![](/images/print.PNG)

<hr>


## Programas e Bibliotecas Utilizados:</B>

* Docker Desktop
* Airflow 2.5.1
* PostgreSQL 13
* PGAdmin4
* apache-airflow-providers-apache-spark==4.0.0
* apache-airflow-providers-google==10.1.0rc1
* apache-airflow-providers-apache-kafka
* pyspark==3.2.1
* delta-spark==2.0.0
* google-cloud-storage
* firebase
* firebase_admin
* kafka-python

<hr>

## Contatos 

Autor: `Thiago Vilarinho Lemes`

Email: `contatothiagolemes@gmail.com`

Likedin: [`Thiago Vilarinho Lemes`](https://www.linkedin.com/in/thiago-l-b1232727/)

<hr>
