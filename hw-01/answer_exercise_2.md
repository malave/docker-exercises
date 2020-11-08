## 2. Indica la diferencia entre el uso de la instrucción ADD y COPY (Dockerfile).

Ambas instrucciones sirven para copiar archivos desde una fuente hacia una destino dentro de la imagen. Existen 2 diferencias principales entre estas instrucciones: 
-	ADD permite que la fuente sea remota por medio de un URL y CMD no.
-	CMD permite que se copien archivos que se hallan generado en un stage posterior