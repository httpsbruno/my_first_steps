# my_first_steps
*Respostas dos meus exercícios* \

1. **Após criado a sua conta no GitHub, crie um repositório remoto público chamado“my_first_steps” e cole o link aqui.**
	 https://github.com/httpsbruno/my_first_steps \
	 
2. **Crie um diretório em sua máquina e o vincule ao seu repositório remoto “my_first_steps” utilizando os comandos git necessários para a realização desta tarefa. Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa.**\
	git init \
	git branch -M "main" \
	git clone https://github.com/httpsbruno/my_first_steps.git \

3. **Dentro do diretório em sua máquina, crie um arquivo chamado “ola_mundo.txt”, adicione algum texto da sua preferência e adicione-o ao seu repositório remoto utilizando os comandos git necessários para a realização desta tarefa. Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa.**\
	git remote add origin https://github.com/httpsbruno/my_first_steps.git \
	git add . \
	git status \
	git commit -m "Enviando txt ola mundo" \
	git status \
	git push -u origin main \
	
4. **4. Se não existir em seu diretório, adicione ao seu diretório um arquivo com o nome de“.gitignore”. Em seguida, crie um arquivo chamado “serei_ignorado.txt” e adicione algum texto dentro dele. Adicione a instrução ao arquivo “.gitignore” para que as alterações realizadas no arquivo “serei_ignorado.txt” não seja controlado pelo git. Cole aqui o conteúdo que você utilizou no “.gitignore” para realizar esta tarefa.**\
    #ignorando arquivo \
    serei_ignorado.txt \

5. **Dentro do seu diretório local, crie um arquivo chamado “README.md” e edite-o contendo todas as respostas aos enunciados das questões anteriores. Adicione-o ao seu repositório remoto utilizando os comandos git necessários para a realização desta tarefa. Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa.**\
	git status \
	git add README.md \
	git status \
	git commit -m "Enviando alterações do README.md" \
	git push -u origin main \