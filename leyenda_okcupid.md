
# Leyenda de columnas - Dataset OkCupid (versión sin ensayos)

Este documento describe cada columna presente en el archivo `okcupid_enriquecido_sin_essays.csv`, indicando si es una columna original del dataset o añadida para enriquecer el análisis.

---

## 🧾 Columnas originales del dataset de OkCupid

| Columna              | Descripción |
|----------------------|-------------|
| `age`                | Edad del usuario |
| `status`             | Estado sentimental (`single`, `available`, etc.) |
| `sex`                | Sexo (`m`, `f`, `o`) |
| `orientation`        | Orientación sexual (`straight`, `gay`, `bisexual`) |
| `body_type`          | Tipo de cuerpo |
| `diet`               | Preferencias alimenticias |
| `drinks`             | Consumo de alcohol |
| `drugs`              | Consumo de drogas |
| `education`          | Nivel educativo |
| `ethnicity`          | Origen étnico |
| `height`             | Altura en pulgadas |
| `income`             | Ingresos anuales (`-1` si no se indica) |
| `job`                | Profesión |
| `last_online`        | Fecha de última conexión |
| `location`           | Ciudad o zona del perfil |
| `offspring`          | Información sobre hijos |
| `pets`               | Preferencia por mascotas |
| `religion`           | Creencias religiosas |
| `sign`               | Signo zodiacal |
| `smokes`             | Fuma o no |
| `speaks`             | Idiomas hablados |

---

## 🆕 Columnas añadidas para enriquecer el análisis

| Columna                    | Descripción |
|----------------------------|-------------|
| `profile_completeness`     | Porcentaje de ensayos completados (0–100%) antes de su eliminación |
| `essay_word_count`         | Total de palabras escritas originalmente en los ensayos |
| `profile_views_last_month`| Nº de veces que fue visto el perfil (simulado) |
| `messages_sent_last_week` | Nº de mensajes enviados (estimado según actividad) |
| `likes_received`           | Likes recibidos (estimado según completitud y texto) |
| `mutual_matches`           | Nº de coincidencias mutuas (basado en likes) |
| `time_spent_daily`         | Minutos diarios promedio usando la app (estimado) |
| `swipe_right_ratio`        | Proporción de swipes hacia la derecha (like) entre 0 y 1 |
| `swipe_right_label`        | Categoría según el ratio: |
|                            | - `Cautious`: hasta 0.30 |
|                            | - `Balanced`: entre 0.31 y 0.60 |
|                            | - `Optimistic`: más de 0.60 |

---
