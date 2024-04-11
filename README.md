# Microservicios Docker - PhP - Mysql
<h2>Instalar y configurar el servidor</h2>
<li>
  <ol>Instalar docker</ol>
  <ol>Descargar docker-compose</ol>
  <ol>Dar permisos al docker-compose</ol>
</li>
<h2>Crear un Topic SNS</h2>
<li>
  <ol>Asegúrate de configurar adecuadamente los ajustes de seguridad ( permitir el tráfico HTTP, SSH) ademas de los puertos 3036 y 8080.</ol>
  <ol>Crea un topic SNS y subscribir tú e-mail al topic, confirmar la subscripción desde su e-mail</ol>
  <ol>En el fichero submit dentro de la carpeta html, debe sustituir el ARN de su Topic SNS</ol>
  <ol>Añadir el Rol a la EC2</ol>
  <ol>Añadir la política "SNSFullAcces"</ol>
  <ol>Lanzar el siguiente comando : sudo docker-compose up</ol>
  <ol>Abre el navegador y envia el formulario una vez rellenado, comprueba que has recibido el e-mail con la información del formulario. </ol>
</li>
