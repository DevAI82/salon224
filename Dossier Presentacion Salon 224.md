# Dossier de Propuesta Comercial & Transformación Digital
## SALÓN 224 — Peluquería y Estética de Vanguardia (Albacete & Alicante)

Este documento recoge la propuesta estratégica, comercial y tecnológica para **Salón 224**, orientada a erradicar la pérdida de citas por llamadas desatendidas, profesionalizar la atención omnicanal 24/7 y reducir a cero la dependencia y las comisiones de software de terceros (Fresha).

---

### 1. Resumen Ejecutivo & Diagnóstico del Negocio

**Salón 224** se ha consolidado como la referencia indiscutible en peluquería de autor, especialistas en rubios (*balayage*, *babylights*, nórdicos), tratamientos capilares de alta gama (embajadores exclusivos de *Authentic Beauty Concept* en Albacete), cortes de tendencia, novias e invitadas.

Con **tres salones en pleno funcionamiento**:
1. **Sede Central:** Calle Torres Quevedo, 8, 02003 Albacete (Centro).
2. **Sede El Corte Inglés Albacete:** Avenida de España, 30 (Primera Planta).
3. **Sede El Corte Inglés Alicante:** Avenida Maisonnave, 53 (Alicante).

#### Los 3 Cuellos de Botella Detectados en la Operativa Actual:
1. **Llamadas y WhatsApps desatendidos en horas punta:** Cuando las estilistas están en cabina lavando, aplicando mechas o secando, no pueden atender el teléfono fijo (`967 105 930`) ni contestar mensajes al instante. Cada llamada no atendida o respuesta tardía de 2 horas es una clienta que reserva en otro salón.
2. **El "Peaje" de Fresha:** Fresha cobra cuotas fijas mensuales por cada estilista ("Fresha Plus" a 20 €/estilista/mes), más un **20% de comisión en primeras reservas** de clientas que descubren el salón a través de su marketplace, más costes adicionales de SMS y comisiones de pasarela de pago. Para una plantilla de 7 estilistas, esto supone **entre 900 € y 1.400 € mensuales** en comisiones que salen directamente del margen neto del salón.
3. **Pérdida de la propiedad de la clientela:** En la app de Fresha, cuando una clienta reserva, la propia plataforma le sugiere otros salones competidores de Albacete o Alicante. Además, las fórmulas técnicas de tinte y matices quedan fuera del sistema.

---

### 2. La Solución en Dos Fases: Cero Riesgo Hoy, Máximo Ahorro Mañana

Para no alterar la rutina de trabajo de las estilistas ni generar fricción, la propuesta se estructura en dos fases:

```
┌────────────────────────────────────────────────────────┐
│ FASE 1: AUTOMATIZACIÓN INMEDIATA (Semana 1-2)          │
│ • Asistente de Voz Telefónico (ElevenLabs)             │
│ • Chatbot Inteligente de WhatsApp (Zernio)             │
│ • Conexión directa a la API de FRESHA (Agenda actual)  │
│ • Recordatorios 24h Anti-No-Show con Google Maps       │
└───────────────────────────┬────────────────────────────┘
                            │ (Validación de resultados)
                            ▼
┌────────────────────────────────────────────────────────┐
│ FASE 2: CRM PROPIO SALÓN 224 (Mes 2-3)                 │
│ • Sustitución definitiva de la suscripción de Fresha   │
│ • Ahorro neto anual de 12.000 € a 15.000 €             │
│ • Ficha Técnica de Colorimetría con fórmulas guardadas │
│ • Disparo automático de WhatsApp a los 75 días         │
│ • Base de datos privada 100% de Salón 224 (Supabase)   │
└────────────────────────────────────────────────────────┘
```

---

### 3. Fase 1: La Recepción Virtual Dual (ElevenLabs + Zernio + Fresha API)

#### A. Asistente Telefónico 24/7 con ElevenLabs Conversational AI
* **Atención inmediata:** Descuelga al primer tono en el fijo de la peluquería (`967 105 930`).
* **Voz humana ultra-realista:** Configurado con acento impecable de España, tono cálido, educado y resolutivo.
* **Resolución de dudas frecuentes:** Informa sobre precios aproximados de servicios de color, tratamientos de nutrición capilar *Authentic Beauty Concept*, horarios y opciones de parking cubierto en El Corte Inglés.
* **Agendamiento directo en Fresha:** Consulta los huecos disponibles en tiempo real según el salón elegido (Torres Quevedo vs. El Corte Inglés) y el estilista de preferencia, confirmando la cita al segundo.
* **Resumen ejecutivo:** Envía automáticamente un WhatsApp a la clienta con la confirmación y ubicación exacta de Google Maps.

#### B. Chatbot de WhatsApp Inteligente con Zernio
* **Atención al instante en el WhatsApp Oficial:** Sin colas ni esperas.
* **Galería visual interactiva:** Muestra imágenes reales de trabajos de Salón 224 (rubios, cortes, novias) para inspirar a la clienta y cerrar la venta.
* **Selector dinámico de salón:** Permite a la clienta elegir entre las 3 sedes con un solo toque.
* **Recordatorio 24 horas Anti-No-Show:** Dispara un mensaje automático un día antes de la cita solicitando confirmación con un botón ("✅ Confirmo mi asistencia"). Si la clienta cancela con antelación, el hueco se libera automáticamente en Fresha para que otra persona lo aproveche.

---

### 4. Fase 2: CRM Propio Salón 224 (Sustitución de Fresha)

Una vez que el sistema de captación y atención automática esté consolidado, se despliega el **CRM a medida de Salón 224**:

1. **Agenda Multi-Sede y Multi-Estilista:** Vista semanal y diaria optimizada por sillón y estilista para los 3 centros.
2. **Ficha Técnica de Colorimetría:** 
   * Registro histórico de cada servicio realizado a la clienta.
   * **Fórmula exacta guardada:** gramos de tinte, marca (Igora, Blond Studio), volúmenes de oxigenada, matiz aplicado (*glaze*) y tiempo de exposición.
   * Fotos de "Antes" y "Después" para documentar la evolución del cabello.
   * Cualquier compañera del equipo puede replicar el color exacto sin riesgo a equivocarse.
3. **Automatización de Retoque (Fidelización Activa):**
   * El sistema detecta cuando una clienta de Balayage cumple 60 o 75 días desde su última sesión.
   * Envía un WhatsApp automático y cercano: *"Hola Elena, hace 10 semanas iluminamos tu melena en Torres Quevedo. ¿Te apetece renovar el brillo o retocar el contorno antes del fin de semana?"*.
   * Cierra citas recurrentes sin esfuerzo comercial.
4. **Independencia Total de Fresha:**
   * Cero comisiones del 20% por clientes nuevos.
   * Cero cuotas de 20 €/mes por estilista.
   * Ahorro neto estimado: **> 12.000 € anuales**.
   * Datos 100% confidenciales bajo RGPD en la Unión Europea.

---

### 5. Arquitectura Técnica bajo Framework WAT

La arquitectura técnica se rige por los más altos estándares de desarrollo:

* **Capa 1: Workflows (SOPs):** Protocolos claros de agendamiento, políticas de cancelación, catálogo de tarifas y reglas de escalado a recepción humana.
* **Capa 2: Agentes Inteligentes:**
  * `ElevenLabs Agent`: Reconocimiento de voz (ASR), razonamiento contextual y síntesis neuronal (TTS).
  * `Zernio Bot`: Orquestación de webhooks de WhatsApp Business API.
* **Capa 3: Tools Deterministas:**
  * `fresha_api_sync.ts`: Conector HTTPS para consultar huecos libres y crear reservas en Fresha vía API REST.
  * `supabase_crm_db`: Base de datos relacional PostgreSQL con políticas RLS (Row Level Security) para proteger las fórmulas y notas privadas.
* **Fichero de Arquitectura Vectorial:** Se adjunta el archivo importable y editable en Excalidraw:
  `arquitectura-salon224.excalidraw`.

---

### 6. Análisis Financiero & Retorno de Inversión (ROI)

#### Comparativa de Costes Anuales (Escenario: 7 estilistas, 500 citas/mes):

| Concepto | Coste con Fresha | Con Solución Salón 224 | Ahorro Anual |
| :--- | :---: | :---: | :---: |
| **Suscripción Estilistas (Fresha Plus)** | 1.680 €/año (20€/mes x 7) | **0 €** | +1.680 € |
| **Comisión Marketplace (20% primer servicio)** | ~11.700 €/año | **0 €** | +11.700 € |
| **SMS Recordatorios & Pasarelas** | ~1.500 €/año | **~180 €/año** (Zernio/WA) | +1.320 € |
| **Llamadas Perdidas Recuperadas** | Pérdida estimada 20 citas/mes | **Recuperadas al 100% con IA** | +14.400 € facturación |
| **Balance Financiero Total** | **-14.880 €/año en peajes** | **Coste fijo mínimo** | **> 14.000 € beneficio neto** |

---

### 7. Entregables Disponibles en este Proyecto

Para que la dirección de Salón 224 pueda evaluar la propuesta y probarla en directo:

1. **Dossier de Presentación Web:** Abrir en navegador `VER PRESENTACION.html`.
2. **Prototipo Interactivo Completo:** Abrir en navegador `mockup_interactivo.html` (incluye simulador telefónico con voz, simulador de WhatsApp, panel Kanban de citas, ficha técnica de color y calculadora de ahorro en tiempo real).
3. **Diagrama Vectorial de Flujos:** Archivo `arquitectura-salon224.excalidraw` (abrible en [excalidraw.com](https://excalidraw.com)).
4. **Recursos de Marca Oficiales:** Carpeta `assets/` con el logotipo oficial y fotografías de las 3 sedes de Salón 224.
