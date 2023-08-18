FROM httpd:2.4
RUN echo "<html><body><h1>Tester</h1>App A works!</body></html>" > /usr/local/apache2/htdocs/index.html
RUN mkdir -p "/usr/local/apache2/htdocs/.well-known/pki-validation/"
RUN echo -e "7C8C0501006BE6A572A04559ADC0C4C61BF07A97BCD99829FAF5637F30EC37A1\ncomodoca.com\n086768f68e22787" > /usr/local/apache2/htdocs/.well-known/pki-validation/82F8DB5E997C80E9A79D652B24830D19.txt