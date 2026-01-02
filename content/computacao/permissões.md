---
title: arquivos e suas permissões
TQ_show_done_date:
tags:
  - computação
  - software
  - permissões
---

bom estamos no nivel 2, arquivos e permissões.

Dentro de cada arquivo nos temos 3 grupos: user, group, others, e cada usuario pode ter 3 tipos de permissão: read, write, execute.

elas quando utilizadas o comando ls -l (como visto na imagem) apareçerão em ordem do usuario, grupo e outros da seguinte maneira: rwx-rwx-rwx

As permissões podem ter valores de numeros sendo eles: read=4 write=2 e execute=1. você somando esses numeros escolhe quantas permissões da a ca individuo.

Sendo você colocar 777 quase um crime, ja que esta falando que todos poderão fazer o que quiserem com o arquivo.

no fim de um arquivo pode se ter um " ", "." ou "+" sendo;
- " "= nada de acessso alternatico, o 
- "." indica contexto de segurança e o 
- "+" indica que ele tem acesso a lista de controles

alem de ser possível adicionar apos isso permissões com o +, ex: u+4 nome do arquivo

---
#### chmod:
comando linux que permite mudar as permissões de um arquivo

colocando: u= usuario, g=grupo, o=outro e a=todos

você pode dar qualquer permissão e acesso alternativo aos arquivos

Você pode aumentar ou diminuir as permissões utilizando o "+" ou o "-"

---
indo para a missão.

É apenas uma brincadeira de permissões.

Onde adicionamos a permissão de executar o arquivo arma.sh ao usuario


![[Pasted image 20251229212439.png]] (missão 1 parte 2)

e depois tiramos e colocamos a permissão de escrever do arquivo confidential.txt
