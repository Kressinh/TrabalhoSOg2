# TrabalhoSOg2
Alunos Kevin B. Moroni, Guilherme Andrade, Helen Kressin.

Trabalho docker - VMs e Containeres

Uma aplicação feita com o uso de NGINX e HTML, onde ao ser executado, o docker-compose criará um container baseado na imagem do NGINX, cujo será iniciado e terá a porta 8000 do host mapeada para a 80 do container.
Além disso, o diretório ./src do host será montado dentro do contêiner no caminho /usr/share/nginx/html, permitindo substituição do conteúdo padrão do Nginx pelo conteúdo presente em ./src.
