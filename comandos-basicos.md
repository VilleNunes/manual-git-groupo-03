-Comandos Básicos do Git:

.Iniciar repositório
git init
Cria um novo repositório Git na pasta atual.

.Clonar repositório
git clone https://github.com/usuario/repositorio.git
Faz uma cópia local de um repositório remoto.

.Ver status
git status
Mostra arquivos modificados, novos e prontos para commit.

.Adicionar mudanças
git add arquivo.txt
Ou para todos:
git add .
Coloca arquivos na “staging area” para o próximo commit.

.Fazer commit
git commit -m "Mensagem do commit"
Registra as mudanças adicionadas.

.Ver histórico
git log
Mostra os commits feitos.

.Enviar para o repositório remoto
git push origin main
Envia seus commits para o GitHub (ou outro remoto), no branch main.

.Trazer mudanças do remoto
git pull origin main
Atualiza seu repositório local com as mudanças do remoto.

.Criar branch
git branch nova-branch
Cria um novo branch.

.Mudar de branch
git checkout nova-branch
Vai para outro branch.

.Mesclar branch
git merge nova-branch
Junta as mudanças de uma branch no branch atual.