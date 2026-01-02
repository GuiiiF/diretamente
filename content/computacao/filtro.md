---
title: greps, pipes e procura
TQ_show_done_date:
tags:
  - computação
  - software
---
Oi, hoje eu irei falar um pouco sobre inputs e outputs no terminal.

imput= entrada,
output= saida.

Bom, dentro de arquivos o input normalmente é  pelo teclado e output pela tela

E no terminal temos três maneira de manipularmos eles, com os: "<", "> " e "|"

---
input ou "<"
ele redireciona a entrada para um comando

ex: sort < data.txt

O "<" geralmente é utilizado remotamente, e ele apenas lê os arquivos, não podendo modificar.

no exemplo apenas manda o conteúdo do arquivo para o sort, sem precisar necessariamente abri-lo, geralmente ele é usando em comados antigos que não conseguem "abrir arquivos"


---
output ou ">"

utilizando apenas um reescrevemos um arquivo, ou seja ele apaga o conteúdo já existente e coloca o que quisermos.

já o >> seria como se anexássemos o que escrevemos dentro do arquivo

---
pipes ou "|"

Ja os pipes pega a saida de um comando e colocar ele na entrada do comando direito, seria como se ligassemos dois comandos de uma unica vez

---
Por fim falaremos do grep.

O grep é um comando no qual podemos achar palavras especificas dentro de um arquivo, ele mostra a linha em que esta esta palavra.

Mas existe um problema nele: ele não ignora normalmente letras maiusculas de minusculas, sendo necessário  a flag -i (ignore-case)