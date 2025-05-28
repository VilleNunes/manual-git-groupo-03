As Branches(ou ramificações) são como "linhas paralelas de desenvolvimento" dentro do repositório.
Elas permitem que nós testamos,trabalhamos com diferentes códigos sem afetar o projeto principal.
AS Branches servem para:
.Desenvolver uma nova função sem atrapalhar o código que está funcionando;
.Testar correções de bugs;
.Experimentar ideias novas;

Comandos básicos das Branches:
.git branch = mostra as branches existentes no repositório
.git branch[branch] = cria uma nova branch,ex: git branch feature1
.git checkout[branch] = muda para o branch desejado
.git merge[branch] = junta as mudanças de outra branch na branch atual



 Criar uma Branch:
 git branch isabely-novais

Mudar uma Banch:
git checkout isabely-vernil

Deletar uma Branch:
Se a Branch já foi mescladda(deu merge): git branch -d isabely-novais
Se não foi mesclada: git branch -D nome-da-branch.Ex: git branch -d isabely-vernil


O comando git merge junta as mudanças de outra branch na branch atual.Se as mudanças das duas branches foram feitas
 em arquivos diferentes ou  em partes diferentes do mesmo arquivo,o Git faz o merge automaticamente.É chamado de merge automático.

 Mas,quando que acontece um conflito?
 Acontece quando duas branches alteram a mesma linha de um arquivo ou quando um branch remove algo que o outro mudou.Ex:
 Eu e uma colega de classe editamos a mesma linha no arquivo index.php em branches diferentes e quando tentarmos dar um git merge,
o Git dirá que houve um conflito.

E como resolver esse conflitos?
O Git vai marcar os arquivos que estão com conflitos e no arquivo afetado veremos algo assim:
Esse é o texto da branch atual
Este é o texto da branch que esta sendo mesclada.
Podemos editar o arquivo manualmente e escolher qual versão mantem ou combinar as duas;
E depois dar os comando:

git add nome-do-arquivo         # Marca como resolvido
git commit                      # Finaliza o merge com um novo commit
