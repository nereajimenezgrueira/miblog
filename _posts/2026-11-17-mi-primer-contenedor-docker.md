---
layout: post
title: "Mi primer contenedor Docker"
date: 2026-11-17 9:49:00
categories: contenedores
tags: [docker, nginx]
---

Levantamos un servidor Nginx dentro de un contenedor en un solo comando.

## Arrancar el contenedor
```
bash
docker run -d --name web -p 8080:80 nginx
curl -I http://localhost:8080
```
