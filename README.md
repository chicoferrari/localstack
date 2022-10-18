Simulador de ambiente da AWS

```
Stack para praticar e testar funcionalidades e automações sem correr 
riscos de ser cobrado (afinal, quem nunca esqueceu um recurso ativado?).

1. Iniciar o ambiente:

$ docker compose up

2. Acessar o ambiente:

$ docker compose exec localstack bash

(dentro do contêiner, substituir os comandos 'aws' por 'aws local')

```