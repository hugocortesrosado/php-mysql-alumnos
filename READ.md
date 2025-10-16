# 🔒 Práctica 3: Configuración de HTTPS en Nginx con Docker

## 🎯 Objetivo

El objetivo de esta práctica es configurar un **servidor Nginx** dentro de un entorno **Docker** que sirva una aplicación PHP por **HTTPS**, utilizando un **certificado SSL/TLS autofirmado**.

Esto permite:
1.  Redirigir automáticamente el tráfico HTTP a HTTPS.
2.  Visualizar cómo Nginx utiliza certificados SSL/TLS para cifrar la comunicación.
3.  Entender la diferencia entre las conexiones HTTP (inseguras) y HTTPS (seguras).

---

## 🏗️ Estructura del Proyecto

La estructura de carpetas requerida para este proyecto es la siguiente:
proyecto-https/
 ├─ code/
 │   └─ index.php
 ├─ nginx.conf
 ├─ docker-compose.yml
 └─ certs/
     ├─ server.crt
     └─ server.key
