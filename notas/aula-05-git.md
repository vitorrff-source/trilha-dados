Editei e quero descartar (ainda sem add)	git restore <arq>	—
Fiz add e quero tirar da staging	git restore --staged <arq>	—
Errei a mensagem do último commit	git commit --amend -m "nova"	não
Quero desfazer um commit que já foi para o GitHub	git revert <hash>	sim
Quero apagar commits locais e manter as mudanças	git reset --soft HEAD~1	não
Quero apagar commits locais e as mudanças	git reset --hard HEAD~1	não
Perdi um commit	git reflog e depois git reset --hard <hash>	—
