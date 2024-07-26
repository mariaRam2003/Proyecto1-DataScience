## Estrategia de Limpieza
1. Unificación de Formato:
Convertir todos los textos a mayúsculas para mantener uniformidad.
Eliminar espacios en blanco adicionales al principio y al final de cada valor.

2. Eliminación de Duplicados:
Revisar y eliminar filas duplicadas en función de una combinación de columnas clave como `CODIGO`, `ESTABLECIMIENTO`, `DIRECCION`, y `TELEFONO`.

3. Corrección de Errores Ortográficos:
Implementar una revisión ortográfica para detectar y corregir errores comunes.
Utilizar listas de valores esperados (por ejemplo, nombres de departamentos y municipios) para identificar y corregir errores de escritura.

#### Especificaciones Por Variable
1. `CODIGO`
- Verificar que todos los códigos tengan un formato consistente (misma longitud y formato alfanumérico).
- Eliminar duplicados.

2. `DISTRITO`
- Normalizar los nombres de los distritos a un formato consistente (mayúsculas).
- Comparar con una lista de distritos válidos para corregir errores ortográficos.

3. `DEPARTAMENTO`
- Normalizar a mayúsculas.
- Corregir errores ortográficos y cambios de letras en nombres de departamentos comparando con una lista oficial.

4. `MUNICIPIO`
- Normalizar a mayúsculas.
- Corregir errores ortográficos y cambios de letras en nombres de municipios comparando con una lista oficial.

5. `ESTABLECIMIENTO`
- Normalizar a mayúsculas.
- Eliminar duplicados.
- Corregir errores ortográficos comunes y variaciones en nombres de establecimientos.

6. `DIRECCION`
- Normalizar a mayúsculas.
- Eliminar espacios adicionales y caracteres especiales innecesarios.

7. `TELEFONO`
- Formatear los números de teléfono para que sigan un patrón consistente (por ejemplo, incluir el código de área).
- Eliminar caracteres no numéricos excepto el guion o paréntesis, si son parte del formato deseado.

8. `SUPERVISOR y DIRECTOR`
- Normalizar nombres a mayúsculas.
- Separar nombres y apellidos si es necesario.
- Corregir errores ortográficos en nombres comunes.

9. `NIVEL`
- Normalizar a mayúsculas.
- Corregir y estandarizar nombres de niveles educativos según una lista de niveles válidos.

10. `SECTOR`
- Normalizar a mayúsculas.
- Corregir y estandarizar nombres de sectores (e.g., "PÚBLICO" o "PRIVADO").

11. `AREA`
- Normalizar a mayúsculas.
- Corregir errores ortográficos y estandarizar áreas geográficas.

12. `STATUS`
- Normalizar a mayúsculas.
- Verificar que los valores sean consistentes (e.g., "ACTIVO" o "INACTIVO").

13. `MODALIDAD`
- Normalizar a mayúsculas.
- Estandarizar nombres de modalidades educativas.

14. `JORNADA`
- Normalizar a mayúsculas.
- Corregir y estandarizar nombres de jornadas (e.g., "MATUTINA", "VESPERTINA").

15. `PLAN`
- Normalizar a mayúsculas.
- Verificar la consistencia y corregir errores en nombres de planes educativos.

16. `DEPARTAMENTAL`
- Normalizar a mayúsculas.
- Corregir y estandarizar nombres de departamentos de supervisión.