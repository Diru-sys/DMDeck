# DMDeck
- Pantalla de control web para Dungeon Masters: combate, ambientación sonora, mapas y dados en un solo panel durante la sesión de *Dungeons & Dragons 5e*.
TFG del Ciclo Formativo de Grado Superior en Desarrollo de Aplicaciones Web (2º DAW, curso 2026/2027).


## ¿Qué problema resuelve?
Durante una sesión, el Dungeon Master alterna entre manuales, hojas de cálculo, reproductores de música y blocs de notas. Eso ralentiza los combates y provoca errores al llevar estados y daño.
DMDeck reúne todo en un panel ligero y gratuito, sin la complejidad de las mesas virtuales completas (VTT).


## Funcionalidades
**Esenciales**
- [ ] Usuarios y acceso (registro, login)
- [ ] Campañas (hasta 2 por usuario) con personajes y criaturas
- [ ] Tracker de combate: iniciativa, turnos, vida, estados alterados y cronómetro
- [ ] Ambientación sonora: música de fondo y soundboard de efectos
- [ ] Visor de mapas
- [ ] Tiradas de dados animadas
- [ ] Notas de campaña
- [ ] Enlaces de consulta (wikis y referencias)


## Tecnologías
| Capa | Tecnología |
|---|---|
| Frontend | HTML, CSS, JavaScript, Bootstrap 5 |
| Backend | Python, Django |
| Base de datos | MySQL |
| Contenedores | Docker |
| Control de versiones | Git y GitHub |


## Instalación
> 🚧 Próximamente. Se completará cuando el entorno con Docker esté listo.

<!-- Cuando funcione, sustituye lo de arriba por esto:

git clone https://github.com/Diru-sys/proyecto_dnd.git
cd proyecto_dnd
cp .env.example .env
docker compose up --build

Después abre http://localhost:8000 en el navegador. -->


## Estructura del repositorio
- `backend/`: aplicación Django
- `frontend/`: plantillas, estilos y scripts
- `database/`: datos iniciales
- `docs/`: memoria y diagramas
---
## Autor
**Carlos Sánchez Damas**