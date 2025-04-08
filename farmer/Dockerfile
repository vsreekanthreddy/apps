FROM ubuntu
RUN apt update -y && apt install apache2 -y
WORKDIR /var/www/html/
ADD . /var/www/html/
ENTRYPOINT apache2ctl -DFOREGROUND
EXPOSE 80
ENV name myenv
