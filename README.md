# ⚔️ Hero's Path: La Sombra del Norte

RPG de aventura y fantasía desarrollado con **RPG Maker MV**, jugable directamente en el navegador.

> En las profundidades heladas de las catacumbas del norte, un antiguo mal conocido como el
> **Rey Demonio** se prepara para despertar. Si logra hacerlo, desatará un ejército de monstruos
> y sumirá todo el **Valle del Norte** bajo su dominio. Cuatro héroes se unen para fortalecerse,
> ayudar a los pueblos y adentrarse en la mazmorra antes de que sea demasiado tarde.

---

## 🎮 Cómo jugar

| Acción | Tecla |
|---|---|
| Moverse | Flechas |
| Accionar / hablar / examinar | `Z` · `Enter` · `Espacio` |
| Menú | `X` · `Esc` |
| Salto rápido por diálogos | `Ctrl` |

**Jugar en línea:** entra al despliegue de Vercel del repositorio (o ejecuta `index.html` localmente).
Las partidas se guardan automáticamente en el navegador.

---

## 🗺️ El mundo

| Mapa | Descripción |
|---|---|
| **mapa1** | Mapa principal del Valle del Norte: punto de partida y conexión a todas las zonas |
| **sala_entrenamiento** | Gimnasio con 3 estaciones de entrenamiento |
| **tienda** | Comercio del valle |
| **armeria** | Forja, muestrarios de armas, armaduras y pociones |
| **aldea_nieve** | Aldea nevada con misiones y habitantes |
| **Mazmorra** | Catacumbas del norte, con encuentros aleatorios |
| **Jefe** | Santuario final del Rey Demonio |

## 🧙 El grupo

| Héroe | Rol | Estilo |
|---|---|---|
| **Harold** | Héroe | Espada y escudo (equilibrio) |
| **Sara** | Guerrera | Hacha y armadura pesada |
| **Jorge** | Mago | Bastón y magia ofensiva |
| **Xochi** | Sacerdote | Arco y apoyo |

---

## ✨ Sistemas del juego

- 🏋️ **Entrenamiento por estaciones** — Ataque, Defensa y Magia: cada sesión de 10 segundos otorga
  +10 al parámetro de todo el grupo, con animaciones propias de cada disciplina. Al completar las
  3 estaciones el grupo **sube 1 nivel** (máximo 3 niveles por entrenamiento).
- 🪵 **Misiones de la aldea de nieve** — Ayuda a **Mateo** (leña) y **Elena** (carbón) para ganar
  **100 de oro** por misión. Los recursos **reaparecen 10 segundos después de salir del mapa**,
  así que las misiones pueden repetirse para juntar oro.
- 🛡️ **Armería y economía equilibrada** — Armas (400 oro), armaduras (250–300 oro) y pociones.
  El precio de compra y venta está balanceado para evitar abusos. El **yunque de forja** mejora
  tu Espada a *Espada mejorada* por 100 de oro.
- ⚔️ **Mazmorra con encuentros aleatorios** — Hordas de murciélagos, lodos, orcos y minotauros
  custodian el camino al santuario.
- 👹 **Batalla final contra el Rey Demonio** — 1000 HP, 3000 EXP y 5000 de oro. La derrota no
  termina la partida: el grupo se recupera y regresa a la mazmorra para intentarlo de nuevo.

---

## 🛠️ Tecnología

- **Motor:** RPG Maker MV (JavaScript / PixiJS)
- **Reproducción:** navegador web (Chrome, Firefox, Edge) o escritorio vía NW.js
- **Guardado:** `localStorage` del navegador
- **Estructura del proyecto:**

```
├── index.html          # punto de entrada del juego web
├── data/               # base de datos (mapas, personajes, items, tropas…)
├── js/                 # motor y plugins
├── img/                # sprites, tilesets, animaciones, fondos
├── audio/              # música (bgm), ambiente (bgs) y efectos (se)
└── fonts/              # tipografía del juego
```

---

## 🚀 Despliegue

El juego se publica automáticamente:

1. **GitHub** — repositorio con el código del juego
2. **Vercel** — despliegue continuo desde la rama `main` (Framework Preset: *Other*,
   sin comando de build)

Para actualizar el juego:

```bash
git add .
git commit -m "Descripción del cambio"
git push
```

Vercel detecta el push y publica la nueva versión en minutos.

---

## 📖 Historia (resumen)

- **Inicio:** el grupo se reúne en el mapa principal ante el aviso de que el Rey Demonio está a
  punto de despertar.
- **Preparación:** entrenamiento, equipo y misiones para fortalecer al equipo.
- **Ascenso:** la mazmorra y sus hordas de monstruos.
- **Clímax:** la batalla final contra el Rey Demonio en su santuario.

---

## ✍️ Créditos

- **Diseño e historia:** Jesús Francisco B. y equipo
- **Motor:** RPG Maker MV (Kadokawa Games)
- **Recursos gráficos y sonoros:** paquetes de RPG Maker MV y sprites personalizados del proyecto

*Hero's Path: La Sombra del Norte — proyecto de desarrollo de videojuegos.*
