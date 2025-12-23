---
title: Os loucos arquivos do linux
TQ_show_done_date:
tags:
  - linux
  - arquvis
  - computação
  - engenharia
---

Oi. Decidi aproveitar um pouco das minhas férias da faculdade para aprender, de verdade, sobre esse sistema chamado Linux e suas caralhocentas distribuições.

Então tive a ideia de começar a documentar todo esse aprendizado. Não como uma aula, mas apenas para mostrar um pouco do que estou descobrindo.

Talvez isso até me ajude a melhorar minha escrita e a me esforçar mais para aprender essas coisas.

---

#### O Início

Com um pouco da ajuda do Gemini, comecei a fazer um roadmap de estudos. Ele me guiou a começar pelo básico: entender como funciona a estrutura de arquivos e pastas, e dominar os comandos `ls` e `cd`.

Não é como se eu fosse um completo imbecil nesse tópico, mas sempre é bom ter um guia e relembrar os fundamentos.

[

![](https://substackcdn.com/image/fetch/$s_!nsLv!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fa9d0c835-3783-4a87-9dca-5ee6bb7fa8ae_615x374.png)



](https://substackcdn.com/image/fetch/$s_!nsLv!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fa9d0c835-3783-4a87-9dca-5ee6bb7fa8ae_615x374.png)

print minha mexendo no terminal

Sinceramente, nunca pensei que o touchpad ou o mouse pudessem ser tão inúteis. Afinal, no Windows, a gente usa eles para praticamente tudo.

Mas, no terminal, a brincadeira é outra. Mouse? Esqueça. Aqui, quem manda é o teclado e seus dedos.

Ainda bem que eu já estava me acostumando a usar mais o teclado por causa do **Arch Linux** (a distribuição que estou usando). Se quiserem depois falo mais sobre ela e sua metodologia KISS (_Keep It Simple, Stupid_).

---

#### Sem enrolação

Para mim, os arquivos e diretórios no Linux funcionam como partes de uma pirâmide invertida (ou um prédio).

Nós entramos na parte superior, o início de tudo, e conforme vamos “escavando”, achamos mais e mais arquivos.

Na imagem acima, eu estou na minha `home`. Com o comando `ls`, ela mostra todos os meus arquivos e diretórios, diferenciando-os por cor (arquivos em branco, diretórios em azul).

Conforme entro em um diretório, ele pode se expandir para outros (incluindo alguns escondidos).

O engraçado é que, se não formos específicos, não sabemos tudo que o computador pode nos mostrar.

- O `ls` sozinho mostra apenas arquivos visíveis.
    
- Se adicionarmos o `-l`, ele lista praticamente tudo (detalhes, permissões).
    
- Se colocarmos o `*`, vemos o que tem dentro de cada diretório listado.
    
- Com o `-a`, vemos até mesmo os diretórios `.` e `..` e os arquivos escondidos.
    

O `cd` seria praticamente o meu guia (ou elevador). Ele me leva para onde eu quiser, basta eu falar o destino, seja para entrar ou sair das pastas.

E, por fim:

- O `pwd` é meu GPS: me mostra tudo o que já caminhei (o caminho absoluto).
    
- O `touch` é a varinha mágica que cria arquivos do nada.
    
