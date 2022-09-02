# nginx-sample-app

#how to use
Clone this repository - $git clone https://github.com/dpraveenreddy/nginx-sample-app.git
cd 'nginx-sample-app'
$docker build -t mynginx .
$docker run -p 8081:80 mynginx
access application - http://localhost:8081 or http://\<public-ip\>:8081
