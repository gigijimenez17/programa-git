# DISEÑO DE INTERFACES Y MOCKUPS
## MINDMEET - INTELIGENCIA ARTIFICIAL PARA REUNIONES

---

### PORTADA

**Proyecto:** MindMeet - Sistema de Reuniones con IA  
**Cliente:** Deloitte Colombia  
**Desarrollador:** InnovApp Solutions  
**Código de Ficha:** 3070387  

**Aprendices:**
- María Virginia Jiménez Narváez
- Brayan Barón

**Instructor:** José Alberto Egurrola Pedraza  
**Fecha:** Noviembre 2024  
**Lugar:** Palmira, Valle del Cauca, Colombia

---

## INTRODUCCIÓN

El presente documento contiene el diseño completo de las interfaces de usuario (UI) y los mockups de navegación para la aplicación **MindMeet**, desarrollada por InnovApp Solutions para Deloitte Colombia. 

MindMeet es una solución innovadora que utiliza Inteligencia Artificial para transformar reuniones de trabajo en documentos estructurados, mapas mentales y planes de acción automáticos. La aplicación está diseñada como una plataforma multiplataforma (web y móvil) que optimiza la productividad empresarial mediante la automatización de tareas repetitivas relacionadas con la gestión de reuniones.

Este documento presenta los mockups interactivos que ilustran la experiencia completa del usuario, desde el proceso de autenticación hasta la generación y gestión de documentos. Cada interfaz ha sido diseñada siguiendo principios de usabilidad, accesibilidad y diseño moderno, con el objetivo de proporcionar una experiencia intuitiva y eficiente para todos los usuarios de Deloitte Colombia.

---

## OBJETIVO

### Objetivo General
Diseñar y documentar las interfaces de usuario de la aplicación MindMeet, creando mockups interactivos que representen fielmente la funcionalidad y flujo de navegación del sistema, cumpliendo con los requerimientos técnicos y funcionales establecidos por Deloitte Colombia.

### Objetivos Específicos

1. **Diseñar interfaces intuitivas** que permitan a los usuarios de Deloitte Colombia acceder y utilizar las funcionalidades de MindMeet sin curva de aprendizaje pronunciada.

2. **Crear mockups navegables** que demuestren el flujo completo de uso de la aplicación, desde el inicio de sesión hasta la generación de documentos finales.

3. **Implementar un sistema visual consistente** utilizando una paleta de colores corporativa y elementos de diseño modernos que reflejen profesionalismo e innovación.

4. **Garantizar la responsividad** del diseño para que funcione correctamente tanto en dispositivos de escritorio como móviles.

5. **Documentar cada interfaz** con descripciones detalladas de sus elementos, funcionalidades y propósito dentro del sistema.

---

## ARQUITECTURA DE INFORMACIÓN

### Estructura de Navegación

La aplicación MindMeet está organizada en 5 pantallas principales:

```
MindMeet
│
├── 1. Autenticación (Login/Registro)
│   ├── Inicio de Sesión
│   ├── Crear Cuenta
│   └── Recuperación de Contraseña
│
├── 2. Dashboard (Panel Principal)
│   ├── Estadísticas
│   ├── Acciones Rápidas
│   └── Reuniones Recientes
│
├── 3. Grabación
│   ├── Control de Grabación
│   ├── Participantes Activos
│   └── Temporizador
│
├── 4. Análisis IA
│   ├── Transcripción Automática
│   ├── Mapa Mental Generado
│   └── Resumen y Acciones
│
└── 5. Documentos
    ├── Biblioteca de Documentos
    ├── Búsqueda y Filtros
    └── Gestión de Archivos
```

---

## PANTALLAS Y MOCKUPS

### 1. PANTALLA DE AUTENTICACIÓN

![Mockup Login Screen]

#### Descripción General
La pantalla de autenticación es el punto de entrada a la aplicación MindMeet. Presenta un diseño limpio y moderno con dos vistas principales: inicio de sesión y registro de cuenta.

#### Elementos de la Interfaz

**Header:**
- **Logo de MindMeet:** Icono con símbolo de cerebro (Brain) representando la IA
- **Nombre de la aplicación:** "MindMeet" en tipografía bold
- **Subtítulo descriptivo:** "Inteligencia Artificial para Reuniones"

**Navegación de Autenticación:**
- Tabs intercambiables entre "Iniciar Sesión" y "Registro"
- Indicador visual de la vista activa
- Transiciones suaves entre vistas

**Formulario de Inicio de Sesión:**
- Campo de correo electrónico con validación en tiempo real
- Campo de contraseña con opción de mostrar/ocultar
- Botón principal "Iniciar Sesión" con gradiente violeta-púrpura
- Enlace "¿Olvidaste tu contraseña?" para recuperación

**Formulario de Registro:**
- Campo de nombre completo
- Campo de correo electrónico corporativo (@deloitte.com)
- Campo de contraseña con requisitos de seguridad (mínimo 8 caracteres)
- Campo de confirmación de contraseña
- Botón "Crear Cuenta" con el mismo estilo corporativo

**Opciones Adicionales:**
- Divider con texto "o continúa con"
- Botones de autenticación social (Google, GitHub)
- Enlaces para cambiar entre login y registro

#### Funcionalidades
1. Validación de formularios en tiempo real
2. Mensajes de error descriptivos
3. Autenticación con credenciales locales
4. Integración con proveedores OAuth (Google, GitHub)
5. Recuperación de contraseña por email
6. Transición automática al Dashboard tras login exitoso

#### Paleta de Colores
- **Primary:** Gradiente Indigo-Púrpura (#6366f1 a #8b5cf6)
- **Background:** Gradiente azul claro (#f8f9ff, #e6f2ff, #f0f8ff)
- **Texto:** Gris oscuro (#1e293b) y gris medio (#64748b)
- **Campos:** Fondo blanco con bordes grises (#e5e7eb)
- **Estados:** Verde para éxito, rojo para error

#### Responsive Design
- En móvil: formulario ocupa el 100% del ancho con padding lateral
- Botones se apilan verticalmente
- Inputs con altura mínima de 44px para táctil
- Logo y título se mantienen centrados

---

### 2. DASHBOARD - PANEL PRINCIPAL

![Mockup Dashboard]

#### Descripción General
El Dashboard es el centro de control de MindMeet. Proporciona una vista general de la actividad del usuario, estadísticas importantes y acceso rápido a las funcionalidades principales.

#### Elementos de la Interfaz

**Header Superior:**
- **Logo y Nombre:** MindMeet con icono de cerebro
- **Navegación Principal:** 
  - Dashboard (Home)
  - Grabación (Mic)
  - Análisis (Brain)
  - Documentos (FileText)
- **Acciones de Usuario:**
  - Configuración (Settings)
  - Cerrar Sesión (LogOut)
  - Menú hamburguesa (responsive)

**Sección de Bienvenida:**
- Saludo personalizado: "¡Bienvenida, María!"
- Subtítulo descriptivo del estado actual
- Diseño amigable y acogedor

**Tarjetas de Estadísticas (Grid 4 columnas):**

1. **Reuniones este mes**
   - Icono: Calendar (azul)
   - Número: 24
   - Visualización destacada

2. **Actas generadas**
   - Icono: FileText (verde)
   - Número: 18
   - Indicador de productividad

3. **Precisión IA**
   - Icono: TrendingUp (púrpura)
   - Número: 94%
   - Métrica de calidad

4. **Tiempo ahorrado**
   - Icono: Clock (naranja)
   - Número: 12h
   - Beneficio cuantificable

**Acciones Rápidas:**
Tres botones principales con gradientes distintivos:

1. **Nueva Grabación** (Rojo-Rosa)
   - Icono: Mic
   - Acción: Iniciar nueva reunión
   - Redirige a pantalla de Grabación

2. **Ver Análisis IA** (Indigo-Púrpura)
   - Icono: Brain
   - Acción: Revisar análisis recientes
   - Redirige a pantalla de Análisis

3. **Mis Documentos** (Azul-Cyan)
   - Icono: FileText
   - Acción: Acceder a biblioteca
   - Redirige a pantalla de Documentos

**Reuniones Recientes:**
Lista de últimas reuniones con:
- Título de la reunión
- Fecha y hora con duración
- Estado visual (badge):
  - "Procesando" (amarillo) - reunión en análisis
  - "Completado" (verde) - reunión finalizada
- Hover effect para interactividad
- Diseño de cards con bordes y sombras suaves

#### Funcionalidades
1. Visualización de métricas en tiempo real
2. Animación de números al cargar (conteo progresivo)
3. Navegación rápida entre secciones
4. Filtrado y ordenamiento de reuniones recientes
5. Actualización automática de estadísticas
6. Responsive design adaptativo

#### Diseño Visual
- Cards con fondo blanco y sombras sutiles
- Espaciado generoso para legibilidad
- Iconos coloridos para identificación rápida
- Tipografía jerárquica (títulos bold, contenido regular)
- Estados hover con elevación y color

---

### 3. PANTALLA DE GRABACIÓN

![Mockup Recording Screen]

#### Descripción General
La pantalla de grabación es el núcleo funcional de MindMeet. Permite iniciar, pausar y finalizar grabaciones de reuniones con transcripción automática en tiempo real mediante IA.

#### Elementos de la Interfaz

**Indicador de Grabación:**
- **Círculo animado central** (120px diámetro)
  - Estado inactivo: gris neutral
  - Estado grabando: gradiente rojo-rosa con animación pulse
  - Icono: micrófono (Mic) en blanco
- **Efecto visual:** animación de pulso continuo durante grabación

**Información de Estado:**
- **Título principal:** 
  - "Listo para Grabar" (estado inicial)
  - "Grabación en Progreso" (estado activo)
- **Subtítulo:** "Transcripción automática activada"
- **Temporizador digital:** 
  - Formato MM:SS
  - Fuente monoespaciada (tipo código)
  - Tamaño grande (60px)
  - Actualización en tiempo real cada segundo

**Panel de Participantes:**
Muestra avatares de participantes activos:
- **Avatar circular:** iniciales en círculo con gradiente
  - MJ - María Jiménez (Azul-Cyan)
  - BB - Brayan Barón (Púrpura-Rosa)
  - JE - José Egurrola (Verde-Esmeralda)
- **Nombre debajo:** texto pequeño gris
- **Indicador de actividad:** sombra pulsante cuando habla

**Controles de Grabación:**

**Estado Inicial:**
- Botón "Iniciar Grabación" (Rojo-Rosa)
  - Icono: Play
  - Acción: comienza grabación y timer

**Durante Grabación:**
- Botón "Pausar" (Gris)
  - Icono: Pause
  - Acción: pausa grabación temporalmente
  
- Botón "Finalizar" (Indigo-Púrpura)
  - Icono: Square
  - Acción: termina y procesa la reunión
  - Redirige a pantalla de Análisis

#### Funcionalidades Técnicas

1. **Grabación de Audio:**
   - Captura de audio en tiempo real
   - Compresión automática
   - Almacenamiento temporal en memoria

2. **Transcripción IA:**
   - Procesamiento con Whisper AI
   - Conversión voz a texto en tiempo real
   - Identificación de hablantes

3. **Gestión de Participantes:**
   - Registro de participantes activos
   - Detección de actividad de voz
   - Asignación de colores únicos

4. **Temporizador:**
   - Contador preciso en segundos
   - Formato tiempo transcurrido
   - Persistencia durante pausas

5. **Controles Interactivos:**
   - Estados del botón dinámicos
   - Validaciones antes de finalizar
   - Confirmaciones de acciones críticas

#### Experiencia de Usuario
- Feedback visual claro del estado de grabación
- Animaciones suaves y profesionales
- Confirmación antes de acciones destructivas
- Indicadores de progreso visibles
- Interfaz minimalista sin distracciones

---

### 4. PANTALLA DE ANÁLISIS IA

![Mockup Analysis Screen]

#### Descripción General
La pantalla de Análisis IA es donde MindMeet demuestra su valor principal: transformar audio de reuniones en información estructurada y accionable mediante Inteligencia Artificial.

#### Elementos de la Interfaz

**Título de Sección:**
- Nombre del análisis: "Análisis de Reunión - Proyecto MindMeet"
- Tipografía grande y bold para jerarquía visual

**Layout de Dos Columnas:**

### Columna Izquierda - Panel de Transcripción

**Header del Panel:**
- Título: "Transcripción"
- Botón de descarga (Download icon)
- Estilo: fondo blanco, sombra suave

**Contenedor de Transcripción:**
- **Área scrollable** con altura máxima 400px
- **Formato de diálogo:**
  - Nombre del hablante en color bold distintivo
  - Texto de lo dicho en gris oscuro
  - Espaciado entre intervenciones
  
**Ejemplo de Contenido:**
```
María: Buen día a todos, vamos a revisar el avance del proyecto...

Brayan: Perfecto. He terminado la implementación del módulo 
de transcripción automática. La precisión está en 94%.

José: Excelente trabajo. ¿Qué tal van los mapas mentales?

María: Ya tenemos el algoritmo funcionando. Utiliza procesamiento 
de lenguaje natural para identificar temas clave.
```

**Características:**
- Colores diferenciados por hablante
- Scrollbar personalizado delgado
- Fondo gris claro para lectura
- Timestamps implícitos

### Columna Derecha - Panel de Mapa Mental

**Header del Panel:**
- Título: "Mapa Mental Generado"
- Botones de acción:
  - Editar (Edit icon)
  - Descargar (Download icon)

**Visualización del Mapa Mental:**
- **Canvas visual** con gradiente azul-púrpura de fondo
- **Nodo central:** 
  - Texto: "Proyecto MindMeet"
  - Estilo: gradiente indigo-púrpura, texto blanco
  - Posición: centro absoluto
  - Tamaño: más grande que nodos secundarios

- **Nodos secundarios (4):**
  1. **Transcripción IA** (superior izquierda)
     - Borde azul, fondo blanco
  
  2. **Mapas Mentales** (superior derecha)
     - Borde púrpura, fondo blanco
  
  3. **Integraciones** (inferior izquierda)
     - Borde verde, fondo blanco
  
  4. **Demo Deloitte** (inferior derecha)
     - Borde naranja, fondo blanco

**Efectos Visuales:**
- Sombras suaves en cada nodo
- Hover effect con escala 1.05
- Animación de entrada secuencial
- Líneas conectoras implícitas por posición

### Sección Inferior - Resumen y Acciones

**Panel de Resumen:**
Grid de 2 columnas con información procesada por IA:

**Columna 1 - Decisiones Clave:**
- Borde izquierdo indigo
- Lista con checkmarks verdes
- Items:
  - "Implementar transcripción con Whisper"
  - "Desarrollar mapas mentales automáticos"

**Columna 2 - Tareas Asignadas:**
- Borde izquierdo púrpura
- Lista con iconos de alerta naranja
- Items:
  - "María: Finalizar algoritmo NLP"
  - "Brayan: Integrar con Teams"

**Botón de Acción Final:**
- "Generar Acta Final"
- Estilo: gradiente indigo-púrpura
- Posición: centrado
- Acción: crea documento y va a Documentos

#### Funcionalidades de IA

1. **Procesamiento de Lenguaje Natural (NLP):**
   - Identificación de temas principales
   - Extracción de decisiones clave
   - Reconocimiento de tareas asignadas
   - Detección de personas mencionadas

2. **Generación de Mapas Mentales:**
   - Análisis semántico del contenido
   - Agrupación de conceptos relacionados
   - Jerarquización de información
   - Visualización automática

3. **Resumen Inteligente:**
   - Extracción de puntos clave
   - Priorización de información
   - Identificación de action items
   - Asignación de responsables

4. **Exportación:**
   - PDF de transcripción
   - Imagen del mapa mental
   - Documento Word con resumen
   - JSON con datos estructurados

#### Experiencia de Usuario
- Carga progresiva con animaciones
- Feedback visual durante procesamiento
- Opciones de edición manual
- Múltiples formatos de exportación
- Navegación fluida hacia documentos

---

### 5. PANTALLA DE DOCUMENTOS

![Mockup Documents Screen]

#### Descripción General
La pantalla de Documentos es la biblioteca central donde los usuarios pueden buscar, visualizar, descargar y compartir todos los documentos generados por MindMeet.

#### Elementos de la Interfaz

**Toolbar Superior:**

**Sección Izquierda:**
- Título: "Mis Documentos" (texto grande, bold)

**Sección Central:**
- **Campo de búsqueda:**
  - Icono de lupa (Search) a la izquierda
  - Placeholder: "Buscar documentos..."
  - Ancho: 256px (desktop), 100% (mobile)
  - Búsqueda en tiempo real
  - Filtra por título y tipo

**Sección Derecha:**
- Botón "+ Nueva Reunión"
- Estilo: gradiente indigo-púrpura
- Acción: redirige a pantalla de Grabación

**Grid de Documentos:**

Layout responsive:
- Desktop: 3 columnas
- Tablet: 2 columnas  
- Mobile: 1 columna

**Card de Documento (Componente Repetible):**

**Header del Card:**
- **Badge de tipo:**
  - "Acta" - fondo azul claro, texto azul
  - "Mapa Mental" - fondo púrpura claro, texto púrpura
  - "Transcripción" - fondo verde claro, texto verde
  - Estilo: pill redondeado, texto pequeño

**Contenido del Card:**
- **Título del documento:** 
  - Texto bold, tamaño 16px
  - Color gris oscuro
  - Ejemplo: "Proyecto MindMeet - Sesión 1"

- **Metadata:**
  - Fecha de creación
  - Separador bullet (•)
  - Información adicional (páginas, tipo)
  - Texto pequeño gris
  - Ejemplo: "15 Mar 2025 • 5 páginas"

**Botones de Acción:**
Grid de 2 botones:

1. **Descargar**
   - Icono: Download
   - Estilo: fondo gris claro
   - Texto gris oscuro

2. **Compartir**
   - Icono: Share2
   - Estilo: fondo indigo, texto blanco
   - Acción primaria

**Ejemplos de Documentos:**

```
1. Card: Acta
   Título: "Proyecto MindMeet - Sesión 1"
   Meta: "15 Mar 2025 • 5 páginas"
   Badge: Azul

2. Card: Mapa Mental
   Título: "Planificación Sprint Q2"
   Meta: "14 Mar 2025 • Interactivo"
   Badge: Púrpura

3. Card: Transcripción
   Título: "Reunión Cliente Deloitte"
   Meta: "13 Mar 2025 • 12 páginas"
   Badge: Verde
```

#### Funcionalidades

1. **Búsqueda Inteligente:**
   - Filtrado en tiempo real
   - Búsqueda por título
   - Búsqueda por tipo de documento
   - Búsqueda por fecha
   - Búsqueda por participantes

2. **Gestión de Documentos:**
   - Descarga individual o masiva
   - Compartir con enlace
   - Eliminar documentos
   - Renombrar documentos
   - Organizar en carpetas (futura)

3. **Visualización:**
   - Vista grid (actual)
   - Vista lista (opcional)
   - Ordenamiento por fecha, nombre, tipo
   - Paginación o scroll infinito

4. **Acciones Contextuales:**
   - Ver detalles del documento
   - Editar mapa mental
   - Re-procesar con IA
   - Exportar en diferentes formatos

5. **Integrations:**
   - Exportar a Google Drive
   - Compartir en Microsoft Teams
   - Sincronizar con calendario
   - Enviar por email

#### Estados de la Interfaz

**Estado Vacío:**
- Ilustración de carpeta vacía
- Mensaje: "Aún no tienes documentos"
- Botón CTA: "Crear tu primera reunión"

**Estado de Carga:**
- Skeleton screens para cards
- Indicador de carga en toolbar
- Animación suave

**Estado de Error:**
- Mensaje de error descriptivo
- Botón "Reintentar"
- Opción de reportar problema

**Estado de Búsqueda Sin Resultados:**
- Mensaje: "No se encontraron documentos"
- Sugerencias de búsqueda
- Limpiar filtros

#### Diseño Responsive

**Desktop (>1024px):**
- Grid de 3 columnas
- Toolbar horizontal completo
- Todos los elementos visibles

**Tablet (768px - 1024px):**
- Grid de 2 columnas
- Búsqueda toma más espacio
- Botones mantienen tamaño

**Mobile (<768px):**
- Grid de 1 columna
- Toolbar apilado verticalmente
- Búsqueda 100% ancho
- Botones full width en cards
- Cards con padding reducido

---

## FLUJO DE NAVEGACIÓN COMPLETO

### Diagrama de Flujo

```
INICIO
  ↓
[1. LOGIN/REGISTRO]
  ↓
¿Autenticado?
  ↓ SÍ
[2. DASHBOARD]
  ↓
  ├─→ [3. GRABACIÓN] ──→ Iniciar Reunión
  │       ↓                      ↓
  │    Grabar Audio         Pausar/Reanudar
  │       ↓                      ↓
  │    Finalizar ──────────→ [4. ANÁLISIS]
  │                              ↓
  │                       Ver Transcripción
  │                              ↓
  │                       Ver Mapa Mental
  │                              ↓
  │                       Ver Resumen/Acciones
  │                              ↓
  │                       Generar Acta
  │                              ↓
  ├─→ [4. ANÁLISIS] ←───────────┘
  │       ↓
  │    Ver reuniones procesadas
  │       ↓
  │    Editar/Exportar
  │       ↓
  └─→ [5. DOCUMENTOS]
          ↓
       Buscar/Filtrar
          ↓
       Descargar/Compartir
          ↓
       Nueva Reunión → [3. GRABACIÓN]
```

### Navegación Primaria

**Header Persistente:**
El header permanece visible en todas las pantallas (excepto login) y permite navegación directa entre las 4 secciones principales:
- Dashboard
- Grabación  
- Análisis
- Documentos

**Navegación Contextual:**
Cada pantalla incluye botones de acción que facilitan el flujo natural:
- Dashboard → Iniciar grabación
- Grabación → Ver análisis
- Análisis → Generar documento
- Documentos → Nueva reunión

---

## SISTEMA DE DISEÑO

### Paleta de Colores

**Colores Primarios:**
```
Indigo: #6366f1
Púrpura: #8b5cf6
Gradiente Principal: linear-gradient(135deg, #6366f1, #8b5cf6)
```

**Colores Secundarios:**
```
Azul: #3b82f6
Cyan: #06b6d4
Verde: #10b981
Naranja: #f97316
Rojo: #ef4444
Rosa: #ec4899
```

**Colores Neutros:**
```
Gris 900: #1e293b (títulos)
Gris 700: #374151 (texto)
Gris 600: #64748b (texto secundario)
Gris 400: #9ca3af (placeholders)
Gris 200: #e5e7eb (bordes)
Gris 100: #f3f4f6 (fondos)
Gris 50: #f8fafc (fondos claros)
Blanco: #ffffff
```

**Colores de Estado:**
```
Éxito: #10b981 (verde)
Error: #ef4444 (rojo)
Advertencia: #