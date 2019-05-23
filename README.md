# -PG1
Meu relatório de PG1

Segue os passos para colocar no seu computador 


1- Abra o Git e escreva o seguinte comando: 
	git clone https://github.com/ProjetosLucas/PG1.git C:\Users\Arthur\Desktop\Visão\PG1\PG1

2- ATENÇÃO: Antes de começa a fazer a alteração no código faça o seguinte, onde você coloca o seu e-mail no "you@example.com", o seu nome em "Your Name".
	
	git config --global user.email "lucassoarespessini@gmail.com"
	git config --global user.name "Lucas Soares Pessini"
	cd C:\Users\Arthur\Desktop\Visão\PG1\PG1
	git pull


3- Qualquer modificação você deve fazer o seguinte, abrir o git e fazer os seguintes comandos, onde você coloca o seu e-mail no "you@example.com", o seu nome em "Your Name" e algum comentário em  "Algum Comentario":
	
	git config --global user.email "lucassoarespessini@gmail.com"
	git config --global user.name "Lucas Soares Pessini"
	cd C:\Users\Arthur\Desktop\Visão\PG1\PG1
	git add .
	git commit -m "Algum Comentario"
	git push

Onde irá atualizar o código do github. Atualiza sempre o beckup do banco de dados que está presente no arquivo C:\xampp\htdocs\Projeto\project.sql. Para fazer o beckup é só digitar localhost/phpmyadmin/ no navegador, apertar no Menu do lado esquerdo em "project", aperta depois em "exportar" e depois em executar. O arquivo que foi feito o download sobreescreve sobre o arquivo C:\xampp\htdocs\Projeto\project.sql.