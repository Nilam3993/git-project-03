FROM ubuntu:latest
RUN apt-get update && apt-get install -y apache2
RUN echo "hello this is DashBoard Dockerfile" > /var/www/html/index.html
ENV ENV_NAME=AWSECR
EXPOSE 80
ENTRYPOINT ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
