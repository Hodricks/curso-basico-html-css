<h1>Comandos para manipular o VS Code:</h1>
<h2>Atalhos:</h2><br>

<p>
---> <b>Alt+Z</b>: Centraliza janela de código;<br>
---> <b>Clicar antes dos caracteres segurando Alt</b>: Seleciona múltiplas linhas de código;<br>
---> <b>Clicar antes dos caracteres segurando Shift + seta esquerda/direita</b>: Seleciona linha de código;<br>
---> <b>Crtl+S</b>: Salva; <br>
---> <b>Ctrl+Z</b>: Volta; <br>
---> <b>Ctrl+C</b>: Copia;<br>
---> <b>Ctrl+X</b>: Recorta;<br>
---> <b>Ctrl+V</b>: Cola;<br>
---> <b>Ctrl+J</b>: Abre/fecha o terminal;<br>
---> <b>Ctrl + ou - </b>: Aumenta/diminui o zoom da tela;<br>
---> <b>Ctrl+shift+P</b>: Envelopa itens selecionados (depois de selecionar os itens e digitar o comando, escreva abb <br> e selecione Wrap with Abbreviation, e em seguida selecione o comando que deseja envelopar ["p","h1","b","i"...]).</p><br><br>

<h2>Comandos para subir novas alterações no reposiório github (Siga a ordem!):</h2> <br>

<p>
---> <b>git add .</b> (Comando git para adicionar novas modificações); <br>
---> <b>git commit -m "Feat: Escreva seu comentário..."</b> (Comando para escrever comentários sobre alterações [Feat:] e/ou bugfixes {Fix:}); <br>
---> <b>git push</b> (Comando para enviar as alterações para o reposiótio git).<br><br>

Em seguida, o VS Code irá solicitar seu nome de Usuário e Senha (Personal access tokens, que tu pega no github), e após isso irá finalizar o push.</p><br>

<h2>Resolvendo possíveis problemas de push no VS Code:</h2><br>

<p><strong>*Obs 1:</strong> Caso houver algum erro no git push (como o mesmo der algum erro ao dar o push), use o comando: <br><br>

"<b>git config --global --unset http.proxy</b>" <br><br>

(sem aspas) e tente novamente o comando <b>git add .</b> e os comandos git sucessivos (<b>git commit</b> e <b>git push</b>).</p><br>

<p><strong>*Obs 2:</strong> Como resolver outro possível problema de desconexão do VS Code: <br><br>

-Primeiro clona a pasta do projeto que está com problema, indo no github, depois clicando no botão Code, e copiando o link HTTPS;

-Crie uma pasta nova com nome aleatório;

-Entra na pasta nova e com botão direito abre o git bash here;

-No console do git bash use os seguinte comando: <br><br>

<strong>git clone "cole o link copiado"</strong> <br><br>

-Depois entre na pasta que está com problema no push e copie todos os arquivos menos o <strong>.git</strong>;

-Depois cola os arquivos na pasta criada nova, e seleciona substituir os arquivos;

-Depois apague a pasta do repositório antigo;

-Agora você pode mover a pasta recém colada de dentro da pasta nova pra fora, e apagar a pasta nova que ficará vazia;

-Agora na pasta recém movida, entre nela e no espaço em branco vá com botão direto e clique em git bash here, e no console digite: <br>

<strong>code .</strong> </p><br>

<p>Agora repita no Vs Code o processo para fazer o push novamente.</p>


