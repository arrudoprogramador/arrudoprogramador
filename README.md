<h1 align="center">👋 João Pedro Arruda</h1>

<p align="center">
Desenvolvedor Backend em Formação
</p>

---

Exercícios (Instalar o Docker-ce na VM Linux e fazer em ambiente local Ou Fazer no Docker
Playground):
1. Além do Nginx, o Apache 2 ou o Apache Tomcat, também são servidores Web muito utilizados
por programadores PHP, Java, etc.
Nesse exercício devemos criar um contêiner servidor Apache 2 e colocar uma página
index.html nele para que seu funcionamento seja testado. Caso o algum contêiner do Nginx
esteja rodando, parar e excluir o contêiner.
Fazer conforme os passos:
1) O contêiner do Apache 2, no Docker hub é chamado httpd. Usar a imagem
lecolevati/apache-httpd:2.4.63
2) O caminho da pasta do Apache 2 para publicar html, termina com htdocs. Localizar na
documentação oficial do Apache 2 (httpd) no Docker hub, qual o caminho completo.
3) Criar no host a pasta /var/www.
4) Criar o docker run, com opção de background, com um nome Apache2, com o volume
mapeado do caminho completo da pasta www do host com o caminho completo da
pasta htdocs do contêiner, mapeando a porta 80 do hospedeiro com a porta 80 do
contêiner, que sempre reinicializa. A imagem pode ser a última.
5) Criar, na máquina hospedeira, na pasta www, um arquivo chamado index.html
6) Com o vim criar com a seguinte estrutura:
<head>
</head>
<body>
<div>
<p><H1>Apache 2 rodando no Docker + <Seu_nome e RA></H1></p>
</div>
</body>
7) Rodar o link para verificar se o contêiner está funcionando.
8) A resposta da atividade deve ser a linha completa do Docker run e a o print do servidor rodando o
html
setxkbmap br
### 👨‍💻 Sobre mim
Olá! Me chamo João Pedro, tenho 18 anos e sou estudante de **Análise e Desenvolvimento de Sistemas** pela **Fatec da Zona Leste**.


### 🛠 Tecnologias e Ferramentas
<div align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" width="40px"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" width="40px"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40px"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="40px"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" width="40px"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/laravel/laravel-original.svg" width="40px"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/reactnative/reactnative-original.svg" width="40px"/>
</div>




---

### 📊 Estatísticas do GitHub
<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=arrudoprogramador&theme=react-dark"/>
</div>

---

### 📬 Conecte-se comigo
<p align="center">
  <a href="https://www.instagram.com/j.arrudaa7" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/joão-pedro-arruda-43b49a2b5/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  
</p>

---

📜 *“A tecnologia move o mundo, mas quem a move são os curiosos.”*
