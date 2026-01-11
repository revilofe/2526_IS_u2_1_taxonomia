# Investigación y Desarrollo de la Taxonomía de Incidentes de Ciberseguridad

**ID Actividad:** 2.a.01  
**Agrupamiento:** Máximo 5 personas  
**Evaluación:** RA2, CE a

---

## 🎯 Objetivo

Desarrollar una comprensión detallada de la taxonomía de incidentes de ciberseguridad, identificar tipos específicos y relacionarlos con casos reales documentados.

### 👉 **[COMIENZA AQUÍ: assets/COMIENZA-AQUI.md](./assets/COMIENZA-AQUI.md)** ← Guía de inicio rápido

### 👉 **[ENTREGA ÚNICA: ENTREGA.md](./ENTREGA.md)** ← Documento de entrega (10 tipos)

---

## 🎯 Trabajo a Realizar

Basandote en la [teoria proporcionada y la taxonomía INCIBE-CERT](https://revilofe.github.io/section2/u02/teoria/IS-U2.1.1.-TaxonomiaDeIncidentes/), completa los siguientes pasos:

### 1. **Seleccionar 2 Agrupaciones de Incidentes**

Elige **2 agrupaciones** de la taxonomía INCIBE-CERT (sin solaparse con otros grupos):

- Contenido abusivo
- Contenido dañino o malicioso
- Obtención de información
- Intento de intrusión
- Intrusión
- Disponibilidad
- Compromiso de la información
- Fraude
- Vulnerable
- Otros

### 2. **Por Cada Agrupación: 5 Tipos Mínimo**

Para cada uno de los 5 tipos, completa la **tabla de características**:

| Campo              | Descripción                         |
|--------------------|-------------------------------------|
| **Descripción**    | ¿Qué es exactamente?                |
| **Funcionamiento** | ¿Cómo funciona el ataque/incidente? |
| **Identificación** | Indicadores/señales de detección    |
| **Protección**     | Medidas preventivas y de mitigación |
| **Ejemplo Real**   | Caso concreto documentado (con URL) |

### 3. **Documentación de Casos Reales**

Para cada tipo, incluye **al menos 1 caso real** con:

| Parámetro              | Descripción                                    |
|------------------------|------------------------------------------------|
| **URL**                | Enlace a noticia/documentación                 |
| **Descripción**        | Resumen breve del incidente                    |
| **Agrupación/Tipo**    | Clasificación según taxonomía                  |
| **Origen**             | Interno/Externo/Desconocido                    |
| **Perfiles Afectados** | Usuarios, roles, privilegios                   |
| **Sistemas Afectados** | Número y tipo (servidores, PCs, móviles, etc.) |
| **Categoría**          | Crítica/Alta/Media/Baja                        |
| **Peligrosidad**       | 1-5 (Bajo-Crítico)                             |
| **Impacto**            | L1-L5 (Bajo-Crítico)                           |
| **Prioridad**          | Emergencia/Alta/Normal/Baja                    |

---

## 📁 Estructura del Repositorio

```
.
├── README.md                          # Este archivo - Guía general
├── ENTREGA.md                         # 👈 ÚNICO DOCUMENTO DE ENTREGA
│                                      #    (10 tipos + casos reales)
├── INDEX.md                           # Índice visual
├── .gitignore                         # Configuración Git (IDEs, logs, etc.)
└── assets/                            # Referencias y ejemplos
    ├── plantilla-tabla.md            # Referencia rápida
    ├── ejemplo-completado.md         # Ejemplo de formato (Ransomware)
    └── guia-busqueda.md              # Cómo buscar casos reales
```

**IMPORTANTE:** Toda la documentación de los 10 tipos va **únicamente en ENTREGA.md**

---

## 📝 Como Usar la Plantilla

**ÚNICA ENTREGA:** `ENTREGA.md`

1. **Abre** el archivo [ENTREGA.md](./ENTREGA.md)
2. **Sustituye** los campos entre corchetes `[Así]`
3. **Rellena:**
   - Datos del grupo (nombres)
   - 2 agrupaciones seleccionadas
   - 5 tipos por agrupación (tabla de características)
   - 1+ caso real por tipo (tabla completa)
4. **Busca** casos reales. Si quieres haz uso de `assets/guia-busqueda.md`
5. **Haz commits** y **push a GitHub**

### Referencias Auxiliares

- `assets/ejemplo-completado.md` → Ver cómo rellenar un tipo
- `assets/guia-busqueda.md` → Dónde buscar casos reales
- `assets/plantilla-tabla.md` → Estructura de un tipo

---

## 🔍 Criterios de Evaluación (Rúbrica)

Pendiente de revisar. 

| Criterio                    | Descripción                                          |
|-----------------------------|------------------------------------------------------|
| **Identificación de tipos** | 5 tipos × 2 agrupaciones = 10 tipos identificados    |
| **Completitud**             | Todos los campos de la tabla rellenados              |
| **Precisión**               | Información detallada y verificable                  |
| **Casos reales**            | Mínimo 1 caso documentado por tipo (10 casos)        |
| **Presentación**            | Claridad y organización del trabajo                  |
| **Repositorio Git**         | Commits claros, registro de aportaciones por usuario |

---

## 📚 Recursos

- [Apuntes de Teoría: Taxonomía de Incidentes](https://revilofe.github.io/section2/u02/teoria/IS-U2.1.1.-TaxonomiaDeIncidentes/)
- [Matriz de Taxonomía INCIBE-CERT](https://github.com/flosada/RSITaxonomy_ES/blob/master/humanv1.md)
- [Guía Nacional de Notificación y Gestión de Ciberincidentes](https://www.incibe.es/sites/default/files/contenidos/guias/doc/guia_nacional_notificacion_gestion_ciberincidentes.pdf)
- [Apuntes proporcionados en clase](../material/apuntes.md)
- [Casos reales INCIBE](https://www.incibe.es/incibe-cert)

---

## 📤 Entrega

### Requisitos

- ✅ Trabajo en repositorio GitHub
- ✅ Commits significativos de cada miembro (git log visible)
- ✅ **Documentación ÚNICA en `ENTREGA.md`**
- ✅ Imágenes referenciadas en `assets/` (opcional)

### Archivo de Entrega Principal

**👉 [ENTREGA.md](./ENTREGA.md)** ← Único documento de entrega con:
- Datos del grupo (nombres, miembros)
- 10 tipos de incidentes documentados (5 × 2 agrupaciones)
- Tabla de características para cada tipo
- Tabla de caso real para cada tipo
- Registro de commits por usuario

---

## 🤝 Trabajo Colaborativo

**Cada miembro debe:**
- Contribuir con commits identificables en ENTREGA.md
- Documentar al menos 2 tipos
- Buscar casos reales
- Usar ramas si es necesario

**Ejemplo de commit:**
```bash
git commit -m "docs: tipos 1-2 agrupación 1 - @usuario"
git commit -m "docs: casos reales malware - @usuario"
git commit -m "docs: completar agrupación 2 - @usuario"
```

**Al final:** Incluye registro de commits en ENTREGA.md (sección "Registro de Commits")

---

## ❓ Preguntas Frecuentes

**P: ¿Dónde entrego los 10 tipos?**  
R: **Únicamente en ENTREGA.md** (este es el único documento de entrega)

**P: ¿Puedo incluir imágenes?**  
R: Sí, guárdalas en `assets/` y enlazalas dentro de ENTREGA.md

**P: ¿Qué hay en la carpeta `assets/`?**  
R: Referencias y ejemplos: plantilla-tabla.md, ejemplo-completado.md, guia-busqueda.md, COMIENZA-AQUI.md

**P: ¿De dónde saco los casos reales?**  
R: Consulta `assets/guia-busqueda.md` para fuentes y términos de búsqueda

**P: ¿Cuánto detalle en "Funcionamiento"?**  
R: 3-5 líneas claras: qué hace, cómo lo hace, por qué es efectivo

**P: ¿Cómo doy prioridad a un incidente?**  
R: Usa la matriz de peligrosidad × impacto de los apuntes de clase

---

**Última actualización:** 2024-01-11  
**Profesor:** Eduardo Fdez
