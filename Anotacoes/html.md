Comandos para manipular o VS Code: ->

Alt+Z Centraliza --->
Crtl+s Salva --->
Ctrl+z Volta --->

Comandos para subir novas alterações (Siga a ordem!): ->

git add . (Comando git para adicionar novas modificações) --->
git commit -m "Feat: Escreva seu comentário..." (Comando para escrever comentários sobre alterações [Feat:] e/ou bugfixes {Fix:}) --->
git push (Comando para enviar as alterações pro reposiótio git)--->

Em seguida, o VS Code irá solicitar seu nome de Usuário e Senha (Personal access tokens, que tu pega no github) --->

Obs: Caso houver algum erro no git push (como o mesmo der algum erro ao dar o push), use o comando: 

"git config --global --unset http.proxy" 

(sem aspas) e tente novamente o comando "git add ." (sem aspas) e os comandos git sucessivos (git commit e git push).
