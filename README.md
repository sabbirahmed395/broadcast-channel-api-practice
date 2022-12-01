# Broadcast Channel API

This is a simple implementation of boradcast channel API that can allow basic communication between browsing Contexts. [Documentation Link](https://developer.mozilla.org/en-US/docs/Web/API/Broadcast_Channel_API)

To run this example in your local system just download the ```src/index.html``` file and open it in browser. And duplicate the table and open two tab side by side. Write a message in one tab upon submission it will display on another tab.

If you have docker installed in your machine just clone the repository, cd into it and run the docker container

```
git clone git@github.com:sabbirahmed395/broadcast-channel-api-practice.git
cd broadcast-channel-api-practice
docker-compose up -d
```

In browers type ```http://localhost/index.html``` or ```127.0.0.1/index.html``` or ```[your local ip]//index.html```