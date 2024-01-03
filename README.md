# myplugin

## Overview
MyPlugin is a Dockerized Nginx server for easy deployment, development, and testing.

## Quick Start
Clone the Repository:

git clone https://github.com/kumarankit999/myplugin.git
cd myplugin
Build and Run Docker Container:

docker build -t myplugin:latest .
docker run -p 8080:80 myplugin:latest
inplace of myplugin:latest you can use the tags (ex:0.1)

Visit http://localhost:8080 in your web browser to see the Nginx default page.


