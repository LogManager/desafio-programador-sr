# Teste Programador PHP LogManager Sênior

Este teste tem como objetivo conhecer um pouco mais como você programa, e como você vai se organizar para montar um sistema complexo.

## O que você precisa fazer

1 - Você precisa criar um mecanismo para sincronizar contas do mercado livre e ressincronziar o token que expira de 6 em 6 horas

2 - Ficar escutando os callbacks de pedidos e criar o pedido na base ou atualizar ele ( aqui tem que baixar pedido e os itens dele ). Criar uma tela para filtrar os pedidos por cliente e por período.


Documentação: https://developers.mercadolivre.com.br/pt_br

Para isto, você precisa criar um app de teste: https://developers.mercadolivre.com.br/devcenter/create-app

Pode utilizar o ambiente de homologação do mercado livre mesmo, não é necessário publicar o app em produção.

Desafio proposto:
- 1 - Criar um app no mercado livre
    - 1.1 - Sincronizar contas no seu app e recuperar o access token ( e salvar no banco )
    - 1.2 - Ressincronizar quando o token expirar, o token expira a cada 6h
    - 1.3 - Documentação: https://developers.mercadolivre.com.br/pt_br/autenticacao-e-autorizacao
- 2 - Back end e Front end de pedidos 
  

Obs 1: de preferência em utilizar o banco de dados MySQL para que seja fácil nossa analise, e também por que é o que utilizamos aqui, ou sqlite.

Obs 2: não esqueça de criar um README.md explicando oque precisamos fazer para rodar sua aplicação aqui em nossa máquina.

Obs 3: não se preocupe em fazer um front-end bonito, mas ele precisa estar desacoplado do projeto e ter uma conexão com a API.

## Seria legal se você fizesse

- Utilizar RabbitMQ ( ou um outro sistema de fila qualquer ) para processar os jobs
- Docker
- Testes unitários
- Algum design pattern
- Usar laravel

## No mais...

Ao finalizar o teste, subir em um reposítorio do github privado e compartilhar com o user grazianilog do github. Após compartilhar enviar a URL do repositório para o e-mail graziani@logmangaer.com.br

---

Boa sorte! Esperamos ter você aqui com a gente :)
