# libro-vivo-hechizos
Libro vivo de Hechizos de Huayra Linux

El libro vivo de hechizos de Huayra es un manual integral, que incluye desde los fundamentos filosóficos y el marco político del proyecto hasta indicaciones técnicas de cómo instalar el sistema operativo, cómo agregar aplicaciones y cómo mantenerlo actualizado. Un libro lleno de secretos, atajos, trucos, y recetas para dominar como nunca antes el sistema operativo Huayra Linux y aprovechar al máximo todas sus virtudes.


¿Por qué un libro de hechizos?  Porque no hay que dejar de jugar,  y si hay que lidiar con lo desconocido, ¡qué mejor que un poco de magia de nuestro lado!

Parte de esa magia consta en que este manual se actualizará automáticamente cuando lo vea en el Escritorio de Huayra, ya que es un paquete más del sistema y cuando hagamos modificaciones, llegarán en forma de actualización junto con las demás mejoras de software.

![](media/tapa.png)

# Pasos para nueva revisión

- incrementar el número de rev en el PDF.
- git push del nuevo PDF

$ dch   
- incrementar versión del paquete

$ pdebuild

- subir nuevo release a github (agregar changelog)
- firmar paquete (debsign)
- enviar el paquete al repo (dput) vía VPN
