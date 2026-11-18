# I&T – Contenido y UX-UI del sitio web corporativo

Módulo de **contenido, casos de éxito y manual de usuario** del sitio web de
**I&T Investigación y Tecnología SpA**.

- **Responsable:** Isabella Lasso Florez (Concepción)
- **Docente guía:** Margot Herrera
- **Período:** 16/11/2026 – 29/01/2027 (aprox.)
- **Modalidad:** virtual · entregas semanales los **viernes**
- **Rama de trabajo:** `feature/contenido-ux`

## 1. Objetivo

Diseñar y producir el contenido y la experiencia de usuario de las secciones
informativas del sitio (**Quiénes somos, Servicios, Casos de éxito, Contacto**),
asegurando coherencia visual, claridad y accesibilidad, y documentar todo el
sitio en un **manual de usuario**.

## 2. Alcance

**Incluye**

- Textos del sitio (Quiénes somos, Servicios, Contacto).
- Casos de éxito (estructura y redacción).
- Guía de estilo (colores, tipografía, tono).
- Diseño UX-UI de esas secciones (wireframes en Figma, accesibilidad y responsivo).
- Integración de textos y diseño en el sitio (React + HTML/CSS).
- Manual de usuario del sitio completo (PDF).

**No incluye**

- Programación intensiva ni lógica de aplicación.
- Secciones técnicas del sitio fuera de las informativas.

## 3. Stack

| Uso | Herramienta |
|---|---|
| Diseño | Figma (gratuito) |
| Contenido | Markdown / Google Docs |
| Integración | React + HTML/CSS |
| Documentación | PDF / GitHub Wiki |
| Repositorio | GitHub (rama `feature/contenido-ux`) |
| Despliegue | Vercel |

## 4. Estructura del repositorio

```
iyt-contenido-ux/
├── README.md                  ← este archivo
├── docs/
│   ├── inventario-contenidos.md   ← Semana 1
│   ├── informes/
│   │   └── semana-01.md           ← informe de 5 líneas
│   └── guia-estilo/               ← Semana 2
├── contenido/                 ← textos finales (semanas 5–8)
├── diseno/                    ← enlaces/exportes de Figma (semanas 3–4)
└── manual/                    ← manual de usuario (semanas 13–14)
```

## 5. Cronograma

| Semana | Objetivo | Entregable |
|---|---|---|
| 1 | Onboarding + Git + alcance | Repo + README + inventario de contenidos |
| 2 | Guía de estilo | Documento de guía de estilo |
| 3–4 | Wireframes de secciones informativas | Wireframes en Figma |
| 5–6 | Textos finales (Quiénes somos, Servicios) | Documento de contenido aprobado |
| 7–8 | Casos de éxito | Sección redactada y maquetada |
| 9–10 | UX-UI aplicado (accesibilidad, responsivo) | Ajustes + pruebas de responsividad |
| 11 | Integración en el sitio | Textos y diseño en React |
| 12 | Pruebas de usabilidad + corrección | Lista de mejoras aplicadas |
| 13–14 | Manual de usuario | PDF del manual completo |
| 15 | Revisión final + despliegue | Verificación en URL pública |
| 16 | Demo final + cierre | Video demo + retroalimentación |

## 6. Flujo de trabajo con Git

1. Trabajar siempre en la rama `feature/contenido-ux`.
2. Un commit por entrega semanal como mínimo, con mensaje claro, por ejemplo:
   `semana 1: repo, README e inventario de contenidos`.
3. Entregar cada **viernes**: commit + demo + informe de 5 líneas (`docs/informes/`).

## 7. Comunicación y ajustes

- Comunicación por **WhatsApp o correo** (sin videollamadas).
- Instrucciones y feedback **por escrito**, claros y paso a paso.
- Pausas visuales con la regla 20-20-20.
- Flexibilidad el día 9 de cada mes (mañana).
