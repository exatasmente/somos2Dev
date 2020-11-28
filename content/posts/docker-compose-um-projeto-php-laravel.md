---
title: "Docker Compose - Montando um Projeto Php Laravel | Parte 1"
draft: false
featuredImage : "images/docker-compose-phplaravel-featured.png"
description : "Nessa série irei mostrar o passo a passo para criar um projeto Php/Laravel utilizando o docker-compose"
summary : "Docker Compose : Php/Laravel (VueJs, TailwindCss + AlpineJs + Livewire) - Nginx - Redis - Mysql/Postgress - npm/yarn"
toc : true
authors : ["Luiz Neto"]
tags : ["tutorial","docker","php","laravel","web", "development"]
categories : ["Web","PHP","Docker"]
series : ["DockerCompose : PHP/Laravel"]
date: 2020-11-28T10:39:08-03:00
lastmod: 2020-11-28T10:39:10-03:00
readingTime: 5

---
Docker Compose : Php/Laravel (VueJs/ReactJs,TailwindCss + AlpineJs + Livewire) - Nginx - Redis - Mysql/Postgress - npm/yarn

<!--more-->
---

<h3> 
Nessa série iremos abordar como podemos usar containers para desenvolver aplicações utilizando a framework php/laravel,com nginx, mysql ou postgress, redis, npm + yarn e faremos também a configuração para Vue.Js ou Livewire com TALL stack. 

</h3> 
 
## Atenção!
### Nessa série irei usar o sistema opeacional lunix com ElementaryOs (Ubuntun)  
Assumindo que você já tem o docker e docker-compose instalados, se está no windows INSTALE O LINUX! e depois volte


## Verificando a versão do docker e docker-compose

```bash
   $ docker --version
   Docker version 19.03.6, build 369ce74a3c
       
```  


```bash
   $ docker-compose --version
    docker-compose version 1.17.1, build unknown
       
```

Se a saída no seu terminal é semelhante a minha está tudo ok, só lembre-se de utlizar a versão mais recente.
Para esse tutorial irei utlizar o docker compose na versão 3.3.

### Estrutura do projeto 

### O Arquivo docker-compose.yml
Nesse arquivo definiremos como quais os containers que iremos utilizar, onde será definido as redes, locais de armazenamento, pacotes e dependências, além de outras configurações.

### Serviços
 
### Redes

### Discos

### Php e composer

### Mysql

### Postgres

### Nginx 

### Npm + yarn

### Olá mundo 

### Próximo passo