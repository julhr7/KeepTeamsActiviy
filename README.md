# 🟢 Keep Teams Active

Un script ligero y eficiente diseñado para mantener tu estado "Activo" en Microsoft Teams (y otras plataformas de comunicación corporativa como Slack o Zoom). El programa evita que tu sesión pase a estado "Ausente" o "Inactivo" simulando de forma invisible actividad en el sistema, como micro-movimientos del ratón o pulsaciones de teclas inofensivas.

---

## ✨ Características Principales

*   **100% Indetectable:** Simula interacciones humanas naturales sin interferir con tu trabajo real.
*   **Ligero y optimizado:** Consume recursos mínimos del sistema; puede ejecutarse en segundo plano todo el día.
*   **Plug & Play:** Configuración mínima requerida. Ejecútalo y olvídate.
*   **Intervalos personalizables:** Permite ajustar el tiempo entre cada "interacción" simulada.

---

## 🚀 Instrucciones de Instalación y Ejecución

*(Nota: Adapta estos comandos dependiendo de si tu script está hecho en Python, PowerShell o C#)*

### 📋 Requisitos previos
*   [Python 3.x](https://www.python.org/downloads/) instalado (Si es un script de Python).
*   Librerías requeridas (ej. `pyautogui` o `keyboard`).

### 💻 Pasos para ejecutar

1. **Clonar el repositorio:**
```bash
   git clone [https://github.com/julhr7/KeepTeamsActiviy.git](https://github.com/julhr7/KeepTeamsActiviy.git)
   ```

2. **Navegar a la carpeta del proyecto:**
```bash
   cd KeepTeamsActiviy
   ```

3. **Instalar dependencias** (Si aplica):
```bash
   pip install -r requirements.txt
   ```

4. **Ejecutar el script:**
```bash
   python main.py
   ```
   *(Si el archivo tiene otro nombre, como `keep_active.py` o un `.ps1`, reemplázalo aquí).*

---

## ⚙️ ¿Cómo funciona?

Una vez iniciado, el script se ejecuta en un bucle infinito (o durante el tiempo que especifiques). Cada `X` segundos (configurable), el sistema enviará una señal al sistema operativo (como mover el cursor 1 píxel de ida y vuelta o presionar la tecla F15) para reiniciar el temporizador de inactividad de Windows/Mac. 

Para detener el script, simplemente presiona `Ctrl + C` en la terminal donde se está ejecutando.

---

## ⚠️ Aviso Legal y Responsabilidad (Disclaimer)

Este proyecto ha sido creado con fines **estrictamente educativos y de desarrollo personal**. 

El uso de scripts para eludir las políticas de seguimiento de actividad o manipular los estados de presencia puede violar los términos de servicio de tu empleador o de Microsoft. El autor de este repositorio (`julhr7`) no se hace responsable de las posibles consecuencias disciplinarias o bloqueos de cuenta derivados del uso de esta herramienta en entornos corporativos. **Úsalo bajo tu propio riesgo.**

---

## 🛠️ Tecnologías Utilizadas

*   **Lenguaje:** Python / PowerShell *(Ajustar según tu código)*
*   **Librerías principales:** OS, Time, PyAutoGUI *(Ajustar según tu código)*
