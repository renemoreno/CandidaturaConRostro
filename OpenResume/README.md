# Esquema de Resume para Candidatos en JSON

Estándar, Especificación, Esquema

Una versión 0.0.0 será lanzada siguiendo las mejores prácticas de [Versionado Semántico 2.0.0-rc.2](https://semver.org/lang/es/). Experimentaremos con un sistema `migration.js`, donde cada cambio será representado con una versión que puede actualizar una versión anterior de `resume.json` a las versiones más recientes.

### Contribuir

Invitamos a cualquier persona que este interesada en contribuir con la formación de este estándar a que siga las discusiones [aquí en github](https://github.com/renemoreno/CandidaturaConRostro/issues). Sientete libre de hacer fork a este proyecto y proponer nuevas ideas para agregar al Esquema de Resume para Candidatos en JSON. Para asegurar que el formato es correcto, por favor instala el [EditorConfig plugin](http://editorconfig.org/) para tu editor de preferencia.

### Versionado

El Estándar de Resume para Candidatos en JSON se adhiere al Versionado Semántico 2.0.0-rc.2. Si existe una violación a este esquema, repórtalo como un bug. Específicamente, si un parche o una versión menor es lanzado y rompe la compatibilidad de las dependencias anteriores, esa versión debería ser inmediantamente desechada y/o una nueva versión que restaure la compatibilidad debe ser inmediatamente lanzada. Cualquier cambio que rompa la API pública solo se podrá introducir como un lanzamiento de versión "major". Como resultado de esta política, tú puedes (y debes) especificar cualquier dependencia en el  Esquema de Resume para Candidatos en JSON usando la versión de restricciones pesimista con dos dígitos de precisión.
