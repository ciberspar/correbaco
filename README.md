# 🐢 Comebaco: Ataque Fuego 🔥

> **¡Los pájaros del balcón se volvieron locos y atacan a Baco con antorchas teledirigidas!**
> Un juego arcade retro de esquive por carriles con dificultad progresiva, programado en HTML5 Canvas y Tailwind CSS.

---

## 🎮 Historia del Juego

**Baco**, la fiel tortuga argentina, solo quiere disfrutar de un día tranquilo en el balcón de Córdoba. Pero las aves de la zona no se lo van a hacer fácil: han formado una escuadra de combate y están equipadas con antorchas encendidas. 

Tu misión es ayudar a Baco a cambiar de carril a tiempo, esquivar el vuelo directo de los pájaros y evitar los proyectiles de fuego teledirigidos.

---

## ⚡ Características Principales

* **Sistema de 3 Carriles:** Movimiento fluido hacia arriba y hacia abajo para esquivar obstáculos.
* **Pájaros Lanzallamas 🐦🔥:** Enemigos que calculan la posición de Baco y le disparan antorchas encendidas que lo persiguen.
* **Dificultad Progresiva:** Cada 80 puntos subís de nivel. Los pájaros vuelan más rápido, atacan con mayor frecuencia y las antorchas ganan velocidad.
* **Récord Local (`localStorage`):** Guarda tu puntuación máxima automáticamente en el navegador para que intentes superarte.
* **Controles Híbridos:** Diseñado para jugarse tanto en PC (teclado) como en dispositivos móviles (pantalla táctil).

---

## 🕹️ Cómo Jugar

### ⌨️ En Computadora (Teclado)
* **Flecha Arriba (`↑`)**: Mover a Baco al carril superior.
* **Flecha Abajo (`↓`)**: Mover a Baco al carril inferior.
* **Barra Espaciadora / R**: Iniciar el juego o reiniciar tras un Game Over.

### 📱 En Celular / Tablet (Pantalla Táctil)
* **Toque en la mitad superior de la pantalla**: Subir de carril.
* **Toque en la mitad inferior de la pantalla**: Bajar de carril.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5 Canvas**: Renderizado 2D liviano a 60 FPS sin dependencias pesadas.
* **JavaScript ES6**: Lógica de vectores, cálculo de ángulos de disparo y colisiones por distancia.
* **Tailwind CSS**: Estilizado moderno para contenedores y tipografía arcade.
* **Google Fonts**: Fuente retro *Press Start 2P*.

---

## 🚀 Cómo Ejecutar Localmente

No requiere instalaciones complejas ni servidores Node.js. 

1. Clona este repositorio o descarga el archivo `comebaco.html`:
   ```bash
   git clone [https://github.com/tu-usuario/comebaco.git](https://github.com/tu-usuario/comebaco.git)
