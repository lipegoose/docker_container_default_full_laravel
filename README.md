# docker_container_default_full_laravel

<h1>Ambiente Completo para Desenvolvimento com</h1>
<h2>PHP7.4-fpm + nginx:latest + mysql5.7.20 + adminer:latest + Composer para Laravel:7.5.2</h1>
<p>Faça o Download deste Repositório na sua pasta do seu Projeto com os comandos <i>Git</i>:</p>
<pre><code>$ git clone https://github.com/lipegoose/docker_container_default_full_laravel.git</code></pre>
<p>ou</p>
<pre><code>$ git clone git@github.com:lipegoose/docker_container_default_full_laravel.git</code></pre>
<p>Após o Download do Git e com o Docker e o Docker-compose previamente instalados, na pasta raiz deste projeto, via Terminal, digite:</p>
<pre><code>$ sudo docker-compose up</code></pre>
<p>ou</p>
<pre><code>$ sudo docker-compose up -d</code></pre>
<p>Pronto! Tudo será instalado e ao final seu Site Laravel -v 7.5.2 com PHP -v 7.4-fpm e com MySQL -v 5.7.20 em um Server nginx estará funcionando.</p>
<p>Para acessar o site em seu navegador, basta digitar (na barra de endereço):</p>
<pre><code><a target="_blanck" href="http://localhost">http://localhost</a></code></pre>
<p>e para acessar o seu <i>Banco de Dados</i> com o <b>Adminer</b>, basta digitar (na barra de endereço do seu navegador):</p>
<pre><code><a target="_blanck" href="http://localhost:8080">http://localhost:8080</a></code></pre>
<p>Caso dê erro e vc não consiga visualizar o site, tente rodar os seguintes comandos com SUDO no seu terminal, na pasta raiz do Git:</p>
<pre><code>$ sudo chmod -R 777 www/site/bootstrap/cache/</code></pre>
<p>&&</p>
<pre><code>$ sudo chmod -R 777 www/site/storage/</code></pre>
<p>Agora, acesse o site novamente e veja a palavra "Laravel" na tela.</p>
<p>Pronto! Vc já pode <i>Codar! <b>;-)</b></i></p>
<h5>e boa diversão. =)</h5>
<p>Se tiver qualquer dúvida, entre em contato.</p>
<p><b><i>#VamoJunto!</i></b></p>
<br>
<br>
<h4>Obrigado por visitar!</h4>
<h3>Mr.Goose</h3>

Docker Container com php:7.4-fpm + nginx:latest + mysql:5.7.20 + adminer:latest + composer + laravel:7.5.2
