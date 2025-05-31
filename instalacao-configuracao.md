O que é o Git?
R: O Git é um sistema de controle de versão distribuído usado para gerenciar o histórico de alterações em projetos de software. Ele permite que várias pessoas trabalhem no mesmo projeto ao mesmo tempo, mantendo o controle de quem fez o quê e quando.

Como instalar o Git
No Windows:
-Acesse o site oficial: https://git-scm.com
-Clique em "Download for Windows".
-Execute o instalador baixado.
-Durante a instalação, mantenha as configurações padrão, a menos que você saiba o que está alterando.
-Finalize a instalação.

No Linux (Ubuntu/Debian):
-Abra o terminal
-Digite os seguintes codigos: 
*sudo apt update
*sudo apt install git

Para verificar se deu certo digite:
--git version no terminal

Configuração inicial do Git
Após instalar o Git, é importante configurar seu nome de usuário e e-mail, que serão usados nas alterações que você fizer nos repositórios.

No terminal, digite:
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"

Para verificar se as configurações foram salvas
Digite: git config --global --list

