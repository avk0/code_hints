## Python Environment

Create virtual environment \
`virtualenv -p python310 env` \
`python -m venv ./venv`

Activate vitrual env. \
`source env/bin/activate` - Linux \
`.\env\Scripts\Activate.ps1` - Windows

Deactivate vitrual env. \
`deactivate`

List of Python packages in venv. \
`pip list`

Save dependencies to requirements.txt file \
`pip freeze > requirements.txt`

## Python Web

Async - [Celery](https://github.com/celery/celery)

Load Testing - [Locust](https://github.com/locustio/locust)

## Python BI Dashboards

[Streamlit](https://streamlit.io/)

[Dash](https://dash.plotly.com/)
