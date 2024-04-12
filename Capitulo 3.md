## CAPÍTULO 3: REQUIREMENTS SPECIFICATION

### 3.1. To-Be Scenario Mapping

![To-be](./images/Captura%20de%20pantalla%202024-04-12%20a%20la(s)%2007.40.52.png)

### 3.2. User Stories

|User Story ID|US01|Epic ID |EP01|
| :- | :-: | :-: | :-: |
|Title |Búsqueda de productos de palabra clave|||
|Description |**Como** usuario **quiero** poder buscar productos por palabra clave **para** encontrar productos específicos |||
|Acceptance criteria|<p>**Escenario 01 : Registro de datos** </p><p></p><p>**Dado que** el usuario quiere ingresar una palabra clave en el campo de búsqueda</p><p>**Y** haga clic en buscar</p><p>**Cuando** la app muestra los resultados correspondientes a esa palabra clave   </p><p>**Entonces** se deberá estar ordenados por relevancia </p>|||

|User Story ID|US02|Epic ID|EP01|
| :- | :-: | :-: | :-: |
|Title |Filtrado de resultados por precios|||
|Description |**Como** usuario **quiero** poder filtrar los resultados de búsqueda por precio **para** encontrar productos que se ajusten a mi presupuesto|||
|Acceptance criteria|<p>**Escenario 01 : Registro de datos** </p><p></p><p>**Dado que** después de realizar una búsqueda apropiada a la necesidad del usuario </p><p>**Y** haga clic en buscar</p><p>**Cuando** la app muestra la selección de un rango de precios para filtrar los resultados </p><p>**Entonces** se mostrará en el rango estimado </p>|||

|User Story ID|US03|Epic ID|EP02|
| :- | :-: | :-: | :-: |
|Title |Guardar productos en lista de deseos|||
|Description |**Como** usuario **quiero** poder guardar productos en una lista de deseos **para** volver a ellos más tarde|||
|Acceptance criteria|<p>**Escenario : Entrada de datos registrado**</p><p></p><p>**Dado que** el usuario agregar un producto a su lista de deseos </p><p>**Y** seleccionar en “Lista de deseos” </p><p>**Cuando** el producto pedido se guardará de manera automática </p><p>**Entonces** se mostrará en guardado el resultado que deseaba buscar </p><p></p><p>**Escenario : Salida de datos registrado**</p><p></p><p>**Dado que** el usuario quiera eliminar el producto después de su búsqueda </p><p>**Y** seleccionar en opción “Eliminar elemento”</p><p>**Cuando** el producto guardado se elimina instantáneamente de su lista de deseos</p><p>**Entonces** se mostrará el producto solo en la seccion de busqueda</p>|||

|User Story ID|US04|Epic ID|EP02|
| :- | :-: | :-: | :-: |
|Title |Ordenamiento de resultados por popularidad |||
|Description |**Como** usuario **quiero** poder ordenar los resultados de búsqueda por popularidad para ver los productos más populares primeros |||
|Acceptance criteria|<p>**Escenario : Popularidad de registro** </p><p></p><p>**Dado que** el usuario quiera mostrar los resultados obtenidos se le mostrará la opción “Por  popularidad o por configuración”</p><p>` `**Y** el usuario deberá selecciona una de las dos opciones</p><p>**Cuando** después de seleccionar el sistema se configura automáticamente </p><p>**Entonces** cada que muestre los resultados también se agregaran las ofertas o descuentos del producto por su popularidad </p><p></p>|||

|User Story ID|US05|Epic ID|EP02|
| :- | :-: | :-: | :-: |
|Title |Comparación de precios|||
|Description |**Como** usuario **quiero** poder comparar precios de un mismo producto en diferentes tiendas para encontrar la mejor opción de compra |||
|Acceptance criteria|<p>**Escenario: Comparación de precios** </p><p></p><p>**Dado que** estoy en la pantalla de resultados </p><p>**Y** haga clic en buscar</p><p>**Cuando** haga click en comparación de precios  </p><p>**Entonces** se mostrará una lista de precios de cada tienda que venda el producto </p><p>**Y** podré hacer click en el producto para ver más detalles del producto y la tienda </p>|||

|User Story ID|US06|Epic ID|EP02|
| :- | :-: | :-: | :-: |
|Title |Notificaciones de precios |||
|Description |**Como** usuario **quiero** recibir notificaciones cuando los productos que estoy buscando estén disponibles o en oferta |||
|Acceptance criteria|<p>**Escenario 1:Configuración de Notificaciones** </p><p></p><p>**Dado que** estoy en la pantalla de detalles de un producto</p><p>**Cuando** haga click en el boton de configuracion de notificaciones</p><p>**Entonces** la app me permitirá seleccionar el tipo de notificación que quiero recibir(Disponibilidad o oferta) </p><p>**Y** puedo elegir cómo quiero recibir la notificación (notificación de la app)</p>|||

|User Story ID|US07|Epic ID|EP03|
| :- | :-: | :-: | :-: |
|Title |Búsqueda de tiendas cercanas|||
|Description |**Como** usuario **quiero** poder buscar tiendas cercanas a mi ubicación para poder encontrar fácilmente una tienda donde comprar el producto que necesito   |||
|Acceptance criteria|<p>**Escenario: Búsqueda por ubicación**</p><p></p><p>**Dado que** estoy en la pantalla principal de la app</p><p>**Cuando** selecciono la opción de búsqueda por ubicación  </p><p>**Entonces** la app me muestra un mapa con mi ubicación actual y las tiendas cercanas</p><p>**Y** puedo hacer clic una tienda para ver más detalles </p><p></p><p>**Escenario 02: Filtración de búsqueda por ubicación**</p><p></p><p>**Dado que** estoy en la pantalla de resultados de búsqueda por ubicación** </p><p>**Cuando** haga clic en el botón de filtro</p><p>**Entonces** la app muestra opciones de filtrado para distancia, tipo de tienda y otras características </p><p>**Y** la app actualiza los resultados para mostrar solo las tiendas que cumplen con los filtros seleccionados</p>|||

|User Story ID|US08|Epic ID|EP03|
| :- | :-: | :-: | :-: |
|Title |Comentarios y reseñas de productos |||
|Description |**Como** usuario **quiero** poder leer comentarios y reseñas de otros usuarios sobre un producto para tomar una decisión de compra informada |||
|Acceptance criteria|<p>**Escenario 01: Ver comentarios y reseñas** </p><p></p><p>**Dado que** estoy en la pantalla de detalles de un producto</p><p>**Cuando** haga clic en el botón de comentarios y reseñas </p><p>**Entonces** la app me muestra una lista de todos los comentarios y reseñas sobre un producto </p><p>**Y** podré ver el nombre de usuario, la calificación y el comentario de cada usuario </p><p></p><p>**Escenario 02: Dejar comentarios y reseñas** </p><p></p><p>**Dado que** estoy en la pantalla de detalles de un producto</p><p>**Cuando** haga clic en el botón de comentarios y reseñas </p><p>**Entonces** la app me permite escribir un comentario o reseña sobre el producto </p><p>**Y** la app publica mi comentario o reseña </p><p></p>|||

|User Story ID|US09|Epic ID|EP03|
| :- | :-: | :-: | :-: |
|Title |Opciones de pago|||
|Description |**Como** usuario **quiero** ver las opciones de pago disponibles en cada tienda para poder elegir la más conveniente|||
|Acceptance criteria|<p>**Escenario 01: Ver opciones de pago**</p><p></p><p>**Dado que** estoy en la pantalla de detalles de una tienda</p><p>**Cuando** haga clic en el botón de opciones de pago</p><p>**Entonces** la app me muestra una lista de todos las opciones de pago disponibles en la tienda </p><p>**Y** puedo hacer clic en la opcion de pago para ver mas detalles de pago </p><p></p>|||

|User Story ID|US10|Epic ID|EP03|
| :- | :-: | :-: | :-: |
|Title |Lista de compras |||
|Description |**Como** usuario **quiero** poder crear listas de compras para organizar mis productos y encontrarlos más fácilmente |||
|Acceptance criteria|<p>**Escenario 01: Crear una lista de compras**</p><p></p><p>**Dado que** estoy en la pantalla principal de la app</p><p>**Cuando** haga clic en el botón de crear una lista de compras para el usuario</p><p>**Entonces** la app me permite escribir un nombre para la lista de compra </p><p>**Y** la app agrega la lista de compras a mi lista de compra</p><p>**Y** puedo hacer clic en la lista de compras para ver los productos que he agregado</p><p></p><p>**Escenario 02: Agregar los productos seleccionado a la lista de compra** </p><p></p><p>**Dado que** estoy en la pantalla de detalles de un producto</p><p>**Cuando** haga clic en el botón de agregar a lista de compra</p><p>**Entonces** la app se muestra una lista de todo lo contenido en la “Lista de compra” </p>|||

|User Story ID|US11|Epic ID|EP03|
| :- | :-: | :-: | :-: |
|Title |Historial de precios|||
|Description |**Como** usuario **quiero** poder ver el historial de precios de un productor para decidir si espero a que baje de precio o lo compro ahora|||
|Acceptance criteria|<p>**Escenario 01: Ver historial de precios**</p><p></p><p>**Dado que** estoy en la pantalla de detalles de un producto</p><p>**Cuando** haga clic en el botón de historial de precios</p><p>**Entonces** la app me muestra un gráfico con el historial de precios del producto en las tiendas disponibles</p><p>**Y** puedo seleccionar un rango de tiempo para ver el historial de precios en ese periodo específico </p><p></p><p>**Escenario 02: Comprar con información de historial de precios** </p><p></p><p>**Dado que** estoy en la pantalla de detalles de un producto</p><p>**Cuando** decido comprar el producto </p><p>**Entonces** la app me muestra un mensaje de advertencia si el precio actual es significativamente más alto que el precio promedio en el historial de precios </p>|||

|User Story ID|US12|Epic ID|EP03|
| :- | :-: | :-: | :-: |
|Title |Ofertas destacadas |||
|Description |**Como** usuario **quiero** poder ver las ofertas más destacadas de la semana para aprovechar los mejores precios|||
|Acceptance criteria|<p>**Escenario 01: Ver ofertas destacadas**</p><p></p><p>**Dado que** estoy en la pantalla de la app </p><p>**Cuando** desplazó hacia abajo en la pantalla </p><p>**Entonces** la app me muestra una sección de ofertas destacadas </p><p>**Y** puedo ver los productos en oferta y la cantidad de descuento</p><p>**Y** puedo hacer clic en un producto para ver los detalles y comprarlo </p><p></p>|||

|User Story ID|US13|Epic ID|EP03|
| :- | :-: | :-: | :-: |
|Title |Alertas de precios|||
|Description |**Como** usuario **quiero recibir** alertas de precio para los productos que me interesan saber cuando bajan de precio|||
|Acceptance criteria|<p>**Escenario 01: Configurar alertas de precio**</p><p></p><p>**Dado que** estoy en la pantalla de detalles de un producto</p><p>**Cuando** haga clic en el boton alerta de precio </p><p>**Entonces** la app me permite configurar la alerta de precio para ese producto</p><p>**Y** puedo elegir una cantidad específica de descuento o un precio objetivo para recibir la alerta</p><p></p><p>**Escenario 02: Recibir alertas de precio**</p><p>**Dado que** he configurado una alerta de precio para un producto</p><p>**Cuando** el precio del producto baja a la cantidad específica o al precio objetivo</p><p>**Entonces** la app me envía una alerta por el método que elegí</p>|||

|User Story ID|US14|Epic ID|EP04|
| :- | :-: | :-: | :-: |
|Title |Compartir productos|||
|Description |**Como** usuario **quiero** poder compartir productos que encuentro en la app con amigos y familiares para obtener sus opiniones |||
|Acceptance criteria|<p>**Escenario 01: Compartir productos en redes sociales**</p><p></p><p>**Dado que** estoy en la pantalla de detalles de un producto</p><p>**Cuando** haga clic en el botón de compartir</p><p>**Entonces** la app me muestra opciones para compartir el producto en redes sociales como Facebook,Twitter y Instagram </p><p>**Y** puedo elegir una red social y compartir el producto con un mensaje personalizado</p><p><br></p><p>**Escenario 02: compartir productos por correo electronicos** </p><p></p><p>**Dado que** estoy en la pantalla de detalles de un producto</p><p>**Cuando** haga clic en el botón de compartir</p><p>**Entonces** la app me permite compartir el producto por correo electrónico</p><p>Y puedo escribir una dirección de correo electrónico y un mensaje para poder enviar el producto a alguien  </p>|||

|User Story ID|US15|Epic ID|EP04|
| :- | :-: | :-: | :-: |
|Title |Códigos de descuento|||
|Description |**Como** usuario **quiero** poder encontrar y aplicar códigos de descuento para ahorrar dinero en mis compras|||
|Acceptance criteria|<p>**Escenario 01: Ver códigos de descuento**</p><p>**Dado que** estoy en la pantalla de detalles de un producto </p><p>**Cuando** desplazó hacia abajo la pantalla en la derecha</p><p>**Entonces** me saldrá la opción “Canjear código”</p><p>**Y** escribes el código solicitado y disponible para aplicar el respectivo descuento </p><p></p>|||

|User Story ID|US16|Epic ID|EP04|
| :- | :-: | :-: | :-: |
|Title |Cambio de contraseñas |||
|Description |**Como** usuario **quiero** que la aplicación me informe cada cierto tiempo a cambiar de contraseña para tener más seguridad.|||
|Acceptance criteria|<p>**Escenario : Cambio frecuente de contraseña** </p><p></p><p>**Dado que** cierto tiempo el sistema le recomendará cambiar de contraseña </p><p>**Cuando** esté usando con normalidad la app </p><p>**Y** ya alla pasado cierto tiempo </p><p>**Entonces** le saldrá un anuncio recomendando el cambio de contraseña para más seguridad**  </p>|||

|User Story ID|US17|Epic ID|EP04|
| :- | :-: | :-: | :-: |
|Title |Búsqueda avanzada|||
|Description |**Como** usuario **quiero** poder analizar una búsqueda avanzada con filtros para poder encontrar productos específicos de manera mas facil y rapida|||
|Acceptance criteria|<p>**Escenario 01: Acceder a la búsqueda avanzada**</p><p></p><p>**Dado que** estoy en la pantalla principal de búsqueda </p><p>**Cuando** selecciono la opcion de “Busqueda avanzada”</p><p>**Entonces** la app me muestra una pantalla con una serie de filtros,como marca,precio,tamaño,color,etc.</p><p></p><p>**Escenario 02: Aplicar filtros en la búsqueda avanzada**</p><p>**Dado que** estoy en la pantalla búsqueda avanzada</p><p>**Cuando** selecciono uno o más filtros y aplicó la búsqueda </p><p>**Entonces** la app me muestra los productos que coinciden con los filtros seleccionados </p><p>**Y** la app me permite deshacer los filtros aplicados si quiero ampliar la búsqueda </p>|||

|User Story ID|US18|Epic ID|EP03|
| :- | :-: | :-: | :-: |
|Title |Búsqueda por voz|||
|Description |**Como** usuario **quiero** poder buscar productos en la app utilizando comando de voz para una experiencia mas practica y facil|||
|Acceptance criteria|<p>**Escenario 01: Activar la búsqueda por voz**</p><p></p><p>**Dado que** estoy en la pantalla de búsqueda</p><p>**Cuando** selecciono la opcion de busqueda por voz</p><p>**Entonces** la app me permite activar la búsqueda por voz a través de microfono de mi dispositivo movil </p><p></p><p>**Escenario 02: Búsqueda un producto por voz** </p><p></p><p>**Dado que** he activado por voz</p><p>**Cuando** digo el nombre del producto que deseo buscar </p><p>**Entonces** la app se muestra resultado de búsqueda correspondientes al producto </p>|||

|User Story ID|US19|Epic ID|EP04|
| :- | :-: | :-: | :-: |
|Title |Compras en grupo|||
|Description |**Como** usuario **quiero** poder crear y unirse a compras en grupo con amigos o familiares para obtener descuentos en productos|||
|Acceptance criteria|<p>**Escenario 01: Crear compra en grupo**</p><p></p><p>**Dado que** quiero realizar una compra en grupo con amigos o familiares</p><p>**Cuando** selecciono la opción de “Crear compra en grupo”</p><p>**Entonces** la app me permite seleccionar el producto que quiero comprar y la cantidad que necesito</p><p></p><p>**Escenario 02: Invitar amigos o familia a una compra en grupo**</p><p></p><p>**Dado que** he creado una compra en grupo</p><p>**Cuando** selecciono la opción “Invitar amigos o familiares” </p><p>**Entonces** la app me permite enviar un enlace de invitación por correo electrónico o mensaje de texto</p>|||

|User Story ID|US**20**|Epic ID|EP04|
| :- | :-: | :-: | :-: |
|Title |Chat con la tienda |||
|Description |**Como** usuario **quiero** poder comunicarme con la tienda sobre un producto para hacer preguntas y aclarar mis dudas antes de realizar la compra|||
|Acceptance criteria|<p>**Escenario 01: Acceder al chat con la tienda**</p><p></p><p>**Dado que** estoy en la pantalla de detalles del producto</p><p>**Cuando** selecciono la opcion “Chat con la tienda seleccionada”</p><p>**Entonces** la app me muestra una pantalla de chat donde puedo comunicarme con el vendedor del producto</p><p></p>|||

### 3.3. Impact Mapping

### 3.4. Product Backlog

A continuación, procederemos a detallar el product backlog de nuestras user stories en donde analizaremos su importancia para el proyecto y los puntos que estaremos cubriendo en cada uno de los sprints de trabajo durante este ciclo.
