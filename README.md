# Turma de dependência em Design Web

Repositório destinado ao desenvolvimento, estudo e práticas de autoria web.

## Como trabalhar no Git e Github

__Preparando seu ambiente__

Se esta é sua primeira vez no computador de trabalho, é importante realizar as configurações globais.
Para isso é preciso usar o `git config` para configurar as credenciais do usuário. 
Siga os passos:
- [ ] Configure o nome que irá aparecer  ```git config --global user.name “João Silva”```
- [ ] Configure o e-mail do seu usuário no Github ```git config --global user.email “joao.silva@gmail.com”```
- [ ] Faça um clone do repositório `git clone https://github.com/awescolar/dwai-r.git` para iniciar os trabalhos.

__Organizando seu trabalho__

Para isso, é preciso que você certifique-se que está na sua branch. Caso ela ainda não tenha sido criada, você deverá fazê-lo. 
Para tanto, siga os passos:

- [ ] Entre na sua branch `git checkout` ```<nome-sua-branch>```
- [ ] Atualize o seu repositório `git pull`

_Caso você ainda não tenha criado sua branch, deverá fazer isso logo no início_

__Realizando a entrega__

1. Você deve atualizar o repositório local usando `git pull`;
2. Para enviar, faça um:
    - `git add .`; 
    - `git commit -m "Mensagem de envio"`; e
    - `git push`;
    - Verificar se o envio deu certo, no seu repositório (Github);
    - Copie o link do commit que você enviou;
    - Acesse a tarefa no Classroom, adicione o link copiado e __Marque como entregue__.

> [!IMPORTANT]
> Após fazer realizar o envio, verifique se o repositório foi atualizado com sucesso. Somente após se certificar, marque a tarefa como concluída e entregue.


__Esclarecendo atualiazções__

No seu primeiro envio vai aparecer uma mensagem conforme abaixo:


_Fatal: The current branch cesimar-xavier has no upstream branch.
To push the current branch and set the remote as upstream, use_

    git push --set-upstream origin cesimar-xavier

_To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'._

__Apenas copie o comando git acima (`git push --set-upstream origin cesimar-xavier`), cole no seu terminal e execute o comando__
