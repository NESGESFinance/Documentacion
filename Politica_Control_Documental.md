# Política de Control Documental NESGESFinance v3.1

**Estado:** Documento institucional de control interno  
**Versión:** 3.1  
**Alcance:** Repositorios, sitios web, aplicación, documentos institucionales, materiales públicos, formularios y comunicaciones digitales.

## 1. Objeto

Esta Política de Control Documental establece las reglas para crear, revisar, aprobar, publicar, modificar, archivar y retirar documentación vinculada con NESGESFinance.

Su finalidad es mantener consistencia institucional, trazabilidad de versiones, precisión técnica, prudencia jurídica, protección de datos y coherencia entre los materiales publicados.

## 2. Principios de control documental

Toda documentación deberá cumplir los siguientes principios:

1. **Veracidad verificable:** ninguna afirmación debe publicarse sin evidencia suficiente.
2. **Fuente única de verdad:** cada dato institucional, técnico o legal debe tener un documento maestro identificable.
3. **Consistencia:** las cifras, definiciones, nombres y estados funcionales deben coincidir en todos los canales.
4. **Trazabilidad:** todo cambio relevante debe quedar registrado en el `CHANGELOG_DOCUMENTAL.md`.
5. **Mínimo necesario:** no se debe publicar información interna, sensible, personal o no confirmada.
6. **Separación de funciones:** el contenido público, el código, los datos personales y la documentación interna deben administrarse separadamente.
7. **Revisión previa:** los contenidos legales, de privacidad, KYC/AML, tokenomics y funciones financieras o transaccionales requieren revisión especializada antes de su publicación.
8. **Comunicación prudente:** no se deben publicar promesas de rendimiento, liquidez, recompra, aprobación, financiación, emisión o disponibilidad futura no confirmada.

## 3. Alcance documental

Esta política aplica, como mínimo, a:

- Whitepapers y documentos institucionales.
- Especificaciones técnicas.
- README, documentación de repositorios y archivos `Markdown`.
- Páginas publicadas mediante GitHub Pages.
- Contenido de `NESGESFinance.app`.
- Términos de uso, avisos legales y políticas de privacidad.
- Formularios de postulación, contacto, registro y KYC.
- Materiales de presentación, pitch decks y publicaciones institucionales.
- Diagramas, infografías, tablas de tokenomics y documentos descargables.
- Código que contenga textos visibles al usuario.
- Comunicaciones relativas a NGF•BTC•AM.
- Registros de cambios, matrices de claims y glosarios.

## 4. Clasificación de información

### 4.1. Información pública

Información aprobada para difusión abierta, incluyendo:

- Propósito institucional.
- Documentación técnica aprobada.
- Datos on-chain verificables.
- Tokenomics v5.0 aprobada.
- Advertencias de riesgo.
- Documentación legal aprobada.
- Estado de funciones, correctamente etiquetado.

### 4.2. Información interna

Información destinada únicamente a personal autorizado, incluyendo:

- Borradores no aprobados.
- Planificación técnica interna.
- Evaluaciones de iniciativas.
- Informes de debida diligencia.
- Listas de revisión.
- Decisiones pendientes.
- Arquitectura interna y configuraciones no públicas.

### 4.3. Información confidencial o restringida

Información que no debe publicarse ni incluirse en repositorios públicos, incluyendo:

- Claves privadas.
- Frases semilla.
- Contraseñas.
- Tokens de acceso.
- Secretos de API.
- Variables de entorno.
- Documentos de identidad.
- Información KYC.
- Datos biométricos.
- Datos financieros personales.
- Informes AML.
- Contratos no autorizados para publicación.
- Datos personales de colaboradores, proveedores o usuarios sin base legal y autorización aplicable.

## 5. Jerarquía de fuentes

Cuando existan diferencias entre documentos, se aplicará el siguiente orden de prevalencia:

1. Registro verificable on-chain, para parámetros técnicos de NGF•BTC•AM.
2. Instrumento jurídico formal vigente, para derechos, obligaciones, entidades y estructuras jurídicas.
3. Especificación Técnica NGF•BTC•AM v3.1, para parámetros técnicos y límites funcionales del activo.
4. Whitepaper Institucional v3.1, para narrativa institucional y modelo conceptual.
5. Paquete Jurídico-Comunicacional v3.1, para textos de uso público, riesgos, privacidad y consentimientos.
6. Matriz de Alineación GitHub Pages v3.1, para la corrección del contenido web.
7. Pitch Deck Institucional v3.1, para presentaciones públicas.
8. README, páginas web, publicaciones y piezas derivadas.

En caso de conflicto, el material de menor jerarquía deberá corregirse o retirarse.

## 6. Documentos maestros v3.1

Los siguientes documentos constituyen las fuentes maestras del ciclo documental v3.1:

| Código | Documento | Uso principal |
|---|---|---|
| DOC-WP-31 | Whitepaper Institucional v3.1 | Narrativa institucional y arquitectura general |
| DOC-TEC-31 | Especificación Técnica NGF•BTC•AM v3.1 | Identidad on-chain, tokenomics y límites técnicos |
| DOC-MAT-31 | Matriz de Alineación GitHub Pages v3.1 | Auditoría y actualización de contenido web |
| DOC-PITCH-31 | Pitch Deck Institucional v3.1 | Comunicación institucional pública |
| DOC-LEG-31 | Paquete Jurídico-Comunicacional v3.1 | Términos, riesgos, privacidad, KYC/AML y consentimientos |
| DOC-CLAIMS-31 | MATRIZ_TRAZABILIDAD_CLAIMS.csv | Control de afirmaciones públicas |
| DOC-GLOS-31 | GLOSARIO_NESGESFinance.md | Uniformidad terminológica |
| DOC-CTRL-31 | POLITICA_CONTROL_DOCUMENTAL.md | Gobierno documental |
| DOC-PUB-31 | CHECKLIST_PUBLICACION_GITHUB_PAGES.md | Control previo a despliegue |
| DOC-CHG-31 | CHANGELOG_DOCUMENTAL.md | Registro histórico de cambios |

## 7. Identificación y versionado

### 7.1. Convención de nombres

Los archivos deben utilizar nombres claros, sin ambigüedad y con extensión correcta.

Ejemplos:

```text
NESGESFinance_Whitepaper_Institucional_v3_1.docx
NESGESFinance_Especificacion_Tecnica_NGF_BTC_AM_v3_1.docx
MATRIZ_TRAZABILIDAD_CLAIMS.csv
GLOSARIO_NESGESFinance.md
