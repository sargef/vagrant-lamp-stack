#vagrant init ubuntu/bionic64
#vagrant up
#vagrant ssh
</br>

##Create Mysql Database 
<h1><b><p align="center">Vagrant Lamp Stack PHP</p></b></h1>
</br>

<h2><b><p align="center">Initialize Vagrant box - ubuntu/bionic64</p></b></h2>
<h3><b><p align="center">vagrant init ubuntu/bionic64</p></b></h3>
<h3><b><p align="center">vagrant up</p></b></h3>
<h3><b><p align="center">vagrant ssh</p></b></h3>
</br>

<h2><b><p align="center">Create mysql database</p></b></h2>
<h3><b><p align="center">mysql -u root -p (no password set, leave blank and press enter!)</p></b></h3>
<h3><b><p align="center">create database test;</p></b></h3>
<h3><b><p align="center">use test;</p></b></h3>
<h3><b><p align="center">create table posts(id INT AUTO_INCREMENT, text VARCHAR(250) NOT NULL, primary key (id));</p></b></h3>
<h3><b><p align="center">show tables;</p></b></h3>
<h3><b><p align="center">insert into posts(text) values('Hello World');</p></b></h3>
<h3><b><p align="center">insert into posts(text) values('Test Test');</p></b></h3>
<h3><b><p align="center">select * from posts;</p></b></h3>
<h3><b><p align="center">quit</p></b></h3>
<h3><b><p align="center">exit</p></b></h3>
</br>

<h2><b><p align="center">Test url: http://localhost:8765/</p></b></h2>







