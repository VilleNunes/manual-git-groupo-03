CRIAR CONTA NO GIT HUB

Acesse o site https://github.com.

Clique em Sign up (cadastrar-se).

Preencha seus dados: nome de usuário, e-mail e senha.

Confirme o e-mail para ativar a conta.

Pronto! Você agora tem uma conta no GitHub.

CRIAR REPOSITORIO REMOTO

Faça login no GitHub.

No canto superior direito, clique no + → New repository.

Preencha os campos:

Repository name: Nome do seu projeto.

Description: (opcional) descrição do projeto.

Escolha Public (público) ou Private (privado).

(Opcional) Marque para criar um .gitignore ou licença.

Clique em Create repository.

CLONAR, PUSH E PULL

 Clonar um repositório
Copie a URL do repositório no GitHub e execute:

bash
Copiar
Editar
git clone https://github.com/usuario/repositorio.git
    Enviar alterações para o GitHub (push)

bash
Copiar
Editar
git add .
git commit -m "mensagem explicando a alteração"
git push origin nome-da-branch
 Buscar atualizações do GitHub (pull)
 git pull origin nome-da-branch
 

PULL REQUESTS E REVISAO DE CODIGO

O que é um Pull Request?

Um Pull Request (PR) é um pedido para mesclar as alterações de uma branch (geralmente uma feature) para outra (geralmente a main). Ele permite que o código seja revisado por outras pessoas antes da integração.

Como criar um Pull Request:
Faça push da sua branch para o GitHub.

No repositório, vá até a aba Pull requests.

Clique em New pull request.

Escolha a branch de origem (ex: feature/login) e a de destino (ex: main).

Adicione um título e uma descrição clara das alterações.

Clique em Create pull request.

Revisão de Código
Outros colaboradores podem comentar, sugerir melhorias ou aprovar o código.

Você pode fazer alterações na branch e o PR será atualizado automaticamente.

Após aprovação, o PR pode ser mergeado (mesclado) ao projeto principal.


