(Hacer inmediatamente)

- CASO TIENE DOCUMENTO DE ACTA DE POSESION Y RUT: RITM0156854

---
- [x] Actualizar el ultimo informe explicado en la sesión con Aura.
- [x] Corregir los captures de las funciones de extraer información de service now.
	- [x] Captures de casos internos.
	- [x] Captures de casos externos.
- [x] Validar casos radicados por Jose.
	- [x] Validar casos cuando solo tienen un archivo para varios documentos.
	- [x] Validar la descarga de documentos cuando vienen por separados.
- [x] Validar la función 08 cuando si coinciden los de la cedula por ejemplo.
- [x] Validar departamento con departamento especial.
	- [x] Validar la ciudad de Bogotá ya que es un caso especial
- [x] Actualizar el número telefónico de la plantilla para incluir el número de Adri 2.
- [x] Retornar el booleano en la función 07 que indique si el comercio esta solicitando multi crédito.
- [x] Revisar el algoritmo de tabla a diccionario en casos externos
- [ ] Incluir las instancias de aprendizaje para validación: certificado Superfinanciera y acta de posesión
	- [ ] Certificado Superfinanciera -> la cámara de comercio no trae los representantes
	- [ ] Acta de posesión -> no hay cámara y se valida acta de posesión con el nombre de la razón social del RUT.
- [x] Preguntar que servicios adicionales aplican para pasarela aliada
- [x] Documentos complementarios para cámara de comercio: rut, acta posesión
- [ ] Certificado de Superfinanciera cuando cámara de comercio no tiene representantes
- [x] Realizar cálculos de ejecución para saber la volumetría del asistente digital.
- [ ] Hacer integración de historia de usuarios para radicación de casos en BizaGi. 
	- [ ] Cerrar caso en Service Now ya cuando se radique el caso en Bizagi.
- [ ] Hacer pruebas de integración para la historia de usuario HU 02 de consultas de informa Colombia.
- [x] Revisar la validación de los correos electrónicos dentro de los archivos que se adjuntan.
- [ ] Validar que el código CIIU y la actividad principal del rut coincidan correctamente: -> más que todo para personas naturales.
- [ ] Validar cuando los archivos vienen adjuntos en un correo electronico y no en un formato zip o archivos netos.
- [ ] La historia de usuario debe recibir un número de caso, el cual es el nombre del archivo json, ese mismo numero es el nombre de la carpeta que tiene los documentos.
	- [x] comprime la carpeta y luego la adjunta y finalmente la elimina de la carpeta temporal
- [ ] Validar si el comercio tiene nit asociado y aplicarle persistencia para que sea retomado en la siguiente ejecución.


- Descargar off line version
- Desinstalar edge
- Borrar temporales 
- Instalar version Off line
- Crear llave para que no actualice el edge
- ![[Pasted image 20250530203113.png]]
```
- HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft
```
	- Crear llave llamada EdgeUpdate
		- Llave DoNotUpdateToEdgeWithChromium = 1
- Cambiar nombre de archivo actualización
- Abrir egde
- Enviar documentación
	- https://apeople.automationanywhere.com/s/article/Error-occurred-while-reading-browser-list
	- Imagen para crear politica en caso de hacer un down grade de ach
	- ![[Pasted image 20250530203831.png]]
	- Aplicar la solución numero 4 mostrada en la imagen
	- Imagen del error causado por el issue
	- ![[Pasted image 20250530204318.png]]


