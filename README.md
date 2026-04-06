# Stack de Salud Laboral: Ingeniería de Prevención en IT 🛡️ SE-TR-INF

> **Repositorio técnico para la optimización del rendimiento del "Humanware" y la mitigación de fallos en entornos de desarrollo.**

## 🔍 1. Análisis de Riesgos en el Ciclo de Vida del Desarrollador

En el sector informático, los riesgos laborales se tratan como errores de configuración en el entorno físico que degradan el rendimiento sistémico a largo plazo.

---

### 🪵 Capa 1: Hardware y Ergonomía (Physical Layer)

El mal posicionamiento de los periféricos genera "latencia" en la salud musculoesquelética y fallos en la estructura ósea.

* **Síndrome del Túnel Carpiano:** Compresión del nervio mediano por ángulos de muñeca incorrectos durante el input.
    * **Fix:** Uso de teclados mecánicos ergonómicos y ratones verticales para mantener una posición neutra.
* **Monitor Out-of-Range:** Desalineación cervical por altura incorrecta del display.
    * **Fix:** El borde superior del monitor debe estar a la altura de los ojos, manteniendo una distancia de entre $60\text{ cm}$ y $80\text{ cm}$.



---

### 👁️ Capa 2: Interfaz Visual y Fatiga (Output Layer)

La exposición prolongada a altas tasas de refresco y emisiones de luz azul provoca el **Síndrome Visual Informático (SVI)**.

* **Refresco Ocular:** El parpadeo humano desciende de 20 a 5 veces por minuto en estado de "coding flow".
* **Implementación de la Regla 20-20-20:**
    * `Cron(every 20min) -> Look(6m) -> Sleep(20s)`
* **Gestión de Iluminación:** Evitar el deslumbramiento directo y mantener un ratio de contraste equilibrado entre la pantalla y la luz ambiental.

---

### 🧠 Capa 3: Estado Psicosocial (Logic Layer)

Riesgos derivados de la gestión de procesos, procesos de *deployment* estresantes y carga cognitiva.

* **Tecnoestrés / Burnout:** Desbordamiento del búfer mental por multitarea masiva y plazos de entrega (*deadlines*) críticos.
* **Prevención de Fallos:**
    * **Deep Work:** Segmentación de bloques de trabajo para minimizar el *context switching*.
    * **Desconexión Digital:** Terminación de procesos y cierre de sockets de comunicación (Slack/Teams) tras la jornada laboral para permitir el *recovery* del sistema.



---

## 🛠️ Checklist de Auditoría del Puesto IT

| Componente | Especificación Técnica | Estado |
| :--- | :--- | :--- |
| **Asiento** | Soporte lumbar dinámico + 5 puntos de apoyo. | [ ] |
| **Teclado** | Posición que evite la desviación cubital. | [ ] |
| **Monitor** | Soporte VESA ajustable y panel antiparpadeo. | [ ] |
| **Ambiente** | Temperatura: 20°C - 24°C | Humedad: > 40%. | [ ] |

---

## 🔗 Referencias Técnicas y Normativa

* **INSST (España):** [Guía técnica para el trabajo con pantallas de visualización](https://www.insst.es/documentacion/catalogos-de-publicaciones/guia-tecnica-para-la-evaluacion-y-prevencion-de-los-riesgos-relativos-a-la-utilizacion-de-equipos-con-pantallas-de-visualizacion).
* **OSHA (Internacional):** [Computer Workstation Safety & Health](https://www.osha.gov/).
* **ISO 9241:** [Ergonomía de la interacción persona-sistema](https://www.iso.org/standard/63900.html).

---

## 📄 Licencia
Este repositorio se distribuye bajo la [Licencia MIT](https://opensource.org/licenses/MIT).
