# Vibe Coding con Inteligencia Artificial - Mapa Conceptual Interactivo

Este repositorio contiene una aplicación web interactiva de un Mapa Conceptual Avanzado diseñado para explicar los conceptos principales de la Inteligencia Artificial y su relación directa con el Vibe Coding como práctica de prototipado rápido.

La aplicación está diseñada en un único archivo auto-contenido e integra llamadas dinámicas a los modelos de lenguaje de Google mediante la API de Gemini.

## 🔗 Demo en Vivo

Puedes explorar e interactuar con el mapa conceptual directamente en producción aquí:

👉 [https://msusanacortes.github.io/mapa_conceptual_vibecoding/](https://msusanacortes.github.io/mapa_conceptual_vibecoding/)

## 🎯 Objetivo de la Actividad

Elaborar y documentar un mapa conceptual dinámico que clarifique la jerarquía y conexiones semánticas de la Inteligencia Artificial y el rol del Vibe Coding en la creación de prototipos de software ágiles, identificando los alcances, limitaciones y la imperante necesidad de la validación humana en cada ciclo iterativo.

## 🧩 Conceptos Clave Implementados

El mapa estructura jerárquicamente y conecta de forma semántica los siguientes conceptos requeridos:

1. **Vibe Coding**: Práctica donde el humano establece la intención, valida los resultados y dirige la generación rápida de software asistido por IA.
2. **Inteligencia Artificial (IA)**: El marco científico-técnico general que simula capacidades cognitivas humanas.
3. **IA Generativa**: La rama de la IA enfocada en la creación de contenido nuevo (código, texto, etc.).
4. **Modelos de Lenguaje (LLMs)**: Redes neuronales probabilísticas que interpretan y generan código.
5. **Prompt**: La especificación detallada e instrucción base para dirigir a la IA.
6. **Validación Humana**: El filtro crítico de pruebas, depuración y auditoría lógica del desarrollador.
7. **Iteración**: Ciclo continuo de retroalimentación para refinar el prototipo.
8. **Prototipo Digital**: El producto interactivo mínimo (MVP) obtenido al final de la sesión de Vibe Coding.
9. **Alcances de la IA**: Automatización de código base, traducción de lenguajes y democratización del desarrollo.
10. **Límites/Riesgos de la IA**: Alucinaciones, vulnerabilidades de seguridad ocultas y falta de visión holística de arquitectura.

## ✨ Características de la Aplicación Interactiva

- **Lienzo con Distribución Anti-Traslape**: Coordenadas espaciadas en un lienzo de 980px × 660px para evitar superposiciones de textos o líneas de conexión.
- **Zoom y Paneo Inteligente**: Controles de lupa (+, −, Reset) integrados para una visualización óptima en cualquier resolución.
- **Exploración de Relaciones en Tiempo Real**: Panel lateral que muestra definiciones, ejemplos en Vibe Coding y vínculos específicos del nodo seleccionado al hacer clic.
- **Laboratorio IA Activo (Gemini API)**:
  - *Optimizador de Prompts*: Transforma ideas de software abstractas en prompts sistemáticos profesionales de ingeniería.
  - *Desafío de Depuración y Validación*: Genera problemas de código erróneo a la medida con IA, califica tu prompt correctivo y te da retroalimentación educativa inmediata.
- **Estructura de Texto Estructurada**: Pestaña dedicada para ver los conceptos de forma tradicional lineal para apuntes rápidos.
- **Exportador de Diagramas**: Generación de código Mermaid.js para renderizar el mapa en Notion, Obsidian, GitHub o Draw.io.

## 🛠️ Tecnologías Utilizadas

- HTML5 & Vanilla JavaScript (ES6+)
- Tailwind CSS (vía CDN para estilos premium adaptables y modernos)
- Lucide Icons (para la interfaz visual de los nodos)
- Gemini API (`gemini-2.5-flash-preview-09-2025` con exponencial backoff de 5 reintentos para máxima tolerancia a fallos)

## 🚀 Cómo Ejecutar de Forma Local

1. Clona el repositorio:

```bash
git clone https://github.com/msusanacortes/mapa_conceptual_vibecoding.git
```

2. Abre el archivo `index.html` en cualquier navegador web moderno (no requiere de compiladores o servidores locales adicionales).
