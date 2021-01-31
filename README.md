# Container_Amaury_5472x3648
Container da Api em flask para classificar imagens de capins atacados por lagartas. As imagens recebidas por ele precisam ser de tamanho 5472x3648.

Para executar o container basta baixar este repositório no computador, abrir ele com o cmd e digita "docker-compose up -d", esse comando se encarregará de instalar todo o ambiente para execução do container, basta esperar de baixar tudo e instalar. Após isso para acessar a API digite na url do insomnia ou postman com o método POST "localhost:5001/upload_image" e para o corpo da requisição utilize o multipart form, entçao crie um campo chamado image com o tipo file, nesse campo você fará o upload da imagem a ser classificada, após isso basta clicar em enviar e aguardar a resposta. Estou deixando no repositório um arquivo do modelo de requisição para a API, para usar basta importar ele no insomnia.

Todo o código da API está na pasta app. Os parâmetros passados para as funções estão todos no arquivo App.py. Sugiro que faça mudanças nos parâmetros passado para as funções nesse arquivo antes de tentar mexer no código dos outros arquivos.
