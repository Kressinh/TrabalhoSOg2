# TrabalhoSOg2
Alunos Kevin B. Moroni, Guilherme Andrade, Helen Kressin.

Trabalho docker - VMs e Containeres

Uma aplicação feita com o uso de NGINX e HTML, onde ao ser executado, o docker-compose criará um container baseado na imagem do NGINX, cujo será iniciado e terá a porta 8000 do host mapeada para a 80 do container.
Além disso, o diretório ./src do host será montado dentro do contêiner no caminho /usr/share/nginx/html, permitindo substituição do conteúdo padrão do Nginx pelo conteúdo presente em ./src.

Fontes: 
https://www.macoratti.net/19/04/docker_compart1.htm
https://nelson-souza.medium.com/docker-virtualbox-linux-c57596256af6
https://dev.to/aminnairi/quick-web-server-with-nginx-on-docker-compose-43ol

