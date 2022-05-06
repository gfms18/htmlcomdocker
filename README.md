# htmldocker
subindo uma pagina html em um container docker

primeiro criei uma pagina html simples como está no codigo 

# sequencia de códigos para rodar a pagina em um container nginx:

docker pull nginx (para baixar a imagem)

docker run -v "C:\Users\Gabriel\Desktop\vscodeprojetos\htmlcomdocker:/usr/share/nginx/html" -p 80:80 -d nginx (especifiquei qual o caminho e a pasta especifica que está na documentação e defini qual é a porta)

DIGITAR LOCALHOST:80 OU LOCALHOST PARA EXIBIR A PAGINA NO NAVEGADOR.