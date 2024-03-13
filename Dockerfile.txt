FROM httpd:2.4
# Copy the index.html file to the Apache web server directory
COPY index.html /usr/local/apache2/htdocs/