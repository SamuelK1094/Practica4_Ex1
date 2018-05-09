# Practica4_Ex1 Recuperación

# CentOS con supervisor configurado para funcionar con httpd-ssh
Centos amb dos serveis Apache i SSH

## Docker run :

Puertos : 
- Apache por defecto: 80
- Supervisor por defecto: 900
- SSH por defecto: 2222

## Usuario para entrar al supervidor

Username: samuel
Password: samuel

## Exemple docker run :

docker run -itd -p 80:8080 -p 2222:22 -p 9001:9001 -e USER=samuel -e PASSWORD=samuel SamuelK1094/centos-supervisor-httpd-ssh
