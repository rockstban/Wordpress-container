# Wordpress en Contenedores
<p>
Es un sistema de código abierto ampliamente utilizado para la creación de sitios web, blogs y aplicaciones sencillas que no requieren un conocimiento avanzado.
</p>
 Características


- No requiere conocimientos de programación:Proporciona una interfaz intuitiva para cualquier tipo de persona enfocada en la creación de páginas web, sin necesidad de poseer conocimientos técnicos avanzados.

- **Flexibilidad**: Uso de temas y complementos para personalizar estilos de sitios web.
  
## Docker

<p2>
Docker es una plataforma de software que permite a los desarrolladores empaquetar y distribuir imágenes que contienen distintas aplicaciones, para que puedan ser ejecutadas de manera consistente en cualquier sistema.
</p2>

### Instalación
<p3>
Para ejecutar Wordpress con Docker se deben seguir los siguientes pasos:
</p3>



- Creamos un archivo YAML en el editor de texto de preferencia, donde se incluya toda la configuración necesaria para el despliegue de los contenedores requeridos.


![](https://github.com/rockstban/Wordpress-container/blob/main/env/wordpress/2.png)



- Posteriormente se busca la imagen oficial en el repositorio de dockerhub tanto de la base de datos como de wordpress.

  
![](https://github.com/rockstban/Wordpress-container/blob/main/env/wordpress/3.png)




![](https://github.com/rockstban/Wordpress-container/blob/main/env/wordpress/4.png)



- Se procede a escribir en el archivo de configuración donde se especifican variables de entorno, volúmenes, puertos e imágenes oficiales que facilitan la construcción sencilla de la página web.


![](https://github.com/rockstban/Wordpress-container/blob/main/env/wordpress/5.png)
![](https://github.com/rockstban/Wordpress-container/blob/main/env/wordpress/6.png)




- Finalmente, en este caso se optó por construir un archivo .env para almacenar todos los secretos de conexión con la base de datos, de modo que el tamaño de configuración del archivo YAML no sea tan extenso. También es importante mencionar que se pueden incluir las variables dentro del mismo archivo.


![](https://github.com/rockstban/Wordpress-container/blob/main/env/wordpress/7.png)



![Conexión con wordpress](https://github.com/rockstban/Wordpress-container/blob/main/env/wordpress/8.png)

## ¡Aprende a Instalar Paso a Paso!
<p4>
¿Quieres dominar la instalación de principio a fin? 🚀 No te pierdas nuestro video tutorial detallado donde te guiamos paso a paso a través del proceso de instalación. 
 ¡Aprender nunca fue tan fácil! 🎥
👇
 

 [¡Haz clic aquí para ver el video tutorial!](https://youtu.be/mTfyDj9v2Zc)

</p4>





## Recursos Adicionales
- Documentación oficial de Docker: https://docs.docker.com/
- Imagen de WordPress en Docker Hub: https://hub.docker.com/_/wordpress
- Ejemplos de Docker Compose para WordPress: https://docs.docker.com/samples/wordpress
