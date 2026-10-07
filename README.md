# DMDeck

> Aplicación web modular concebida como pantalla de control centralizada (*DM Screen* interactiva) para directores de juego de *Dungeons & Dragons 5e*.

Proyecto Final de Grado (TFG) — Ciclo Formativo de Grado Superior en Desarrollo de Aplicaciones Web (2º DAW).

---

## Estado del proyecto
En desarrollo activo — **Fase H1 (Idea, Investigación y Alcance inicial definida)**.

---

## Problema y Propuesta de Valor
* **Problema:** En sesiones de rol en directo, el máster sufre dispersión y sobrecarga cognitiva al alternar entre múltiples herramientas inconexas (manuales, hojas de cálculo, reproductores de audio externos y notas físicas), ralentizando el ritmo de los combates y rompiendo la inmersión.
* **Propuesta:** DMDeck unifica en un único panel ligero la gestión de combates, la ambientación acústica y el soporte visual de mapas y dados, evitando la complejidad excesiva de plataformas VTT pesadas y eliminando los muros de pago de plataformas oficiales.

---

## Requisitos Funcionales (MVP)

* **RF-01 [MUST] Gestión de usuarios y sesiones:** Registro, autenticación y gestión de perfil del director de juego.
* **RF-02 [MUST] Gestión de campañas y fichas:** Persistencia de campañas, perfiles de personajes jugadores y estadísticas de monstruos (PG, CA, modificadores).
* **RF-03 [MUST] Rastreador de combate (*Combat Tracker*):** Cálculo y ordenación de iniciativa, conteo dinámico de vida/daño y asignación visual de estados alterados.
* **RF-04 [MUST] Ambientación sonora dual:** Reproductor de música ambiental en bucle y botonera de efectos de sonido (*soundboard*) con soporte de audio local.
* **RF-05 [MUST] Visor de mapas integrado:** Carga y visualización de planos/mapas de referencia rápida durante la sesión.
* **RF-06 [MUST] Bandeja de dados virtuales:** Sistema de tiradas de dados 3D/animadas integrado en el propio panel.
* **RF-07 [SHOULD] Bloc de notas rápidas:** Editor ligero de anotaciones contextuales por campaña o encuentro.
* **RF-08 [COULD] Enlaces de consulta rápida:** Acceso directo a reglas y tablas del SRD 5.1.

> *Límite de alcance inicial:* La versión 1.0 se centra exclusivamente en el panel de control del director. Se excluye la sincronización multiusuario en tiempo real para jugadores (tablero compartido por WebSockets y niebla de guerra).

---

## Requisitos No Funcionales

* **RNF-01 [Arquitectura]:** Aplicación web full-stack con diseño responsive y modular para escritorio/portátil.
* **RNF-02 [Rendimiento]:** Interfaz optimizada para cambios de turno y cálculo de daño en tiempo real sin recarga de página.
* **RNF-03 [Almacenamiento]:** Gestión eficiente y almacenamiento local de archivos multimedia (imágenes de mapas y pistas de audio).
* **RNF-04 [Compatibilidad]:** Soporte para navegadores web modernos (Chromium, Firefox, Safari).

---

## 👤 Autor
* **Carlos Sánchez Damas** — *2º DAW (Curso 2026/2027)*
