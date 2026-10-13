# MemoriaconCartas
Juego de memoria clásico (Memory Match) con la baraja española del Truco, desarrollado como Telegram Mini App. Avanza por niveles, encuentra las parejas de Oros, Copas, Espadas y Bastos. Construido con HTML5/JS, respuesta háptica e integración de anuncios interstitials cada 3 niveles.
# 🎴 Memoria de Cartas Españolas — Telegram Mini App 🇻🇪

![Memoria de Cartas Españolas Banner](watermarked_img_1326547483738364946.jpg)

**Memoria de Cartas Españolas** es un dinámico juego de memoria (*Memory Match*) diseñado específicamente como una **Telegram Mini App**, utilizando la icónica baraja española tradicional (Oros, Copas, Espadas y Bastos).

El objetivo es poner a prueba la agilidad mental y la memoria visual del jugador, haciendo que descubra y empareje las cartas en el menor número de intentos y tiempo posible a medida que la dificultad se incrementa nivel tras nivel.

---

## 🎮 Mecánica de Juego

* **Progreso por Niveles:** El número de cartas en el tablero aumenta a medida que el jugador supera los desafíos:
  * **Nivel 1:** Grilla de $3 \times 4$ (6 parejas / 12 cartas).
  * **Nivel 2:** Grilla de $4 \times 4$ (8 parejas / 16 cartas).
  * **Nivel 3:** Grilla de $4 \times 5$ (10 parejas / 20 cartas).
  * **Niveles Avanzados:** Grillas complejas y mayores combinaciones de naipes.
* **Flujo del Juego:**
  1. Las cartas permanecen ocultas mostrando el reverso tradicional.
  2. El jugador selecciona dos cartas para voltearlas.
  3. Si las cartas coinciden, se mantienen descubiertas y se deshabilitan.
  4. Si no coinciden, se muestran brevemente para memorizar su ubicación y vuelven a ocultarse automáticamente.
* **Condición de Victoria:** Revelar todas las parejas del tablero para desbloquear el siguiente nivel.

---

## 💡 Características Principales

* 🎴 **Efectos 3D Fluidos:** Animación de volteo de cartas implementada en CSS3 puro (`transform-style: preserve-3d`) para un acabado realista.
* 📳 **Respuesta Háptica (Haptic Feedback):** Integración nativa con la API de Telegram para emitir vibraciones al acertar o fallar una combinación.
* 📱 **Diseño Mobile-First:** Interfaz adaptada para pantallas táctiles con renderizado optimizado y respuesta inmediata.
* 💾 **Persistencia de Progreso:** Almacenamiento local (`localStorage`) para registrar el nivel actual y el récord de tiempo/movimientos.

---

## 💰 Estrategia de Monetización

* **Anuncios Interstitials (Pantalla Completa):**
  * Se muestra un anuncio a pantalla completa de forma no invasiva al **completar cada 3 niveles** (Nivel 3, 6, 9, etc.).
  * Transición fluida integrada en la pantalla de "Nivel Completado" antes de pasar al siguiente reto.

---

## 🛠️ Tecnologías Utilizadas

* **Frontend:** HTML5, CSS3 (3D Transforms & Grid), JavaScript (ES6+).
* **Telegram Integration:** `@telegram-apps/sdk` / Telegram WebApp JS.
* **Monetización:** Redes de anuncios publicitarios para Telegram Mini Apps (Adsgram, Monetag, etc.).
* **Alojamiento:** Servidor con soporte HTTPS (Vercel, Netlify o Render).
