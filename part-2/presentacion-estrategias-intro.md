---
theme: gaia
_class: lead
paginate: false
backgroundColor: #e7252f
backgroundImage: url('./../img/background-white.png')
color: #e7252f
marp: true
---
<!-- _backgroundImage: url('./../img/background-red.png') -->
<!-- _color: white -->

# 2.5 Desplegando Contenedores

---
# Contenido

- Estrategias más comunes de despliegue.
    - Recreate
    - Rolling Update
    - Blue-Green / Red-Black / A/B
    - Shadow
    - Canary


---
# Cómo

Por cada una de las estrategias que veamos veremos y haremos algunas de ellas:
- Manual, `docker run`
- Manual, `docker-compose`
- Automática, `ansible`/`chef`/`puppet`/`saltstack`/etc..
- Automática, `kubernetes`
