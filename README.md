# TesteApiPostmanNewman
Repositório com codigo de automação de teste de api com postman e newman



Documentação da Api do trello

https://developer.atlassian.com/cloud/trello/rest/api-group-actions/

Como fazer login no trello

https://trello.com/login?returnUrl=%2F1%2Fauthorize%3FrequestKey%3Dca601a06e233d54bbdd877165fece044

Como adquirir uma chave do trello (a variavel ja esta preenchida com a minha chave)

https://trello.com/app-key

Como adquirir um token do trello (a variável ja esta preenchida com o meu token)

https://trello.com/1/authorize?expiration=never&scope=read,write,account&response_type=token&name=Server%20Token&key=e2c3f68a3fe5c94b87af806ba1a7abd2

Indo atras da informação sobre a biblioteca postmanBDD no git no criador:

https://github.com/JamesMessinger/postman-bdd

Descobri que a biblioteca não é mais necessária, pois o postman tem suporte para Chai Assertion Library

https://www.chaijs.com/api/bdd/

Documentação do Newman

https://www.npmjs.com/package/newman

Documentação com passos para instalação do gerador de relatórios HTML

https://www.npmjs.com/package/newman-reporter-htmlextra


Instruçoes para executar o newman: Após realizar as instalações descritas acima, baixar os arquivos teste_api_barroco e trelloapi e salvar no diretório onde o postman foi instalado.

Abrir o terminal, ir para o diretorio onde o postman foi instalado e executar o comando abaixo.

newman run teste_api_barroco --environment trelloapi -r htmlextra --reporter-htmlextra
