# Carga manual de la edición 1.4

1. Extraer el ZIP de carga. No subir el ZIP como único archivo: subir su contenido extraído.
2. Abrir el repositorio y mantener la revisión inicial en privado. Crear una rama carga-editorial-1-4 desde main.
3. En Add file > Upload files, arrastrar el contenido del paquete: archivos raíz y carpetas data, docs y metadata. No arrastrar la carpeta contenedora del ZIP como un nivel adicional. Asegurar que .zenodo.json se incluye (puede estar oculto en el explorador local).
4. Revisar rutas y confirmar que se actualizan README.md, CITATION.cff, metadata/publication.json y docs/manuscript/README.md. No borrar otras carpetas ni las fuentes históricas.
5. Commit con mensaje: Incorpora edición aprobada 1.4, PDF, portada y metadatos de publicación.
6. Abrir pull request hacia main, revisar archivos y fusionar. Si una regla protege main, seguir el procedimiento del repositorio.
7. Abrir el PDF en docs/manuscript, comprobar su versión y que los enlaces del README resuelven. El archivo histórico con sufijo v1.md no es el principal.
8. Antes de cambiar visibilidad, revisar archivos e historial por secretos, datos personales y derechos de terceros. No se declara una auditoría de secretos ya realizada.
9. Si eliges integración GitHub–Zenodo: hacer público el repositorio cuando esté revisado, autorizar GitHub en Zenodo, habilitar el repositorio, y solo después crear el release que quieras archivar. Verificar el registro resultante en Zenodo; no asumir DOI asignado por la mera creación del release.
10. Usar tag v1.4 para alinearlo con versión documental 1.4. Si prefieres llamar v1 al primer lanzamiento público, documentar que corresponde al manuscrito 1.4; no cambiar silenciosamente versión a 1.0 en los documentos.

No se modifica el PDF ni el contenido aprobado. .zenodo.json usa publicación/informe, no software; debe revisarse en Zenodo antes de considerar cerrado el depósito. Zenodo usa .zenodo.json en preferencia a CITATION.cff si ambos existen. Ningún archivo preparado asigna un DOI por sí solo.
