# EJEMPLO COMPLETADO - Tipo de Incidente

## Ransomware (Sistema Infectado)

**Agrupación:** Contenido dañino o malicioso  
**Tipo:** Sistema infectado (Ransomware)

---

### Características del Incidente

| Campo | Contenido |
|-------|-----------|
| **Descripción** | Software malicioso que cifra los archivos del sistema víctima y exige un rescate económico para proporcionar la clave de descifrado. El atacante toma el control de datos críticos como forma de extorsión. |
| **Funcionamiento** | 1) Se distribuye vía email malicioso, descarga drive-by o exploit kit. 2) Se ejecuta con permisos de usuario o administrador. 3) Cifra archivos críticos (documentos, bases de datos, copias de seguridad) con algoritmo RSA/AES. 4) Muestra pantalla de rescate con instrucciones de pago. 5) Amenaza con publicar datos o borrar archivos si no paga. |
| **Identificación** | - Archivos con extensión desconocida (.locked, .encrypted, .xxx). - Presencia de archivo de nota de rescate (README.txt, DECRYPT.html). - Actividad de cifrado inusual en procesos de sistema. - Caída súbita de rendimiento. - Alertas de antivirus sobre comportamiento sospechoso. - Comunicaciones de red a servidores C&C. |
| **Protección** | - **Técnica:** Copias de seguridad offline desconectadas de red. Actualizaciones de SO y software. EDR (Endpoint Detection). Bloqueo de puertos RDP. Segmentación de red. - **Organizativa:** Formación a empleados. Política de contraseñas fuertes. Restricción de permisos administrativos. Plan de recuperación ante desastres. |

---

### Caso Real Documentado

| Parámetro | Contenido |
|-----------|-----------|
| **URL** | https://www.incibe.es/incibe-cert/publicaciones/bitacora-de-seguridad/el-ransomware-wannacry-infecta-multitud-equipos |
| **Breve Descripción** | WannaCry fue un ataque ransomware global en mayo 2017 que afectó a más de 200,000 ordenadores en 150 países. Explotaba vulnerabilidad EternalBlue en Windows. Paralizó hospitales, bancos y gobiernos. Pidió rescate en Bitcoin. Generó pérdidas estimadas en 4.000 millones de dólares. |
| **Agrupación/Tipo** | Contenido dañino o malicioso > Sistema infectado |
| **Origen** | Externo (atribuido a Lazarus Group, Corea del Norte) |
| **Perfiles Afectados** | Usuarios generales, administrativos, responsables TI. Afectó a cualquier persona con acceso a sistemas infectados. |
| **Nº y Tipología Sistemas** | 200.000+ computadoras (Windows: servidores, PCs de escritorio, portátiles). Afectó redes completas. |
| **Categoría Sistemas** | Crítica (hospitales, infraestructura bancaria, gobiernos) |
| **Peligrosidad** | 5 (Crítico) - Malware sofisticado, propagación rápida, exploit zero-day |
| **Impacto** | L5 (Crítico) - Paralización mundial, servicios esenciales interrumpidos, pérdidas financieras masivas |
| **Prioridad Asignada** | **Emergencia** - Requería respuesta inmediata global, todos los recursos disponibles |

---

## ✏️ Cómo Usar Este Ejemplo

1. **Copia la estructura** a tus propios archivos
2. **Adapta los campos** con tu tipo de incidente
3. **Busca tus propios casos** reales (que no sean WannaCry)
4. **Mantén la claridad** y precisión en cada campo

**Tips:**
- Sé específico: no escribas párrafos largos
- Enlaza con conceptos de clase
- Busca casos diversos (no todos famosos)
- Verifica URLs antes de entregar
