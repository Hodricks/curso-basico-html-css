<h1>Comandos para manipular o VS Code:</h1>
<h2>Atalhos:</h2><br>


<p>
---> <b>Alt+Z</b>: Centraliza janela de código;<br>
---> <b>Clicar antes dos caracteres segurando Alt</b>: Seleciona múltiplas linhas de código;<br>  
---> <b>Crtl+S</b>: Salva; <br>
---> <b>Ctrl+Z</b>: Volta; <br>
---> <b>Ctrl+C</b>: Copia;<br>
---> <b>Ctrl+X</b>: Recorta;<br>
---> <b>Ctrl+V</b>: Cola;<br>
---> <b>Ctrl+shift+P</b>: Envelopa itens selecionados (depois de selecionar os itens e digitar o comando, escreva abb <br> e selecione Wrap with Abbreviation, e em seguida selecione o comando que deseja envelopar ["p","h1","b","i"...]).</p><br><br>

<h2>Comandos para subir novas alterações no reposiório github (Siga a ordem!):</h2> <br>

<p>---> <b>git add .</b> (Comando git para adicionar novas modificações); <br>
---> <b>git commit -m "Feat: Escreva seu comentário..."</b> (Comando para escrever comentários sobre alterações [Feat:] e/ou bugfixes {Fix:}); <br>
---> <b>git push</b> (Comando para enviar as alterações para o reposiótio git).<br><br>

Em seguida, o VS Code irá solicitar seu nome de Usuário e Senha (Personal access tokens, que tu pega no github).<br>
*Obs: Caso houver algum erro no git push (como o mesmo der algum erro ao dar o push), use o comando: <br><br>

"<b>git config --global --unset http.proxy</b>" <br><br>

(sem aspas) e tente novamente o comando <b>git add .</b> e os comandos git sucessivos (<b>git commit</b> e <b>git push</b>).</p>
