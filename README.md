A simple Nginx configuration running a webserver with a custom message.

It is based on `tutum/hello-world`.

To run the image:
```
sudo docker run -p 80 -e MSG='This message will be displayed on the web page' --rm wouterm/helloworld
```
