# Live Call Guide — Maersk × Lowe's Home Delivery

> Herramienta interna de apoyo para agentes de Customer Experience durante llamadas en vivo

[![Demo en vivo](https://img.shields.io/badge/Demo-En_vivo-brightgreen?style=flat)](https://livecallguide.netlify.app/)
![Stack](https://img.shields.io/badge/Stack-HTML%20%C2%B7%20CSS%20%C2%B7%20JS-blue?style=flat)
![Deploy](https://img.shields.io/badge/Deploy-Netlify-00C7B7?style=flat&logo=netlify)

---

## El problema

Los agentes de CX de Maersk Last Mile manejan llamadas de entrega a domicilio para Lowe's en tiempo real — bajo presión, con múltiples variables simultáneas. Sin una guía estructurada, la calidad de la llamada dependía completamente de la experiencia individual del agente, haciendo difícil mantener consistencia, generar notas precisas y medir el desempeño de forma objetiva.

---

## La solución

Una herramienta web que corre directo en el navegador durante la llamada — sin instalación, sin login, sin fricción. Divide cada llamada en 5 etapas con checkpoints accionables y calcula un score de calidad en tiempo real.

**[→ Ver demo en vivo](https://livecallguide.netlify.app/)**

---

## Flujo de la llamada

| Etapa | Puntos | Qué cubre |
|---|---|---|
| Opening | 12 pts | Script de apertura, tono, empatía, ownership |
| Listen & Diagnose | 25 pts | Escucha activa, preguntas correctas, confirmación |
| Resolve It | 27 pts | Claridad de respuesta, manejo de objeciones, proactividad |
| Close Strong | 20 pts | Recap, próximos pasos, pitch de encuesta |
| Notes & Done | 16 pts | Nota EDP, disposición correcta |

**Total: 100 puntos**

---

## Funcionalidades

- **Score en vivo** — anillo visual 0–100 con mini-barras por sección
- **Notas EDP automáticas** — se generan en tiempo real conforme el agente llena los campos
- **Auto-avance de secciones** — al completar una etapa abre la siguiente automáticamente
- **Disposiciones rápidas** — 12 opciones con un tap (Delivery Confirmed, NAH, Ghost Call, etc.)
- **Timer de llamada** — visible en header y sidebar
- **Modo oscuro** — persistente entre sesiones via localStorage
- **Score final animado** — resumen por sección al cerrar la llamada
- **Reset instantáneo** — nueva llamada en un clic

---

## Stack

```
HTML5 · CSS3 · JavaScript (vanilla)
Google Fonts — Inter + JetBrains Mono
Sin frameworks · Sin dependencias · Un solo archivo
```

La decisión de mantenerlo en vanilla JS fue intencional: cero dependencias significa cero puntos de falla durante una llamada en vivo.

---

## Contexto

Desarrollado internamente para el equipo de **Maersk Last Mile** operando las entregas a domicilio de **Lowe's**. La herramienta nació de identificar un proceso manual repetitivo — tomar notas EDP + evaluar calidad — y convertirlo en un flujo guiado y automatizado.

**Tipo de proyecto:** Herramienta operacional en uso real  
**Industria:** Logística de última milla / Customer Experience  
**Mercado:** EE.UU. (operaciones Lowe's)

---

## Cómo usarlo

No requiere instalación. Abre [livecallguide.netlify.app](https://livecallguide.netlify.app/) en el navegador al inicio de cada llamada.

Para correrlo localmente:

```bash
git clone https://github.com/tu-usuario/live-call-guide.git
cd live-call-guide
# Abrir index.html en el navegador — no requiere servidor
```

---

## Autor

**Edgar Rocha Huerta** — Dispatcher & CX Specialist @ Maersk  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Edgar_Rocha-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/edgar-rocha-huerta-5b81682a1/)
