### 4. `CHECKLIST_PUBLICACION_GITHUB_PAGES.md`

```markdown
# Checklist de Publicación para GitHub Pages — NESGESFinance v3.1

**Uso:** obligatorio antes de fusionar cambios hacia la rama de producción o publicar contenido en GitHub Pages.

## 1. Identificación del despliegue

- [ ] El repositorio que se modificará es el repositorio canónico del sitio institucional.
- [ ] Se confirmó la configuración activa en `Settings → Pages`.
- [ ] Se confirmó la rama y carpeta o flujo de GitHub Actions que realiza la publicación.
- [ ] Se creó una rama de trabajo separada de la rama de producción.
- [ ] Existe una rama o etiqueta de respaldo anterior al cambio.
- [ ] El cambio tiene un objetivo definido y documentado.
- [ ] El cambio no mezcla correcciones no relacionadas.

## 2. Fuente documental

- [ ] Se identificó el documento maestro que respalda cada cambio.
- [ ] Se revisó `MATRIZ_TRAZABILIDAD_CLAIMS.csv`.
- [ ] Se revisó `GLOSARIO_NESGESFinance.md`.
- [ ] Se verificó que el cambio es compatible con el Whitepaper Institucional v3.1.
- [ ] Se verificó que el cambio es compatible con la Especificación Técnica NGF•BTC•AM v3.1.
- [ ] Se verificó que el cambio es compatible con el Paquete Jurídico-Comunicacional v3.1.
- [ ] Se verificó que el cambio respeta la Matriz de Alineación GitHub Pages v3.1.
- [ ] Si no existe fuente o evidencia suficiente, el contenido no se publicará como hecho.

## 3. Marca e identidad institucional

- [ ] La marca se escribe uniformemente como `NESGESFinance`.
- [ ] Se utiliza el lema: “Y a tu prójimo como a ti mismo”.
- [ ] Se utiliza el tagline: “Tokenización con Propósito”.
- [ ] No existen denominaciones no autorizadas o confusas.
- [ ] Las entidades corporativas solo se mencionan cuando corresponden al contenido y han sido verificadas.
- [ ] No se publicaron datos personales de personas naturales sin autorización aplicable.

## 4. NGF•BTC•AM: verificación técnica

- [ ] El nombre se muestra exactamente como `NGF•BTC•AM`.
- [ ] El Rune Number es `#208,645`.
- [ ] El Rune ID es `923867:120`.
- [ ] El suministro total es `5.930.000.000`.
- [ ] La divisibilidad se muestra como `0`.
- [ ] No se afirma que el activo sea minteable.
- [ ] No se afirma que el activo sea quemable.
- [ ] Los datos técnicos fueron contrastados con una fuente on-chain verificable.
- [ ] Ninguna pieza presenta datos técnicos divergentes.

## 5. Tokenomics v5.0

- [ ] Reserva: 30% — 1.779.000.000 unidades.
- [ ] Proyectos: 25% — 1.482.500.000 unidades.
- [ ] Social y Ambiental: 15% — 889.500.000 unidades.
- [ ] Alianzas y Gobernanza: 10% — 593.000.000 unidades.
- [ ] Tesorería: 10% — 593.000.000 unidades.
- [ ] Comunidad: 5% — 296.500.000 unidades.
- [ ] Equipo: 4% — 237.200.000 unidades.
- [ ] Operativo: 1% — 59.300.000 unidades.
- [ ] La suma de porcentajes es 100%.
- [ ] La suma de unidades es 5.930.000.000.
- [ ] Se actualizaron simultáneamente tablas, gráficos, tarjetas, PDF, textos y metadatos.
- [ ] No existe otra tokenomics presentada como vigente.

## 6. Lenguaje legal y de riesgos

- [ ] Se indica que NGF•BTC•AM es un activo de utilidad técnica.
- [ ] Se indica que NGF•BTC•AM no representa acciones societarias.
- [ ] Se indica que NGF•BTC•AM no otorga dividendos, intereses ni derechos económicos.
- [ ] Se indica que no existe garantía de rendimiento.
- [ ] Se indica que no existe garantía de liquidez.
- [ ] Se indica que no existe obligación de recompra.
- [ ] Se indica que las operaciones en Bitcoin L1 son irreversibles.
- [ ] Se indica que el usuario es responsable de sus claves privadas y direcciones de destino.
- [ ] No existen promesas económicas explícitas o implícitas.
- [ ] No se presenta asesoría legal, financiera, tributaria, contable o de inversión como parte del contenido.
- [ ] Las menciones a SPV, Reg D 506(c), Reg S, trust o fideicomisos tienen revisión jurídica y evidencia formal, si se presentan como vigentes.

## 7. Directriz de contenido público v3.1

- [ ] El contenido mantiene un enfoque institucional y genérico.
- [ ] No se mencionan proyectos específicos.
- [ ] No se mencionan series privadas o emisiones específicas.
- [ ] No se incluyen activos físicos, inmuebles, negocios o iniciativas individualizadas.
- [ ] No se incluyen porcentajes de distribución aplicables a un proyecto individual.
- [ ] No se incluyen cronogramas, retornos, aprobaciones o resultados de una operación concreta.
- [ ] Las referencias a postulación se limitan al proceso genérico aplicable.
- [ ] El formulario de postulación aclara que enviar información no implica aprobación, emisión ni financiamiento.

## 8. Estado real de funcionalidades

Para cada sección o función visible, seleccionar un estado correcto:

- [ ] Implementado y verificable.
- [ ] En desarrollo.
- [ ] Planificado.
- [ ] Conceptual.
- [ ] No disponible públicamente.

Comprobar específicamente:

- [ ] Wallet.
- [ ] Conexión de billetera.
- [ ] Visualización de saldos.
- [ ] Runes.
- [ ] Ordinals.
- [ ] Generación o firma de PSBT.
- [ ] Lightning Network.
- [ ] Taproot Assets.
- [ ] P2P.
- [ ] Trade o spot.
- [ ] Gobernanza.
- [ ] KYC.
- [ ] AML.
- [ ] API.
- [ ] Notificaciones.
- [ ] Historial.
- [ ] Soporte.

- [ ] Ninguna función se presenta como operativa sin prueba funcional, responsable definido y revisión de seguridad aplicable.
- [ ] Las interfaces visuales no simulan disponibilidad de una función no implementada.
- [ ] Las funciones no disponibles se deshabilitan o se etiquetan claramente.

## 9. Privacidad y formularios

- [ ] Cada formulario identifica la finalidad de los datos solicitados.
- [ ] Cada formulario evita solicitar datos innecesarios.
- [ ] Cada formulario incluye un enlace visible a la Política de Privacidad.
- [ ] Cada formulario requiere aceptación de Términos de Uso y Aviso Legal cuando corresponda.
- [ ] Los consentimientos no están preseleccionados.
- [ ] El consentimiento es específico, claro y registrable.
- [ ] El formulario KYC no se habilita sin flujo seguro, responsable definido y aprobación aplicable.
- [ ] No se recolectan frases semilla, claves privadas ni credenciales de billeteras.
- [ ] No se almacenan documentos KYC o datos personales en el repositorio público.
- [ ] Los formularios no envían información a destinos desconocidos o no autorizados.
- [ ] Existe una página o mecanismo definido para ejercer derechos de privacidad, sujeto a revisión jurídica.

## 10. Seguridad de repositorio y despliegue

- [ ] No se incluyeron archivos `.env`.
- [ ] No se incluyeron contraseñas, claves privadas, seed phrases ni tokens.
- [ ] No se incluyeron secretos de API.
- [ ] No se incluyeron documentos de identidad, información KYC o datos biométricos.
- [ ] Se revisó el historial de cambios para evitar exposición accidental de secretos.
- [ ] La rama de producción está protegida.
- [ ] El cambio se realiza mediante Pull Request.
- [ ] El Pull Request fue revisado antes de fusionarse.
- [ ] Las dependencias agregadas fueron revisadas.
- [ ] No se añadieron scripts externos no verificados.
- [ ] No se habilitaron integraciones de terceros sin evaluar sus datos, permisos y riesgos.

## 11. Calidad web

- [ ] El sitio carga correctamente en computadora.
- [ ] El sitio carga correctamente en móvil.
- [ ] La navegación principal funciona.
- [ ] No hay enlaces rotos.
- [ ] Los documentos descargables corresponden a la versión vigente.
- [ ] Los enlaces externos son pertinentes y funcionan.
- [ ] Las imágenes tienen texto alternativo cuando corresponda.
- [ ] Los títulos y metadatos reflejan el contenido real.
- [ ] No hay texto de plantilla, contenido de prueba o secciones incompletas.
- [ ] Las fechas visibles son correctas y no inducen a error.
- [ ] El pie de página contiene información vigente y consistente.

## 12. Validación final antes de publicar

- [ ] Se revisó el contenido completo en vista previa.
- [ ] Se realizó búsqueda global de afirmaciones, porcentajes y nombres antiguos.
- [ ] Se verificó que no hay proyectos específicos publicados.
- [ ] Se verificó que no hay promesas de rendimiento o disponibilidad.
- [ ] Se verificó que todos los consentimientos legales requeridos están implementados.
- [ ] Se actualizó `CHANGELOG_DOCUMENTAL.md`.
- [ ] Se documentó el Pull Request o cambio de publicación.
- [ ] La persona responsable autorizó la publicación.
- [ ] La versión desplegada fue comprobada después de la publicación.
- [ ] Se archivó la evidencia de verificación correspondiente.

## 13. Regla de bloqueo

No se debe publicar ni fusionar un cambio si se cumple cualquiera de estas condiciones:

- Contiene secretos, claves privadas, frases semilla o datos KYC.
- Contradice la tokenomics v5.0.
- Presenta funcionalidades no implementadas como operativas.
- Incluye promesas de rendimiento, liquidez, recompra o retorno.
- Incluye proyectos específicos en materiales públicos v3.1.
- Carece de revisión jurídica cuando el contenido es legal, de privacidad, KYC/AML o regulatorio.
- Carece de evidencia para una afirmación técnica, corporativa o on-chain.
- No fue registrado en el changelog cuando el cambio es material.

## 14. Registro de aprobación

| Campo | Registro |
|---|---|
| Repositorio |  |
| Rama de trabajo |  |
| Pull Request / referencia de cambio |  |
| Fecha de revisión |  |
| Responsable técnico |  |
| Responsable institucional |  |
| Revisión jurídica requerida | Sí / No |
| Responsable de aprobación |  |
| Resultado | Aprobado / Rechazado / Pendiente |
| Observaciones |  |
