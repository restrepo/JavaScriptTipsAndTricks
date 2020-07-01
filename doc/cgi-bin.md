# `cgi-bin` module in `apache2`
For debian (see [here](https://www.server-world.info/en/note?os=Debian_9&p=httpd&f=2) for details)
* Enable CGI module
```bash
sudo a2enmod cgid
```
* Assuming the the repository was copied lik
```
sudo cp -r REPODIR/* /var/www/html
```
it is necessary to configure the CGI directory of Apache to `/var/www/html/cgi-bin`
