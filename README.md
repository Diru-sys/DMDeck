# DMDeck

> Pantalla de control web modular (*DM Screen* interactiva) concebida para la gestión y agilización de sesiones en directo de *Dungeons & Dragons 5e*.

Proyecto Final de Grado (TFG) — Ciclo Formativo de Grado Superior en Desarrollo de Aplicaciones Web (2º DAW, Curso 2026/2027).

---

## Estado del Proyecto
En fase de desarrollo activo — **H1: Idea, Investigación y Alcance completados**.

---

## Problema y Propuesta de Valor

* **El Problema:** Durante las sesiones de rol presenciales o híbridas, el director de juego (*Dungeon Master*) sufre sobrecarga cognitiva al alternar entre múltiples herramientas inconexas (manuales impresos, hojas de cálculo, reproductores externos de música y blocs de notas). Esta dispersión ralentiza los combates, interrumpe el ritmo narrativo y provoca errores frecuentes en el cálculo de estados y daño.
* **Nuestra Propuesta:** DMDeck consolida en un único panel ligero la gestión operativa del combate, la ambientación sonora dual y el soporte visual de mapas y tiradas de dados. Elimina la complejidad y pesadez técnica de las plataformas de mesa virtual completas (VTT) y suprime las barreras de pago de herramientas oficiales.

---

## Requisitos Funcionales

### Núcleo de la Aplicación
* **RF-01 [MUST] Gestión de usuarios y acceso:** Autenticación de sesiones y gestión de cuenta del director de juego.
* **RF-02 [MUST] Gestión de campañas y entidades:** Persistencia de campañas, personajes jugadores y perfiles de criaturas con estadísticas clave (PG, CA, modificadores).
* **RF-03 [MUST] Rastreador de combate (*Combat Tracker*):** Ordenación automática de turnos por iniciativa, cálculo interactivo de daño/puntos de golpe y supervisión de estados alterados con ayuda visual.
* **RF-04 [MUST] Sistema de ambientación sonora dual:** Reproducción simultánea de música ambiental en bucle y consola de efectos de sonido (*soundboard*) a partir de archivos locales.
* **RF-05 [MUST] Visor centralizado de mapas:** Carga y navegación de mapas/planos de apoyo en el panel principal sin recarga de contexto.
* **RF-06 [MUST] Bandeja de dados integrada:** Motor de tiradas virtuales animadas accesible desde la propia vista de combate.

### Extensiones del Sistema
* **RF-07 [SHOULD] Bloc de notas contextuales:** Editor ligero para anotaciones de sesión asociadas a cada encuentro o campaña.
* **RF-08 [COULD] Compendio de consulta rápida:** Acceso directo a tablas de referencia y reglas básicas del documento de sistema abierto (SRD 5.1).

---

## Requisitos No Funcionales

* **RNF-01 [Arquitectura]:** Aplicación web full-stack modular con interfaz optimizada para pantallas de ordenador portátil y sobremesa.
* **RNF-02 [Rendimiento e Interactividad]:** Actualización inmediata de estados de combate y manipulación de vida sin recargas de página (*Single Page Application* o renderizado dinámico por componentes).
* **RNF-03 [Gestión de Recursos]:** Almacenamiento y procesamiento eficiente en cliente/servidor de archivos multimedia locales (pistas de audio e imágenes de alta resolución).
* **RNF-04 [Compatibilidad]:** Ejecución estándar garantizada en motores basados en Chromium y Gecko (Google Chrome, Firefox, Microsoft Edge, Brave).

---

## 👤 Autor
* **Carlos Sánchez Damas** — *Desarrollo de Aplicaciones Web (2º DAW)*
