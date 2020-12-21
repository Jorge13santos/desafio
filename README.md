       ### DESAFIO

     1 - Download do Docker
         # apt-get ou yum install curl wget git -y
         # curl -fsSL https://get.docker.com | bash
         
     2 - Download da image nginx-alpine / conectar no container
         # docker container run -it -p 5500:5000 alpine
         
         3 - Preparando o container
           # apk add python3 py-virtualenv
           # mkdir /home/docker_flask_server
           # cd /home/docker_flask_server
           # crie o arquivo app.py ( codigo python)
           # mkdir templates && cd templates 
           # crie o arquivo home.html (codigo em html)
           # virtualenv venv  (executar o comando)
           # source ./venv/bin/activate ( flash variavel)
           # pip install flask ( instalar flask)
           # ls (visualizar os arquivos criados)
           # python app.py ( comando para executar aplicação)
   
      4 - ACESSO APLICAÇÃO
   
       # LOCALHOST OU IP:5500
       




