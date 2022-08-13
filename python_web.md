### Flask
`export FLASK_APP="template_autofill:create_app()"` - Linux \
`set FLASK_APP=template_autofill:create_app()` - Windows

`export FLASK_ENV='developement'` \
`python -m flask run –host=”0.0.0.0”` \
`python -m flask run –host=0.0.0.0` Linux

`set` – list of all env vars

завершение процесса Flask \
`stop flask app on port 5000` \
`sudo netstat -tulnp | grep :5000` \
`sudo kill ID`

### Gunicorn
 can be run only on Linux \
`gunicorn -w 4 -b 0.0.0.0:5000 "template_autofill:create_app()"` \
`gunicorn -w 4 -b 0.0.0.0:5000 "template_autofill:create_app()" --daemon`

завершение процесса Gunicorn \
`ps ax|grep gunicorn` \
`pkill gunicorn`

### Apache2
рестарт Apache2 \
`sudo systemctl restart apache2` \
`sudo service apache2 restart`

Step 1     `sudo apt-get update -y` \
Step 2     `sudo apt-get install -y apache2-dev` \
Step 3     `pip install mod_wsgi`

### Nginx
Nginx debug   - https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-gunicorn-and-nginx-on-ubuntu-20-04

`less /var/log/nginx/error.log` \
`nano /etc/systemd/system/template_autofill.service` \
`nano /etc/nginx/sites-enabled/template_autofill` \
`ln -s /etc/nginx/sites-available/template_autofill /etc/nginx/sites-enabled` \
`systemctl restart nginx` \
`systemctl status template_autofill`
