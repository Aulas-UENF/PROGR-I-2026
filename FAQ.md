# ❓ Perguntas Frequentes (FAQ) - Git & GitHub

### 1. O Git diz que meu "push" foi rejeitado (erro: non-fast-forward). O que fazer?
**Causa:** Alguém (ou você mesmo em outro PC) enviou alterações para o GitHub que você ainda não tem no seu computador local.  
**Solução:** Digite `git pull origin main`. O Git vai baixar as novidades e tentar unir com as suas. Depois disso, você conseguirá dar o `git push`.

### 2. Cometi um erro na mensagem do commit. Posso mudar?
**Solução:** Se você ainda não deu push, use o comando:
`git commit --amend -m "Nova mensagem correta"`

### 3. O Git está pedindo meu nome e e-mail toda hora. Como salvar?
**Solução:** Configure globalmente no seu terminal:
`git config --global user.name "Seu Nome"`  
`git config --global user.email "seuemail@exemplo.com"`

### 4. O que é um "Merge Conflict" (Conflito de Merge)?
**Causa:** Isso acontece quando duas pessoas editam a mesma linha do mesmo arquivo. O Git não sabe qual versão manter.
**Solução:** O VS Code mostrará as duas opções em cores diferentes. Você deve escolher qual fica (ou manter as duas), salvar o arquivo, dar um `git add` e depois um `git commit`.

### 5. Esqueci de criar uma branch e fiz tudo na 'main'. Tem problema?
**Resposta:** Para as tarefas iniciais de PROG-I, não há problema grave. Mas tente se acostumar a criar branches para organizar melhor o trabalho em equipe no futuro.

### 6. Como eu sei se meu arquivo foi enviado com sucesso?
**Resposta:** Entre na página do seu repositório no navegador (GitHub.com). Se os arquivos aparecerem lá com a data e mensagem de commit recentes, está tudo certo!
