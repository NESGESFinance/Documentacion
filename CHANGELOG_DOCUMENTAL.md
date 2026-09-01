# Changelog Documental NESGESFinance

Todas las modificaciones relevantes de documentación institucional, contenido web, lenguaje legal, tokenomics, afirmaciones públicas y controles editoriales deben registrarse en este archivo.

El formato se inspira en el principio de mantener un historial claro de cambios. Las versiones publicadas deben corresponder a documentos, Pull Requests o publicaciones verificables.

## Convenciones

### Tipos de cambio

- **Añadido:** contenido, control o documento nuevo.
- **Modificado:** cambio compatible o corrección de contenido existente.
- **Corregido:** subsanación de error, inconsistencia o ambigüedad.
- **Retirado:** contenido eliminado de publicación.
- **Deprecado:** contenido aún archivado pero no vigente.
- **Seguridad:** cambio relativo a secretos, vulnerabilidades, privacidad o controles técnicos.
- **Legal:** cambio relativo a términos, riesgos, privacidad, KYC/AML o cumplimiento.

### Estados de versión

- **Borrador:** no autorizado para publicación.
- **Aprobado para publicación:** validado según el proceso interno aplicable.
- **Publicado:** disponible en un canal público.
- **Archivado:** conservado internamente como historial.
- **Obsoleto:** reemplazado por una versión posterior.

## [No publicado] — Próximos cambios pendientes

### Pendiente de verificación

- Confirmar cuál repositorio es la fuente canónica de GitHub Pages para el sitio institucional.
- Verificar la configuración activa de publicación en GitHub Pages.
- Auditar todas las rutas del sitio y de la aplicación antes de declarar su estado funcional.
- Verificar todos los enlaces externos visibles.
- Confirmar las personas, cargos, domicilios y datos corporativos que puedan ser publicados.
- Obtener revisión jurídica de los textos que serán publicados como Términos de Uso, Aviso Legal, Política de Privacidad y Política KYC/AML.
- Definir el responsable operativo y el mecanismo verificable para solicitudes relacionadas con privacidad.
- Definir y verificar cualquier flujo real de KYC/AML antes de habilitarlo públicamente.
- Verificar la existencia, alcance y evidencia de toda integración de wallet, P2P, trade, Lightning, Taproot Assets, API y gobernanza.
- Retirar o reclasificar toda afirmación no respaldada por evidencia técnica, jurídica o documental.

## [3.1] — 2026-09-01 — Borrador institucional consolidado

### Añadido

- Whitepaper Institucional v3.1 como documento maestro de narrativa, propósito, arquitectura y procesos institucionales genéricos.
- Especificación Técnica NGF•BTC•AM v3.1 como documento maestro de identidad on-chain, parámetros técnicos, tokenomics y límites funcionales.
- Matriz de Alineación GitHub Pages v3.1 como guía de auditoría para rutas públicas y contenido de aplicación.
- Pitch Deck Institucional v3.1 como guion de comunicación pública prudente.
- Paquete Jurídico-Comunicacional v3.1, que incluye:
  - Términos y Condiciones Generales de Uso.
  - Aviso Legal y Delimitación de Responsabilidad.
  - Divulgación de Riesgos.
  - Política de Privacidad.
  - Política KYC/AML/CFT.
  - Textos de consentimiento para formularios.
- `MATRIZ_TRAZABILIDAD_CLAIMS.csv` para control de afirmaciones públicas y evidencia requerida.
- `GLOSARIO_NESGESFinance.md` para uniformidad de definiciones institucionales.
- `POLITICA_CONTROL_DOCUMENTAL.md` para gobierno, revisión, publicación y archivo documental.
- `CHECKLIST_PUBLICACION_GITHUB_PAGES.md` para validación previa a despliegues públicos.
- `CHANGELOG_DOCUMENTAL.md` como registro central de cambios documentales.

### Modificado

- Se consolidó la identidad técnica pública de NGF•BTC•AM:
  - Rune Number: `#208,645`.
  - Rune ID: `923867:120`.
  - Suministro fijo: `5.930.000.000`.
  - Divisibilidad: `0`.
  - Minteable: no.
  - Quemable: no.
- Se consolidó la tokenomics institucional v5.0:
  - Reserva: 30%.
  - Proyectos: 25%.
  - Social y Ambiental: 15%.
  - Alianzas y Gobernanza: 10%.
  - Tesorería: 10%.
  - Comunidad: 5%.
  - Equipo: 4%.
  - Operativo: 1%.
- Se estableció que los materiales públicos deben utilizar una clasificación honesta de estado funcional:
  - Implementado.
  - En desarrollo.
  - Planificado.
  - Conceptual.
  - No disponible públicamente.
- Se estableció un enfoque institucional genérico para los procesos de postulación y participación.

### Corregido

- Se unificó el uso de la denominación institucional `NESGESFinance`.
- Se incorporó una regla de consistencia para evitar múltiples tokenomics vigentes o porcentajes divergentes.
- Se incorporaron delimitaciones explícitas para evitar presentar NGF•BTC•AM como acción, valor mobiliario, derecho económico, promesa de rendimiento o instrumento con liquidez garantizada.
- Se incorporó el principio de que toda afirmación pública debe contar con una fuente maestra y evidencia verificable.

### Retirado

- De los materiales públicos v3.1 deben retirarse referencias a proyectos específicos, series privadas, activos físicos individualizados, términos económicos particulares o promesas asociadas a iniciativas concretas.
- Deben retirarse o reclasificarse afirmaciones de funcionalidades no verificadas, incluyendo cualquier referencia presentada como operativa a wallet, P2P, trade, Lightning, Taproot Assets, KYC/AML, API, custodia, auditoría o gobernanza vinculante, cuando no exista evidencia aplicable.

### Legal

- Se estableció que los textos jurídicos generados son borradores institucionales de trabajo hasta que sean revisados y validados por asesoría jurídica competente.
- Se estableció que los formularios deben incorporar consentimiento informado y avisos de privacidad antes de recolectar datos personales.
- Se estableció que los procesos KYC/AML no deben activarse o anunciarse como disponibles sin procedimiento operativo, responsable, controles de seguridad y revisión aplicable.
- Se estableció que las referencias a estructuras SPV, Reg D 506(c), Reg S, trust, fideicomisos o patrimonios autónomos requieren formalización y respaldo jurídico antes de afirmarse como activas.

### Seguridad

- Se estableció la prohibición de publicar claves privadas, frases semilla, secretos de API, archivos `.env`, credenciales, documentos KYC, información biométrica o datos personales sensibles en repositorios públicos.
- Se estableció el uso de ramas de trabajo, Pull Requests, revisión previa y protección de la rama de producción.
- Se incorporó la advertencia de que las operaciones en Bitcoin L1 son finales e irreversibles.
- Se incorporó la advertencia de responsabilidad del usuario respecto de claves privadas, frases semilla y direcciones de destino.

## [3.0] — Archivado / Reemplazado por v3.1

### Deprecado

- Materiales previos que contengan cifras, distribución de tokenomics, narrativas, funcionalidades, denominaciones, proyectos específicos o afirmaciones que no coincidan con los documentos maestros v3.1.
- Versiones anteriores de textos legales, privacidad, KYC/AML o consentimientos que no incorporen las delimitaciones de v3.1.
- Páginas públicas que presenten funciones no implementadas o no verificables como disponibles.

### Acción requerida

- Mantener las versiones anteriores únicamente como archivo interno identificable.
- No presentar documentación `v3.0` o anterior como vigente.
- Vincular cada material retirado con el documento v3.1 que lo reemplaza.
- Revisar el historial de GitHub Pages y los repositorios públicos para identificar contenido heredado o duplicado.

## Plantilla para futuras entradas

```markdown
## [X.Y] — AAAA-MM-DD — Estado

### Añadido

- 

### Modificado

- 

### Corregido

- 

### Retirado

- 

### Legal

- 

### Seguridad

-
