# docker-app-get-it-done-win
Get IT Done Carrousel - Docker App for Windows (2021)

## Download the code and Build the container (on PowerShell)
> git clone https://github.com/Juli-BCN/get-it-done-docker-windows.git

> cd get-it-done-docker-windows

> docker build -t get-it-win .

> docker images



## Run, Test & Stop the Docker container
> docker run -it -p 80:80 get-it-win

> curl -L http://localhost

> docker ps

> :eyeglasses: docker stop *CONTAINER_ID*