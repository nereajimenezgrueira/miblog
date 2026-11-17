---
layout: post
title: "Apache frente a Nginx"
date: 2026-11-17 9:44:00"
categories: servidores
tags: [apache, nginx, comparativa]
---

Comparamos los dos servidores web más usados en Linux.

| Característica | Apache | Nginx |
|---|---|---|
| Modelo | Procesos / hilos (MPM) | Eventos, asíncrono |
| Configuración | `.htaccess` por carpeta | Centralizada |
| Contenido estático | Bueno | Muy eficiente |

Si aún no tienes Apache instalado, sigue el [post anterior]({%post_url 2026-11-17-instalar-apache-en-ubuntu %}).