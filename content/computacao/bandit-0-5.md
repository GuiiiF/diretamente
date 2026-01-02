bom pondo em prática ainda mais tudo que aprendemos nessas ultimas 2 news eu comecei a jogar um "jogo".

O nome dele é bandit, um dos jogos do over the wire.

![[Pasted image 20251227201840.png]](imagem do site over the wire)


a pratica aqui é se conectar a um ssh(secure shell) e tentar achar a senha para o proximo level.

Eles te falam aonde esta a senha, agora você tem que se virar para acha-la e este foi meu progresso indo do level 0-5.

Sim nós começamos pelo 0.

---
level 0:
Apenas loguei na porta 2220 do ssh do bandit usando o comando:
 ssh -p 2220 bandit0@bandit.labs.overthewire.org


level1:
utilizando o comando cat eu li o arquivo readme e achei a senha:

level 2:
utilizando o comando cat ./nomedoarquivo eu li o arquivo "-" e achei a senha

Level 3:
utilizando o comando cat "./nome do arquivo com espaco--" achei a senha:


Level 4:
utilizando o comano cd eu entrei no diretorio in here, com o comando find . eu procurei todos os arquivos e com o comando cat "./aqruivo-escondido" achei a senha:


level 5: 
com o coamando file ./*   eu vi todos os tipos do sarquivos e achei o unico legivel por humanos com a senha

como você pode ver não são caralhocentos comandos, mas sim poucos comandos que tem que ser utilizados da forma correta.

Coisas como ./* ver os arquivos, " " em arquivos com espaço, etc...

E para quem ficou curioso é mais ou menos assim que fica seu terminal quando você loga:

![[Pasted image 20251227202634.png]]