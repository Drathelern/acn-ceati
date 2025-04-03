# Repositorio de Proyectos de la iniciativa de CEATI de Accenture en conjunto con la UANL

Este repositorio forma parte de la iniciativa de **CEATI** de **Accenture** en conjunto con la **Universidad Autónoma de Nuevo León (UANL)** .

Aquí se alojarán los proyectos desarrollados por los equipos participantes en los distintos proyectos de CEATI.

---

## 📁 Estructura del Repositorio

Todos los proyectos deben ubicarse en la carpeta:

```
projects/
```

Dentro de esta carpeta, cada equipo deberá crear su propia subcarpeta utilizando el siguiente **naming convention**:

```
projects/<nombre-equipo>/
```

### Ejemplos:
- `projects/umbrella_tech/`
- `projects/sss_initiative/`

---

## 🚀 Flujo de Trabajo

Cada equipo deberá trabajar en su propia rama y levantar un **Pull Request (PR)** hacia la rama `dev` siguiendo estas indicaciones:

1. Crear una nueva rama desde `dev`:
   ```bash
   git checkout dev
   git checkout -b <nombre-equipo>
   ```
   Ejemplo:
   ```bash
   git checkout -b sss_initiative
   ```

2. Subir sus cambios y hacer `push` a su nueva rama:
   ```bash
   git push origin<codigo-materia>_<nombre-equipo>
   ```

3. Levantar un **Pull Request (PR)** hacia la rama `dev`.

4. Asegurarse de que su PR contenga solamente los archivos de su carpeta dentro de `projects/`.

---

## ✅ Requisitos para aceptar un PR

- La carpeta del proyecto debe seguir el formato de nombre establecido.
- El contenido debe estar completamente dentro de su carpeta correspondiente en `projects/`.
- No debe haber conflictos con otros equipos.
- El PR debe estar dirigido a la rama `dev`.
- Una realizado el PR se considera que no requiere ninguna modificacion y esta listo para su Revision

---

## 📬 Contacto

Para cualquier duda técnica o relacionada con el repositorio, favor de comunicarse con los encargados de CEATI o su docente correspondiente.

---

> ¡Gracias por formar parte de esta iniciativa!
